# 2025-11-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.51696  |       0.800002 |   0.432288 |
| k-d_tree_polars      |     0.539277 |       0.408952 |   0.43933  |
| barab-szabi-1        |     0.536612 |       0.409819 |   0.440885 |
| Bori_Aron_solution-1 |     0.542358 |       0.556793 |   0.556175 |
| k-d_tree_pandas      |     8.03328  |       0.477702 |   0.815032 |
| solution-1           |     7.34961  |       1e-06    |   0.90268  |
| k-d_tree_sklearn     |     3.05144  |       1.5985   |   1.0871   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.530734 |       0.415225 |   0.433889 |
| barab-szabi-2        |     0.535832 |       0.433015 |   0.438555 |
| barab-szabi-1        |     0.52976  |       0.413227 |   0.446306 |
| Bori_Aron_solution-1 |     0.535154 |       0.563862 |   0.550346 |
| k-d_tree_pandas      |     0.5395   |       0.393781 |   0.564445 |
| k-d_tree_sklearn     |     0.543555 |       1.01244  |   1.07611  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534159 |       0.441143 |   0.446848 |
| k-d_tree_polars      |     0.539089 |       0.46179  |   0.464234 |
| barab-szabi-1        |     0.530216 |       0.442369 |   0.467347 |
| Bori_Aron_solution-1 |     0.525608 |       0.601335 |   0.553482 |
| k-d_tree_pandas      |     0.529895 |       0.42294  |   0.611501 |
| k-d_tree_sklearn     |     0.570294 |       1.02846  |   1.10939  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541197 |       0.512614 |   0.479686 |
| k-d_tree_polars      |     0.545449 |       0.565141 |   0.555569 |
| barab-szabi-1        |     0.533129 |       0.567516 |   0.579239 |
| Bori_Aron_solution-1 |     0.523745 |       0.805486 |   0.585636 |
| k-d_tree_pandas      |     0.527337 |       0.511532 |   0.749558 |
| k-d_tree_sklearn     |     0.535509 |       1.28049  |   1.16246  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529415 |       0.747457 |   0.509579 |
| Bori_Aron_solution-1 |     0.526682 |       1.46992  |   0.594149 |
| k-d_tree_polars      |     0.533663 |       0.936824 |   0.922431 |
| barab-szabi-1        |     0.561517 |       0.930631 |   0.962533 |
| k-d_tree_pandas      |     0.540352 |       0.803393 |   1.19158  |
| k-d_tree_sklearn     |     0.538132 |       2.13659  |   1.23157  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541858 |        5.53249 |   0.787764 |
| Bori_Aron_solution-1 |     0.525031 |       11.5723  |   0.857917 |
| k-d_tree_sklearn     |     0.537421 |       17.6455  |   1.33758  |
| barab-szabi-1        |     0.529254 |        5.38582 |   6.76082  |
| k-d_tree_polars      |     0.531879 |        5.50047 |   7.01875  |
| k-d_tree_pandas      |     0.534728 |        4.5171  |   7.26591  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532434 |        84.9728 |    3.12086 |
| k-d_tree_sklearn     |     0.554889 |       246.31   |    4.24714 |
| Bori_Aron_solution-1 |     0.70588  |       155.315  |   17.5733  |