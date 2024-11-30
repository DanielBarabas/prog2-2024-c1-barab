# 2024-11-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.625836 |       0.410547 |   0.394055 |
| k-d_tree_polars      |     0.627646 |       0.408513 |   0.396461 |
| barab-szabi-2        |     0.626732 |       0.386655 |   0.397992 |
| solution-1           |     8.03591  |       1e-06    |   0.477734 |
| Bori_Aron_solution-1 |     0.615214 |       0.521582 |   0.526674 |
| k-d_tree_pandas      |     0.613532 |       0.381364 |   0.531562 |
| k-d_tree_sklearn     |    10.6413   |       1.23395  |   0.991688 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618678 |       0.386587 |   0.394425 |
| k-d_tree_polars      |     0.609641 |       0.402655 |   0.395129 |
| barab-szabi-1        |     0.615799 |       0.408923 |   0.39695  |
| Bori_Aron_solution-1 |     0.607161 |       0.522849 |   0.516763 |
| k-d_tree_pandas      |     0.616144 |       0.379514 |   0.532143 |
| k-d_tree_sklearn     |     0.616786 |       0.909516 |   0.965059 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613503 |       0.404886 |   0.396991 |
| k-d_tree_polars      |     0.618284 |       0.431218 |   0.420889 |
| barab-szabi-1        |     0.645406 |       0.429015 |   0.423461 |
| Bori_Aron_solution-1 |     0.60787  |       0.563454 |   0.519823 |
| k-d_tree_pandas      |     0.622463 |       0.415821 |   0.569554 |
| k-d_tree_sklearn     |     0.615798 |       0.972197 |   0.983626 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614419 |       0.471621 |   0.426078 |
| k-d_tree_polars      |     0.617716 |       0.532141 |   0.515797 |
| barab-szabi-1        |     0.612802 |       0.533062 |   0.528261 |
| Bori_Aron_solution-1 |     0.6021   |       0.747145 |   0.532194 |
| k-d_tree_pandas      |     0.619434 |       0.485888 |   0.715365 |
| k-d_tree_sklearn     |     0.623032 |       1.16836  |   1.04816  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60926  |       0.716211 |   0.458132 |
| Bori_Aron_solution-1 |     0.602891 |       1.38951  |   0.562536 |
| k-d_tree_polars      |     0.614766 |       0.856782 |   0.859711 |
| barab-szabi-1        |     0.617674 |       0.847029 |   0.906882 |
| k-d_tree_pandas      |     0.636258 |       0.742038 |   1.1442   |
| k-d_tree_sklearn     |     0.624838 |       2.09325  |   1.17081  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614547 |        5.33211 |   0.716845 |
| Bori_Aron_solution-1 |     0.608031 |       10.7775  |   0.810525 |
| k-d_tree_sklearn     |     0.612596 |       15.882   |   1.23182  |
| k-d_tree_polars      |     0.608905 |        5.18372 |   6.52618  |
| barab-szabi-1        |     0.614099 |        4.91152 |   6.75141  |
| k-d_tree_pandas      |     0.621225 |        3.86064 |   7.09113  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.63785  |        74.4192 |    2.95019 |
| k-d_tree_sklearn     |     0.643055 |       226.977  |    4.21001 |
| Bori_Aron_solution-1 |     0.647913 |       157.96   |   16.2064  |