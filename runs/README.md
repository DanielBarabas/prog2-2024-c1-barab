# 2025-08-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.57318  |       0.427109 |   0.454541 |
| solution-1           |     8.03168  |       1e-06    |   0.460858 |
| barab-szabi-2        |     0.566677 |       0.466292 |   0.477856 |
| barab-szabi-1        |     0.655992 |       0.451714 |   0.480558 |
| Bori_Aron_solution-1 |     0.573895 |       0.568681 |   0.574789 |
| k-d_tree_pandas      |     9.02507  |       0.454535 |   0.756353 |
| k-d_tree_sklearn     |     3.29763  |       1.13085  |   1.11924  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561267 |       0.449366 |   0.44461  |
| k-d_tree_polars      |     0.562542 |       0.42273  |   0.451229 |
| barab-szabi-1        |     0.568573 |       0.433724 |   0.454038 |
| Bori_Aron_solution-1 |     0.558999 |       0.577216 |   0.572823 |
| k-d_tree_pandas      |     0.562487 |       0.416071 |   0.581781 |
| k-d_tree_sklearn     |     0.569497 |       1.034    |   1.12571  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558504 |       0.459499 |   0.456671 |
| k-d_tree_polars      |     0.55755  |       0.452767 |   0.470398 |
| barab-szabi-1        |     0.561954 |       0.455574 |   0.477699 |
| Bori_Aron_solution-1 |     0.554734 |       0.624615 |   0.608219 |
| k-d_tree_pandas      |     0.561861 |       0.428383 |   0.619081 |
| k-d_tree_sklearn     |     0.560889 |       1.0915   |   1.13404  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563998 |       0.521966 |   0.484082 |
| k-d_tree_polars      |     0.566504 |       0.558298 |   0.57116  |
| barab-szabi-1        |     0.564679 |       0.563152 |   0.584238 |
| Bori_Aron_solution-1 |     0.555807 |       0.797267 |   0.597704 |
| k-d_tree_pandas      |     0.563219 |       0.507295 |   0.767201 |
| k-d_tree_sklearn     |     0.565963 |       1.29812  |   1.1852   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546992 |       0.752901 |   0.508694 |
| Bori_Aron_solution-1 |     0.548293 |       1.44149  |   0.60948  |
| k-d_tree_polars      |     0.55953  |       0.896846 |   0.931764 |
| barab-szabi-1        |     0.567074 |       0.898991 |   0.97384  |
| k-d_tree_pandas      |     0.553825 |       0.777947 |   1.23121  |
| k-d_tree_sklearn     |     0.5567   |       2.20551  |   1.27351  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552368 |        5.53111 |   0.774942 |
| Bori_Aron_solution-1 |     0.544398 |       10.7556  |   0.860259 |
| k-d_tree_sklearn     |     0.566022 |       16.827   |   1.3368   |
| barab-szabi-1        |     0.549677 |        5.08355 |   6.77549  |
| k-d_tree_polars      |     0.551552 |        5.03887 |   6.81415  |
| k-d_tree_pandas      |     0.562158 |        3.98136 |   7.0762   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550886 |        73.3148 |    2.74631 |
| k-d_tree_sklearn     |     0.566029 |       234.059  |    4.09962 |
| Bori_Aron_solution-1 |     0.586773 |       144.128  |   18.2105  |