# 2024-04-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.73154  |       0.398758 |   0.33942  |
| barab-szabi-2        |     0.70566  |       0.339676 |   0.340953 |
| barab-szabi-1        |     8.69071  |       0.424465 |   0.353354 |
| solution-1           |     8.11593  |       1e-06    |   0.384651 |
| k-d_tree_pandas      |     0.699688 |       0.390936 |   0.473323 |
| Bori_Aron_solution-1 |     0.697462 |       0.472715 |   0.475895 |
| k-d_tree_sklearn     |     3.28081  |       0.878743 |   0.654881 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.726398 |       0.342436 |   0.335292 |
| k-d_tree_polars      |     0.734629 |       0.410061 |   0.34531  |
| barab-szabi-1        |     0.732983 |       0.409468 |   0.351596 |
| Bori_Aron_solution-1 |     0.731568 |       0.48047  |   0.474626 |
| k-d_tree_pandas      |     0.731853 |       0.389195 |   0.485118 |
| k-d_tree_sklearn     |     0.736414 |       0.832809 |   0.656827 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.724057 |       0.363944 |   0.352342 |
| k-d_tree_polars      |     0.734142 |       0.429597 |   0.372294 |
| barab-szabi-1        |     0.731885 |       0.429578 |   0.387734 |
| Bori_Aron_solution-1 |     0.742684 |       0.520481 |   0.479271 |
| k-d_tree_sklearn     |     0.744204 |       0.890463 |   0.687639 |
| k-d_tree_pandas      |     0.739398 |       0.408549 |   0.772507 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732063 |       0.424259 |   0.379108 |
| k-d_tree_polars      |     0.734658 |       0.540573 |   0.474947 |
| Bori_Aron_solution-1 |     0.723515 |       0.693608 |   0.484414 |
| barab-szabi-1        |     0.731339 |       0.540066 |   0.484831 |
| k-d_tree_pandas      |     0.736691 |       0.484274 |   0.657995 |
| k-d_tree_sklearn     |     0.747337 |       1.11275  |   0.743026 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732578 |       0.676448 |   0.429065 |
| Bori_Aron_solution-1 |     0.725694 |       1.3331   |   0.519496 |
| k-d_tree_polars      |     0.737355 |       0.847286 |   0.82318  |
| k-d_tree_sklearn     |     0.746707 |       1.90973  |   0.848534 |
| barab-szabi-1        |     0.738779 |       0.847605 |   0.853255 |
| k-d_tree_pandas      |     0.73123  |       0.751297 |   1.10395  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.735615 |        5.42785 |   0.738744 |
| Bori_Aron_solution-1 |     0.723801 |       10.612   |   0.765146 |
| k-d_tree_sklearn     |     0.740316 |       15.9004  |   1.054    |
| barab-szabi-1        |     0.737612 |        4.8457  |   6.58695  |
| k-d_tree_polars      |     0.737079 |        4.84605 |   6.59606  |
| k-d_tree_pandas      |     0.731196 |        3.89348 |   6.91266  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.25893  |        74.2216 |    4.07434 |
| k-d_tree_sklearn     |     0.926385 |       230.463  |    4.91933 |
| Bori_Aron_solution-1 |     0.727929 |       164.656  |   19.2408  |