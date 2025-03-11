# 2025-03-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579025 |       0.406846 |   0.404036 |
| barab-szabi-1        |     0.58105  |       0.404392 |   0.408615 |
| k-d_tree_polars      |     0.576043 |       0.399807 |   0.411342 |
| solution-1           |     7.29903  |       1e-06    |   0.414904 |
| Bori_Aron_solution-1 |     0.575702 |       0.545737 |   0.536747 |
| k-d_tree_pandas      |     7.54164  |       0.407958 |   0.596406 |
| k-d_tree_sklearn     |     3.09235  |       1.04549  |   1.03215  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.592934 |       0.410901 |   0.410175 |
| k-d_tree_polars      |     0.595717 |       0.407752 |   0.414851 |
| barab-szabi-2        |     0.589381 |       0.410061 |   0.417954 |
| Bori_Aron_solution-1 |     0.625942 |       0.552139 |   0.543195 |
| k-d_tree_pandas      |     0.588796 |       0.387229 |   0.554724 |
| k-d_tree_sklearn     |     0.590553 |       0.950996 |   1.02313  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598241 |       0.469712 |   0.431852 |
| k-d_tree_polars      |     0.589465 |       0.432597 |   0.43659  |
| barab-szabi-1        |     0.590277 |       0.429227 |   0.439512 |
| Bori_Aron_solution-1 |     0.578548 |       0.598173 |   0.546617 |
| k-d_tree_pandas      |     0.590686 |       0.405607 |   0.592645 |
| k-d_tree_sklearn     |     0.608039 |       1.03446  |   1.0858   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58955  |       0.482412 |   0.458529 |
| k-d_tree_polars      |     0.591873 |       0.538348 |   0.53464  |
| barab-szabi-1        |     0.589728 |       0.536471 |   0.540478 |
| Bori_Aron_solution-1 |     0.582363 |       0.758852 |   0.568373 |
| k-d_tree_pandas      |     0.592806 |       0.477362 |   0.727913 |
| k-d_tree_sklearn     |     0.593821 |       1.21951  |   1.10674  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.599124 |       0.743171 |   0.488641 |
| Bori_Aron_solution-1 |     0.580246 |       1.38419  |   0.587834 |
| k-d_tree_polars      |     0.59818  |       0.874969 |   0.903451 |
| barab-szabi-1        |     0.594828 |       0.880153 |   0.933535 |
| k-d_tree_pandas      |     0.587392 |       0.748099 |   1.1717   |
| k-d_tree_sklearn     |     0.610332 |       2.14592  |   1.26593  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.640041 |        5.50454 |   0.747336 |
| Bori_Aron_solution-1 |     0.581913 |       10.6618  |   0.880484 |
| k-d_tree_sklearn     |     0.601923 |       16.8297  |   1.36227  |
| barab-szabi-1        |     0.598037 |        4.90337 |   6.71129  |
| k-d_tree_polars      |     0.59637  |        4.98318 |   6.94931  |
| k-d_tree_pandas      |     0.606237 |        3.8312  |   7.05372  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.723056 |        72.0249 |    3.58962 |
| k-d_tree_sklearn     |     0.633025 |       227.583  |    4.27806 |
| Bori_Aron_solution-1 |     0.597861 |       154.214  |   14.1722  |