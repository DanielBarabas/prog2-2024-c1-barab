# 2025-11-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.531094 |       0.456862 |   0.428571 |
| barab-szabi-1        |     0.529598 |       0.406705 |   0.444269 |
| barab-szabi-2        |     0.522789 |       0.572406 |   0.451372 |
| Bori_Aron_solution-1 |     0.522913 |       0.547292 |   0.549059 |
| solution-1           |     8.44454  |       1e-06    |   0.719601 |
| k-d_tree_pandas      |     9.41404  |       0.509348 |   0.768241 |
| k-d_tree_sklearn     |     3.22004  |       1.23029  |   1.06783  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539168 |       0.425875 |   0.436591 |
| barab-szabi-1        |     0.529701 |       0.409783 |   0.439533 |
| k-d_tree_polars      |     0.534164 |       0.417594 |   0.462627 |
| k-d_tree_pandas      |     0.531536 |       0.394864 |   0.558957 |
| Bori_Aron_solution-1 |     0.535178 |       0.59884  |   0.570075 |
| k-d_tree_sklearn     |     0.537538 |       1.00574  |   1.08188  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528164 |       0.454362 |   0.442385 |
| k-d_tree_polars      |     0.535014 |       0.437627 |   0.459759 |
| barab-szabi-1        |     0.529471 |       0.449191 |   0.461785 |
| Bori_Aron_solution-1 |     0.519964 |       0.594417 |   0.548421 |
| k-d_tree_pandas      |     0.541303 |       0.416256 |   0.601723 |
| k-d_tree_sklearn     |     0.53219  |       1.02717  |   1.09384  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533754 |       0.507021 |   0.469294 |
| k-d_tree_polars      |     0.529658 |       0.560066 |   0.563021 |
| barab-szabi-1        |     0.531354 |       0.561749 |   0.575079 |
| Bori_Aron_solution-1 |     0.523259 |       0.793894 |   0.579979 |
| k-d_tree_pandas      |     0.527388 |       0.507856 |   0.744426 |
| k-d_tree_sklearn     |     0.533651 |       1.26705  |   1.14883  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536116 |       0.751204 |   0.506356 |
| Bori_Aron_solution-1 |     0.522776 |       1.45616  |   0.585854 |
| k-d_tree_polars      |     0.532345 |       0.924176 |   0.914432 |
| barab-szabi-1        |     0.52726  |       0.936156 |   0.949904 |
| k-d_tree_pandas      |     0.530898 |       0.818823 |   1.18296  |
| k-d_tree_sklearn     |     0.533144 |       2.11846  |   1.22239  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538476 |        5.19336 |   0.750318 |
| Bori_Aron_solution-1 |     0.522717 |       11.0494  |   0.854082 |
| k-d_tree_sklearn     |     0.536671 |       16.4855  |   1.3317   |
| barab-szabi-1        |     0.531808 |        5.38574 |   6.48813  |
| k-d_tree_polars      |     0.533842 |        5.4047  |   6.55176  |
| k-d_tree_pandas      |     0.53099  |        4.48281 |   7.19574  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535187 |        79.1475 |    2.74421 |
| k-d_tree_sklearn     |     0.548294 |       237.072  |    4.29686 |
| Bori_Aron_solution-1 |     0.687156 |       155.733  |   17.63    |