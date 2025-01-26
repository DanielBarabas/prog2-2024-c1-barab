# 2025-01-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.00299  |       0.993904 |   0.401184 |
| k-d_tree_polars      |     0.581058 |       0.409239 |   0.407798 |
| barab-szabi-1        |     0.596121 |       0.413224 |   0.428161 |
| Bori_Aron_solution-1 |     0.583283 |       0.536207 |   0.53732  |
| k-d_tree_pandas      |     0.597029 |       0.400352 |   0.560421 |
| solution-1           |     7.61629  |       1e-06    |   0.851894 |
| k-d_tree_sklearn     |     3.1086   |       1.43518  |   1.0419   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.594746 |       0.411464 |   0.410551 |
| k-d_tree_polars      |     0.592532 |       0.422043 |   0.418564 |
| barab-szabi-1        |     0.58799  |       0.413126 |   0.431864 |
| Bori_Aron_solution-1 |     0.587982 |       0.549164 |   0.540187 |
| k-d_tree_pandas      |     0.590578 |       0.395569 |   0.552647 |
| k-d_tree_sklearn     |     0.604223 |       0.978205 |   1.04425  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590985 |       0.421132 |   0.43046  |
| k-d_tree_polars      |     0.591174 |       0.445283 |   0.434766 |
| barab-szabi-1        |     0.590464 |       0.454764 |   0.451488 |
| Bori_Aron_solution-1 |     0.580276 |       0.582702 |   0.546839 |
| k-d_tree_pandas      |     0.596429 |       0.415134 |   0.598889 |
| k-d_tree_sklearn     |     0.621678 |       1.01072  |   1.09902  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591162 |       0.488307 |   0.451885 |
| k-d_tree_polars      |     0.600326 |       0.556442 |   0.545443 |
| barab-szabi-1        |     0.588558 |       0.553674 |   0.547837 |
| Bori_Aron_solution-1 |     0.584746 |       0.75578  |   0.556837 |
| k-d_tree_pandas      |     0.585316 |       0.490751 |   0.728953 |
| k-d_tree_sklearn     |     0.601456 |       1.24511  |   1.12796  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.594559 |       0.735794 |   0.489438 |
| Bori_Aron_solution-1 |     0.589188 |       1.40775  |   0.588374 |
| k-d_tree_polars      |     0.593383 |       0.882651 |   0.900691 |
| barab-szabi-1        |     0.590157 |       0.885468 |   0.933763 |
| k-d_tree_pandas      |     0.589703 |       0.758112 |   1.19282  |
| k-d_tree_sklearn     |     0.594821 |       2.08686  |   1.23571  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.594593 |        6.04897 |   0.897269 |
| Bori_Aron_solution-1 |     0.595496 |       11.3865  |   0.915098 |
| k-d_tree_sklearn     |     0.590172 |       17.8961  |   1.36155  |
| barab-szabi-1        |     0.598602 |        4.95791 |   7.34896  |
| k-d_tree_polars      |     0.590276 |        4.99668 |   7.3963   |
| k-d_tree_pandas      |     0.601807 |        3.86752 |   7.7389   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.597316 |        88.8743 |    3.91775 |
| k-d_tree_sklearn     |     0.616833 |       260.068  |    4.55371 |
| Bori_Aron_solution-1 |     0.631306 |       160.011  |   17.5542  |