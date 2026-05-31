# 2026-05-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.451703 |       0.420796 |   0.426424 |
| k-d_tree_polars      |     0.455172 |       0.398762 |   0.427792 |
| solution-1           |     8.19811  |       1e-06    |   0.51545  |
| Bori_Aron_solution-1 |     0.449077 |       0.536952 |   0.530828 |
| k-d_tree_pandas      |     0.455477 |       0.376927 |   0.539467 |
| barab-szabi-1        |     8.68293  |       0.461641 |   0.679622 |
| k-d_tree_sklearn     |     3.2055   |       1.18814  |   1.05399  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462089 |       0.42569  |   0.428126 |
| barab-szabi-1        |     0.46441  |       0.407334 |   0.434629 |
| k-d_tree_polars      |     0.462083 |       0.403968 |   0.436425 |
| Bori_Aron_solution-1 |     0.462031 |       0.541086 |   0.534996 |
| k-d_tree_pandas      |     0.465531 |       0.389442 |   0.542694 |
| k-d_tree_sklearn     |     0.464605 |       0.967237 |   1.05549  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462776 |       0.443437 |   0.439315 |
| barab-szabi-1        |     0.466481 |       0.432178 |   0.456953 |
| k-d_tree_polars      |     0.46172  |       0.431596 |   0.457986 |
| Bori_Aron_solution-1 |     0.473525 |       0.585223 |   0.535529 |
| k-d_tree_pandas      |     0.464293 |       0.404111 |   0.579901 |
| k-d_tree_sklearn     |     0.468337 |       1.0068   |   1.08084  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462301 |       0.50027  |   0.464634 |
| Bori_Aron_solution-1 |     0.456185 |       0.785099 |   0.54794  |
| k-d_tree_polars      |     0.466677 |       0.558616 |   0.562306 |
| barab-szabi-1        |     0.469119 |       0.551713 |   0.572772 |
| k-d_tree_pandas      |     0.464194 |       0.503436 |   0.708486 |
| k-d_tree_sklearn     |     0.46648  |       1.2378   |   1.10361  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465966 |       0.753618 |   0.503891 |
| Bori_Aron_solution-1 |     0.454967 |       1.47474  |   0.574245 |
| k-d_tree_polars      |     0.46392  |       0.911066 |   0.953798 |
| barab-szabi-1        |     0.463909 |       0.897861 |   0.988969 |
| k-d_tree_sklearn     |     0.465078 |       2.12454  |   1.14751  |
| k-d_tree_pandas      |     0.465129 |       0.777611 |   1.16591  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469397 |        5.59402 |   0.791214 |
| Bori_Aron_solution-1 |     0.468236 |       11.6018  |   0.820152 |
| k-d_tree_sklearn     |     0.534962 |       19.2412  |   1.41262  |
| barab-szabi-1        |     0.470705 |        5.21895 |   7.29193  |
| k-d_tree_pandas      |     0.527068 |        4.15463 |   7.73881  |
| k-d_tree_polars      |     0.485051 |        5.18963 |   7.7703   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.523273 |        76.6437 |    2.46277 |
| k-d_tree_sklearn     |     0.672994 |       263.751  |    3.40662 |
| Bori_Aron_solution-1 |     0.463602 |       154.247  |   25.0319  |