# 2025-02-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.83526  |       1e-06    |   0.366615 |
| barab-szabi-2        |     8.12046  |       0.471432 |   0.403912 |
| k-d_tree_polars      |     0.58949  |       0.402946 |   0.410047 |
| barab-szabi-1        |     0.59736  |       0.409203 |   0.415124 |
| Bori_Aron_solution-1 |     0.586076 |       0.544844 |   0.552451 |
| k-d_tree_pandas      |     0.615111 |       0.405527 |   0.586257 |
| k-d_tree_sklearn     |     3.21835  |       0.997849 |   1.02751  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620609 |       0.4134   |   0.411987 |
| barab-szabi-1        |     0.59575  |       0.413997 |   0.415264 |
| k-d_tree_polars      |     0.617051 |       0.420204 |   0.421016 |
| k-d_tree_pandas      |     0.60632  |       0.414405 |   0.550477 |
| Bori_Aron_solution-1 |     0.594348 |       0.575861 |   0.559372 |
| k-d_tree_sklearn     |     0.618321 |       0.990954 |   1.04945  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.595317 |       0.42902  |   0.421005 |
| k-d_tree_polars      |     0.595198 |       0.434285 |   0.439903 |
| barab-szabi-1        |     0.594805 |       0.445106 |   0.461921 |
| Bori_Aron_solution-1 |     0.581321 |       0.580931 |   0.545145 |
| k-d_tree_pandas      |     0.620056 |       0.402878 |   0.595973 |
| k-d_tree_sklearn     |     0.600861 |       1.00349  |   1.0963   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.596756 |       0.478949 |   0.445369 |
| k-d_tree_polars      |     0.597212 |       0.540904 |   0.55055  |
| barab-szabi-1        |     0.60778  |       0.555629 |   0.550945 |
| Bori_Aron_solution-1 |     0.58865  |       0.754751 |   0.560201 |
| k-d_tree_pandas      |     0.597464 |       0.485175 |   0.723264 |
| k-d_tree_sklearn     |     0.596648 |       1.21446  |   1.14976  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590123 |       0.723553 |   0.48436  |
| Bori_Aron_solution-1 |     0.585181 |       1.37538  |   0.581415 |
| k-d_tree_polars      |     0.592448 |       0.865718 |   0.89523  |
| barab-szabi-1        |     0.592863 |       0.875178 |   0.926577 |
| k-d_tree_pandas      |     0.605233 |       0.751229 |   1.19119  |
| k-d_tree_sklearn     |     0.601813 |       2.05218  |   1.20885  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.597191 |        5.5364  |   0.777504 |
| Bori_Aron_solution-1 |     0.593338 |       10.8938  |   0.889024 |
| k-d_tree_sklearn     |     0.594449 |       17.5909  |   1.3537   |
| barab-szabi-1        |     0.594273 |        4.93328 |   6.80035  |
| k-d_tree_polars      |     0.597585 |        4.98485 |   6.81594  |
| k-d_tree_pandas      |     0.597933 |        3.87263 |   7.27807  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598131 |        83.6123 |    3.20398 |
| k-d_tree_sklearn     |     0.603033 |       254.133  |    4.65063 |
| Bori_Aron_solution-1 |     0.70246  |       157.644  |   16.0128  |