# 2026-02-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.943443 |       0.775453 |   0.427685 |
| barab-szabi-1        |     0.487011 |       0.400319 |   0.428181 |
| k-d_tree_polars      |     0.492853 |       0.408632 |   0.435485 |
| Bori_Aron_solution-1 |     0.486514 |       0.54476  |   0.547158 |
| solution-1           |     8.4157   |       1e-06    |   0.893712 |
| k-d_tree_pandas      |     8.45137  |       0.445033 |   1.05185  |
| k-d_tree_sklearn     |     3.19857  |       1.56053  |   1.07786  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485878 |       0.437178 |   0.427951 |
| k-d_tree_polars      |     0.488038 |       0.412995 |   0.438782 |
| barab-szabi-1        |     0.486927 |       0.406993 |   0.441277 |
| Bori_Aron_solution-1 |     0.48315  |       0.547909 |   0.54553  |
| k-d_tree_pandas      |     0.49554  |       0.415681 |   0.554806 |
| k-d_tree_sklearn     |     0.493577 |       0.966036 |   1.1012   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.494387 |       0.450845 |   0.454193 |
| barab-szabi-1        |     0.492076 |       0.434392 |   0.462468 |
| k-d_tree_polars      |     0.490724 |       0.441162 |   0.470985 |
| Bori_Aron_solution-1 |     0.481397 |       0.589903 |   0.544683 |
| k-d_tree_pandas      |     0.49021  |       0.408189 |   0.602719 |
| k-d_tree_sklearn     |     0.497855 |       1.03407  |   1.10379  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485685 |       0.513277 |   0.472112 |
| k-d_tree_polars      |     0.49499  |       0.553993 |   0.561397 |
| Bori_Aron_solution-1 |     0.479198 |       0.780958 |   0.561983 |
| barab-szabi-1        |     0.492633 |       0.55747  |   0.567532 |
| k-d_tree_pandas      |     0.485076 |       0.495115 |   0.737908 |
| k-d_tree_sklearn     |     0.492229 |       1.29665  |   1.15692  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488097 |       0.73406  |   0.510442 |
| Bori_Aron_solution-1 |     0.484766 |       1.47631  |   0.587913 |
| k-d_tree_polars      |     0.493087 |       0.931681 |   0.922781 |
| barab-szabi-1        |     0.498651 |       0.939936 |   0.963287 |
| k-d_tree_pandas      |     0.482563 |       0.819116 |   1.19579  |
| k-d_tree_sklearn     |     0.493386 |       2.18016  |   1.23171  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48867  |        5.09472 |   0.752717 |
| Bori_Aron_solution-1 |     0.487903 |       11.1715  |   0.862997 |
| k-d_tree_sklearn     |     0.494359 |       16.8594  |   1.30783  |
| k-d_tree_polars      |     0.494154 |        5.61222 |   6.62716  |
| barab-szabi-1        |     0.491112 |        5.51948 |   6.7756   |
| k-d_tree_pandas      |     0.488067 |        4.47675 |   6.95019  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.4924   |        72.0194 |    2.83579 |
| k-d_tree_sklearn     |     0.519051 |       236.764  |    4.04479 |
| Bori_Aron_solution-1 |     0.611315 |       147.167  |   18.0667  |