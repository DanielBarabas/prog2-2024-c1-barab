# 2026-06-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.04444  |       1e-06    |   0.394492 |
| barab-szabi-2        |     9.60761  |       1.33084  |   0.441234 |
| barab-szabi-1        |     0.462791 |       0.404065 |   0.442874 |
| k-d_tree_polars      |     0.469643 |       0.408802 |   0.452865 |
| k-d_tree_pandas      |     0.474367 |       0.385093 |   0.552075 |
| Bori_Aron_solution-1 |     0.45595  |       0.553948 |   0.554701 |
| k-d_tree_sklearn     |     3.31631  |       1.08972  |   1.07343  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472165 |       0.450368 |   0.444309 |
| k-d_tree_polars      |     0.471266 |       0.412611 |   0.45046  |
| barab-szabi-1        |     0.478602 |       0.415673 |   0.45344  |
| Bori_Aron_solution-1 |     0.474529 |       0.557422 |   0.553488 |
| k-d_tree_pandas      |     0.47581  |       0.393402 |   0.559257 |
| k-d_tree_sklearn     |     0.478432 |       1.0012   |   1.08386  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476665 |       0.463941 |   0.459563 |
| barab-szabi-1        |     0.476747 |       0.440535 |   0.48392  |
| k-d_tree_polars      |     0.475101 |       0.441171 |   0.490017 |
| Bori_Aron_solution-1 |     0.469434 |       0.597325 |   0.552634 |
| k-d_tree_pandas      |     0.473459 |       0.41424  |   0.616532 |
| k-d_tree_sklearn     |     0.490599 |       1.04382  |   1.12656  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485383 |       0.520198 |   0.485718 |
| Bori_Aron_solution-1 |     0.468094 |       0.787827 |   0.568362 |
| k-d_tree_polars      |     0.485533 |       0.567776 |   0.575853 |
| barab-szabi-1        |     0.474823 |       0.568631 |   0.581594 |
| k-d_tree_pandas      |     0.478031 |       0.495819 |   0.739214 |
| k-d_tree_sklearn     |     0.476116 |       1.27706  |   1.16906  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471833 |       0.733173 |   0.524289 |
| Bori_Aron_solution-1 |     0.471369 |       1.45446  |   0.592272 |
| k-d_tree_polars      |     0.474804 |       0.928124 |   0.928878 |
| barab-szabi-1        |     0.474681 |       0.938252 |   0.966991 |
| k-d_tree_pandas      |     0.487318 |       0.827056 |   1.20193  |
| k-d_tree_sklearn     |     0.478574 |       2.13598  |   1.26204  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487012 |        5.17468 |   0.77369  |
| Bori_Aron_solution-1 |     0.484912 |       11.0926  |   0.833727 |
| k-d_tree_sklearn     |     0.504462 |       17.0063  |   1.33747  |
| k-d_tree_polars      |     0.491047 |        5.49145 |   6.65262  |
| barab-szabi-1        |     0.484993 |        5.55882 |   6.82169  |
| k-d_tree_pandas      |     0.47981  |        4.50917 |   7.02542  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.4726   |        70.0899 |    2.73225 |
| k-d_tree_sklearn     |     0.84934  |       242.905  |    4.02809 |
| Bori_Aron_solution-1 |     0.470928 |       149.216  |   25.132   |