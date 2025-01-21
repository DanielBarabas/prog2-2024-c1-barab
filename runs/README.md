# 2025-01-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.583252 |       0.402515 |   0.400856 |
| barab-szabi-2        |     0.591163 |       0.659068 |   0.402136 |
| barab-szabi-1        |     0.574308 |       0.405647 |   0.405493 |
| Bori_Aron_solution-1 |     0.576625 |       0.536916 |   0.532169 |
| solution-1           |     7.69529  |       1e-06    |   0.701781 |
| k-d_tree_sklearn     |     3.15044  |       1.32669  |   1.01108  |
| k-d_tree_pandas      |     8.05053  |       0.46333  |   1.05167  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.595879 |       0.425094 |   0.404522 |
| barab-szabi-1        |     0.58425  |       0.412211 |   0.407456 |
| barab-szabi-2        |     0.584805 |       0.402044 |   0.409611 |
| Bori_Aron_solution-1 |     0.576972 |       0.541557 |   0.529149 |
| k-d_tree_pandas      |     0.582695 |       0.388959 |   0.550182 |
| k-d_tree_sklearn     |     0.585159 |       0.967556 |   1.02906  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583992 |       0.414486 |   0.413574 |
| k-d_tree_polars      |     0.60971  |       0.434318 |   0.431821 |
| barab-szabi-1        |     0.586506 |       0.438346 |   0.453522 |
| Bori_Aron_solution-1 |     0.581729 |       0.58044  |   0.541743 |
| k-d_tree_pandas      |     0.593529 |       0.408316 |   0.586509 |
| k-d_tree_sklearn     |     0.587891 |       0.988774 |   1.04854  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588172 |       0.476599 |   0.444691 |
| k-d_tree_polars      |     0.596058 |       0.540926 |   0.52802  |
| barab-szabi-1        |     0.588339 |       0.536134 |   0.532837 |
| Bori_Aron_solution-1 |     0.574668 |       0.736935 |   0.551337 |
| k-d_tree_pandas      |     0.584405 |       0.48204  |   0.742113 |
| k-d_tree_sklearn     |     0.586029 |       1.22295  |   1.10934  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58771  |       0.715293 |   0.481398 |
| Bori_Aron_solution-1 |     0.575779 |       1.38434  |   0.583099 |
| k-d_tree_polars      |     0.590127 |       0.884903 |   0.888844 |
| barab-szabi-1        |     0.584999 |       0.858084 |   0.911846 |
| k-d_tree_pandas      |     0.579636 |       0.745123 |   1.15754  |
| k-d_tree_sklearn     |     0.588619 |       2.06403  |   1.22726  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586483 |        5.35055 |   0.743409 |
| Bori_Aron_solution-1 |     0.585808 |       10.6271  |   0.865691 |
| k-d_tree_sklearn     |     0.586108 |       16.1675  |   1.303    |
| barab-szabi-1        |     0.585291 |        4.88896 |   6.63185  |
| k-d_tree_polars      |     0.586809 |        4.90623 |   6.65249  |
| k-d_tree_pandas      |     0.593582 |        3.84013 |   7.04168  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.59832  |        74.5369 |    3.02954 |
| k-d_tree_sklearn     |     0.600295 |       231.585  |    4.83386 |
| Bori_Aron_solution-1 |     0.616858 |       143.306  |   18.3191  |