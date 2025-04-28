# 2025-04-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     1.08813  |       0.42028  |   0.446822 |
| barab-szabi-2        |     1.06726  |       0.472733 |   0.469031 |
| k-d_tree_pandas      |     0.606411 |       0.464164 |   0.574406 |
| Bori_Aron_solution-1 |     0.738301 |       0.603755 |   0.58612  |
| solution-1           |     8.11934  |       1e-06    |   0.615081 |
| k-d_tree_polars      |     8.46181  |       0.496922 |   0.642803 |
| k-d_tree_sklearn     |     3.01657  |       1.18435  |   1.11771  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5941   |       0.444799 |   0.443127 |
| barab-szabi-1        |     0.594864 |       0.434386 |   0.446974 |
| k-d_tree_polars      |     0.60376  |       0.433674 |   0.451283 |
| k-d_tree_pandas      |     0.639024 |       0.416802 |   0.607601 |
| Bori_Aron_solution-1 |     0.583565 |       0.638967 |   0.608093 |
| k-d_tree_sklearn     |     0.584464 |       1.01449  |   1.13399  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581573 |       0.442631 |   0.426594 |
| k-d_tree_polars      |     0.577117 |       0.462891 |   0.46999  |
| barab-szabi-1        |     0.585952 |       0.447436 |   0.470814 |
| Bori_Aron_solution-1 |     0.560784 |       0.591836 |   0.5504   |
| k-d_tree_pandas      |     0.561614 |       0.403834 |   0.635146 |
| k-d_tree_sklearn     |     0.592783 |       1.01721  |   1.10939  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564277 |       0.48745  |   0.450756 |
| k-d_tree_polars      |     0.599114 |       0.542945 |   0.541524 |
| barab-szabi-1        |     0.571437 |       0.554404 |   0.553261 |
| Bori_Aron_solution-1 |     0.562561 |       0.777853 |   0.556088 |
| k-d_tree_pandas      |     0.592263 |       0.527611 |   0.741484 |
| k-d_tree_sklearn     |     0.568031 |       1.2279   |   1.20521  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588109 |       0.723694 |   0.487073 |
| Bori_Aron_solution-1 |     0.587752 |       1.43359  |   0.659874 |
| k-d_tree_polars      |     0.594374 |       0.89297  |   0.889796 |
| barab-szabi-1        |     0.589962 |       0.901693 |   0.95779  |
| k-d_tree_pandas      |     0.57167  |       0.765998 |   1.20378  |
| k-d_tree_sklearn     |     0.604182 |       2.15826  |   1.25173  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564903 |        5.40009 |   0.735296 |
| Bori_Aron_solution-1 |     0.559834 |       10.6956  |   0.879939 |
| k-d_tree_sklearn     |     0.570881 |       16.4596  |   1.32708  |
| barab-szabi-1        |     0.563131 |        4.98911 |   6.63378  |
| k-d_tree_polars      |     0.61122  |        5.06493 |   6.70367  |
| k-d_tree_pandas      |     0.568584 |        3.97118 |   7.03801  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565971 |        81.5238 |    2.96328 |
| k-d_tree_sklearn     |     0.732969 |       234.994  |    4.28193 |
| Bori_Aron_solution-1 |     0.673143 |       149.733  |   18.128   |