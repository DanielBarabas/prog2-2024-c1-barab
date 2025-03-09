# 2025-03-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.572263 |       0.396847 |   0.40605  |
| barab-szabi-1        |     0.569005 |       0.396497 |   0.410255 |
| barab-szabi-2        |     0.590616 |       0.409929 |   0.428264 |
| Bori_Aron_solution-1 |     0.559963 |       0.545229 |   0.535688 |
| solution-1           |     7.07259  |       1e-06    |   0.572652 |
| k-d_tree_pandas      |     7.68394  |       0.458992 |   0.690796 |
| k-d_tree_sklearn     |     3.05658  |       1.30177  |   1.03081  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.578278 |       0.40184  |   0.399485 |
| k-d_tree_polars      |     0.583495 |       0.421163 |   0.406974 |
| barab-szabi-1        |     0.579747 |       0.402275 |   0.409572 |
| Bori_Aron_solution-1 |     0.573081 |       0.542678 |   0.5325   |
| k-d_tree_pandas      |     0.604229 |       0.382314 |   0.551324 |
| k-d_tree_sklearn     |     0.58891  |       0.935422 |   1.009    |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587468 |       0.41469  |   0.414345 |
| k-d_tree_polars      |     0.600766 |       0.428675 |   0.432909 |
| barab-szabi-1        |     0.57994  |       0.425523 |   0.435485 |
| Bori_Aron_solution-1 |     0.573729 |       0.580709 |   0.550317 |
| k-d_tree_pandas      |     0.592884 |       0.397139 |   0.586726 |
| k-d_tree_sklearn     |     0.584191 |       0.986228 |   1.05094  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5855   |       0.47758  |   0.446406 |
| k-d_tree_polars      |     0.584056 |       0.540484 |   0.527915 |
| barab-szabi-1        |     0.582871 |       0.538921 |   0.540455 |
| Bori_Aron_solution-1 |     0.576622 |       0.76265  |   0.553361 |
| k-d_tree_pandas      |     0.585129 |       0.472942 |   0.727021 |
| k-d_tree_sklearn     |     0.589046 |       1.21864  |   1.13826  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585295 |       0.731768 |   0.477985 |
| Bori_Aron_solution-1 |     0.595355 |       1.38108  |   0.583979 |
| k-d_tree_polars      |     0.583094 |       0.860606 |   0.875292 |
| barab-szabi-1        |     0.584796 |       0.868455 |   0.920696 |
| k-d_tree_sklearn     |     0.59167  |       2.01594  |   1.18807  |
| k-d_tree_pandas      |     0.580723 |       0.737165 |   1.22131  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585686 |        5.46141 |   0.746    |
| Bori_Aron_solution-1 |     0.58224  |       10.5766  |   0.868257 |
| k-d_tree_sklearn     |     0.587385 |       16.3999  |   1.299    |
| barab-szabi-1        |     0.583714 |        4.87617 |   6.7389   |
| k-d_tree_polars      |     0.584532 |        4.90194 |   6.78931  |
| k-d_tree_pandas      |     0.585626 |        3.8132  |   7.11249  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.816005 |        72.6744 |    3.48299 |
| k-d_tree_sklearn     |     0.664551 |       227.099  |    4.31886 |
| Bori_Aron_solution-1 |     0.58246  |       153.466  |   14.3454  |