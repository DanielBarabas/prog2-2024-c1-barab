# 2025-10-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.977866 |       0.657024 |   0.422801 |
| k-d_tree_polars      |     0.53792  |       0.395386 |   0.423127 |
| barab-szabi-1        |     0.535796 |       0.396528 |   0.426794 |
| Bori_Aron_solution-1 |     0.528483 |       0.533111 |   0.538562 |
| solution-1           |     7.94234  |       1e-06    |   0.771209 |
| k-d_tree_pandas      |     8.5037   |       0.45805  |   0.870738 |
| k-d_tree_sklearn     |     3.28646  |       1.22914  |   1.04893  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.548595 |       0.420221 |   0.431104 |
| k-d_tree_polars      |     0.542538 |       0.409378 |   0.433161 |
| barab-szabi-2        |     0.545388 |       0.429792 |   0.448808 |
| Bori_Aron_solution-1 |     0.534969 |       0.555469 |   0.544904 |
| k-d_tree_pandas      |     0.54048  |       0.38548  |   0.55494  |
| k-d_tree_sklearn     |     0.552618 |       0.977646 |   1.09149  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535567 |       0.439537 |   0.444426 |
| k-d_tree_polars      |     0.543655 |       0.440037 |   0.460652 |
| barab-szabi-1        |     0.54479  |       0.457638 |   0.464346 |
| Bori_Aron_solution-1 |     0.534899 |       0.5934   |   0.540547 |
| k-d_tree_pandas      |     0.537739 |       0.404148 |   0.594427 |
| k-d_tree_sklearn     |     0.548233 |       1.05668  |   1.10089  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538745 |       0.501607 |   0.469024 |
| k-d_tree_polars      |     0.536671 |       0.559159 |   0.551107 |
| Bori_Aron_solution-1 |     0.529743 |       0.772801 |   0.555256 |
| barab-szabi-1        |     0.543321 |       0.559885 |   0.564218 |
| k-d_tree_pandas      |     0.544222 |       0.501519 |   0.730585 |
| k-d_tree_sklearn     |     0.544398 |       1.26264  |   1.12048  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541923 |       0.740622 |   0.498196 |
| Bori_Aron_solution-1 |     0.536106 |       1.46958  |   0.582493 |
| k-d_tree_polars      |     0.536984 |       0.966535 |   0.903885 |
| barab-szabi-1        |     0.539691 |       0.962671 |   0.946623 |
| k-d_tree_pandas      |     0.535301 |       0.834104 |   1.1699   |
| k-d_tree_sklearn     |     0.545361 |       2.11954  |   1.19488  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535732 |        5.32285 |   0.749562 |
| Bori_Aron_solution-1 |     0.530909 |       11.2486  |   0.837551 |
| k-d_tree_sklearn     |     0.540578 |       17.2228  |   1.30238  |
| barab-szabi-1        |     0.537487 |        5.69469 |   6.63917  |
| k-d_tree_polars      |     0.536266 |        5.62421 |   6.65318  |
| k-d_tree_pandas      |     0.541808 |        4.61391 |   7.16941  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539226 |         81.765 |    3.32    |
| k-d_tree_sklearn     |     0.564072 |        236.751 |    3.99525 |
| Bori_Aron_solution-1 |     0.692107 |        150.818 |   16.7281  |