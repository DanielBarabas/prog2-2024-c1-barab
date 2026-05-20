# 2026-05-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.46922  |       1e-06    |   0.390585 |
| barab-szabi-2        |     0.454359 |       0.432237 |   0.424248 |
| k-d_tree_polars      |     0.457901 |       0.404013 |   0.431454 |
| barab-szabi-1        |     8.03383  |       0.431952 |   0.530682 |
| k-d_tree_pandas      |     0.458165 |       0.378785 |   0.547099 |
| Bori_Aron_solution-1 |     0.470744 |       0.541241 |   0.555091 |
| k-d_tree_sklearn     |     2.88361  |       1.05945  |   1.05801  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.468216 |       0.408195 |   0.439136 |
| k-d_tree_polars      |     0.467934 |       0.409804 |   0.440154 |
| Bori_Aron_solution-1 |     0.457963 |       0.551537 |   0.542986 |
| k-d_tree_pandas      |     0.493175 |       0.403255 |   0.55398  |
| barab-szabi-2        |     0.468756 |       0.438068 |   0.555646 |
| k-d_tree_sklearn     |     0.472734 |       0.969726 |   1.07181  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47383  |       0.445698 |   0.447909 |
| barab-szabi-1        |     0.472913 |       0.433411 |   0.462129 |
| k-d_tree_polars      |     0.463582 |       0.434845 |   0.468528 |
| Bori_Aron_solution-1 |     0.460423 |       0.600176 |   0.543556 |
| k-d_tree_pandas      |     0.465371 |       0.435169 |   0.596364 |
| k-d_tree_sklearn     |     0.472342 |       1.02504  |   1.10461  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465336 |       0.503926 |   0.47309  |
| Bori_Aron_solution-1 |     0.466215 |       0.781213 |   0.557991 |
| k-d_tree_polars      |     0.465117 |       0.557877 |   0.560595 |
| barab-szabi-1        |     0.465936 |       0.55686  |   0.573071 |
| k-d_tree_pandas      |     0.46804  |       0.506205 |   0.72551  |
| k-d_tree_sklearn     |     0.469586 |       1.26     |   1.12749  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465551 |       0.719086 |   0.503193 |
| Bori_Aron_solution-1 |     0.467634 |       1.46007  |   0.595049 |
| k-d_tree_polars      |     0.46903  |       0.936046 |   0.911462 |
| barab-szabi-1        |     0.467852 |       0.9313   |   0.95772  |
| k-d_tree_pandas      |     0.463692 |       0.816992 |   1.17652  |
| k-d_tree_sklearn     |     0.470777 |       2.12131  |   1.23231  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469636 |        5.31638 |   0.783975 |
| Bori_Aron_solution-1 |     0.475312 |       11.4005  |   0.82135  |
| k-d_tree_sklearn     |     0.475711 |       17.819   |   1.3132   |
| k-d_tree_polars      |     0.465193 |        5.42341 |   6.79138  |
| barab-szabi-1        |     0.474592 |        5.52947 |   6.83022  |
| k-d_tree_pandas      |     0.469889 |        4.50121 |   7.35674  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483915 |        73.2571 |    2.68688 |
| k-d_tree_sklearn     |     0.479706 |       248.303  |    3.60646 |
| Bori_Aron_solution-1 |     0.464152 |       150.493  |   20.5477  |