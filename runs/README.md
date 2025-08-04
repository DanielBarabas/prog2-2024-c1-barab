# 2025-08-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.02334  |       0.798669 |   0.420619 |
| k-d_tree_polars      |     0.565746 |       0.404057 |   0.425672 |
| barab-szabi-1        |     0.56285  |       0.407254 |   0.42709  |
| Bori_Aron_solution-1 |     0.536129 |       0.547662 |   0.542327 |
| k-d_tree_pandas      |     0.561441 |       0.391014 |   0.550249 |
| solution-1           |     7.88179  |       1e-06    |   0.691296 |
| k-d_tree_sklearn     |     3.30959  |       1.11186  |   1.05802  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.559084 |       0.413787 |   0.43085  |
| k-d_tree_polars      |     0.557852 |       0.412747 |   0.435698 |
| barab-szabi-2        |     0.557129 |       0.419121 |   0.441811 |
| Bori_Aron_solution-1 |     0.547278 |       0.554788 |   0.552154 |
| k-d_tree_pandas      |     0.559173 |       0.393939 |   0.556085 |
| k-d_tree_sklearn     |     0.559141 |       0.969859 |   1.0623   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56171  |       0.441272 |   0.435879 |
| k-d_tree_polars      |     0.564575 |       0.438869 |   0.451759 |
| barab-szabi-1        |     0.553265 |       0.431504 |   0.457921 |
| Bori_Aron_solution-1 |     0.547373 |       0.592543 |   0.553185 |
| k-d_tree_pandas      |     0.563609 |       0.411598 |   0.600731 |
| k-d_tree_sklearn     |     0.558545 |       1.01738  |   1.08635  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554805 |       0.509789 |   0.467848 |
| k-d_tree_polars      |     0.557546 |       0.551091 |   0.551545 |
| barab-szabi-1        |     0.563985 |       0.550216 |   0.561065 |
| Bori_Aron_solution-1 |     0.548679 |       0.764536 |   0.562101 |
| k-d_tree_pandas      |     0.556451 |       0.493207 |   0.740483 |
| k-d_tree_sklearn     |     0.566532 |       1.25783  |   1.13163  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554648 |       0.751054 |   0.500563 |
| Bori_Aron_solution-1 |     0.556968 |       1.41261  |   0.599458 |
| k-d_tree_polars      |     0.565462 |       0.886191 |   0.905811 |
| barab-szabi-1        |     0.552997 |       0.89534  |   0.947407 |
| k-d_tree_pandas      |     0.55097  |       0.765666 |   1.18387  |
| k-d_tree_sklearn     |     0.566315 |       2.10314  |   1.21184  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562105 |        5.19983 |   0.725354 |
| Bori_Aron_solution-1 |     0.546515 |       10.6135  |   0.846378 |
| k-d_tree_sklearn     |     0.560377 |       16.1027  |   1.31271  |
| k-d_tree_polars      |     0.562213 |        5.04904 |   6.53062  |
| barab-szabi-1        |     0.559528 |        5.00698 |   6.63579  |
| k-d_tree_pandas      |     0.555689 |        3.94272 |   7.00512  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55628  |        72.8217 |    2.67841 |
| k-d_tree_sklearn     |     0.806006 |       230.159  |    3.9564  |
| Bori_Aron_solution-1 |     0.560368 |       142.463  |   18.0158  |