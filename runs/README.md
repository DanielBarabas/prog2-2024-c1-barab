# 2026-09-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.7492   |       1e-06    |   0.362499 |
| barab-szabi-2        |     0.463571 |       0.427535 |   0.430668 |
| k-d_tree_polars      |     0.464971 |       0.419383 |   0.446445 |
| barab-szabi-1        |     8.87254  |       0.447273 |   0.487066 |
| k-d_tree_pandas      |     0.454801 |       0.389854 |   0.548137 |
| Bori_Aron_solution-1 |     0.456365 |       0.548113 |   0.552267 |
| k-d_tree_sklearn     |     3.0871   |       1.03998  |   1.04416  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481248 |       0.442277 |   0.438218 |
| barab-szabi-1        |     0.518847 |       0.431125 |   0.44902  |
| k-d_tree_polars      |     0.482217 |       0.448986 |   0.474332 |
| k-d_tree_pandas      |     0.465487 |       0.389662 |   0.542379 |
| Bori_Aron_solution-1 |     0.458817 |       0.546811 |   0.555873 |
| k-d_tree_sklearn     |     0.484887 |       1.01071  |   1.10654  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464488 |       0.443905 |   0.445623 |
| k-d_tree_polars      |     0.46597  |       0.503368 |   0.466681 |
| barab-szabi-1        |     0.468067 |       0.45857  |   0.469105 |
| Bori_Aron_solution-1 |     0.460486 |       0.592688 |   0.556852 |
| k-d_tree_pandas      |     0.461524 |       0.406399 |   0.582349 |
| k-d_tree_sklearn     |     0.466584 |       1.03365  |   1.09643  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467876 |       0.507649 |   0.477473 |
| Bori_Aron_solution-1 |     0.468203 |       0.769765 |   0.550331 |
| k-d_tree_polars      |     0.462852 |       0.563455 |   0.56452  |
| barab-szabi-1        |     0.467039 |       0.568834 |   0.578263 |
| k-d_tree_pandas      |     0.478841 |       0.526095 |   0.710745 |
| k-d_tree_sklearn     |     0.468081 |       1.25728  |   1.10496  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466593 |       0.753117 |   0.51761  |
| Bori_Aron_solution-1 |     0.471272 |       1.44724  |   0.577935 |
| k-d_tree_polars      |     0.467257 |       0.902747 |   0.943788 |
| barab-szabi-1        |     0.473971 |       0.892844 |   0.990968 |
| k-d_tree_sklearn     |     0.473979 |       2.11378  |   1.15278  |
| k-d_tree_pandas      |     0.468371 |       0.787868 |   1.17565  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468168 |        5.50329 |   0.71304  |
| Bori_Aron_solution-1 |     0.463337 |       11.2143  |   0.808182 |
| k-d_tree_sklearn     |     0.478033 |       16.8929  |   1.23306  |
| barab-szabi-1        |     0.468764 |        5.10359 |   7.32634  |
| k-d_tree_polars      |     0.463416 |        5.05529 |   7.34227  |
| k-d_tree_pandas      |     0.465615 |        3.96439 |   7.79779  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538239 |        77.3631 |    2.53304 |
| k-d_tree_sklearn     |     0.679486 |       260.802  |    3.44351 |
| Bori_Aron_solution-1 |     0.460808 |       156.002  |   22.4025  |