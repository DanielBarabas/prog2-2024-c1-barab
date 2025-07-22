# 2025-07-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.569103 |       0.409769 |   0.42511  |
| barab-szabi-1        |     0.660027 |       0.408955 |   0.427924 |
| barab-szabi-2        |     8.04858  |       0.708908 |   0.430809 |
| solution-1           |     7.84724  |       1e-06    |   0.512711 |
| k-d_tree_pandas      |     0.640454 |       0.39014  |   0.546248 |
| Bori_Aron_solution-1 |     0.5324   |       0.551021 |   0.55261  |
| k-d_tree_sklearn     |     3.03153  |       1.27271  |   1.08127  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557452 |       0.421911 |   0.426815 |
| barab-szabi-1        |     0.554429 |       0.412833 |   0.431164 |
| k-d_tree_polars      |     0.572835 |       0.424451 |   0.43571  |
| Bori_Aron_solution-1 |     0.550175 |       0.552319 |   0.556917 |
| k-d_tree_pandas      |     0.55776  |       0.418492 |   0.572431 |
| k-d_tree_sklearn     |     0.564667 |       0.97893  |   1.06528  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554214 |       0.441444 |   0.448912 |
| k-d_tree_polars      |     0.561589 |       0.450797 |   0.455797 |
| barab-szabi-1        |     0.566541 |       0.434493 |   0.460639 |
| Bori_Aron_solution-1 |     0.572508 |       0.621042 |   0.582615 |
| k-d_tree_pandas      |     0.557573 |       0.414001 |   0.610096 |
| k-d_tree_sklearn     |     0.577239 |       1.03433  |   1.10215  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562554 |       0.505825 |   0.471326 |
| Bori_Aron_solution-1 |     0.556355 |       0.769372 |   0.558976 |
| k-d_tree_polars      |     0.565591 |       0.558861 |   0.562737 |
| barab-szabi-1        |     0.568299 |       0.549967 |   0.563588 |
| k-d_tree_pandas      |     0.571952 |       0.488791 |   0.749778 |
| k-d_tree_sklearn     |     0.560833 |       1.24402  |   1.17646  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571548 |       0.753287 |   0.515425 |
| Bori_Aron_solution-1 |     0.554816 |       1.46079  |   0.593776 |
| k-d_tree_polars      |     0.567856 |       0.928307 |   0.940483 |
| barab-szabi-1        |     0.577851 |       0.896243 |   0.957219 |
| k-d_tree_pandas      |     0.566179 |       0.77355  |   1.18693  |
| k-d_tree_sklearn     |     0.575531 |       2.1882   |   1.28558  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556097 |        5.54507 |   0.778027 |
| Bori_Aron_solution-1 |     0.571937 |       10.7655  |   0.867496 |
| k-d_tree_sklearn     |     0.568993 |       16.3684  |   1.31493  |
| k-d_tree_polars      |     0.558867 |        5.07645 |   6.71523  |
| barab-szabi-1        |     0.560503 |        4.9806  |   6.75471  |
| k-d_tree_pandas      |     0.560421 |        3.96096 |   7.06308  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555595 |        71.6859 |    2.79623 |
| k-d_tree_sklearn     |     0.733538 |       252.522  |    4.46018 |
| Bori_Aron_solution-1 |     0.562433 |       154.526  |   18.3998  |