# 2026-05-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.23744  |       1e-06    |   0.430645 |
| barab-szabi-2        |     0.477842 |       0.447962 |   0.446757 |
| k-d_tree_polars      |     0.487159 |       0.429283 |   0.453313 |
| Bori_Aron_solution-1 |     0.473596 |       0.558219 |   0.565088 |
| k-d_tree_pandas      |     0.468123 |       0.394177 |   0.566997 |
| barab-szabi-1        |     7.99362  |       0.454061 |   0.686602 |
| k-d_tree_sklearn     |     2.95438  |       1.18903  |   1.13571  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491251 |       0.462444 |   0.453575 |
| k-d_tree_polars      |     0.492473 |       0.418726 |   0.456549 |
| barab-szabi-1        |     0.485951 |       0.51791  |   0.471596 |
| k-d_tree_pandas      |     0.486549 |       0.401576 |   0.578463 |
| Bori_Aron_solution-1 |     0.481662 |       0.588055 |   0.580407 |
| k-d_tree_sklearn     |     0.505553 |       1.03315  |   1.13928  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496055 |       0.475091 |   0.46414  |
| barab-szabi-1        |     0.478721 |       0.456195 |   0.478006 |
| k-d_tree_polars      |     0.489328 |       0.453499 |   0.484274 |
| Bori_Aron_solution-1 |     0.476127 |       0.618464 |   0.574617 |
| k-d_tree_pandas      |     0.491397 |       0.43085  |   0.622272 |
| k-d_tree_sklearn     |     0.487966 |       1.05275  |   1.13785  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474179 |       0.516193 |   0.485777 |
| Bori_Aron_solution-1 |     0.462565 |       0.775541 |   0.558686 |
| k-d_tree_polars      |     0.489543 |       0.585745 |   0.569115 |
| barab-szabi-1        |     0.470956 |       0.579592 |   0.609316 |
| k-d_tree_pandas      |     0.510991 |       0.508517 |   0.735569 |
| k-d_tree_sklearn     |     0.480388 |       1.25292  |   1.14393  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47835  |       0.72004  |   0.509266 |
| Bori_Aron_solution-1 |     0.454674 |       1.43616  |   0.575882 |
| k-d_tree_polars      |     0.462424 |       0.927424 |   0.922597 |
| barab-szabi-1        |     0.480249 |       0.931247 |   0.948407 |
| k-d_tree_pandas      |     0.493794 |       0.813042 |   1.18008  |
| k-d_tree_sklearn     |     0.4759   |       2.08847  |   1.20896  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.461008 |        4.96679 |   0.742883 |
| Bori_Aron_solution-1 |     0.452523 |       10.9736  |   0.804526 |
| k-d_tree_sklearn     |     0.470944 |       16.4725  |   1.28338  |
| barab-szabi-1        |     0.462422 |        5.51382 |   6.48604  |
| k-d_tree_polars      |     0.458849 |        5.43794 |   6.51442  |
| k-d_tree_pandas      |     0.460724 |        4.43723 |   6.97943  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464991 |        70.9468 |    2.57401 |
| k-d_tree_sklearn     |     0.474617 |       237.72   |    3.62053 |
| Bori_Aron_solution-1 |     0.461039 |       149.216  |   23.1358  |