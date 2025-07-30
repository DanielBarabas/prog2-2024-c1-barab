# 2025-07-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.04555  |       0.782336 |   0.44052  |
| k-d_tree_polars      |     0.595285 |       0.438598 |   0.447506 |
| barab-szabi-1        |     0.574696 |       0.431475 |   0.451339 |
| Bori_Aron_solution-1 |     0.54925  |       0.570462 |   0.568346 |
| k-d_tree_pandas      |     0.590605 |       0.415952 |   0.58817  |
| solution-1           |     8.14462  |       1e-06    |   0.667711 |
| k-d_tree_sklearn     |     3.14607  |       1.28842  |   1.13485  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.580708 |       0.438019 |   0.450128 |
| barab-szabi-2        |     0.581828 |       0.443043 |   0.464478 |
| barab-szabi-1        |     0.586104 |       0.442415 |   0.466898 |
| Bori_Aron_solution-1 |     0.579874 |       0.619555 |   0.588055 |
| k-d_tree_pandas      |     0.592148 |       0.417934 |   0.620173 |
| k-d_tree_sklearn     |     0.580868 |       1.01842  |   1.12888  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610102 |       0.523063 |   0.469074 |
| k-d_tree_polars      |     0.58862  |       0.463851 |   0.482026 |
| barab-szabi-1        |     0.597191 |       0.464875 |   0.487025 |
| Bori_Aron_solution-1 |     0.569922 |       0.62301  |   0.594546 |
| k-d_tree_pandas      |     0.572031 |       0.42837  |   0.635711 |
| k-d_tree_sklearn     |     0.584125 |       1.07024  |   1.15648  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581089 |       0.518444 |   0.483575 |
| k-d_tree_polars      |     0.583534 |       0.588289 |   0.578963 |
| Bori_Aron_solution-1 |     0.57536  |       0.806481 |   0.587161 |
| barab-szabi-1        |     0.57995  |       0.575959 |   0.606673 |
| k-d_tree_pandas      |     0.573351 |       0.506751 |   0.761914 |
| k-d_tree_sklearn     |     0.584072 |       1.30227  |   1.20357  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577325 |       0.81087  |   0.598906 |
| Bori_Aron_solution-1 |     0.567451 |       1.45564  |   0.610493 |
| k-d_tree_polars      |     0.574645 |       0.926077 |   0.957408 |
| barab-szabi-1        |     0.578768 |       0.927976 |   0.987589 |
| k-d_tree_pandas      |     0.577602 |       0.780197 |   1.22938  |
| k-d_tree_sklearn     |     0.582112 |       2.21618  |   1.28311  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57827  |        5.62306 |   0.752491 |
| Bori_Aron_solution-1 |     0.56965  |       11.1572  |   0.876427 |
| k-d_tree_sklearn     |     0.575416 |       17.5794  |   1.36918  |
| barab-szabi-1        |     0.579788 |        5.12536 |   6.97908  |
| k-d_tree_polars      |     0.573924 |        5.15305 |   7.03163  |
| k-d_tree_pandas      |     0.600176 |        4.02107 |   7.36606  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575258 |        74.9653 |    2.71946 |
| k-d_tree_sklearn     |     0.834293 |       237.849  |    4.12794 |
| Bori_Aron_solution-1 |     0.583703 |       146.067  |   14.9504  |