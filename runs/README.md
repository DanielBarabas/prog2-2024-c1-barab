# 2025-08-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538524 |       0.426446 |   0.434841 |
| solution-1           |     8.20046  |       1e-06    |   0.439942 |
| k-d_tree_polars      |     0.549264 |       0.412167 |   0.452317 |
| barab-szabi-1        |     0.559577 |       0.452005 |   0.493994 |
| Bori_Aron_solution-1 |     0.558898 |       0.563895 |   0.568319 |
| k-d_tree_pandas      |     8.33494  |       0.41361  |   0.647668 |
| k-d_tree_sklearn     |     3.05272  |       1.13833  |   1.0792   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55753  |       0.430004 |   0.431916 |
| barab-szabi-1        |     0.564459 |       0.42046  |   0.432124 |
| k-d_tree_polars      |     0.552723 |       0.42368  |   0.448681 |
| k-d_tree_pandas      |     0.55872  |       0.402625 |   0.559552 |
| Bori_Aron_solution-1 |     0.546576 |       0.576675 |   0.561065 |
| k-d_tree_sklearn     |     0.553539 |       0.992636 |   1.09441  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552211 |       0.451498 |   0.454391 |
| k-d_tree_polars      |     0.577174 |       0.443491 |   0.473817 |
| barab-szabi-1        |     0.559015 |       0.455465 |   0.484262 |
| Bori_Aron_solution-1 |     0.567226 |       0.599503 |   0.575258 |
| k-d_tree_pandas      |     0.558959 |       0.421507 |   0.622729 |
| k-d_tree_sklearn     |     0.56144  |       1.0297   |   1.11872  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554028 |       0.517306 |   0.48258  |
| k-d_tree_polars      |     0.547784 |       0.562187 |   0.56053  |
| Bori_Aron_solution-1 |     0.552237 |       0.777988 |   0.572309 |
| barab-szabi-1        |     0.554797 |       0.563075 |   0.583416 |
| k-d_tree_pandas      |     0.555445 |       0.507106 |   0.757002 |
| k-d_tree_sklearn     |     0.563131 |       1.27663  |   1.16383  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54859  |       0.753252 |   0.507349 |
| Bori_Aron_solution-1 |     0.541135 |       1.41552  |   0.589221 |
| k-d_tree_polars      |     0.545393 |       0.884401 |   0.919458 |
| barab-szabi-1        |     0.555729 |       0.897601 |   0.968708 |
| k-d_tree_pandas      |     0.561115 |       0.759822 |   1.21281  |
| k-d_tree_sklearn     |     0.545983 |       2.12751  |   1.21873  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554996 |        5.37694 |   0.763284 |
| Bori_Aron_solution-1 |     0.545739 |       10.6196  |   0.855796 |
| k-d_tree_sklearn     |     0.559009 |       16.4361  |   1.34564  |
| k-d_tree_polars      |     0.559988 |        5.09389 |   6.5891   |
| barab-szabi-1        |     0.546284 |        5.11852 |   6.64126  |
| k-d_tree_pandas      |     0.542911 |        3.88759 |   6.92161  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562521 |        73.8646 |    2.73675 |
| k-d_tree_sklearn     |     0.565402 |       235.983  |    4.34262 |
| Bori_Aron_solution-1 |     0.649365 |       143.879  |   17.8281  |