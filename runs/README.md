# 2026-05-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484795 |       0.453848 |   0.455263 |
| k-d_tree_polars      |     0.484424 |       0.444666 |   0.456452 |
| solution-1           |     8.47727  |       1e-06    |   0.518914 |
| barab-szabi-1        |     9.34944  |       0.556355 |   0.545226 |
| Bori_Aron_solution-1 |     0.479711 |       0.580304 |   0.570575 |
| k-d_tree_pandas      |     0.483507 |       0.404052 |   0.575505 |
| k-d_tree_sklearn     |     3.42272  |       1.29363  |   1.10681  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.493673 |       0.44044  |   0.455819 |
| barab-szabi-2        |     0.492301 |       0.454118 |   0.458242 |
| k-d_tree_polars      |     0.488529 |       0.436345 |   0.463406 |
| k-d_tree_pandas      |     0.50546  |       0.413557 |   0.580083 |
| Bori_Aron_solution-1 |     0.491159 |       0.581418 |   0.581935 |
| k-d_tree_sklearn     |     0.494985 |       1.08493  |   1.16432  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491635 |       0.47614  |   0.471717 |
| barab-szabi-1        |     0.497912 |       0.466266 |   0.479227 |
| k-d_tree_polars      |     0.49302  |       0.46731  |   0.479357 |
| Bori_Aron_solution-1 |     0.492375 |       0.640705 |   0.599036 |
| k-d_tree_pandas      |     0.510769 |       0.441694 |   0.688694 |
| k-d_tree_sklearn     |     0.561127 |       1.10227  |   1.1885   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498206 |       0.534986 |   0.49603  |
| k-d_tree_polars      |     0.491651 |       0.598855 |   0.589006 |
| Bori_Aron_solution-1 |     0.485705 |       0.816703 |   0.59636  |
| barab-szabi-1        |     0.494062 |       0.585323 |   0.599314 |
| k-d_tree_pandas      |     0.493618 |       0.51934  |   0.745182 |
| k-d_tree_sklearn     |     0.497465 |       1.34744  |   1.22922  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491414 |       0.794928 |   0.563396 |
| Bori_Aron_solution-1 |     0.483304 |       1.62052  |   0.630413 |
| k-d_tree_polars      |     0.497093 |       0.942032 |   0.996601 |
| barab-szabi-1        |     0.497571 |       0.933556 |   1.02525  |
| k-d_tree_pandas      |     0.492912 |       0.828581 |   1.22086  |
| k-d_tree_sklearn     |     0.491272 |       2.26831  |   1.27937  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498174 |        6.03524 |   0.785683 |
| Bori_Aron_solution-1 |     0.483393 |       13.0272  |   0.925746 |
| k-d_tree_sklearn     |     0.494475 |       19.2012  |   1.34431  |
| k-d_tree_polars      |     0.508687 |        5.30135 |   8.00381  |
| barab-szabi-1        |     0.49595  |        5.25848 |   8.07908  |
| k-d_tree_pandas      |     0.493031 |        4.19314 |   8.32103  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559419 |        83.8221 |    2.66659 |
| k-d_tree_sklearn     |     0.518514 |       274.825  |    3.36419 |
| Bori_Aron_solution-1 |     0.49077  |       161.525  |   18.2166  |