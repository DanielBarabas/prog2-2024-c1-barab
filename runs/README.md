# 2024-09-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610458 |       0.392519 |   0.390573 |
| barab-szabi-1        |     0.60771  |       0.405989 |   0.394858 |
| k-d_tree_polars      |     0.61861  |       0.405228 |   0.40013  |
| Bori_Aron_solution-1 |     4.48035  |       0.64396  |   0.470441 |
| solution-1           |     8.01285  |       1e-06    |   0.477561 |
| k-d_tree_pandas      |     4.14341  |       0.451526 |   0.545585 |
| k-d_tree_sklearn     |     3.12275  |       1.05568  |   0.965699 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627043 |       0.390887 |   0.387676 |
| barab-szabi-1        |     0.631884 |       0.413395 |   0.397792 |
| k-d_tree_polars      |     0.614766 |       0.4131   |   0.398076 |
| Bori_Aron_solution-1 |     0.614839 |       0.538998 |   0.529483 |
| k-d_tree_pandas      |     0.612312 |       0.431624 |   0.548173 |
| k-d_tree_sklearn     |     0.622617 |       0.963013 |   1.00679  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620467 |       0.408313 |   0.401972 |
| k-d_tree_polars      |     0.614228 |       0.436122 |   0.426891 |
| barab-szabi-1        |     0.638196 |       0.458985 |   0.432356 |
| Bori_Aron_solution-1 |     0.606544 |       0.572713 |   0.544723 |
| k-d_tree_pandas      |     0.618713 |       0.417144 |   0.626162 |
| k-d_tree_sklearn     |     0.622982 |       1.00791  |   1.01628  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.624387 |       0.469823 |   0.437382 |
| k-d_tree_polars      |     0.638818 |       0.558017 |   0.527177 |
| barab-szabi-1        |     0.626992 |       0.535086 |   0.536054 |
| Bori_Aron_solution-1 |     0.634888 |       0.78382  |   0.576167 |
| k-d_tree_pandas      |     0.643456 |       0.494538 |   0.722396 |
| k-d_tree_sklearn     |     0.627386 |       1.19933  |   1.07863  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623647 |       0.728111 |   0.492658 |
| Bori_Aron_solution-1 |     0.619088 |       1.40566  |   0.585192 |
| k-d_tree_polars      |     0.64072  |       0.878517 |   0.899858 |
| barab-szabi-1        |     0.627963 |       0.863971 |   0.946379 |
| k-d_tree_sklearn     |     0.62852  |       2.09023  |   1.16765  |
| k-d_tree_pandas      |     0.635339 |       0.751079 |   1.20993  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626507 |        5.5682  |   0.773021 |
| Bori_Aron_solution-1 |     0.623823 |       10.8568  |   0.832356 |
| k-d_tree_sklearn     |     0.622408 |       16.6242  |   1.30603  |
| barab-szabi-1        |     0.614673 |        4.76759 |   6.56083  |
| k-d_tree_polars      |     0.633484 |        4.75855 |   6.60058  |
| k-d_tree_pandas      |     0.629173 |        3.8684  |   7.19645  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.697506 |        77.1034 |    3.27238 |
| k-d_tree_sklearn     |     0.948338 |       240.061  |    4.26287 |
| Bori_Aron_solution-1 |     0.622    |       146.877  |   16.9624  |