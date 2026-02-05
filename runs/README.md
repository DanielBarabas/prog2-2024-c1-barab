# 2026-02-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49663  |       0.489328 |   0.40714  |
| k-d_tree_polars      |     0.495232 |       0.385218 |   0.417918 |
| barab-szabi-1        |     0.508159 |       0.384548 |   0.426634 |
| solution-1           |     7.7191   |       1e-06    |   0.473031 |
| Bori_Aron_solution-1 |     0.505025 |       0.525091 |   0.516833 |
| k-d_tree_pandas      |     9.37641  |       0.385251 |   0.608504 |
| k-d_tree_sklearn     |     2.94233  |       1.01733  |   1.01866  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.501492 |       0.427788 |   0.419782 |
| barab-szabi-1        |     0.505379 |       0.391544 |   0.421447 |
| k-d_tree_polars      |     0.537591 |       0.395481 |   0.42991  |
| Bori_Aron_solution-1 |     0.508967 |       0.540584 |   0.529191 |
| k-d_tree_pandas      |     0.507927 |       0.381374 |   0.538045 |
| k-d_tree_sklearn     |     0.506907 |       0.925929 |   1.03215  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.511915 |       0.426116 |   0.432981 |
| k-d_tree_polars      |     0.505319 |       0.418813 |   0.448748 |
| barab-szabi-1        |     0.510188 |       0.419897 |   0.451977 |
| Bori_Aron_solution-1 |     0.513745 |       0.57743  |   0.535647 |
| k-d_tree_pandas      |     0.507417 |       0.397408 |   0.576468 |
| k-d_tree_sklearn     |     0.510719 |       0.975078 |   1.05609  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.516304 |       0.493177 |   0.456064 |
| Bori_Aron_solution-1 |     0.501991 |       0.763059 |   0.545475 |
| k-d_tree_polars      |     0.494477 |       0.542662 |   0.551894 |
| barab-szabi-1        |     0.515319 |       0.549779 |   0.55896  |
| k-d_tree_pandas      |     0.501942 |       0.480707 |   0.71013  |
| k-d_tree_sklearn     |     0.499996 |       1.20541  |   1.09556  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.513441 |       0.707899 |   0.499254 |
| Bori_Aron_solution-1 |     0.507134 |       1.40918  |   0.561066 |
| k-d_tree_polars      |     0.505819 |       0.907186 |   0.886508 |
| barab-szabi-1        |     0.498657 |       0.891805 |   0.89821  |
| k-d_tree_sklearn     |     0.490635 |       2.0219   |   1.14237  |
| k-d_tree_pandas      |     0.512104 |       0.803829 |   1.14458  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.502542 |        4.68945 |   0.722637 |
| Bori_Aron_solution-1 |     0.509394 |       10.7807  |   0.829516 |
| k-d_tree_sklearn     |     0.507407 |       15.3813  |   1.26759  |
| barab-szabi-1        |     0.504838 |        5.17889 |   6.08688  |
| k-d_tree_polars      |     0.496773 |        5.46071 |   6.24744  |
| k-d_tree_pandas      |     0.509362 |        4.26151 |   6.62176  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.517618 |        65.5512 |    2.56377 |
| k-d_tree_sklearn     |     0.511464 |       215.098  |    3.75307 |
| Bori_Aron_solution-1 |     0.583735 |       142.409  |   17.6363  |