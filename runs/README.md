# 2025-03-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.41003  |       1e-06    |   0.376553 |
| barab-szabi-2        |     0.56795  |       0.412377 |   0.412687 |
| k-d_tree_polars      |     0.559649 |       0.407007 |   0.419716 |
| barab-szabi-1        |     0.55928  |       0.410123 |   0.424905 |
| Bori_Aron_solution-1 |     0.550043 |       0.55182  |   0.549291 |
| k-d_tree_pandas      |     7.46572  |       0.406717 |   0.586889 |
| k-d_tree_sklearn     |     2.90019  |       0.999379 |   1.03895  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.558408 |       0.405026 |   0.407986 |
| k-d_tree_polars      |     0.559422 |       0.403783 |   0.409346 |
| barab-szabi-2        |     0.562749 |       0.412271 |   0.420166 |
| Bori_Aron_solution-1 |     0.560814 |       0.567125 |   0.538812 |
| k-d_tree_pandas      |     0.574792 |       0.390618 |   0.548944 |
| k-d_tree_sklearn     |     0.566166 |       0.946385 |   1.01273  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57146  |       0.445784 |   0.421125 |
| k-d_tree_polars      |     0.566497 |       0.442314 |   0.439157 |
| barab-szabi-1        |     0.558952 |       0.428352 |   0.439755 |
| Bori_Aron_solution-1 |     0.552886 |       0.583645 |   0.550032 |
| k-d_tree_pandas      |     0.566542 |       0.402411 |   0.587749 |
| k-d_tree_sklearn     |     0.58259  |       0.991839 |   1.03693  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562818 |       0.483602 |   0.448152 |
| k-d_tree_polars      |     0.573036 |       0.538639 |   0.532394 |
| barab-szabi-1        |     0.564446 |       0.537478 |   0.542201 |
| Bori_Aron_solution-1 |     0.55131  |       0.745373 |   0.556248 |
| k-d_tree_pandas      |     0.560916 |       0.47542  |   0.726535 |
| k-d_tree_sklearn     |     0.560952 |       1.24921  |   1.14722  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567884 |       0.720894 |   0.482919 |
| Bori_Aron_solution-1 |     0.553957 |       1.3707   |   0.579616 |
| k-d_tree_polars      |     0.56171  |       0.872059 |   0.888534 |
| barab-szabi-1        |     0.563837 |       0.861511 |   0.906558 |
| k-d_tree_pandas      |     0.573596 |       0.738563 |   1.15668  |
| k-d_tree_sklearn     |     0.560919 |       2.00953  |   1.18231  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570587 |        5.30592 |   0.738775 |
| Bori_Aron_solution-1 |     0.554635 |       11.245   |   0.932958 |
| k-d_tree_sklearn     |     0.558379 |       16.4699  |   1.3141   |
| k-d_tree_polars      |     0.568941 |        4.87558 |   6.69464  |
| barab-szabi-1        |     0.575105 |        5.00389 |   6.97307  |
| k-d_tree_pandas      |     0.553671 |        3.83947 |   7.12776  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.764207 |        80.4225 |    3.76991 |
| k-d_tree_sklearn     |     0.635477 |       243.14   |    4.1798  |
| Bori_Aron_solution-1 |     0.563502 |       161.12   |   16.123   |