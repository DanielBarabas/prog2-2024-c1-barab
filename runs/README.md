# 2025-10-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.558503 |       0.414135 |   0.441403 |
| barab-szabi-2        |     0.712096 |       0.5855   |   0.443216 |
| barab-szabi-1        |     0.568687 |       0.41748  |   0.447193 |
| Bori_Aron_solution-1 |     0.560829 |       0.574913 |   0.566886 |
| solution-1           |     8.05495  |       1e-06    |   0.690544 |
| k-d_tree_pandas      |     9.24164  |       0.457321 |   0.802032 |
| k-d_tree_sklearn     |     3.32485  |       1.53248  |   1.10769  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.561759 |       0.424519 |   0.444162 |
| barab-szabi-2        |     0.568575 |       0.442504 |   0.445965 |
| k-d_tree_polars      |     0.559776 |       0.426769 |   0.470373 |
| Bori_Aron_solution-1 |     0.553709 |       0.5736   |   0.566529 |
| k-d_tree_pandas      |     0.561818 |       0.404492 |   0.587927 |
| k-d_tree_sklearn     |     0.582583 |       1.01455  |   1.13556  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564649 |       0.452818 |   0.454042 |
| k-d_tree_polars      |     0.566065 |       0.454712 |   0.472362 |
| barab-szabi-1        |     0.561508 |       0.45618  |   0.485187 |
| Bori_Aron_solution-1 |     0.554522 |       0.617539 |   0.578828 |
| k-d_tree_pandas      |     0.55991  |       0.425582 |   0.619507 |
| k-d_tree_sklearn     |     0.559266 |       1.1188   |   1.15934  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55968  |       0.519522 |   0.482503 |
| k-d_tree_polars      |     0.562247 |       0.582541 |   0.56744  |
| barab-szabi-1        |     0.560213 |       0.579848 |   0.581067 |
| Bori_Aron_solution-1 |     0.551625 |       0.796666 |   0.593575 |
| k-d_tree_pandas      |     0.574617 |       0.519449 |   0.752894 |
| k-d_tree_sklearn     |     0.563829 |       1.31888  |   1.19799  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562576 |       0.775801 |   0.524889 |
| Bori_Aron_solution-1 |     0.554009 |       1.51615  |   0.60555  |
| k-d_tree_polars      |     0.560525 |       0.972586 |   0.94462  |
| barab-szabi-1        |     0.559956 |       0.968489 |   0.980323 |
| k-d_tree_pandas      |     0.558973 |       0.84531  |   1.22121  |
| k-d_tree_sklearn     |     0.560073 |       2.24301  |   1.28804  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566285 |        5.5816  |   0.775484 |
| Bori_Aron_solution-1 |     0.549216 |       11.6852  |   0.872212 |
| k-d_tree_sklearn     |     0.562205 |       17.9752  |   1.3881   |
| k-d_tree_polars      |     0.560178 |        5.7084  |   6.89821  |
| barab-szabi-1        |     0.561092 |        5.70273 |   6.99433  |
| k-d_tree_pandas      |     0.558841 |        4.65297 |   7.40305  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560437 |        85.7523 |    2.90495 |
| k-d_tree_sklearn     |     0.582641 |       248.837  |    4.26036 |
| Bori_Aron_solution-1 |     0.785517 |       152.035  |   18.5828  |