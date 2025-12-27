# 2025-12-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465914 |       0.473065 |   0.40498  |
| barab-szabi-1        |     0.476251 |       0.375553 |   0.406919 |
| k-d_tree_polars      |     0.510477 |       0.376479 |   0.414675 |
| solution-1           |     6.42365  |       1e-06    |   0.417532 |
| Bori_Aron_solution-1 |     0.482933 |       0.519427 |   0.511864 |
| k-d_tree_pandas      |     7.04533  |       0.392432 |   0.604631 |
| k-d_tree_sklearn     |     2.5779   |       0.990298 |   0.970054 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.47156  |       0.386882 |   0.407917 |
| barab-szabi-2        |     0.474563 |       0.412173 |   0.408095 |
| barab-szabi-1        |     0.480403 |       0.38288  |   0.40951  |
| k-d_tree_pandas      |     0.479619 |       0.36723  |   0.518749 |
| Bori_Aron_solution-1 |     0.472013 |       0.513689 |   0.525549 |
| k-d_tree_sklearn     |     0.480407 |       0.93785  |   0.983243 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477918 |       0.419634 |   0.422039 |
| barab-szabi-1        |     0.476631 |       0.410237 |   0.430883 |
| k-d_tree_polars      |     0.473337 |       0.404557 |   0.433033 |
| Bori_Aron_solution-1 |     0.47393  |       0.639899 |   0.530972 |
| k-d_tree_pandas      |     0.475534 |       0.384863 |   0.549961 |
| k-d_tree_sklearn     |     0.483475 |       0.93476  |   0.993232 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480077 |       0.48549  |   0.460243 |
| k-d_tree_polars      |     0.475541 |       0.530095 |   0.523039 |
| Bori_Aron_solution-1 |     0.475529 |       0.714978 |   0.529352 |
| barab-szabi-1        |     0.475555 |       0.522195 |   0.534616 |
| k-d_tree_pandas      |     0.476653 |       0.465115 |   0.672136 |
| k-d_tree_sklearn     |     0.485152 |       1.16155  |   1.0294   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479881 |       0.698416 |   0.478455 |
| Bori_Aron_solution-1 |     0.472383 |       1.31141  |   0.562869 |
| k-d_tree_polars      |     0.472432 |       0.843244 |   0.834871 |
| barab-szabi-1        |     0.481907 |       0.849072 |   0.860672 |
| k-d_tree_pandas      |     0.474381 |       0.71901  |   1.0585   |
| k-d_tree_sklearn     |     0.484437 |       1.93047  |   1.12019  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470131 |        4.88998 |   0.695081 |
| Bori_Aron_solution-1 |     0.471921 |        9.90118 |   0.897397 |
| k-d_tree_sklearn     |     0.479054 |       14.8214  |   1.26054  |
| k-d_tree_polars      |     0.481259 |        4.87714 |   6.09021  |
| barab-szabi-1        |     0.478287 |        4.82541 |   6.15425  |
| k-d_tree_pandas      |     0.472147 |        3.78091 |   6.35711  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478522 |        83.7966 |    2.73319 |
| k-d_tree_sklearn     |     0.495707 |       177.263  |    4.31001 |
| Bori_Aron_solution-1 |     0.582955 |       138.012  |   17.1923  |