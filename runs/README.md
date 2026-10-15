# 2026-10-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468633 |       0.446098 |   0.434747 |
| k-d_tree_polars      |     0.472449 |       0.42212  |   0.437671 |
| barab-szabi-1        |     9.92495  |       0.538737 |   0.515902 |
| solution-1           |     8.5113   |       1e-06    |   0.526843 |
| Bori_Aron_solution-1 |     0.46884  |       0.566633 |   0.553249 |
| k-d_tree_pandas      |     0.505012 |       0.408482 |   0.573078 |
| k-d_tree_sklearn     |     3.43195  |       1.28783  |   1.10074  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482477 |       0.463274 |   0.451379 |
| barab-szabi-1        |     0.495142 |       0.453453 |   0.451852 |
| k-d_tree_polars      |     0.4898   |       0.436747 |   0.454454 |
| Bori_Aron_solution-1 |     0.481423 |       0.578046 |   0.558989 |
| k-d_tree_pandas      |     0.486227 |       0.397929 |   0.584248 |
| k-d_tree_sklearn     |     0.491583 |       1.03298  |   1.13419  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486733 |       0.459751 |   0.452197 |
| barab-szabi-1        |     0.490765 |       0.480013 |   0.485264 |
| Bori_Aron_solution-1 |     0.471758 |       0.604722 |   0.581293 |
| k-d_tree_pandas      |     0.482412 |       0.425313 |   0.610542 |
| k-d_tree_polars      |     0.487131 |       0.454579 |   0.647248 |
| k-d_tree_sklearn     |     0.483801 |       1.08097  |   1.17057  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47593  |       0.526231 |   0.473364 |
| Bori_Aron_solution-1 |     0.469934 |       0.773594 |   0.581476 |
| barab-szabi-1        |     0.497344 |       0.595865 |   0.583706 |
| k-d_tree_polars      |     0.502932 |       0.603688 |   0.588883 |
| k-d_tree_pandas      |     0.483521 |       0.511949 |   0.750519 |
| k-d_tree_sklearn     |     0.496198 |       1.29916  |   1.18767  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47883  |       0.772177 |   0.516598 |
| Bori_Aron_solution-1 |     0.473333 |       1.46909  |   0.592728 |
| k-d_tree_polars      |     0.491397 |       0.937727 |   0.959592 |
| barab-szabi-1        |     0.495366 |       0.913312 |   0.984768 |
| k-d_tree_pandas      |     0.482387 |       0.811241 |   1.21084  |
| k-d_tree_sklearn     |     0.484555 |       2.19574  |   1.23743  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477654 |        5.64033 |   0.779218 |
| Bori_Aron_solution-1 |     0.480702 |       11.2177  |   0.838372 |
| k-d_tree_sklearn     |     0.487587 |       17.4797  |   1.36397  |
| barab-szabi-1        |     0.475876 |        5.36826 |   6.93527  |
| k-d_tree_polars      |     0.483211 |        5.34877 |   6.97904  |
| k-d_tree_pandas      |     0.477108 |        4.34828 |   7.30955  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.825653 |        76.6058 |    2.95318 |
| k-d_tree_sklearn     |     0.592814 |       245.296  |    3.7967  |
| Bori_Aron_solution-1 |     0.472652 |       154.714  |   25.4321  |