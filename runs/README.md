# 2025-03-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.592291 |       0.421357 |   0.422073 |
| solution-1           |     7.28146  |       1e-06    |   0.424787 |
| barab-szabi-2        |     0.589336 |       0.419217 |   0.430879 |
| barab-szabi-1        |     0.588893 |       0.42079  |   0.441368 |
| Bori_Aron_solution-1 |     0.578138 |       0.563189 |   0.564864 |
| k-d_tree_pandas      |     7.62621  |       0.41292  |   0.605804 |
| k-d_tree_sklearn     |     2.94699  |       1.01233  |   1.06259  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614008 |       0.421007 |   0.418907 |
| barab-szabi-1        |     0.60345  |       0.418633 |   0.420949 |
| k-d_tree_polars      |     0.609485 |       0.420268 |   0.454101 |
| Bori_Aron_solution-1 |     0.597773 |       0.565037 |   0.560851 |
| k-d_tree_pandas      |     0.611068 |       0.4167   |   0.57459  |
| k-d_tree_sklearn     |     0.616277 |       0.98954  |   1.06252  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612695 |       0.430709 |   0.440869 |
| k-d_tree_polars      |     0.605561 |       0.448734 |   0.452185 |
| barab-szabi-1        |     0.604085 |       0.446714 |   0.454798 |
| Bori_Aron_solution-1 |     0.598982 |       0.608679 |   0.572893 |
| k-d_tree_pandas      |     0.603442 |       0.42607  |   0.623909 |
| k-d_tree_sklearn     |     0.610385 |       1.02764  |   1.09624  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617129 |       0.51167  |   0.462582 |
| barab-szabi-1        |     0.619334 |       0.552986 |   0.558964 |
| k-d_tree_polars      |     0.608918 |       0.580763 |   0.567132 |
| Bori_Aron_solution-1 |     0.601402 |       0.798735 |   0.591476 |
| k-d_tree_pandas      |     0.599362 |       0.493467 |   0.763697 |
| k-d_tree_sklearn     |     0.606669 |       1.27866  |   1.17718  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608767 |       0.737761 |   0.511893 |
| Bori_Aron_solution-1 |     0.600421 |       1.42604  |   0.607919 |
| k-d_tree_polars      |     0.609446 |       0.887466 |   0.906735 |
| barab-szabi-1        |     0.605579 |       0.875741 |   0.958899 |
| k-d_tree_pandas      |     0.613228 |       0.761836 |   1.20235  |
| k-d_tree_sklearn     |     0.604444 |       2.11803  |   1.24932  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591667 |        5.55644 |   0.76083  |
| Bori_Aron_solution-1 |     0.597721 |       10.6885  |   0.879345 |
| k-d_tree_sklearn     |     0.611264 |       16.5315  |   1.32203  |
| barab-szabi-1        |     0.596367 |        4.93559 |   6.67657  |
| k-d_tree_polars      |     0.59164  |        4.95803 |   6.70878  |
| k-d_tree_pandas      |     0.602034 |        3.87918 |   7.28678  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.765962 |        74.4543 |    3.75528 |
| k-d_tree_sklearn     |     0.684264 |       235.785  |    4.34504 |
| Bori_Aron_solution-1 |     0.591503 |       152.584  |   16.9025  |