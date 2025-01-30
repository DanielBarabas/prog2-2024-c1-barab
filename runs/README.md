# 2025-01-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.31374  |       1e-06    |   0.360802 |
| barab-szabi-2        |     7.51117  |       0.463342 |   0.404755 |
| barab-szabi-1        |     0.591889 |       0.411942 |   0.406596 |
| k-d_tree_polars      |     0.58475  |       0.407319 |   0.410213 |
| Bori_Aron_solution-1 |     0.616999 |       0.541858 |   0.540591 |
| k-d_tree_pandas      |     0.594749 |       0.391705 |   0.541218 |
| k-d_tree_sklearn     |     2.91402  |       0.976865 |   1.07359  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.602334 |       0.413015 |   0.406866 |
| barab-szabi-2        |     0.590161 |       0.409946 |   0.407669 |
| barab-szabi-1        |     0.593703 |       0.421538 |   0.415176 |
| Bori_Aron_solution-1 |     0.584685 |       0.546453 |   0.540335 |
| k-d_tree_pandas      |     0.597592 |       0.393295 |   0.55938  |
| k-d_tree_sklearn     |     0.596362 |       0.957488 |   1.08027  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.596404 |       0.420144 |   0.419016 |
| k-d_tree_polars      |     0.593106 |       0.437511 |   0.434646 |
| barab-szabi-1        |     0.593448 |       0.437647 |   0.442128 |
| Bori_Aron_solution-1 |     0.585994 |       0.579701 |   0.541135 |
| k-d_tree_pandas      |     0.591633 |       0.406878 |   0.591265 |
| k-d_tree_sklearn     |     0.598497 |       1.017    |   1.05835  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588303 |       0.488379 |   0.445756 |
| k-d_tree_polars      |     0.593487 |       0.554992 |   0.538866 |
| Bori_Aron_solution-1 |     0.591015 |       0.753618 |   0.548065 |
| barab-szabi-1        |     0.591596 |       0.539759 |   0.550711 |
| k-d_tree_pandas      |     0.597258 |       0.482108 |   0.729313 |
| k-d_tree_sklearn     |     0.600075 |       1.26215  |   1.12144  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.592776 |       0.725502 |   0.486046 |
| Bori_Aron_solution-1 |     0.585223 |       1.39204  |   0.582912 |
| k-d_tree_polars      |     0.589311 |       0.872735 |   0.883502 |
| barab-szabi-1        |     0.588074 |       0.892328 |   0.924051 |
| k-d_tree_pandas      |     0.591949 |       0.74969  |   1.17249  |
| k-d_tree_sklearn     |     0.602919 |       2.05272  |   1.20455  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588317 |        5.28524 |   0.742259 |
| Bori_Aron_solution-1 |     0.5891   |       10.6225  |   0.875411 |
| k-d_tree_sklearn     |     0.594549 |       16.3639  |   1.33384  |
| k-d_tree_polars      |     0.59625  |        4.87575 |   6.61883  |
| barab-szabi-1        |     0.627774 |        4.92095 |   6.65483  |
| k-d_tree_pandas      |     0.600892 |        3.8507  |   7.06799  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.59251  |        75.8616 |    3.0439  |
| k-d_tree_sklearn     |     0.598269 |       231.373  |    4.48149 |
| Bori_Aron_solution-1 |     0.65528  |       144.243  |   18.3711  |