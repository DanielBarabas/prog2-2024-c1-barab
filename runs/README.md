# 2025-04-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549546 |       0.413215 |   0.403683 |
| barab-szabi-1        |     0.551407 |       0.401504 |   0.412027 |
| Bori_Aron_solution-1 |     0.54622  |       0.558241 |   0.549761 |
| k-d_tree_pandas      |     0.549925 |       0.383066 |   0.552922 |
| solution-1           |     7.79837  |       1e-06    |   0.638073 |
| k-d_tree_polars      |     7.72996  |       0.579095 |   0.675143 |
| k-d_tree_sklearn     |     2.96897  |       1.2236   |   1.03157  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561841 |       0.40998  |   0.407797 |
| barab-szabi-1        |     0.563746 |       0.410599 |   0.415249 |
| k-d_tree_polars      |     0.564438 |       0.410024 |   0.41752  |
| Bori_Aron_solution-1 |     0.57648  |       0.553937 |   0.544434 |
| k-d_tree_pandas      |     0.570246 |       0.388927 |   0.548658 |
| k-d_tree_sklearn     |     0.572904 |       0.968587 |   1.04572  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561415 |       0.423018 |   0.435485 |
| k-d_tree_polars      |     0.564219 |       0.433957 |   0.44101  |
| barab-szabi-1        |     0.56791  |       0.433476 |   0.442149 |
| Bori_Aron_solution-1 |     0.555992 |       0.58675  |   0.545352 |
| k-d_tree_pandas      |     0.560976 |       0.404642 |   0.599191 |
| k-d_tree_sklearn     |     0.575815 |       1.01968  |   1.08595  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.568711 |       0.491799 |   0.454987 |
| barab-szabi-1        |     0.575186 |       0.55071  |   0.548083 |
| k-d_tree_polars      |     0.565732 |       0.544168 |   0.556537 |
| Bori_Aron_solution-1 |     0.56499  |       0.772511 |   0.569062 |
| k-d_tree_pandas      |     0.563543 |       0.484084 |   0.727257 |
| k-d_tree_sklearn     |     0.564291 |       1.22898  |   1.11856  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.572877 |       0.727001 |   0.480289 |
| Bori_Aron_solution-1 |     0.560695 |       1.40687  |   0.591399 |
| k-d_tree_polars      |     0.570944 |       0.884788 |   0.892655 |
| barab-szabi-1        |     0.566376 |       0.892989 |   0.938606 |
| k-d_tree_pandas      |     0.568728 |       0.764243 |   1.18815  |
| k-d_tree_sklearn     |     0.575041 |       2.1022   |   1.23165  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562184 |        5.26892 |   0.723337 |
| Bori_Aron_solution-1 |     0.562207 |       10.5773  |   0.88302  |
| k-d_tree_sklearn     |     0.570208 |       16.0629  |   1.31044  |
| k-d_tree_polars      |     0.563019 |        5.02856 |   6.52365  |
| barab-szabi-1        |     0.564541 |        4.99211 |   6.52452  |
| k-d_tree_pandas      |     0.569859 |        3.9566  |   6.95013  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563894 |        74.5372 |    2.73323 |
| k-d_tree_sklearn     |     0.86124  |       231.32   |    4.55113 |
| Bori_Aron_solution-1 |     0.573509 |       153.311  |   16.104   |