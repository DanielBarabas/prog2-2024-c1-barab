# 2026-07-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.53724  |       1e-06    |   0.353851 |
| barab-szabi-2        |     0.398525 |       0.370694 |   0.360702 |
| barab-szabi-1        |     0.36819  |       0.329921 |   0.371382 |
| Bori_Aron_solution-1 |     0.361667 |       0.449376 |   0.44003  |
| k-d_tree_pandas      |     0.394408 |       0.317851 |   0.444731 |
| k-d_tree_sklearn     |     2.73901  |       0.949937 |   0.850906 |
| k-d_tree_polars      |     9.95329  |       0.45131  |   1.08055  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.373268 |       0.367297 |   0.37243  |
| k-d_tree_polars      |     0.368668 |       0.345352 |   0.376304 |
| barab-szabi-1        |     0.375532 |       0.347572 |   0.379151 |
| k-d_tree_pandas      |     0.365731 |       0.320777 |   0.453427 |
| Bori_Aron_solution-1 |     0.371912 |       0.454538 |   0.513691 |
| k-d_tree_sklearn     |     0.370063 |       0.841886 |   0.852901 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.362209 |       0.378281 |   0.372714 |
| k-d_tree_polars      |     0.36697  |       0.373097 |   0.39707  |
| barab-szabi-1        |     0.365823 |       0.374636 |   0.415544 |
| Bori_Aron_solution-1 |     0.361684 |       0.477447 |   0.44036  |
| k-d_tree_pandas      |     0.364969 |       0.335942 |   0.479494 |
| k-d_tree_sklearn     |     0.368625 |       0.830421 |   0.878467 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.367362 |       0.430324 |   0.39789  |
| Bori_Aron_solution-1 |     0.362356 |       0.625806 |   0.459944 |
| k-d_tree_polars      |     0.368739 |       0.47207  |   0.471209 |
| barab-szabi-1        |     0.374996 |       0.467843 |   0.47388  |
| k-d_tree_pandas      |     0.364474 |       0.401748 |   0.572509 |
| k-d_tree_sklearn     |     0.367412 |       1.02679  |   0.906723 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.36481  |       0.617717 |   0.451491 |
| Bori_Aron_solution-1 |     0.359939 |       1.13559  |   0.482961 |
| barab-szabi-1        |     0.363514 |       0.744329 |   0.753194 |
| k-d_tree_polars      |     0.3633   |       0.897382 |   0.839603 |
| k-d_tree_pandas      |     0.36326  |       0.631223 |   0.905231 |
| k-d_tree_sklearn     |     0.366663 |       1.73952  |   0.95141  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.36497  |        3.7327  |   0.591161 |
| Bori_Aron_solution-1 |     0.361193 |        8.1295  |   0.768759 |
| k-d_tree_sklearn     |     0.368918 |       12.0747  |   1.06071  |
| barab-szabi-1        |     0.36778  |        4.55925 |   4.84127  |
| k-d_tree_polars      |     0.366932 |        4.71021 |   4.86609  |
| k-d_tree_pandas      |     0.375282 |        3.22079 |   5.26202  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.02432  |        55.8654 |    2.55576 |
| k-d_tree_sklearn     |     1.84843  |       168.603  |    5.11461 |
| Bori_Aron_solution-1 |     0.362292 |       136.058  |   49.8639  |