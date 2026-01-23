# 2026-01-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.530839 |       0.415604 |   0.431551 |
| barab-szabi-2        |     0.515718 |       0.638226 |   0.436618 |
| k-d_tree_polars      |     0.531244 |       0.402876 |   0.437761 |
| Bori_Aron_solution-1 |     0.520124 |       0.54537  |   0.544858 |
| solution-1           |     8.02618  |       1e-06    |   0.725356 |
| k-d_tree_pandas      |     8.6807   |       0.450755 |   0.766654 |
| k-d_tree_sklearn     |     3.14178  |       1.30733  |   1.05228  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.535269 |       0.405939 |   0.439433 |
| barab-szabi-1        |     0.528677 |       0.414852 |   0.440851 |
| barab-szabi-2        |     0.535589 |       0.437978 |   0.441041 |
| Bori_Aron_solution-1 |     0.524239 |       0.551397 |   0.549489 |
| k-d_tree_pandas      |     0.531595 |       0.389452 |   0.553499 |
| k-d_tree_sklearn     |     0.538912 |       0.97141  |   1.07404  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540195 |       0.443038 |   0.451445 |
| barab-szabi-1        |     0.528766 |       0.432637 |   0.465317 |
| k-d_tree_polars      |     0.53381  |       0.436513 |   0.465748 |
| Bori_Aron_solution-1 |     0.528717 |       0.654339 |   0.553833 |
| k-d_tree_pandas      |     0.542056 |       0.410146 |   0.597907 |
| k-d_tree_sklearn     |     0.533172 |       1.03913  |   1.08554  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525531 |       0.518827 |   0.473454 |
| Bori_Aron_solution-1 |     0.523445 |       0.778098 |   0.561868 |
| k-d_tree_polars      |     0.533768 |       0.565089 |   0.566442 |
| barab-szabi-1        |     0.526407 |       0.55588  |   0.589821 |
| k-d_tree_pandas      |     0.535671 |       0.502704 |   0.727754 |
| k-d_tree_sklearn     |     0.532984 |       1.25023  |   1.12779  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527895 |       0.735524 |   0.50269  |
| Bori_Aron_solution-1 |     0.520134 |       1.46825  |   0.587356 |
| k-d_tree_polars      |     0.531421 |       0.92965  |   0.910565 |
| barab-szabi-1        |     0.531754 |       0.925117 |   0.947362 |
| k-d_tree_pandas      |     0.531003 |       0.810416 |   1.177    |
| k-d_tree_sklearn     |     0.532589 |       2.13465  |   1.2176   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533369 |        5.20113 |   0.749088 |
| Bori_Aron_solution-1 |     0.518996 |       11.2421  |   0.850756 |
| k-d_tree_sklearn     |     0.577821 |       16.9533  |   1.31679  |
| barab-szabi-1        |     0.53213  |        5.4454  |   6.62324  |
| k-d_tree_polars      |     0.529549 |        5.56444 |   6.6329   |
| k-d_tree_pandas      |     0.5327   |        4.3311  |   7.05469  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528551 |        78.3293 |    2.80515 |
| k-d_tree_sklearn     |     0.557458 |       246.206  |    4.21903 |
| Bori_Aron_solution-1 |     0.69048  |       155.138  |   18.38    |