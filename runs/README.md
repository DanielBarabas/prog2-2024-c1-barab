# 2024-04-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.731425 |       0.422667 |   0.358222 |
| barab-szabi-1        |     8.50964  |       0.435249 |   0.372727 |
| barab-szabi-2        |     0.72315  |       0.370107 |   0.388274 |
| solution-1           |     8.22624  |       1e-06    |   0.401894 |
| Bori_Aron_solution-1 |     0.722986 |       0.49538  |   0.497597 |
| k-d_tree_pandas      |     0.723766 |       0.404384 |   0.510429 |
| k-d_tree_sklearn     |     3.18506  |       0.917794 |   0.688453 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.767923 |       0.437624 |   0.358875 |
| barab-szabi-1        |     0.764796 |       0.437974 |   0.365575 |
| barab-szabi-2        |     0.755949 |       0.371212 |   0.369768 |
| Bori_Aron_solution-1 |     0.755705 |       0.517736 |   0.507244 |
| k-d_tree_pandas      |     0.777498 |       0.417564 |   0.52879  |
| k-d_tree_sklearn     |     0.768138 |       0.918474 |   0.694042 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.773378 |       0.380857 |   0.387682 |
| barab-szabi-1        |     0.761698 |       0.463517 |   0.395864 |
| k-d_tree_polars      |     0.79283  |       0.479364 |   0.396095 |
| Bori_Aron_solution-1 |     0.761137 |       0.564849 |   0.524202 |
| k-d_tree_pandas      |     0.775873 |       0.447503 |   0.580898 |
| k-d_tree_sklearn     |     0.82217  |       1.00071  |   0.738709 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.765348 |       0.453103 |   0.418812 |
| k-d_tree_polars      |     0.775657 |       0.579234 |   0.503803 |
| barab-szabi-1        |     0.771101 |       0.598298 |   0.515919 |
| Bori_Aron_solution-1 |     0.761194 |       0.744219 |   0.55323  |
| k-d_tree_pandas      |     0.766451 |       0.520653 |   0.703315 |
| k-d_tree_sklearn     |     0.781616 |       1.1953   |   0.796193 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.762681 |       0.703149 |   0.483886 |
| Bori_Aron_solution-1 |     0.764862 |       1.41     |   0.546126 |
| k-d_tree_sklearn     |     0.78029  |       2.08602  |   0.887398 |
| k-d_tree_polars      |     0.767981 |       0.893549 |   0.888123 |
| barab-szabi-1        |     0.772649 |       0.903807 |   0.907519 |
| k-d_tree_pandas      |     0.764443 |       0.793223 |   1.17809  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.756604 |        5.3049  |   0.749488 |
| Bori_Aron_solution-1 |     0.747628 |       11.1808  |   0.851789 |
| k-d_tree_sklearn     |     0.747515 |       16.4648  |   1.07491  |
| barab-szabi-1        |     0.765863 |        4.94256 |   6.89723  |
| k-d_tree_polars      |     0.790067 |        4.88852 |   6.97381  |
| k-d_tree_pandas      |     0.746333 |        3.91222 |   7.00256  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.02308  |        73.7092 |    4.01104 |
| k-d_tree_sklearn     |     0.849542 |       235.344  |    4.88645 |
| Bori_Aron_solution-1 |     0.73223  |       153.346  |   15.8733  |