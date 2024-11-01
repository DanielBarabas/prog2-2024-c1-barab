# 2024-11-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.58214  |       1e-06    |   0.379169 |
| barab-szabi-1        |     0.632739 |       0.399947 |   0.389789 |
| barab-szabi-2        |     0.63498  |       0.395629 |   0.391041 |
| k-d_tree_polars      |     0.643152 |       0.416292 |   0.39928  |
| Bori_Aron_solution-1 |     0.621094 |       0.540125 |   0.533325 |
| k-d_tree_pandas      |     0.643999 |       0.414542 |   0.547994 |
| k-d_tree_sklearn     |    10.219    |       1.12017  |   0.991669 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.62027  |       0.414344 |   0.396758 |
| barab-szabi-1        |     0.626999 |       0.415518 |   0.40275  |
| Bori_Aron_solution-1 |     0.623611 |       0.531895 |   0.530491 |
| k-d_tree_pandas      |     0.620481 |       0.390491 |   0.544548 |
| barab-szabi-2        |     0.688521 |       0.401192 |   0.61087  |
| k-d_tree_sklearn     |     0.633441 |       0.916438 |   0.968725 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632563 |       0.415719 |   0.41083  |
| k-d_tree_polars      |     0.634328 |       0.445912 |   0.42897  |
| barab-szabi-1        |     0.641202 |       0.449127 |   0.439574 |
| Bori_Aron_solution-1 |     0.635802 |       0.58854  |   0.553493 |
| k-d_tree_pandas      |     0.649226 |       0.4253   |   0.599623 |
| k-d_tree_sklearn     |     0.627851 |       0.94749  |   1.00892  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.644352 |       0.487918 |   0.449719 |
| k-d_tree_polars      |     0.650582 |       0.561079 |   0.541652 |
| barab-szabi-1        |     0.642307 |       0.561261 |   0.557557 |
| Bori_Aron_solution-1 |     0.634132 |       0.777916 |   0.579523 |
| k-d_tree_pandas      |     0.652411 |       0.518888 |   0.746259 |
| k-d_tree_sklearn     |     0.653606 |       1.22192  |   1.12146  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.639066 |       0.758514 |   0.568709 |
| Bori_Aron_solution-1 |     0.64406  |       1.44748  |   0.593207 |
| k-d_tree_polars      |     0.644884 |       0.887278 |   0.919096 |
| barab-szabi-1        |     0.645314 |       0.994379 |   1.05278  |
| k-d_tree_sklearn     |     0.658667 |       2.08162  |   1.19468  |
| k-d_tree_pandas      |     0.644954 |       0.761195 |   1.21396  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.639766 |        5.64051 |   0.729693 |
| Bori_Aron_solution-1 |     0.623357 |       10.8257  |   0.807101 |
| k-d_tree_sklearn     |     0.674337 |       17.177   |   1.31214  |
| barab-szabi-1        |     0.623735 |        4.97211 |   6.66177  |
| k-d_tree_polars      |     0.663601 |        4.87867 |   6.80772  |
| k-d_tree_pandas      |     0.61817  |        3.9089  |   6.99252  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629442 |        74.3737 |    3.00994 |
| k-d_tree_sklearn     |     0.632162 |       227.517  |    4.20716 |
| Bori_Aron_solution-1 |     0.652672 |       151.412  |   18.7977  |