# 2025-09-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.526127 |       0.396788 |   0.41895  |
| barab-szabi-2        |     8.4384   |       0.734144 |   0.419457 |
| k-d_tree_polars      |     0.52269  |       0.400435 |   0.425311 |
| Bori_Aron_solution-1 |     0.539404 |       0.540713 |   0.531368 |
| k-d_tree_pandas      |     0.521154 |       0.378904 |   0.540257 |
| solution-1           |     8.25778  |       1e-06    |   0.656083 |
| k-d_tree_sklearn     |     3.07438  |       1.2553   |   1.03499  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537104 |       0.417898 |   0.424989 |
| k-d_tree_polars      |     0.536546 |       0.414307 |   0.429102 |
| barab-szabi-1        |     0.53665  |       0.405455 |   0.430332 |
| k-d_tree_pandas      |     0.540428 |       0.383908 |   0.549906 |
| Bori_Aron_solution-1 |     0.526572 |       0.539329 |   0.560619 |
| k-d_tree_sklearn     |     0.537358 |       0.953883 |   1.04434  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534919 |       0.430387 |   0.435121 |
| k-d_tree_polars      |     0.538598 |       0.425988 |   0.450974 |
| barab-szabi-1        |     0.534113 |       0.433365 |   0.456099 |
| Bori_Aron_solution-1 |     0.530166 |       0.58715  |   0.551506 |
| k-d_tree_pandas      |     0.535725 |       0.406899 |   0.589786 |
| k-d_tree_sklearn     |     0.53943  |       0.98974  |   1.06196  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536376 |       0.49684  |   0.463586 |
| k-d_tree_polars      |     0.534821 |       0.540314 |   0.543526 |
| Bori_Aron_solution-1 |     0.530936 |       0.755074 |   0.549473 |
| barab-szabi-1        |     0.536086 |       0.543398 |   0.558974 |
| k-d_tree_pandas      |     0.53436  |       0.48297  |   0.738082 |
| k-d_tree_sklearn     |     0.539184 |       1.22535  |   1.12775  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538505 |       0.737751 |   0.493439 |
| Bori_Aron_solution-1 |     0.530932 |       1.37008  |   0.579204 |
| k-d_tree_polars      |     0.535891 |       0.860233 |   0.884378 |
| barab-szabi-1        |     0.535041 |       0.877255 |   0.921822 |
| k-d_tree_pandas      |     0.535191 |       0.744049 |   1.15005  |
| k-d_tree_sklearn     |     0.536527 |       2.0441   |   1.18534  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530688 |        5.12467 |   0.724763 |
| Bori_Aron_solution-1 |     0.529923 |       10.5163  |   0.837495 |
| k-d_tree_sklearn     |     0.538501 |       15.9037  |   1.28353  |
| barab-szabi-1        |     0.533666 |        5.04866 |   6.46105  |
| k-d_tree_polars      |     0.534288 |        5.01673 |   6.48113  |
| k-d_tree_pandas      |     0.535993 |        3.93457 |   6.87264  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538731 |        76.0814 |    2.72343 |
| k-d_tree_sklearn     |     0.671407 |       227.657  |    3.94977 |
| Bori_Aron_solution-1 |     0.540269 |       140.256  |   17.2932  |