# 2026-09-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.43307  |       0.42719  |   0.411501 |
| k-d_tree_polars      |     0.417725 |       0.381112 |   0.439671 |
| k-d_tree_pandas      |     0.416482 |       0.357581 |   0.502793 |
| Bori_Aron_solution-1 |     0.417347 |       0.516033 |   0.505422 |
| barab-szabi-1        |     8.68355  |       0.464719 |   0.662457 |
| k-d_tree_sklearn     |     2.9191   |       1.21337  |   1.00387  |
| solution-1           |     7.41479  |       1e-06    |   1.09959  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.426814 |       0.390879 |   0.427474 |
| barab-szabi-2        |     0.425509 |       0.423781 |   0.427902 |
| barab-szabi-1        |     0.429267 |       0.389403 |   0.437921 |
| Bori_Aron_solution-1 |     0.418379 |       0.525403 |   0.514679 |
| k-d_tree_pandas      |     0.422805 |       0.365322 |   0.516227 |
| k-d_tree_sklearn     |     0.427862 |       0.91367  |   0.983823 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.433151 |       0.432493 |   0.42613  |
| barab-szabi-1        |     0.430015 |       0.435401 |   0.451351 |
| k-d_tree_polars      |     0.43135  |       0.425109 |   0.451748 |
| Bori_Aron_solution-1 |     0.417625 |       0.556594 |   0.518227 |
| k-d_tree_pandas      |     0.425498 |       0.384035 |   0.560836 |
| k-d_tree_sklearn     |     0.431134 |       0.966595 |   1.00368  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.428745 |       0.480824 |   0.462762 |
| k-d_tree_polars      |     0.432233 |       0.529532 |   0.536768 |
| barab-szabi-1        |     0.424417 |       0.551503 |   0.538545 |
| Bori_Aron_solution-1 |     0.419272 |       0.717536 |   0.567609 |
| k-d_tree_pandas      |     0.439338 |       0.468853 |   0.669382 |
| k-d_tree_sklearn     |     0.435395 |       1.16357  |   1.04432  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.429995 |       0.731558 |   0.494633 |
| Bori_Aron_solution-1 |     0.424959 |       1.29774  |   0.557204 |
| k-d_tree_polars      |     0.43305  |       0.858774 |   0.851242 |
| barab-szabi-1        |     0.43153  |       0.841213 |   0.881593 |
| k-d_tree_pandas      |     0.426694 |       0.731893 |   1.05352  |
| k-d_tree_sklearn     |     0.42806  |       1.93573  |   1.13055  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.429389 |        5.00081 |   0.68676  |
| Bori_Aron_solution-1 |     0.429393 |        9.77006 |   0.863272 |
| k-d_tree_sklearn     |     0.434375 |       14.4061  |   1.22208  |
| barab-szabi-1        |     0.425337 |        4.76045 |   6.08952  |
| k-d_tree_polars      |     0.430509 |        4.73779 |   6.18701  |
| k-d_tree_pandas      |     0.426642 |        3.76133 |   6.63958  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546524 |        68.2999 |    2.6503  |
| k-d_tree_sklearn     |     0.671327 |       176.416  |    4.13572 |
| Bori_Aron_solution-1 |     0.42192  |       136.223  |   30.0019  |