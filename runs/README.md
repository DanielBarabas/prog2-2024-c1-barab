# 2025-12-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.518084 |       0.540241 |   0.428569 |
| k-d_tree_polars      |     0.530707 |       0.405633 |   0.433656 |
| barab-szabi-1        |     0.53033  |       0.404798 |   0.434144 |
| solution-1           |     7.66936  |       1e-06    |   0.476001 |
| Bori_Aron_solution-1 |     0.524634 |       0.54599  |   0.580479 |
| k-d_tree_pandas      |     8.36189  |       0.458562 |   0.720491 |
| k-d_tree_sklearn     |     3.12338  |       1.23013  |   1.06762  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528857 |       0.430435 |   0.432627 |
| barab-szabi-1        |     0.531438 |       0.411389 |   0.436921 |
| k-d_tree_polars      |     0.536032 |       0.410563 |   0.446157 |
| Bori_Aron_solution-1 |     0.519196 |       0.55532  |   0.544142 |
| k-d_tree_pandas      |     0.528101 |       0.39097  |   0.557297 |
| k-d_tree_sklearn     |     0.528651 |       0.96662  |   1.08209  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525735 |       0.442828 |   0.443744 |
| barab-szabi-1        |     0.529479 |       0.439038 |   0.45989  |
| k-d_tree_polars      |     0.528006 |       0.437234 |   0.462252 |
| Bori_Aron_solution-1 |     0.520418 |       0.604889 |   0.547271 |
| k-d_tree_pandas      |     0.534357 |       0.409645 |   0.596034 |
| k-d_tree_sklearn     |     0.532432 |       1.01086  |   1.11953  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529129 |       0.506581 |   0.474471 |
| k-d_tree_polars      |     0.523475 |       0.571993 |   0.557682 |
| Bori_Aron_solution-1 |     0.518971 |       0.78049  |   0.561239 |
| barab-szabi-1        |     0.530224 |       0.559052 |   0.56939  |
| k-d_tree_pandas      |     0.530919 |       0.501199 |   0.735003 |
| k-d_tree_sklearn     |     0.531923 |       1.2479   |   1.13394  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.523651 |       0.746235 |   0.50629  |
| Bori_Aron_solution-1 |     0.524705 |       1.45764  |   0.585877 |
| k-d_tree_polars      |     0.523776 |       0.94058  |   0.916297 |
| barab-szabi-1        |     0.522154 |       0.919312 |   0.944874 |
| k-d_tree_pandas      |     0.53036  |       0.817098 |   1.18144  |
| k-d_tree_sklearn     |     0.528631 |       2.09968  |   1.22113  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.524143 |        5.15856 |   0.75125  |
| Bori_Aron_solution-1 |     0.521175 |       11.1724  |   0.845588 |
| k-d_tree_sklearn     |     0.532509 |       16.7571  |   1.31067  |
| barab-szabi-1        |     0.528465 |        5.31865 |   6.62077  |
| k-d_tree_polars      |     0.528399 |        5.39357 |   6.65125  |
| k-d_tree_pandas      |     0.526984 |        4.4434  |   7.03137  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.526024 |        75.8309 |    2.75708 |
| k-d_tree_sklearn     |     0.564551 |       232.129  |    4.3014  |
| Bori_Aron_solution-1 |     0.691372 |       154.15   |   18.229   |