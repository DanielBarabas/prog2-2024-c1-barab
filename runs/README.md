# 2025-05-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549707 |       0.409541 |   0.419715 |
| k-d_tree_polars      |     0.538079 |       0.403731 |   0.422245 |
| Bori_Aron_solution-1 |     0.522424 |       0.536747 |   0.538441 |
| barab-szabi-1        |     7.79283  |       0.451101 |   0.544057 |
| solution-1           |     7.60831  |       1e-06    |   0.546927 |
| k-d_tree_pandas      |     0.551646 |       0.392291 |   0.561346 |
| k-d_tree_sklearn     |     2.99657  |       1.06759  |   1.06968  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551859 |       0.424404 |   0.423725 |
| k-d_tree_polars      |     0.558337 |       0.415304 |   0.427921 |
| barab-szabi-1        |     0.554743 |       0.419204 |   0.433827 |
| k-d_tree_pandas      |     0.549892 |       0.387964 |   0.555025 |
| Bori_Aron_solution-1 |     0.550086 |       0.619092 |   0.562652 |
| k-d_tree_sklearn     |     0.552851 |       0.966544 |   1.04602  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551727 |       0.431098 |   0.427577 |
| k-d_tree_polars      |     0.551795 |       0.436311 |   0.451804 |
| barab-szabi-1        |     0.555402 |       0.440325 |   0.458588 |
| Bori_Aron_solution-1 |     0.548527 |       0.591334 |   0.550772 |
| k-d_tree_pandas      |     0.549296 |       0.403844 |   0.60231  |
| k-d_tree_sklearn     |     0.551325 |       1.004    |   1.06998  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547267 |       0.500029 |   0.465112 |
| k-d_tree_polars      |     0.557509 |       0.558317 |   0.545888 |
| barab-szabi-1        |     0.557302 |       0.544589 |   0.557209 |
| Bori_Aron_solution-1 |     0.543593 |       0.767294 |   0.560244 |
| k-d_tree_pandas      |     0.551692 |       0.49254  |   0.734744 |
| k-d_tree_sklearn     |     0.551516 |       1.23116  |   1.1406   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549158 |       0.745559 |   0.496257 |
| Bori_Aron_solution-1 |     0.545529 |       1.4023   |   0.585631 |
| k-d_tree_polars      |     0.554741 |       0.87901  |   0.914065 |
| barab-szabi-1        |     0.553499 |       0.878968 |   0.962569 |
| k-d_tree_pandas      |     0.546191 |       0.759999 |   1.17184  |
| k-d_tree_sklearn     |     0.557587 |       2.04749  |   1.24046  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583256 |        5.60559 |   0.773466 |
| Bori_Aron_solution-1 |     0.566013 |       10.7123  |   0.887211 |
| k-d_tree_sklearn     |     0.556829 |       17.2428  |   1.39211  |
| barab-szabi-1        |     0.55726  |        4.95019 |   6.71109  |
| k-d_tree_polars      |     0.562302 |        5.05796 |   6.94744  |
| k-d_tree_pandas      |     0.572978 |        4.00274 |   7.39483  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621956 |        74.2665 |    3.06362 |
| k-d_tree_sklearn     |     0.83521  |       234.314  |    4.31235 |
| Bori_Aron_solution-1 |     0.557503 |       144.944  |   18.3297  |