# 2025-02-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     3.70914  |       0.520057 |   0.400456 |
| k-d_tree_polars      |     0.585549 |       0.405746 |   0.402991 |
| barab-szabi-1        |     0.587946 |       0.404001 |   0.40852  |
| Bori_Aron_solution-1 |     4.36237  |       0.823518 |   0.484127 |
| k-d_tree_pandas      |     0.586215 |       0.382576 |   0.549396 |
| solution-1           |     7.05862  |       1e-06    |   0.625413 |
| k-d_tree_sklearn     |     3.01422  |       1.25285  |   1.01793  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.582237 |       0.408155 |   0.400199 |
| barab-szabi-1        |     0.58282  |       0.405133 |   0.406055 |
| k-d_tree_polars      |     0.580323 |       0.402609 |   0.410028 |
| k-d_tree_pandas      |     0.590439 |       0.382042 |   0.549465 |
| Bori_Aron_solution-1 |     0.590536 |       0.55313  |   0.559736 |
| k-d_tree_sklearn     |     0.587786 |       0.938689 |   1.01336  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57733  |       0.421226 |   0.415546 |
| k-d_tree_polars      |     0.581367 |       0.42673  |   0.430199 |
| barab-szabi-1        |     0.581997 |       0.428596 |   0.434523 |
| Bori_Aron_solution-1 |     0.575069 |       0.579736 |   0.539549 |
| k-d_tree_pandas      |     0.598114 |       0.397879 |   0.589694 |
| k-d_tree_sklearn     |     0.592638 |       1.00816  |   1.03031  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581125 |       0.479782 |   0.454855 |
| k-d_tree_polars      |     0.581628 |       0.528248 |   0.526189 |
| barab-szabi-1        |     0.581198 |       0.530501 |   0.542065 |
| Bori_Aron_solution-1 |     0.578894 |       0.753794 |   0.552284 |
| k-d_tree_pandas      |     0.585284 |       0.47418  |   0.729296 |
| k-d_tree_sklearn     |     0.610071 |       1.21042  |   1.08523  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57853  |       0.726978 |   0.476449 |
| Bori_Aron_solution-1 |     0.574327 |       1.37891  |   0.584003 |
| k-d_tree_polars      |     0.582645 |       0.859536 |   0.873999 |
| barab-szabi-1        |     0.580515 |       0.865388 |   0.91601  |
| k-d_tree_pandas      |     0.584391 |       0.735783 |   1.16141  |
| k-d_tree_sklearn     |     0.586207 |       2.02047  |   1.18377  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580762 |        5.29004 |   0.718782 |
| Bori_Aron_solution-1 |     0.577848 |       10.4853  |   0.86402  |
| k-d_tree_sklearn     |     0.585475 |       15.8584  |   1.30962  |
| barab-szabi-1        |     0.583405 |        4.89614 |   6.54629  |
| k-d_tree_polars      |     0.598223 |        4.88417 |   6.72925  |
| k-d_tree_pandas      |     0.591873 |        3.8174  |   6.92759  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.775655 |        70.9971 |    2.99606 |
| k-d_tree_sklearn     |     0.697554 |       226.493  |    4.09499 |
| Bori_Aron_solution-1 |     0.57655  |       164.91   |   13.6311  |