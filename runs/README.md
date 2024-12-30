# 2024-12-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613791 |       0.387124 |   0.379524 |
| k-d_tree_polars      |     0.608974 |       0.393986 |   0.385213 |
| barab-szabi-1        |     0.609281 |       0.395781 |   0.386123 |
| solution-1           |     7.78927  |       1e-06    |   0.458546 |
| k-d_tree_pandas      |     0.607491 |       0.379061 |   0.523627 |
| Bori_Aron_solution-1 |     0.598824 |       0.515896 |   0.536501 |
| k-d_tree_sklearn     |    10.5114   |       1.56088  |   0.982152 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617551 |       0.389323 |   0.385041 |
| barab-szabi-1        |     0.627579 |       0.405894 |   0.389069 |
| k-d_tree_polars      |     0.603818 |       0.402244 |   0.393483 |
| Bori_Aron_solution-1 |     0.602905 |       0.521104 |   0.513804 |
| k-d_tree_pandas      |     0.615111 |       0.377213 |   0.527257 |
| k-d_tree_sklearn     |     0.610511 |       0.905679 |   0.957791 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614063 |       0.402954 |   0.394777 |
| k-d_tree_polars      |     0.609646 |       0.423525 |   0.417496 |
| barab-szabi-1        |     0.639673 |       0.430412 |   0.420796 |
| Bori_Aron_solution-1 |     0.600141 |       0.558846 |   0.520298 |
| k-d_tree_pandas      |     0.611205 |       0.397651 |   0.567596 |
| k-d_tree_sklearn     |     0.619665 |       0.936869 |   1.00115  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603937 |       0.462292 |   0.428451 |
| k-d_tree_polars      |     0.60939  |       0.531719 |   0.512167 |
| barab-szabi-1        |     0.612323 |       0.534135 |   0.526422 |
| Bori_Aron_solution-1 |     0.604367 |       0.742734 |   0.532644 |
| k-d_tree_pandas      |     0.607764 |       0.484637 |   0.711646 |
| k-d_tree_sklearn     |     0.633212 |       1.15439  |   1.05104  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615508 |       0.727754 |   0.480635 |
| Bori_Aron_solution-1 |     0.626305 |       1.37765  |   0.561965 |
| k-d_tree_polars      |     0.607331 |       0.877839 |   0.864002 |
| barab-szabi-1        |     0.611195 |       0.867848 |   0.905846 |
| k-d_tree_sklearn     |     0.617441 |       1.98054  |   1.13378  |
| k-d_tree_pandas      |     0.607059 |       0.750068 |   1.14424  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604401 |        5.46952 |   0.755048 |
| Bori_Aron_solution-1 |     0.60192  |       10.8178  |   0.821028 |
| k-d_tree_sklearn     |     0.626951 |       15.8298  |   1.24405  |
| k-d_tree_polars      |     0.607041 |        4.88613 |   6.47416  |
| barab-szabi-1        |     0.620559 |        4.90897 |   6.51914  |
| k-d_tree_pandas      |     0.627818 |        3.9369  |   6.95321  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.645324 |        69.8749 |    2.92526 |
| k-d_tree_sklearn     |     0.616472 |       222.567  |    4.16051 |
| Bori_Aron_solution-1 |     0.62249  |       151.523  |   18.2693  |