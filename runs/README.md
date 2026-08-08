# 2026-08-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48283  |       0.445791 |   0.467834 |
| barab-szabi-1        |     0.478482 |       0.439884 |   0.496113 |
| Bori_Aron_solution-1 |     0.456713 |       0.558513 |   0.551358 |
| k-d_tree_pandas      |     0.473279 |       0.385962 |   0.552246 |
| solution-1           |     7.87599  |       1e-06    |   0.577018 |
| k-d_tree_polars      |     8.16626  |       0.487162 |   0.689286 |
| k-d_tree_sklearn     |     2.91832  |       1.14143  |   1.06659  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470633 |       0.448712 |   0.440725 |
| k-d_tree_polars      |     0.487133 |       0.427477 |   0.45023  |
| barab-szabi-1        |     0.472081 |       0.421475 |   0.458298 |
| Bori_Aron_solution-1 |     0.465178 |       0.557257 |   0.550744 |
| k-d_tree_pandas      |     0.504412 |       0.403584 |   0.558044 |
| k-d_tree_sklearn     |     0.490219 |       1.0026   |   1.07702  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47351  |       0.456064 |   0.456308 |
| barab-szabi-1        |     0.476917 |       0.463589 |   0.477457 |
| k-d_tree_polars      |     0.470133 |       0.451809 |   0.479415 |
| Bori_Aron_solution-1 |     0.478516 |       0.595352 |   0.551866 |
| k-d_tree_pandas      |     0.479508 |       0.407797 |   0.605877 |
| k-d_tree_sklearn     |     0.477696 |       1.04347  |   1.08895  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47718  |       0.516264 |   0.487276 |
| Bori_Aron_solution-1 |     0.466918 |       0.783822 |   0.57006  |
| barab-szabi-1        |     0.474125 |       0.585219 |   0.578192 |
| k-d_tree_polars      |     0.475437 |       0.583703 |   0.580617 |
| k-d_tree_pandas      |     0.47876  |       0.506134 |   0.745519 |
| k-d_tree_sklearn     |     0.477937 |       1.28913  |   1.14011  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471941 |       0.7307   |   0.520223 |
| Bori_Aron_solution-1 |     0.473221 |       1.40259  |   0.582339 |
| k-d_tree_polars      |     0.476472 |       0.922985 |   0.933098 |
| barab-szabi-1        |     0.47108  |       0.899805 |   0.959223 |
| k-d_tree_pandas      |     0.470485 |       0.798126 |   1.18376  |
| k-d_tree_sklearn     |     0.475048 |       2.12754  |   1.23762  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469883 |        5.1129  |   0.756875 |
| Bori_Aron_solution-1 |     0.464447 |       10.8555  |   0.963097 |
| k-d_tree_sklearn     |     0.475038 |       16.3081  |   1.3139   |
| barab-szabi-1        |     0.474249 |        5.29963 |   6.53379  |
| k-d_tree_polars      |     0.47574  |        5.34481 |   6.5866   |
| k-d_tree_pandas      |     0.470978 |        4.35203 |   6.93408  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559462 |        71.6363 |    2.87178 |
| k-d_tree_sklearn     |     0.782721 |       237.421  |    3.97612 |
| Bori_Aron_solution-1 |     0.479974 |       155.226  |   23.5638  |