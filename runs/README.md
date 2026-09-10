# 2026-09-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463857 |       0.429544 |   0.429644 |
| k-d_tree_polars      |     0.451732 |       0.408177 |   0.431345 |
| Bori_Aron_solution-1 |     0.448316 |       0.531386 |   0.529017 |
| k-d_tree_pandas      |     0.45399  |       0.378282 |   0.529424 |
| solution-1           |     7.9237   |       1e-06    |   0.578138 |
| barab-szabi-1        |     8.61576  |       0.607913 |   0.707981 |
| k-d_tree_sklearn     |     3.12533  |       1.30581  |   1.03597  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.469057 |       0.413473 |   0.435072 |
| barab-szabi-1        |     0.463189 |       0.421675 |   0.440434 |
| barab-szabi-2        |     0.462652 |       0.431102 |   0.445526 |
| Bori_Aron_solution-1 |     0.455295 |       0.541968 |   0.534543 |
| k-d_tree_pandas      |     0.460438 |       0.386225 |   0.539799 |
| k-d_tree_sklearn     |     0.465105 |       0.980081 |   1.05996  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469059 |       0.45778  |   0.444817 |
| k-d_tree_polars      |     0.469626 |       0.451122 |   0.459675 |
| barab-szabi-1        |     0.459079 |       0.446943 |   0.462298 |
| Bori_Aron_solution-1 |     0.456929 |       0.581393 |   0.551309 |
| k-d_tree_pandas      |     0.464653 |       0.404534 |   0.5743   |
| k-d_tree_sklearn     |     0.475877 |       1.05095  |   1.07174  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.461375 |       0.507267 |   0.474061 |
| Bori_Aron_solution-1 |     0.460473 |       0.775797 |   0.557625 |
| k-d_tree_polars      |     0.472028 |       0.569793 |   0.571356 |
| barab-szabi-1        |     0.471869 |       0.562417 |   0.586483 |
| k-d_tree_pandas      |     0.472224 |       0.514317 |   0.719247 |
| k-d_tree_sklearn     |     0.473638 |       1.28257  |   1.11404  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.45859  |       0.758217 |   0.506375 |
| Bori_Aron_solution-1 |     0.461812 |       1.47242  |   0.600138 |
| k-d_tree_polars      |     0.471626 |       0.899885 |   0.941828 |
| barab-szabi-1        |     0.461042 |       0.891602 |   0.975559 |
| k-d_tree_sklearn     |     0.466549 |       2.1021   |   1.14018  |
| k-d_tree_pandas      |     0.467495 |       0.770657 |   1.1745   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469741 |        5.52823 |   0.722926 |
| k-d_tree_sklearn     |     0.471839 |       16.8073  |   1.23764  |
| Bori_Aron_solution-1 |     0.459142 |       11.1223  |   1.27769  |
| barab-szabi-1        |     0.461106 |        5.14473 |   7.15304  |
| k-d_tree_polars      |     0.47454  |        5.12948 |   7.32904  |
| k-d_tree_pandas      |     0.461707 |        3.93483 |   7.56376  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567365 |         74.058 |    2.57213 |
| k-d_tree_sklearn     |     0.751459 |        256.769 |    3.60303 |
| Bori_Aron_solution-1 |     0.475879 |        154.981 |   23.3221  |