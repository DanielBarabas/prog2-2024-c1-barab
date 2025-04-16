# 2025-04-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.594467 |       0.42779  |   0.43457  |
| barab-szabi-2        |     0.574587 |       0.436199 |   0.436286 |
| barab-szabi-1        |     0.585382 |       0.446187 |   0.548498 |
| Bori_Aron_solution-1 |     0.58858  |       0.595006 |   0.579705 |
| solution-1           |     8.13065  |       1e-06    |   0.596848 |
| k-d_tree_pandas      |     8.04526  |       0.492805 |   0.740137 |
| k-d_tree_sklearn     |     3.38219  |       1.18408  |   1.10921  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.590626 |       0.43881  |   0.433655 |
| k-d_tree_polars      |     0.586574 |       0.445526 |   0.449276 |
| barab-szabi-2        |     0.625974 |       0.456283 |   0.455228 |
| Bori_Aron_solution-1 |     0.603791 |       0.619967 |   0.575779 |
| k-d_tree_pandas      |     0.599332 |       0.426499 |   0.627999 |
| k-d_tree_sklearn     |     0.602206 |       1.02213  |   1.13221  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607942 |       0.4522   |   0.451625 |
| k-d_tree_polars      |     0.6037   |       0.47809  |   0.468833 |
| barab-szabi-1        |     0.595499 |       0.482371 |   0.480594 |
| Bori_Aron_solution-1 |     0.603244 |       0.650371 |   0.611712 |
| k-d_tree_pandas      |     0.584831 |       0.433932 |   0.652632 |
| k-d_tree_sklearn     |     0.602691 |       1.0877   |   1.14794  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590625 |       0.515813 |   0.486476 |
| k-d_tree_polars      |     0.60582  |       0.582279 |   0.576348 |
| barab-szabi-1        |     0.592538 |       0.590768 |   0.587368 |
| Bori_Aron_solution-1 |     0.605322 |       0.82004  |   0.603457 |
| k-d_tree_pandas      |     0.592303 |       0.516414 |   0.797986 |
| k-d_tree_sklearn     |     0.602543 |       1.33804  |   1.21508  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60821  |       0.76796  |   0.603965 |
| Bori_Aron_solution-1 |     0.594019 |       1.47711  |   0.626438 |
| k-d_tree_polars      |     0.615913 |       0.937209 |   0.968361 |
| barab-szabi-1        |     0.597444 |       0.934327 |   0.990925 |
| k-d_tree_pandas      |     0.605847 |       0.799327 |   1.25748  |
| k-d_tree_sklearn     |     0.594836 |       2.24163  |   1.32422  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.594698 |        6.19153 |   0.78359  |
| Bori_Aron_solution-1 |     0.597402 |       11.742   |   0.927838 |
| k-d_tree_sklearn     |     0.609136 |       18.4018  |   1.44868  |
| barab-szabi-1        |     0.61494  |        5.13407 |   7.41204  |
| k-d_tree_polars      |     0.603825 |        5.13766 |   7.43751  |
| k-d_tree_pandas      |     0.603484 |        4.0561  |   7.84047  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.863109 |        78.9023 |    3.20377 |
| k-d_tree_sklearn     |     0.691606 |       248.563  |    4.53052 |
| Bori_Aron_solution-1 |     0.600868 |       166.601  |   16.3444  |