# 2024-11-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.615473 |       0.395671 |   0.385306 |
| barab-szabi-2        |     0.614399 |       0.382    |   0.386312 |
| k-d_tree_polars      |     0.609233 |       0.394753 |   0.388618 |
| Bori_Aron_solution-1 |     0.599955 |       0.544637 |   0.516551 |
| k-d_tree_pandas      |     0.618654 |       0.375541 |   0.517948 |
| solution-1           |     7.44107  |       1e-06    |   0.653565 |
| k-d_tree_sklearn     |    10.0281   |       1.36936  |   0.979988 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610322 |       0.386078 |   0.386683 |
| barab-szabi-1        |     0.611174 |       0.401577 |   0.391645 |
| k-d_tree_polars      |     0.612634 |       0.397904 |   0.39223  |
| k-d_tree_pandas      |     0.604949 |       0.380841 |   0.5278   |
| Bori_Aron_solution-1 |     0.603827 |       0.538284 |   0.545028 |
| k-d_tree_sklearn     |     0.618256 |       0.876644 |   0.955758 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619634 |       0.405438 |   0.405016 |
| barab-szabi-1        |     0.61396  |       0.427951 |   0.420318 |
| k-d_tree_polars      |     0.622274 |       0.42552  |   0.423986 |
| Bori_Aron_solution-1 |     0.642044 |       0.562752 |   0.51547  |
| k-d_tree_pandas      |     0.606954 |       0.396964 |   0.569982 |
| k-d_tree_sklearn     |     0.620608 |       0.955123 |   1.0044   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606501 |       0.466336 |   0.422487 |
| k-d_tree_polars      |     0.613885 |       0.532012 |   0.509348 |
| barab-szabi-1        |     0.6123   |       0.531181 |   0.526908 |
| Bori_Aron_solution-1 |     0.599789 |       0.742902 |   0.53079  |
| k-d_tree_pandas      |     0.609859 |       0.476354 |   0.699963 |
| k-d_tree_sklearn     |     0.612181 |       1.14859  |   1.02678  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605517 |       0.706102 |   0.459043 |
| Bori_Aron_solution-1 |     0.600678 |       1.37309  |   0.553724 |
| k-d_tree_polars      |     0.603276 |       0.855167 |   0.852234 |
| barab-szabi-1        |     0.619196 |       0.862732 |   0.890815 |
| k-d_tree_sklearn     |     0.614764 |       1.9636   |   1.11488  |
| k-d_tree_pandas      |     0.606712 |       0.771177 |   1.12646  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.601379 |        5.36832 |   0.73988  |
| Bori_Aron_solution-1 |     0.602163 |       10.8179  |   0.851358 |
| k-d_tree_sklearn     |     0.610337 |       15.7656  |   1.23113  |
| k-d_tree_polars      |     0.604578 |        4.8513  |   6.55764  |
| barab-szabi-1        |     0.610189 |        4.87495 |   6.58215  |
| k-d_tree_pandas      |     0.612803 |        3.84585 |   6.89988  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.648334 |        72.1499 |    2.92302 |
| k-d_tree_sklearn     |     0.61475  |       225.141  |    4.36242 |
| Bori_Aron_solution-1 |     0.620475 |       154.767  |   15.1479  |