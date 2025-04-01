# 2025-04-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.49173  |       1e-06    |   0.357414 |
| barab-szabi-2        |     0.546482 |       0.40444  |   0.401501 |
| k-d_tree_polars      |     0.548295 |       0.396351 |   0.406523 |
| barab-szabi-1        |     0.550129 |       0.402901 |   0.411942 |
| Bori_Aron_solution-1 |     0.537844 |       0.5362   |   0.537461 |
| k-d_tree_pandas      |     7.85528  |       0.397228 |   0.616991 |
| k-d_tree_sklearn     |     3.03732  |       0.972664 |   1.01179  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.560517 |       0.408119 |   0.409688 |
| k-d_tree_polars      |     0.561829 |       0.408213 |   0.410391 |
| barab-szabi-2        |     0.55994  |       0.433774 |   0.416119 |
| Bori_Aron_solution-1 |     0.562549 |       0.548796 |   0.53729  |
| k-d_tree_pandas      |     0.561614 |       0.388118 |   0.564801 |
| k-d_tree_sklearn     |     0.560542 |       0.940887 |   1.02418  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561249 |       0.434014 |   0.418015 |
| k-d_tree_polars      |     0.564335 |       0.429446 |   0.438763 |
| barab-szabi-1        |     0.561411 |       0.42951  |   0.441631 |
| Bori_Aron_solution-1 |     0.55383  |       0.588618 |   0.53996  |
| k-d_tree_pandas      |     0.567175 |       0.402668 |   0.591726 |
| k-d_tree_sklearn     |     0.566789 |       0.986848 |   1.04527  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558557 |       0.481549 |   0.445094 |
| k-d_tree_polars      |     0.559531 |       0.536374 |   0.535846 |
| barab-szabi-1        |     0.565241 |       0.535972 |   0.545983 |
| Bori_Aron_solution-1 |     0.558025 |       0.750552 |   0.552735 |
| k-d_tree_pandas      |     0.564384 |       0.473747 |   0.734013 |
| k-d_tree_sklearn     |     0.565475 |       1.20683  |   1.09463  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560405 |       0.718893 |   0.479829 |
| Bori_Aron_solution-1 |     0.555597 |       1.37815  |   0.581834 |
| k-d_tree_polars      |     0.562849 |       0.861756 |   0.885107 |
| barab-szabi-1        |     0.558922 |       0.865686 |   0.915701 |
| k-d_tree_pandas      |     0.559168 |       0.730923 |   1.16434  |
| k-d_tree_sklearn     |     0.563262 |       2.01858  |   1.18477  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561917 |        5.13346 |   0.698444 |
| Bori_Aron_solution-1 |     0.557801 |       10.3883  |   0.872247 |
| k-d_tree_sklearn     |     0.56406  |       15.7545  |   1.30236  |
| k-d_tree_polars      |     0.56011  |        4.93378 |   6.40236  |
| barab-szabi-1        |     0.564005 |        4.92957 |   6.40453  |
| k-d_tree_pandas      |     0.558497 |        3.83155 |   6.83171  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.704195 |        71.4742 |    2.7027  |
| k-d_tree_sklearn     |     0.619238 |       225.659  |    4.25643 |
| Bori_Aron_solution-1 |     0.55619  |       150.303  |   16.7547  |