# 2026-06-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.04641  |       1e-06    |   0.398877 |
| barab-szabi-2        |     8.59658  |       0.508362 |   0.426179 |
| barab-szabi-1        |     0.452593 |       0.401189 |   0.427174 |
| k-d_tree_polars      |     0.468705 |       0.411304 |   0.435441 |
| k-d_tree_pandas      |     0.474051 |       0.388278 |   0.565838 |
| Bori_Aron_solution-1 |     0.466956 |       0.567983 |   0.569499 |
| k-d_tree_sklearn     |     3.03613  |       1.04491  |   1.07304  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491292 |       0.434601 |   0.441541 |
| barab-szabi-1        |     0.468433 |       0.425143 |   0.449472 |
| k-d_tree_polars      |     0.47984  |       0.431099 |   0.462344 |
| k-d_tree_pandas      |     0.474096 |       0.392888 |   0.557225 |
| Bori_Aron_solution-1 |     0.480368 |       0.570765 |   0.57149  |
| k-d_tree_sklearn     |     0.509537 |       1.04819  |   1.11407  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482789 |       0.454325 |   0.450704 |
| k-d_tree_polars      |     0.490412 |       0.439029 |   0.463913 |
| barab-szabi-1        |     0.480345 |       0.460563 |   0.478576 |
| Bori_Aron_solution-1 |     0.465498 |       0.594335 |   0.552019 |
| k-d_tree_pandas      |     0.491883 |       0.424475 |   0.623411 |
| k-d_tree_sklearn     |     0.472796 |       1.04536  |   1.15369  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476757 |       0.537253 |   0.49422  |
| Bori_Aron_solution-1 |     0.491866 |       0.794081 |   0.56757  |
| k-d_tree_polars      |     0.491757 |       0.58492  |   0.571017 |
| barab-szabi-1        |     0.477562 |       0.573564 |   0.610149 |
| k-d_tree_pandas      |     0.483361 |       0.511517 |   0.72989  |
| k-d_tree_sklearn     |     0.490912 |       1.32039  |   1.17861  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476115 |       0.786036 |   0.590476 |
| Bori_Aron_solution-1 |     0.474793 |       1.50412  |   0.591949 |
| k-d_tree_polars      |     0.487831 |       0.923561 |   0.968009 |
| barab-szabi-1        |     0.481545 |       0.906068 |   0.998885 |
| k-d_tree_sklearn     |     0.485059 |       2.2364   |   1.18583  |
| k-d_tree_pandas      |     0.470169 |       0.801767 |   1.2272   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475295 |        5.84376 |   0.741055 |
| Bori_Aron_solution-1 |     0.470623 |       11.6292  |   0.804122 |
| k-d_tree_sklearn     |     0.463275 |       18.8408  |   1.33127  |
| k-d_tree_polars      |     0.465585 |        5.2371  |   7.54682  |
| barab-szabi-1        |     0.475167 |        5.29684 |   7.67187  |
| k-d_tree_pandas      |     0.481518 |        4.18368 |   8.01486  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465956 |         75.287 |    2.53832 |
| k-d_tree_sklearn     |     0.678766 |        257.274 |    3.35678 |
| Bori_Aron_solution-1 |     0.462759 |        151.065 |   16.0183  |