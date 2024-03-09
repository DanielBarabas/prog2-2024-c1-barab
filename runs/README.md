# 2024-03-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.730896 |       0.35636  |   0.352308 |
| barab-szabi-1        |     0.733528 |       0.399108 |   0.363564 |
| solution-1           |     8.3694   |       1e-06    |   0.460587 |
| k-d_tree_pandas      |     0.729096 |       0.37742  |   0.49471  |
| Bori_Aron_solution-1 |     0.713993 |       0.492592 |   0.495446 |
| k-d_tree_polars      |     8.217    |       0.462658 |   0.607148 |
| k-d_tree_sklearn     |     3.18881  |       0.975306 |   0.662455 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.726239 |       0.361838 |   0.355843 |
| k-d_tree_polars      |     0.725646 |       0.405041 |   0.362812 |
| barab-szabi-1        |     0.73196  |       0.416369 |   0.363744 |
| Bori_Aron_solution-1 |     0.715698 |       0.507915 |   0.493807 |
| k-d_tree_pandas      |     0.728755 |       0.381335 |   0.503207 |
| k-d_tree_sklearn     |     0.742054 |       0.854373 |   0.667669 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.725176 |       0.380064 |   0.372079 |
| k-d_tree_polars      |     0.723068 |       0.427469 |   0.391989 |
| barab-szabi-1        |     0.757834 |       0.428012 |   0.395205 |
| Bori_Aron_solution-1 |     0.731418 |       0.550131 |   0.502707 |
| k-d_tree_pandas      |     0.727195 |       0.403103 |   0.547984 |
| k-d_tree_sklearn     |     0.734474 |       0.909809 |   0.696932 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.743638 |       0.446325 |   0.409935 |
| k-d_tree_polars      |     0.738498 |       0.544177 |   0.493598 |
| barab-szabi-1        |     0.741294 |       0.549283 |   0.50514  |
| Bori_Aron_solution-1 |     0.717045 |       0.735754 |   0.521491 |
| k-d_tree_pandas      |     0.747787 |       0.49826  |   0.687738 |
| k-d_tree_sklearn     |     0.74027  |       1.12009  |   0.774834 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.730419 |       0.684534 |   0.436693 |
| Bori_Aron_solution-1 |     0.715226 |       1.37635  |   0.532292 |
| k-d_tree_polars      |     0.742252 |       0.867802 |   0.838287 |
| k-d_tree_sklearn     |     0.739076 |       1.92743  |   0.857501 |
| barab-szabi-1        |     0.732694 |       0.865876 |   0.866827 |
| k-d_tree_pandas      |     0.727875 |       0.754364 |   1.11189  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.724256 |        5.53272 |   0.770331 |
| Bori_Aron_solution-1 |     0.741824 |       10.703   |   0.792802 |
| k-d_tree_sklearn     |     0.733816 |       15.9485  |   1.06326  |
| k-d_tree_polars      |     0.723443 |        4.95191 |   6.49633  |
| barab-szabi-1        |     0.728053 |        5.0441  |   6.51201  |
| k-d_tree_pandas      |     0.734734 |        4.00404 |   6.896    |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.878824 |        76.3399 |    3.86838 |
| k-d_tree_sklearn     |     0.731747 |       239.096  |    5.30516 |
| Bori_Aron_solution-1 |     0.855103 |       139.518  |   18.5866  |