# 2024-09-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623763 |       0.393953 |   0.391235 |
| barab-szabi-1        |     0.62547  |       0.415829 |   0.397667 |
| solution-1           |     8.10717  |       1e-06    |   0.408549 |
| k-d_tree_polars      |    14.2579   |       0.46972  |   0.415977 |
| Bori_Aron_solution-1 |     6.98631  |       0.553607 |   0.477033 |
| k-d_tree_pandas      |     0.607839 |       0.391488 |   0.546092 |
| k-d_tree_sklearn     |     3.33412  |       1.03018  |   0.745506 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.624527 |       0.397335 |   0.395716 |
| barab-szabi-1        |     0.634747 |       0.419981 |   0.405481 |
| k-d_tree_polars      |     0.640144 |       0.413291 |   0.413507 |
| Bori_Aron_solution-1 |     0.626529 |       0.551328 |   0.543491 |
| k-d_tree_pandas      |     0.62538  |       0.393732 |   0.564655 |
| k-d_tree_sklearn     |     0.637926 |       0.935609 |   0.73831  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62167  |       0.411897 |   0.405621 |
| k-d_tree_polars      |     0.633071 |       0.443992 |   0.428211 |
| barab-szabi-1        |     0.628302 |       0.460837 |   0.431134 |
| Bori_Aron_solution-1 |     0.631378 |       0.592664 |   0.54963  |
| k-d_tree_pandas      |     0.627938 |       0.430928 |   0.592232 |
| k-d_tree_sklearn     |     0.637474 |       0.967539 |   0.746721 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625841 |       0.475167 |   0.440251 |
| k-d_tree_polars      |     0.622724 |       0.540488 |   0.533954 |
| barab-szabi-1        |     0.636922 |       0.547898 |   0.543538 |
| Bori_Aron_solution-1 |     0.620605 |       0.770351 |   0.560739 |
| k-d_tree_pandas      |     0.645108 |       0.492455 |   0.731346 |
| k-d_tree_sklearn     |     0.625387 |       1.21325  |   0.815288 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.63429  |       0.741355 |   0.483186 |
| Bori_Aron_solution-1 |     0.640401 |       1.42322  |   0.585225 |
| k-d_tree_polars      |     0.626279 |       0.869674 |   0.892903 |
| k-d_tree_sklearn     |     0.637812 |       2.04958  |   0.903289 |
| barab-szabi-1        |     0.636102 |       0.860997 |   0.92417  |
| k-d_tree_pandas      |     0.62666  |       0.757919 |   1.17386  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.657349 |        5.64299 |   0.796039 |
| Bori_Aron_solution-1 |     0.61769  |       10.9782  |   0.850418 |
| k-d_tree_sklearn     |     0.632489 |       16.8586  |   1.02584  |
| k-d_tree_polars      |     0.623487 |        4.93005 |   6.89364  |
| barab-szabi-1        |     0.631899 |        4.87953 |   7.07516  |
| k-d_tree_pandas      |     0.640026 |        3.87252 |   7.25126  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.703453 |         72.046 |    3.71449 |
| k-d_tree_sklearn     |     0.884476 |        226.756 |    3.9369  |
| Bori_Aron_solution-1 |     0.629092 |        146.751 |   18.9451  |