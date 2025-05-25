# 2025-05-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.546896 |       0.406165 |   0.418308 |
| barab-szabi-2        |     0.547413 |       0.415833 |   0.431528 |
| solution-1           |     8.13711  |       1e-06    |   0.464165 |
| Bori_Aron_solution-1 |     0.534953 |       0.553597 |   0.547596 |
| barab-szabi-1        |     8.44888  |       0.443022 |   0.560437 |
| k-d_tree_pandas      |     0.553338 |       0.390966 |   0.563201 |
| k-d_tree_sklearn     |     3.15111  |       1.06225  |   1.04266  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.551189 |       0.413571 |   0.424863 |
| barab-szabi-1        |     0.557657 |       0.412614 |   0.425405 |
| barab-szabi-2        |     0.555208 |       0.42356  |   0.43363  |
| Bori_Aron_solution-1 |     0.548397 |       0.555576 |   0.54896  |
| k-d_tree_pandas      |     0.560168 |       0.395554 |   0.556504 |
| k-d_tree_sklearn     |     0.577386 |       0.960124 |   1.05886  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554936 |       0.430803 |   0.432061 |
| barab-szabi-1        |     0.551297 |       0.435867 |   0.450992 |
| k-d_tree_polars      |     0.556856 |       0.44155  |   0.453749 |
| Bori_Aron_solution-1 |     0.549306 |       0.587103 |   0.556709 |
| k-d_tree_pandas      |     0.564785 |       0.407662 |   0.596433 |
| k-d_tree_sklearn     |     0.556643 |       1.00212  |   1.08002  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554117 |       0.492732 |   0.463461 |
| k-d_tree_polars      |     0.558111 |       0.542028 |   0.546932 |
| barab-szabi-1        |     0.555582 |       0.545979 |   0.562106 |
| Bori_Aron_solution-1 |     0.556155 |       0.766499 |   0.562754 |
| k-d_tree_pandas      |     0.553689 |       0.487519 |   0.744472 |
| k-d_tree_sklearn     |     0.559433 |       1.24313  |   1.15613  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551217 |       0.749541 |   0.496309 |
| Bori_Aron_solution-1 |     0.545085 |       1.40468  |   0.590956 |
| k-d_tree_polars      |     0.555894 |       0.889035 |   0.897176 |
| barab-szabi-1        |     0.554605 |       0.879845 |   0.941629 |
| k-d_tree_pandas      |     0.550096 |       0.773149 |   1.17561  |
| k-d_tree_sklearn     |     0.555185 |       2.07356  |   1.24222  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550492 |        5.32878 |   0.738607 |
| Bori_Aron_solution-1 |     0.546056 |       10.6889  |   0.879998 |
| k-d_tree_sklearn     |     0.55854  |       16.1441  |   1.32125  |
| k-d_tree_polars      |     0.568948 |        4.94481 |   6.58151  |
| barab-szabi-1        |     0.556483 |        5.01434 |   6.61025  |
| k-d_tree_pandas      |     0.554626 |        3.91868 |   6.98007  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.593576 |        72.2532 |    2.78618 |
| k-d_tree_sklearn     |     0.690592 |       230.327  |    5.06684 |
| Bori_Aron_solution-1 |     0.544216 |       142.372  |   17.2226  |