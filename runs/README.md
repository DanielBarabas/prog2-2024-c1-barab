# 2025-09-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.54005  |       1.24446  |   0.41767  |
| barab-szabi-1        |     0.521041 |       0.3993   |   0.43571  |
| k-d_tree_polars      |     0.523411 |       0.404568 |   0.438437 |
| Bori_Aron_solution-1 |     0.513349 |       0.535306 |   0.537709 |
| k-d_tree_pandas      |     0.529315 |       0.38284  |   0.542019 |
| solution-1           |     8.08366  |       1e-06    |   0.720589 |
| k-d_tree_sklearn     |     3.17904  |       1.32909  |   1.05434  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.538916 |       0.40681  |   0.424904 |
| barab-szabi-2        |     0.544754 |       0.424018 |   0.427567 |
| barab-szabi-1        |     0.534512 |       0.403694 |   0.428827 |
| Bori_Aron_solution-1 |     0.535156 |       0.555051 |   0.541254 |
| k-d_tree_pandas      |     0.543199 |       0.392887 |   0.551214 |
| k-d_tree_sklearn     |     0.539326 |       0.95857  |   1.05524  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537424 |       0.437421 |   0.437104 |
| k-d_tree_polars      |     0.540059 |       0.431942 |   0.452651 |
| barab-szabi-1        |     0.53349  |       0.431752 |   0.456052 |
| Bori_Aron_solution-1 |     0.529953 |       0.582226 |   0.5423   |
| k-d_tree_pandas      |     0.537641 |       0.406478 |   0.586721 |
| k-d_tree_sklearn     |     0.544253 |       0.999127 |   1.05985  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533844 |       0.493223 |   0.460407 |
| Bori_Aron_solution-1 |     0.529549 |       0.759087 |   0.550134 |
| k-d_tree_polars      |     0.539996 |       0.540264 |   0.552894 |
| barab-szabi-1        |     0.542586 |       0.540327 |   0.558917 |
| k-d_tree_pandas      |     0.534438 |       0.478935 |   0.728156 |
| k-d_tree_sklearn     |     0.537593 |       1.2506   |   1.11102  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533659 |       0.741491 |   0.492546 |
| Bori_Aron_solution-1 |     0.530053 |       1.38695  |   0.576694 |
| k-d_tree_polars      |     0.534681 |       0.888946 |   0.898708 |
| barab-szabi-1        |     0.535738 |       0.883357 |   0.938417 |
| k-d_tree_pandas      |     0.531831 |       0.781168 |   1.17238  |
| k-d_tree_sklearn     |     0.537554 |       2.06404  |   1.19078  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533753 |        5.20562 |   0.730054 |
| Bori_Aron_solution-1 |     0.528489 |       10.5539  |   0.849042 |
| k-d_tree_sklearn     |     0.538956 |       16.1696  |   1.28817  |
| k-d_tree_polars      |     0.536488 |        4.99725 |   6.53227  |
| barab-szabi-1        |     0.536955 |        4.99319 |   6.55094  |
| k-d_tree_pandas      |     0.537656 |        3.91916 |   6.96447  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533421 |        73.8508 |    2.72049 |
| k-d_tree_sklearn     |     1.0842   |       232.204  |    3.97443 |
| Bori_Aron_solution-1 |     0.537265 |       141.909  |   18.3549  |