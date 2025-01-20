# 2025-01-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.21611  |       1e-06    |   0.368235 |
| barab-szabi-2        |     0.574182 |       0.406945 |   0.392661 |
| barab-szabi-1        |     0.57286  |       0.400649 |   0.399946 |
| k-d_tree_polars      |     0.582378 |       0.40001  |   0.401105 |
| Bori_Aron_solution-1 |     0.579063 |       0.529861 |   0.531053 |
| k-d_tree_pandas      |     7.85993  |       0.400084 |   0.625251 |
| k-d_tree_sklearn     |     3.03189  |       1.00294  |   1.04813  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581322 |       0.40232  |   0.397375 |
| barab-szabi-1        |     0.583689 |       0.410211 |   0.406669 |
| k-d_tree_polars      |     0.580903 |       0.406153 |   0.408178 |
| Bori_Aron_solution-1 |     0.609145 |       0.543422 |   0.532439 |
| k-d_tree_pandas      |     0.613565 |       0.387105 |   0.546342 |
| k-d_tree_sklearn     |     0.591434 |       0.937479 |   1.0194   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581712 |       0.416243 |   0.41046  |
| k-d_tree_polars      |     0.586524 |       0.432562 |   0.431028 |
| barab-szabi-1        |     0.583084 |       0.434409 |   0.432146 |
| Bori_Aron_solution-1 |     0.594388 |       0.573257 |   0.537538 |
| k-d_tree_pandas      |     0.581882 |       0.406345 |   0.583248 |
| k-d_tree_sklearn     |     0.589776 |       0.991587 |   1.04076  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589268 |       0.476043 |   0.471939 |
| k-d_tree_polars      |     0.581821 |       0.5396   |   0.525704 |
| barab-szabi-1        |     0.585511 |       0.541342 |   0.537352 |
| Bori_Aron_solution-1 |     0.57841  |       0.744945 |   0.549307 |
| k-d_tree_pandas      |     0.589214 |       0.478908 |   0.715378 |
| k-d_tree_sklearn     |     0.597634 |       1.20797  |   1.09958  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584064 |       0.715856 |   0.476923 |
| Bori_Aron_solution-1 |     0.576251 |       1.3733   |   0.572516 |
| k-d_tree_polars      |     0.584768 |       0.870082 |   0.872642 |
| barab-szabi-1        |     0.580609 |       0.865396 |   0.91035  |
| k-d_tree_pandas      |     0.590049 |       0.745114 |   1.15142  |
| k-d_tree_sklearn     |     0.587533 |       2.02363  |   1.18673  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.593522 |        5.1788  |   0.74705  |
| Bori_Aron_solution-1 |     0.577842 |       10.4667  |   0.862767 |
| k-d_tree_sklearn     |     0.587219 |       15.7426  |   1.29349  |
| k-d_tree_polars      |     0.58441  |        4.90139 |   6.47408  |
| barab-szabi-1        |     0.585961 |        4.92776 |   6.49753  |
| k-d_tree_pandas      |     0.58463  |        3.83763 |   6.84434  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584195 |        76.0885 |    3.06576 |
| k-d_tree_sklearn     |     0.592021 |       230.486  |    4.42679 |
| Bori_Aron_solution-1 |     0.690145 |       148.538  |   18.7712  |