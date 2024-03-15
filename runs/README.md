# 2024-03-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.56707  |       1e-06    |   0.347373 |
| barab-szabi-2        |     0.698656 |       0.379788 |   0.364212 |
| k-d_tree_polars      |     0.743059 |       0.409337 |   0.369174 |
| barab-szabi-1        |     0.746122 |       0.410699 |   0.373063 |
| Bori_Aron_solution-1 |     0.695961 |       0.520073 |   0.505533 |
| k-d_tree_pandas      |     7.71656  |       0.395742 |   0.531073 |
| k-d_tree_sklearn     |     3.27697  |       0.908473 |   0.681222 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.740456 |       0.372535 |   0.365773 |
| k-d_tree_polars      |     0.74225  |       0.417437 |   0.3725   |
| barab-szabi-1        |     0.739331 |       0.413422 |   0.374556 |
| Bori_Aron_solution-1 |     0.72571  |       0.52692  |   0.503007 |
| k-d_tree_pandas      |     0.739276 |       0.394736 |   0.51931  |
| k-d_tree_sklearn     |     0.750438 |       0.878755 |   0.686916 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734165 |       0.365723 |   0.354141 |
| k-d_tree_polars      |     0.710595 |       0.409742 |   0.377609 |
| barab-szabi-1        |     0.686975 |       0.405187 |   0.385038 |
| Bori_Aron_solution-1 |     0.686102 |       0.525343 |   0.486244 |
| k-d_tree_pandas      |     0.759431 |       0.409379 |   0.559942 |
| k-d_tree_sklearn     |     0.73263  |       0.846305 |   0.693402 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.702467 |       0.446304 |   0.390019 |
| Bori_Aron_solution-1 |     0.676795 |       0.697274 |   0.498125 |
| k-d_tree_polars      |     0.696272 |       0.543044 |   0.499007 |
| barab-szabi-1        |     0.730796 |       0.541581 |   0.50352  |
| k-d_tree_pandas      |     0.7325   |       0.473504 |   0.649658 |
| k-d_tree_sklearn     |     0.69215  |       1.08569  |   0.724411 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.73771  |       0.696039 |   0.451721 |
| Bori_Aron_solution-1 |     0.720869 |       1.36263  |   0.538947 |
| k-d_tree_sklearn     |     0.741033 |       1.93939  |   0.836785 |
| k-d_tree_polars      |     0.719789 |       0.889902 |   0.867939 |
| barab-szabi-1        |     0.772393 |       0.86891  |   0.888028 |
| k-d_tree_pandas      |     0.730526 |       0.75773  |   1.1342   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.736133 |        5.23702 |   0.733553 |
| Bori_Aron_solution-1 |     0.698236 |       10.5054  |   0.776899 |
| k-d_tree_sklearn     |     0.743413 |       16.0127  |   1.06528  |
| k-d_tree_polars      |     0.725538 |        4.91728 |   6.63968  |
| barab-szabi-1        |     0.739487 |        4.90259 |   6.68135  |
| k-d_tree_pandas      |     0.769307 |        4.00056 |   6.898    |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.739862 |        69.7042 |    3.55919 |
| k-d_tree_sklearn     |     0.884613 |       224.351  |    4.74258 |
| Bori_Aron_solution-1 |     0.834983 |       142.346  |   14.5474  |