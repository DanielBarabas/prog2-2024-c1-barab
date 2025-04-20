# 2025-04-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.569039 |       0.414159 |   0.422508 |
| barab-szabi-2        |     0.562875 |       0.415483 |   0.425058 |
| solution-1           |     7.61163  |       1e-06    |   0.427654 |
| barab-szabi-1        |     0.564336 |       0.421674 |   0.429488 |
| Bori_Aron_solution-1 |     0.560428 |       0.56907  |   0.564657 |
| k-d_tree_pandas      |     8.1285   |       0.416421 |   0.612765 |
| k-d_tree_sklearn     |     3.0492   |       1.02006  |   1.07827  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586674 |       0.419229 |   0.416668 |
| k-d_tree_polars      |     0.581337 |       0.419155 |   0.421593 |
| barab-szabi-1        |     0.577184 |       0.420357 |   0.424101 |
| Bori_Aron_solution-1 |     0.570669 |       0.561985 |   0.560445 |
| k-d_tree_pandas      |     0.577196 |       0.398988 |   0.57423  |
| k-d_tree_sklearn     |     0.580591 |       0.977581 |   1.09584  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577224 |       0.429808 |   0.430103 |
| k-d_tree_polars      |     0.575797 |       0.445283 |   0.446712 |
| barab-szabi-1        |     0.581324 |       0.443564 |   0.452901 |
| Bori_Aron_solution-1 |     0.571997 |       0.595837 |   0.564889 |
| k-d_tree_pandas      |     0.573912 |       0.416878 |   0.618208 |
| k-d_tree_sklearn     |     0.582212 |       1.03557  |   1.08833  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577281 |       0.497011 |   0.45611  |
| k-d_tree_polars      |     0.583492 |       0.550918 |   0.547487 |
| barab-szabi-1        |     0.575897 |       0.550562 |   0.559779 |
| Bori_Aron_solution-1 |     0.575627 |       0.779131 |   0.572407 |
| k-d_tree_pandas      |     0.575662 |       0.505449 |   0.742617 |
| k-d_tree_sklearn     |     0.578798 |       1.24586  |   1.14568  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.576415 |       0.743085 |   0.496015 |
| Bori_Aron_solution-1 |     0.568873 |       1.42678  |   0.599503 |
| k-d_tree_polars      |     0.577516 |       0.892213 |   0.909455 |
| barab-szabi-1        |     0.575387 |       0.898387 |   0.952942 |
| k-d_tree_pandas      |     0.57813  |       0.773556 |   1.19742  |
| k-d_tree_sklearn     |     0.577247 |       2.12216  |   1.23382  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574855 |        5.44088 |   0.730211 |
| Bori_Aron_solution-1 |     0.583492 |       10.8788  |   0.877465 |
| k-d_tree_sklearn     |     0.579854 |       16.744   |   1.34445  |
| barab-szabi-1        |     0.575385 |        5.05143 |   6.71793  |
| k-d_tree_polars      |     0.581632 |        5.12145 |   6.74055  |
| k-d_tree_pandas      |     0.584684 |        3.9663  |   7.15533  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.887419 |        73.6865 |    2.80886 |
| k-d_tree_sklearn     |     0.645985 |       232.688  |    4.35717 |
| Bori_Aron_solution-1 |     0.572202 |       154.098  |   17.9193  |