# 2026-01-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.587605 |       0.422422 |   0.461294 |
| barab-szabi-1        |     0.547454 |       0.413334 |   0.472511 |
| barab-szabi-2        |     0.539928 |       0.53335  |   0.488062 |
| Bori_Aron_solution-1 |     0.553237 |       0.566822 |   0.592543 |
| solution-1           |     8.46323  |       1e-06    |   0.593745 |
| k-d_tree_pandas      |     8.8657   |       0.463719 |   0.75774  |
| k-d_tree_sklearn     |     3.21259  |       1.13825  |   1.12972  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552386 |       0.463952 |   0.448489 |
| k-d_tree_polars      |     0.573681 |       0.433367 |   0.451282 |
| barab-szabi-1        |     0.550169 |       0.41988  |   0.466103 |
| Bori_Aron_solution-1 |     0.528986 |       0.557785 |   0.569796 |
| k-d_tree_pandas      |     0.560852 |       0.408338 |   0.577116 |
| k-d_tree_sklearn     |     0.547182 |       1.0109   |   1.09033  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557409 |       0.447927 |   0.446623 |
| k-d_tree_polars      |     0.541678 |       0.437475 |   0.472953 |
| barab-szabi-1        |     0.55858  |       0.461116 |   0.483013 |
| Bori_Aron_solution-1 |     0.548928 |       0.603071 |   0.558761 |
| k-d_tree_pandas      |     0.538388 |       0.42207  |   0.609987 |
| k-d_tree_sklearn     |     0.561486 |       1.06633  |   1.11603  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539108 |       0.499936 |   0.474126 |
| k-d_tree_polars      |     0.537095 |       0.556829 |   0.557497 |
| Bori_Aron_solution-1 |     0.526472 |       0.784045 |   0.56816  |
| barab-szabi-1        |     0.560408 |       0.557295 |   0.569893 |
| k-d_tree_pandas      |     0.546654 |       0.51028  |   0.821187 |
| k-d_tree_sklearn     |     0.535765 |       1.26413  |   1.18333  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53355  |       0.787257 |   0.585535 |
| Bori_Aron_solution-1 |     0.536706 |       1.53142  |   0.60359  |
| k-d_tree_polars      |     0.550812 |       0.937556 |   0.94753  |
| barab-szabi-1        |     0.575359 |       0.946629 |   1.00752  |
| k-d_tree_pandas      |     0.537079 |       0.817934 |   1.18248  |
| k-d_tree_sklearn     |     0.549749 |       2.27528  |   1.29621  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559379 |        5.27372 |   0.746331 |
| Bori_Aron_solution-1 |     0.54387  |       11.5242  |   0.877941 |
| k-d_tree_sklearn     |     0.540423 |       17.0297  |   1.33654  |
| k-d_tree_polars      |     0.531413 |        5.47824 |   6.66993  |
| barab-szabi-1        |     0.534948 |        5.45115 |   6.74045  |
| k-d_tree_pandas      |     0.546769 |        4.46344 |   7.32061  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548162 |        78.5253 |    2.69957 |
| k-d_tree_sklearn     |     0.558003 |       240.139  |    4.16625 |
| Bori_Aron_solution-1 |     0.679983 |       157.291  |   16.4793  |