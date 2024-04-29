# 2024-04-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.727465 |       0.359931 |   0.357238 |
| k-d_tree_polars      |     0.718243 |       0.415575 |   0.359096 |
| barab-szabi-1        |     8.32654  |       0.477083 |   0.368474 |
| solution-1           |     8.06254  |       1e-06    |   0.390094 |
| Bori_Aron_solution-1 |     0.708648 |       0.495949 |   0.487736 |
| k-d_tree_pandas      |     0.731035 |       0.39994  |   0.502486 |
| k-d_tree_sklearn     |     3.25586  |       0.91773  |   0.684347 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.747551 |       0.346628 |   0.340076 |
| barab-szabi-1        |     0.746605 |       0.412488 |   0.35578  |
| k-d_tree_polars      |     0.730851 |       0.419831 |   0.360666 |
| Bori_Aron_solution-1 |     0.73095  |       0.528555 |   0.475457 |
| k-d_tree_pandas      |     0.73368  |       0.390226 |   0.510953 |
| k-d_tree_sklearn     |     0.744874 |       0.862842 |   0.672662 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.737538 |       0.364727 |   0.360421 |
| barab-szabi-1        |     0.73976  |       0.432253 |   0.377088 |
| k-d_tree_polars      |     0.751902 |       0.435977 |   0.378425 |
| Bori_Aron_solution-1 |     0.727079 |       0.552335 |   0.481553 |
| k-d_tree_pandas      |     0.778462 |       0.419389 |   0.520487 |
| k-d_tree_sklearn     |     0.739469 |       0.891495 |   0.69801  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.750787 |       0.438049 |   0.402765 |
| k-d_tree_polars      |     0.760146 |       0.549482 |   0.487975 |
| barab-szabi-1        |     0.743278 |       0.546012 |   0.492623 |
| Bori_Aron_solution-1 |     0.745519 |       0.700762 |   0.495732 |
| k-d_tree_pandas      |     0.75464  |       0.514603 |   0.67713  |
| k-d_tree_sklearn     |     0.775758 |       1.12123  |   0.782328 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.743971 |       0.670332 |   0.427237 |
| Bori_Aron_solution-1 |     0.743989 |       1.37363  |   0.527325 |
| k-d_tree_polars      |     0.738839 |       0.868925 |   0.828497 |
| k-d_tree_sklearn     |     0.740603 |       1.9493   |   0.865042 |
| barab-szabi-1        |     0.756966 |       0.871208 |   0.874003 |
| k-d_tree_pandas      |     0.72749  |       0.766381 |   1.09546  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.742117 |        5.61101 |   0.766795 |
| Bori_Aron_solution-1 |     0.755667 |       10.7593  |   0.786225 |
| k-d_tree_sklearn     |     0.799603 |       15.6213  |   1.0601   |
| k-d_tree_polars      |     0.750489 |        4.79557 |   6.89554  |
| barab-szabi-1        |     0.738019 |        4.90854 |   6.90811  |
| k-d_tree_pandas      |     0.779496 |        3.87671 |   7.39773  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.04895  |        71.5043 |    3.54713 |
| k-d_tree_sklearn     |     0.812441 |       236.932  |    5.30658 |
| Bori_Aron_solution-1 |     0.730329 |       155.069  |   18.0155  |