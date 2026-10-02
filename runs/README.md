# 2026-10-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.275925 |       0.289255 |   0.2923   |
| k-d_tree_polars      |     0.270491 |       0.278535 |   0.295445 |
| k-d_tree_pandas      |     0.280454 |       0.255888 |   0.347997 |
| Bori_Aron_solution-1 |     0.262381 |       0.359049 |   0.350131 |
| solution-1           |     4.63068  |       0        |   0.389053 |
| barab-szabi-1        |     6.51232  |       0.335787 |   0.441512 |
| k-d_tree_sklearn     |     2.0163   |       0.824671 |   0.690364 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.288869 |       0.283438 |   0.293534 |
| barab-szabi-1        |     0.297042 |       0.294896 |   0.299021 |
| barab-szabi-2        |     0.277973 |       0.296727 |   0.303306 |
| Bori_Aron_solution-1 |     0.293424 |       0.364432 |   0.344861 |
| k-d_tree_pandas      |     0.291569 |       0.269551 |   0.372637 |
| k-d_tree_sklearn     |     0.278845 |       0.688185 |   0.720049 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.28153  |       0.305147 |   0.304601 |
| k-d_tree_polars      |     0.290206 |       0.309029 |   0.320062 |
| Bori_Aron_solution-1 |     0.286878 |       0.385984 |   0.359356 |
| k-d_tree_pandas      |     0.293332 |       0.311615 |   0.469686 |
| k-d_tree_sklearn     |     0.282121 |       0.679916 |   0.685902 |
| barab-szabi-1        |     0.306129 |       0.310721 |   0.7063   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.280504 |       0.511122 |   0.360997 |
| k-d_tree_polars      |     0.271706 |       0.431705 |   0.382731 |
| barab-szabi-1        |     0.289116 |       0.383047 |   0.390247 |
| barab-szabi-2        |     0.287709 |       0.347113 |   0.392203 |
| k-d_tree_sklearn     |     0.368975 |       0.817038 |   0.76075  |
| k-d_tree_pandas      |     0.296768 |       0.320978 |   0.816903 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.277898 |       0.488553 |   0.34497  |
| Bori_Aron_solution-1 |     0.287397 |       0.857504 |   0.398595 |
| k-d_tree_polars      |     0.295051 |       0.583865 |   0.589076 |
| barab-szabi-1        |     0.295772 |       0.612421 |   0.650875 |
| k-d_tree_pandas      |     0.30943  |       0.489416 |   0.727884 |
| k-d_tree_sklearn     |     0.291274 |       1.32699  |   1.09591  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.286209 |        6.82156 |   0.524756 |
| barab-szabi-2        |     0.285584 |        3.62036 |   0.548465 |
| k-d_tree_sklearn     |     0.280641 |       11.9732  |   0.780288 |
| k-d_tree_polars      |     0.284112 |        3.62564 |   4.72707  |
| k-d_tree_pandas      |     0.316069 |        2.12789 |   5.05306  |
| barab-szabi-1        |     0.276853 |        3.60678 |   5.10352  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.396136 |       161.206  |    2.11195 |
| barab-szabi-2        |     0.460953 |        56.6988 |    2.13695 |
| Bori_Aron_solution-1 |     0.283677 |       121.903  |   22.1003  |