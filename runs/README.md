# 2024-09-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618178 |       0.38909  |   0.388806 |
| barab-szabi-1        |     0.60953  |       0.411899 |   0.390402 |
| k-d_tree_polars      |     4.41544  |       0.481326 |   0.455046 |
| Bori_Aron_solution-1 |     4.57137  |       0.630976 |   0.472721 |
| k-d_tree_pandas      |     0.6133   |       0.396665 |   0.547161 |
| solution-1           |     7.84978  |       1e-06    |   0.56592  |
| k-d_tree_sklearn     |     3.15895  |       1.46445  |   0.798737 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608339 |       0.387727 |   0.389558 |
| k-d_tree_polars      |     0.615387 |       0.408895 |   0.393087 |
| barab-szabi-1        |     0.620386 |       0.413787 |   0.394605 |
| Bori_Aron_solution-1 |     0.611738 |       0.537214 |   0.529812 |
| k-d_tree_pandas      |     0.645211 |       0.383255 |   0.570114 |
| k-d_tree_sklearn     |     0.62349  |       0.90132  |   0.703814 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615705 |       0.405129 |   0.402378 |
| k-d_tree_polars      |     0.619458 |       0.433266 |   0.423304 |
| barab-szabi-1        |     0.610988 |       0.435578 |   0.426534 |
| Bori_Aron_solution-1 |     0.622156 |       0.57144  |   0.550472 |
| k-d_tree_pandas      |     0.619186 |       0.403874 |   0.603034 |
| k-d_tree_sklearn     |     0.62158  |       0.951699 |   0.741296 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615654 |       0.469223 |   0.429037 |
| k-d_tree_polars      |     0.61624  |       0.534315 |   0.519557 |
| barab-szabi-1        |     0.611403 |       0.537815 |   0.532975 |
| Bori_Aron_solution-1 |     0.620637 |       0.778058 |   0.542511 |
| k-d_tree_pandas      |     0.623808 |       0.478247 |   0.723367 |
| k-d_tree_sklearn     |     0.618856 |       1.17978  |   0.796913 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614073 |       0.716201 |   0.470601 |
| Bori_Aron_solution-1 |     0.610038 |       1.41812  |   0.572814 |
| k-d_tree_sklearn     |     0.646411 |       2.02052  |   0.881327 |
| k-d_tree_polars      |     0.612083 |       0.900539 |   0.882764 |
| barab-szabi-1        |     0.643821 |       0.866253 |   0.926368 |
| k-d_tree_pandas      |     0.620969 |       0.751039 |   1.19839  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.672267 |        5.30712 |   0.746725 |
| Bori_Aron_solution-1 |     0.620996 |       10.794   |   0.833495 |
| k-d_tree_sklearn     |     0.648403 |       17.1559  |   1.02427  |
| barab-szabi-1        |     0.62222  |        4.88246 |   6.68324  |
| k-d_tree_polars      |     0.630968 |        4.95195 |   6.82036  |
| k-d_tree_pandas      |     0.64915  |        3.93706 |   7.28826  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.770109 |        74.7011 |    3.76913 |
| k-d_tree_sklearn     |     0.973668 |       240.665  |    3.97231 |
| Bori_Aron_solution-1 |     0.620317 |       152.242  |   16.097   |