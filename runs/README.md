# 2024-03-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732334 |       0.363187 |   0.367735 |
| solution-1           |     8.2933   |       1e-06    |   0.368505 |
| barab-szabi-1        |     0.744427 |       0.41064  |   0.369573 |
| k-d_tree_polars      |     9.23838  |       0.426941 |   0.419516 |
| Bori_Aron_solution-1 |     0.737804 |       0.50619  |   0.502014 |
| k-d_tree_pandas      |     0.745828 |       0.389534 |   0.516519 |
| k-d_tree_sklearn     |     3.36811  |       0.933344 |   0.681915 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.738774 |       0.424036 |   0.370752 |
| barab-szabi-2        |     0.76111  |       0.37777  |   0.373499 |
| barab-szabi-1        |     0.757694 |       0.419288 |   0.382759 |
| Bori_Aron_solution-1 |     0.731521 |       0.527065 |   0.515786 |
| k-d_tree_pandas      |     0.74896  |       0.394246 |   0.521445 |
| k-d_tree_sklearn     |     0.739223 |       0.890829 |   0.695161 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.733032 |       0.384237 |   0.380898 |
| k-d_tree_polars      |     0.746885 |       0.440325 |   0.396564 |
| barab-szabi-1        |     0.744008 |       0.474109 |   0.403518 |
| Bori_Aron_solution-1 |     0.729751 |       0.556958 |   0.508495 |
| k-d_tree_pandas      |     0.75006  |       0.407349 |   0.556872 |
| k-d_tree_sklearn     |     0.755667 |       0.913924 |   0.737586 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.73092  |       0.453252 |   0.407593 |
| k-d_tree_polars      |     0.735003 |       0.55052  |   0.502805 |
| barab-szabi-1        |     0.739964 |       0.547732 |   0.506591 |
| Bori_Aron_solution-1 |     0.727856 |       0.741704 |   0.52764  |
| k-d_tree_pandas      |     0.738318 |       0.491378 |   0.7117   |
| k-d_tree_sklearn     |     0.761795 |       1.14863  |   0.770237 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.750639 |       0.724145 |   0.472841 |
| Bori_Aron_solution-1 |     0.736224 |       1.40611  |   0.550648 |
| k-d_tree_polars      |     0.761685 |       0.892976 |   0.862295 |
| k-d_tree_sklearn     |     0.7509   |       2.00576  |   0.881787 |
| barab-szabi-1        |     0.742679 |       0.897839 |   0.888612 |
| k-d_tree_pandas      |     0.747816 |       0.770255 |   1.12561  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.735406 |        5.61742 |   0.790844 |
| Bori_Aron_solution-1 |     0.761703 |       10.938   |   0.863655 |
| k-d_tree_sklearn     |     0.742153 |       16.7993  |   1.08487  |
| k-d_tree_polars      |     0.738667 |        4.97204 |   6.5958   |
| barab-szabi-1        |     0.772365 |        4.93976 |   6.80852  |
| k-d_tree_pandas      |     0.743776 |        3.99324 |   7.06161  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.85394  |        75.9574 |    3.6588  |
| k-d_tree_sklearn     |     0.750547 |       237.382  |    5.21648 |
| Bori_Aron_solution-1 |     0.81907  |       148.654  |   16.5912  |