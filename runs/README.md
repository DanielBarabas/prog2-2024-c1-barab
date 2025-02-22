# 2025-02-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.70338  |       1e-06    |   0.381081 |
| barab-szabi-2        |     4.14651  |       0.438546 |   0.402588 |
| k-d_tree_polars      |     0.604542 |       0.423455 |   0.432942 |
| barab-szabi-1        |     0.59083  |       0.426984 |   0.515649 |
| Bori_Aron_solution-1 |     4.74553  |       0.626883 |   0.517196 |
| k-d_tree_pandas      |     0.611643 |       0.379408 |   0.552283 |
| k-d_tree_sklearn     |     3.04167  |       1.0749   |   1.05568  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.587448 |       0.406665 |   0.411005 |
| barab-szabi-1        |     0.600039 |       0.414935 |   0.416264 |
| barab-szabi-2        |     0.583909 |       0.416423 |   0.4172   |
| Bori_Aron_solution-1 |     0.599252 |       0.559127 |   0.540634 |
| k-d_tree_pandas      |     0.594813 |       0.395976 |   0.558763 |
| k-d_tree_sklearn     |     0.615133 |       0.984556 |   1.04203  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589588 |       0.428238 |   0.429889 |
| k-d_tree_polars      |     0.614084 |       0.449204 |   0.446923 |
| barab-szabi-1        |     0.620416 |       0.434783 |   0.453813 |
| Bori_Aron_solution-1 |     0.590434 |       0.594551 |   0.553192 |
| k-d_tree_pandas      |     0.60497  |       0.423393 |   0.609963 |
| k-d_tree_sklearn     |     0.608218 |       1.03293  |   1.09848  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609436 |       0.506693 |   0.455078 |
| barab-szabi-1        |     0.610834 |       0.556616 |   0.550952 |
| k-d_tree_polars      |     0.602043 |       0.567515 |   0.560444 |
| Bori_Aron_solution-1 |     0.602321 |       0.769418 |   0.590369 |
| k-d_tree_pandas      |     0.598933 |       0.493777 |   0.752468 |
| k-d_tree_sklearn     |     0.594256 |       1.24429  |   1.15031  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604879 |       0.741649 |   0.499208 |
| Bori_Aron_solution-1 |     0.596466 |       1.42952  |   0.606774 |
| k-d_tree_polars      |     0.591199 |       0.88757  |   0.913693 |
| barab-szabi-1        |     0.586483 |       0.893777 |   0.963429 |
| k-d_tree_pandas      |     0.60302  |       0.743053 |   1.18042  |
| k-d_tree_sklearn     |     0.608702 |       2.12495  |   1.23867  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60048  |        5.44822 |   0.740777 |
| Bori_Aron_solution-1 |     0.5903   |       10.9493  |   0.888782 |
| k-d_tree_sklearn     |     0.608733 |       16.3302  |   1.31843  |
| barab-szabi-1        |     0.617146 |        4.97482 |   6.74911  |
| k-d_tree_polars      |     0.593239 |        4.99481 |   6.81226  |
| k-d_tree_pandas      |     0.603379 |        3.84112 |   7.16535  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.975052 |        71.8657 |    3.49291 |
| k-d_tree_sklearn     |     0.692547 |       231.431  |    4.22657 |
| Bori_Aron_solution-1 |     0.594284 |       156.233  |   16.1045  |