# 2024-05-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     8.6624   |       0.429947 |   0.356494 |
| k-d_tree_polars      |     0.723824 |       0.422289 |   0.357635 |
| barab-szabi-2        |     0.741204 |       0.372663 |   0.360063 |
| solution-1           |     8.07428  |       1e-06    |   0.372852 |
| Bori_Aron_solution-1 |     0.713915 |       0.49083  |   0.489606 |
| k-d_tree_pandas      |     0.727193 |       0.400198 |   0.499108 |
| k-d_tree_sklearn     |     3.3136   |       0.998077 |   0.676689 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.745513 |       0.35613  |   0.352845 |
| barab-szabi-1        |     0.751186 |       0.421993 |   0.356179 |
| k-d_tree_polars      |     0.76204  |       0.421219 |   0.361743 |
| Bori_Aron_solution-1 |     0.737786 |       0.506355 |   0.494288 |
| k-d_tree_pandas      |     0.762722 |       0.404639 |   0.502394 |
| k-d_tree_sklearn     |     0.767238 |       0.877208 |   0.683977 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.770171 |       0.37269  |   0.362708 |
| k-d_tree_polars      |     0.747057 |       0.444313 |   0.382768 |
| barab-szabi-1        |     0.775248 |       0.445526 |   0.391475 |
| Bori_Aron_solution-1 |     0.744515 |       0.537947 |   0.490148 |
| k-d_tree_pandas      |     0.74494  |       0.417904 |   0.541191 |
| k-d_tree_sklearn     |     0.752915 |       0.932925 |   0.701733 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.743503 |       0.43858  |   0.395541 |
| k-d_tree_polars      |     0.749675 |       0.553342 |   0.483965 |
| barab-szabi-1        |     0.736701 |       0.546091 |   0.495701 |
| Bori_Aron_solution-1 |     0.730472 |       0.718515 |   0.504991 |
| k-d_tree_pandas      |     0.746156 |       0.489843 |   0.672658 |
| k-d_tree_sklearn     |     0.747594 |       1.13345  |   0.759788 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.744614 |       0.679348 |   0.439408 |
| Bori_Aron_solution-1 |     0.737908 |       1.37334  |   0.529151 |
| k-d_tree_polars      |     0.745026 |       0.868184 |   0.8398   |
| k-d_tree_sklearn     |     0.757218 |       1.96542  |   0.867248 |
| barab-szabi-1        |     0.746598 |       0.875657 |   0.879159 |
| k-d_tree_pandas      |     0.747592 |       0.759222 |   1.11264  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.739352 |        5.3326  |   0.721152 |
| Bori_Aron_solution-1 |     0.719621 |       10.7024  |   0.769305 |
| k-d_tree_sklearn     |     0.747939 |       16.0406  |   1.04964  |
| k-d_tree_polars      |     0.736754 |        4.89114 |   6.61705  |
| barab-szabi-1        |     0.748259 |        4.7939  |   6.66235  |
| k-d_tree_pandas      |     0.738073 |        3.9112  |   6.95852  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.27871  |         74.238 |    3.88339 |
| k-d_tree_sklearn     |     0.88157  |        227.555 |    4.83615 |
| Bori_Aron_solution-1 |     0.722813 |        155.016 |   17.383   |