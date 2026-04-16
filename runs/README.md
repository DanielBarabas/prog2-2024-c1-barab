# 2026-04-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.455736 |       0.422925 |   0.420946 |
| barab-szabi-1        |     0.457588 |       0.400292 |   0.42439  |
| k-d_tree_polars      |     0.457387 |       0.402494 |   0.443445 |
| solution-1           |     9.57874  |       1e-06    |   0.462857 |
| k-d_tree_pandas      |     0.45282  |       0.385894 |   0.538317 |
| Bori_Aron_solution-1 |     0.457695 |       0.543519 |   0.573234 |
| k-d_tree_sklearn     |    11.117    |       1.27778  |   1.0643   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466238 |       0.436056 |   0.423743 |
| barab-szabi-1        |     0.456948 |       0.409463 |   0.42806  |
| k-d_tree_polars      |     0.460805 |       0.406659 |   0.430931 |
| k-d_tree_pandas      |     0.465346 |       0.389349 |   0.545882 |
| Bori_Aron_solution-1 |     0.45199  |       0.556295 |   0.553112 |
| k-d_tree_sklearn     |     0.458614 |       0.9612   |   1.06242  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456356 |       0.449333 |   0.446736 |
| k-d_tree_polars      |     0.458299 |       0.430818 |   0.449024 |
| barab-szabi-1        |     0.469124 |       0.46734  |   0.467965 |
| Bori_Aron_solution-1 |     0.454071 |       0.609309 |   0.552471 |
| k-d_tree_pandas      |     0.476201 |       0.418612 |   0.598612 |
| k-d_tree_sklearn     |     0.458907 |       1.01311  |   1.13952  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462326 |       0.535897 |   0.489125 |
| Bori_Aron_solution-1 |     0.458246 |       0.789791 |   0.566209 |
| barab-szabi-1        |     0.460777 |       0.575776 |   0.571498 |
| k-d_tree_polars      |     0.464025 |       0.610368 |   0.596784 |
| k-d_tree_pandas      |     0.458248 |       0.502656 |   0.728135 |
| k-d_tree_sklearn     |     0.465396 |       1.28523  |   1.12643  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484062 |       0.763427 |   0.533684 |
| Bori_Aron_solution-1 |     0.457671 |       1.46613  |   0.574727 |
| k-d_tree_polars      |     0.452129 |       0.926059 |   0.970305 |
| barab-szabi-1        |     0.468519 |       0.927949 |   1.00942  |
| k-d_tree_sklearn     |     0.461917 |       2.13588  |   1.13935  |
| k-d_tree_pandas      |     0.45942  |       0.785373 |   1.21817  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.526798 |        5.98905 |   0.785119 |
| Bori_Aron_solution-1 |     0.499866 |       11.9562  |   0.898875 |
| k-d_tree_sklearn     |     0.47291  |       18.4592  |   1.38545  |
| barab-szabi-1        |     0.489072 |        5.46281 |   7.74129  |
| k-d_tree_polars      |     0.511419 |        5.56469 |   7.80338  |
| k-d_tree_pandas      |     0.486619 |        4.29816 |   8.3575   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.73896  |        80.6757 |    2.75248 |
| k-d_tree_sklearn     |     0.49064  |       271.75   |    3.47404 |
| Bori_Aron_solution-1 |     0.462449 |       156.34   |   24.0893  |