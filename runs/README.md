# 2026-07-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.80755  |       1e-06    |   0.392794 |
| k-d_tree_polars      |     0.510169 |       0.50135  |   0.450119 |
| barab-szabi-2        |     0.478392 |       0.45685  |   0.46202  |
| barab-szabi-1        |     8.5773   |       0.45599  |   0.524542 |
| Bori_Aron_solution-1 |     0.459839 |       0.555389 |   0.547972 |
| k-d_tree_pandas      |     0.468493 |       0.381194 |   0.550842 |
| k-d_tree_sklearn     |     2.97476  |       1.08946  |   1.08099  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473138 |       0.448101 |   0.44591  |
| k-d_tree_polars      |     0.477246 |       0.442042 |   0.45484  |
| barab-szabi-1        |     0.479521 |       0.421097 |   0.459481 |
| k-d_tree_pandas      |     0.473124 |       0.392294 |   0.559185 |
| Bori_Aron_solution-1 |     0.465103 |       0.557223 |   0.581465 |
| k-d_tree_sklearn     |     0.472846 |       1.00889  |   1.07691  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470936 |       0.448364 |   0.451285 |
| k-d_tree_polars      |     0.478    |       0.446892 |   0.476479 |
| barab-szabi-1        |     0.470823 |       0.45937  |   0.478026 |
| Bori_Aron_solution-1 |     0.461575 |       0.596227 |   0.550551 |
| k-d_tree_pandas      |     0.471944 |       0.410399 |   0.605206 |
| k-d_tree_sklearn     |     0.474405 |       1.06257  |   1.10973  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47366  |       0.509208 |   0.475296 |
| Bori_Aron_solution-1 |     0.468427 |       0.774974 |   0.571471 |
| k-d_tree_polars      |     0.472993 |       0.56765  |   0.573651 |
| barab-szabi-1        |     0.470261 |       0.57042  |   0.576837 |
| k-d_tree_pandas      |     0.475014 |       0.499219 |   0.736902 |
| k-d_tree_sklearn     |     0.483432 |       1.28063  |   1.13548  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473092 |       0.72842  |   0.507018 |
| Bori_Aron_solution-1 |     0.462545 |       1.43443  |   0.597568 |
| k-d_tree_polars      |     0.476671 |       0.927374 |   0.919872 |
| barab-szabi-1        |     0.469948 |       0.936196 |   0.946955 |
| k-d_tree_pandas      |     0.472819 |       0.79705  |   1.16886  |
| k-d_tree_sklearn     |     0.494902 |       2.11721  |   1.21467  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468786 |        5.06413 |   0.799887 |
| Bori_Aron_solution-1 |     0.468977 |       11.2065  |   0.848752 |
| k-d_tree_sklearn     |     0.496549 |       16.584   |   1.31833  |
| k-d_tree_polars      |     0.471009 |        5.28416 |   6.56639  |
| barab-szabi-1        |     0.496597 |        5.28978 |   6.63075  |
| k-d_tree_pandas      |     0.473005 |        4.33938 |   7.05841  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470437 |        71.1122 |    2.71007 |
| k-d_tree_sklearn     |     0.868499 |       234.107  |    4.0531  |
| Bori_Aron_solution-1 |     0.474423 |       151.451  |   17.0758  |