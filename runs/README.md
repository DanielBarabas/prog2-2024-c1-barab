# 2024-09-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.6609   |       1e-06    |   0.357682 |
| barab-szabi-2        |     0.620657 |       0.397436 |   0.401238 |
| k-d_tree_polars      |     4.28085  |       0.417598 |   0.403194 |
| barab-szabi-1        |     0.636116 |       0.412557 |   0.40554  |
| Bori_Aron_solution-1 |     4.55585  |       0.513805 |   0.460045 |
| k-d_tree_pandas      |     0.604206 |       0.38565  |   0.544016 |
| k-d_tree_sklearn     |     3.06989  |       0.921426 |   0.96948  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.646998 |       0.413258 |   0.411411 |
| k-d_tree_polars      |     0.678892 |       0.427841 |   0.414669 |
| barab-szabi-1        |     0.636941 |       0.449944 |   0.433633 |
| k-d_tree_pandas      |     0.633137 |       0.424428 |   0.546394 |
| Bori_Aron_solution-1 |     0.637293 |       0.573321 |   0.559093 |
| k-d_tree_sklearn     |     0.622519 |       0.923786 |   1.03688  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625286 |       0.416165 |   0.418412 |
| k-d_tree_polars      |     0.632956 |       0.452528 |   0.435758 |
| barab-szabi-1        |     0.63231  |       0.456592 |   0.449989 |
| Bori_Aron_solution-1 |     0.63636  |       0.593874 |   0.537131 |
| k-d_tree_pandas      |     0.643088 |       0.429246 |   0.600977 |
| k-d_tree_sklearn     |     0.638383 |       0.986886 |   1.00782  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618919 |       0.467804 |   0.433957 |
| barab-szabi-1        |     0.628127 |       0.538887 |   0.533531 |
| Bori_Aron_solution-1 |     0.630447 |       0.774039 |   0.565045 |
| k-d_tree_polars      |     0.619495 |       0.55242  |   0.568603 |
| k-d_tree_pandas      |     0.641937 |       0.506794 |   0.729031 |
| k-d_tree_sklearn     |     0.627192 |       1.19984  |   1.04633  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612812 |       0.727901 |   0.497933 |
| Bori_Aron_solution-1 |     0.61535  |       1.41774  |   0.568934 |
| k-d_tree_polars      |     0.618316 |       0.867796 |   0.873953 |
| barab-szabi-1        |     0.640026 |       0.876884 |   0.931849 |
| k-d_tree_sklearn     |     0.624512 |       1.96446  |   1.12624  |
| k-d_tree_pandas      |     0.616708 |       0.745562 |   1.18164  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610804 |        5.34222 |   0.748511 |
| Bori_Aron_solution-1 |     0.632981 |       10.8536  |   0.820998 |
| k-d_tree_sklearn     |     0.615468 |       16.0389  |   1.25149  |
| barab-szabi-1        |     0.616389 |        4.84347 |   6.71779  |
| k-d_tree_polars      |     0.619973 |        4.79571 |   6.74305  |
| k-d_tree_pandas      |     0.623443 |        3.85318 |   6.98426  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.752924 |        75.1379 |    3.76922 |
| k-d_tree_sklearn     |     1.05996  |       233.202  |    4.24114 |
| Bori_Aron_solution-1 |     0.614691 |       156.286  |   17.5828  |