# 2025-09-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.61817  |       0.749538 |   0.419385 |
| k-d_tree_polars      |     0.524185 |       0.401961 |   0.421577 |
| barab-szabi-1        |     0.521229 |       0.397997 |   0.430736 |
| solution-1           |     8.43834  |       1e-06    |   0.455234 |
| Bori_Aron_solution-1 |     0.518345 |       0.540406 |   0.550292 |
| k-d_tree_pandas      |     0.531681 |       0.386109 |   0.559653 |
| k-d_tree_sklearn     |     3.0332   |       1.11389  |   1.05353  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542732 |       0.421694 |   0.425591 |
| barab-szabi-1        |     0.538588 |       0.406187 |   0.432398 |
| k-d_tree_polars      |     0.553045 |       0.409602 |   0.433942 |
| Bori_Aron_solution-1 |     0.53285  |       0.554487 |   0.539667 |
| k-d_tree_pandas      |     0.546609 |       0.398724 |   0.558031 |
| k-d_tree_sklearn     |     0.538875 |       0.959255 |   1.06055  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547446 |       0.434935 |   0.437658 |
| k-d_tree_polars      |     0.539639 |       0.432821 |   0.453032 |
| barab-szabi-1        |     0.537971 |       0.432168 |   0.463589 |
| Bori_Aron_solution-1 |     0.535471 |       0.586626 |   0.545784 |
| k-d_tree_pandas      |     0.533986 |       0.404106 |   0.607705 |
| k-d_tree_sklearn     |     0.539503 |       1.02993  |   1.10129  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540532 |       0.498384 |   0.463821 |
| k-d_tree_polars      |     0.536287 |       0.544833 |   0.547096 |
| Bori_Aron_solution-1 |     0.536298 |       0.76223  |   0.561326 |
| barab-szabi-1        |     0.538531 |       0.540918 |   0.561953 |
| k-d_tree_pandas      |     0.539411 |       0.486246 |   0.730695 |
| k-d_tree_sklearn     |     0.537443 |       1.22273  |   1.14068  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538407 |       0.752954 |   0.502664 |
| Bori_Aron_solution-1 |     0.535301 |       1.40864  |   0.586959 |
| k-d_tree_polars      |     0.545876 |       0.883965 |   0.899948 |
| barab-szabi-1        |     0.534798 |       0.880969 |   0.946267 |
| k-d_tree_pandas      |     0.544517 |       0.760449 |   1.17503  |
| k-d_tree_sklearn     |     0.541497 |       2.06645  |   1.20759  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536368 |        5.19499 |   0.720587 |
| Bori_Aron_solution-1 |     0.532433 |       10.563   |   0.840875 |
| k-d_tree_sklearn     |     0.543596 |       16.1147  |   1.30738  |
| k-d_tree_polars      |     0.541889 |        5.04601 |   6.52283  |
| barab-szabi-1        |     0.542862 |        5.04696 |   6.53109  |
| k-d_tree_pandas      |     0.539261 |        3.9592  |   6.98111  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53981  |        72.5177 |    2.64024 |
| k-d_tree_sklearn     |     1.15832  |       228.368  |    4.00362 |
| Bori_Aron_solution-1 |     0.546385 |       142.404  |   17.7925  |