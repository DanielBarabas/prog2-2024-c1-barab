# 2025-02-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.26941  |       1e-06    |   0.369445 |
| k-d_tree_polars      |     0.598583 |       0.428168 |   0.427035 |
| barab-szabi-2        |     4.20773  |       0.444293 |   0.429755 |
| barab-szabi-1        |     0.608974 |       0.420055 |   0.431241 |
| Bori_Aron_solution-1 |     4.4603   |       0.660491 |   0.517027 |
| k-d_tree_pandas      |     0.602894 |       0.400058 |   0.562455 |
| k-d_tree_sklearn     |     3.09383  |       1.09918  |   1.09177  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.626885 |       0.434076 |   0.426447 |
| barab-szabi-1        |     0.615057 |       0.422292 |   0.426984 |
| barab-szabi-2        |     0.614442 |       0.431859 |   0.436531 |
| Bori_Aron_solution-1 |     0.590244 |       0.594991 |   0.561872 |
| k-d_tree_pandas      |     0.617867 |       0.407628 |   0.581318 |
| k-d_tree_sklearn     |     0.611692 |       1.00677  |   1.05894  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605461 |       0.43239  |   0.445328 |
| barab-szabi-1        |     0.633886 |       0.47078  |   0.468493 |
| k-d_tree_polars      |     0.629041 |       0.470028 |   0.479992 |
| Bori_Aron_solution-1 |     0.607618 |       0.631628 |   0.591456 |
| k-d_tree_pandas      |     0.620379 |       0.436772 |   0.639398 |
| k-d_tree_sklearn     |     0.616053 |       1.10226  |   1.1631   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606339 |       0.52359  |   0.468748 |
| k-d_tree_polars      |     0.601419 |       0.548954 |   0.546654 |
| barab-szabi-1        |     0.606822 |       0.560486 |   0.572208 |
| Bori_Aron_solution-1 |     0.612364 |       0.78934  |   0.586986 |
| k-d_tree_pandas      |     0.595644 |       0.49626  |   0.750666 |
| k-d_tree_sklearn     |     0.622134 |       1.29     |   1.15345  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598038 |       0.761997 |   0.512014 |
| Bori_Aron_solution-1 |     0.613724 |       1.45524  |   0.620867 |
| k-d_tree_polars      |     0.603222 |       0.895662 |   0.905113 |
| barab-szabi-1        |     0.599227 |       0.90346  |   0.940063 |
| k-d_tree_pandas      |     0.598867 |       0.752687 |   1.18512  |
| k-d_tree_sklearn     |     0.599502 |       2.10443  |   1.22562  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611965 |        5.55186 |   0.786495 |
| Bori_Aron_solution-1 |     0.589065 |       10.9516  |   0.904297 |
| k-d_tree_sklearn     |     0.609508 |       17.9962  |   1.42601  |
| barab-szabi-1        |     0.622752 |        4.90461 |   6.96605  |
| k-d_tree_polars      |     0.624378 |        4.95869 |   7.11035  |
| k-d_tree_pandas      |     0.626381 |        3.88968 |   7.63845  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.8131   |        74.0207 |    3.61512 |
| k-d_tree_sklearn     |     0.674729 |       239.244  |    4.33526 |
| Bori_Aron_solution-1 |     0.594656 |       155.199  |   16.3655  |