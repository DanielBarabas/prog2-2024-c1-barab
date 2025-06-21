# 2025-06-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542481 |       0.418756 |   0.427058 |
| k-d_tree_polars      |     0.538567 |       0.403189 |   0.430029 |
| barab-szabi-1        |     0.535173 |       0.435533 |   0.445498 |
| solution-1           |     7.4431   |       1e-06    |   0.541522 |
| Bori_Aron_solution-1 |     0.534452 |       0.542499 |   0.546042 |
| k-d_tree_pandas      |     7.68247  |       0.403968 |   0.673598 |
| k-d_tree_sklearn     |     3.04489  |       1.11698  |   1.0903   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.573095 |       0.427433 |   0.434057 |
| k-d_tree_polars      |     0.564585 |       0.416672 |   0.435153 |
| barab-szabi-1        |     0.568352 |       0.422761 |   0.438896 |
| Bori_Aron_solution-1 |     0.555966 |       0.566326 |   0.547454 |
| k-d_tree_pandas      |     0.565618 |       0.402681 |   0.574083 |
| k-d_tree_sklearn     |     0.563732 |       0.999398 |   1.07399  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561462 |       0.440648 |   0.450207 |
| barab-szabi-1        |     0.5744   |       0.440877 |   0.460434 |
| k-d_tree_polars      |     0.555781 |       0.461429 |   0.463281 |
| Bori_Aron_solution-1 |     0.565101 |       0.595279 |   0.565328 |
| k-d_tree_pandas      |     0.558728 |       0.413968 |   0.60868  |
| k-d_tree_sklearn     |     0.569035 |       1.0503   |   1.09784  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558054 |       0.496447 |   0.466002 |
| k-d_tree_polars      |     0.560907 |       0.547143 |   0.552623 |
| barab-szabi-1        |     0.553766 |       0.543377 |   0.560709 |
| Bori_Aron_solution-1 |     0.555963 |       0.784761 |   0.569143 |
| k-d_tree_pandas      |     0.557294 |       0.487528 |   0.74942  |
| k-d_tree_sklearn     |     0.55691  |       1.29248  |   1.15859  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551838 |       0.744418 |   0.496661 |
| Bori_Aron_solution-1 |     0.556847 |       1.40306  |   0.580798 |
| k-d_tree_polars      |     0.548873 |       0.886821 |   0.903567 |
| barab-szabi-1        |     0.555518 |       0.885273 |   0.943751 |
| k-d_tree_pandas      |     0.55599  |       0.761766 |   1.1937   |
| k-d_tree_sklearn     |     0.559375 |       2.09518  |   1.20733  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562272 |        5.46996 |   0.737705 |
| Bori_Aron_solution-1 |     0.556302 |       10.7188  |   0.85272  |
| k-d_tree_sklearn     |     0.561735 |       16.726   |   1.40994  |
| barab-szabi-1        |     0.563815 |        5.01705 |   6.71955  |
| k-d_tree_polars      |     0.553798 |        4.993   |   6.81306  |
| k-d_tree_pandas      |     0.559196 |        3.93094 |   7.11061  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.791917 |        71.3841 |    2.78081 |
| k-d_tree_sklearn     |     0.633326 |       229.562  |    3.95041 |
| Bori_Aron_solution-1 |     0.563651 |       143.539  |   17.4616  |