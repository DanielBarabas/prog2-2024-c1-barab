# 2026-07-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.35001  |       1e-06    |   0.393589 |
| barab-szabi-2        |     0.456607 |       0.43472  |   0.433832 |
| k-d_tree_polars      |     0.492743 |       0.414435 |   0.43925  |
| barab-szabi-1        |     8.28325  |       0.46234  |   0.490951 |
| Bori_Aron_solution-1 |     0.447937 |       0.533635 |   0.53674  |
| k-d_tree_pandas      |     0.462201 |       0.374917 |   0.537773 |
| k-d_tree_sklearn     |     3.20926  |       1.04141  |   1.04873  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466603 |       0.436496 |   0.441351 |
| barab-szabi-1        |     0.464531 |       0.41423  |   0.449865 |
| k-d_tree_polars      |     0.465728 |       0.424446 |   0.459191 |
| k-d_tree_pandas      |     0.481024 |       0.382412 |   0.545028 |
| Bori_Aron_solution-1 |     0.464463 |       0.575549 |   0.570426 |
| k-d_tree_sklearn     |     0.468756 |       1.01781  |   1.06552  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.46548  |       0.447737 |   0.460973 |
| k-d_tree_polars      |     0.480188 |       0.442412 |   0.470979 |
| barab-szabi-1        |     0.465602 |       0.432867 |   0.477263 |
| Bori_Aron_solution-1 |     0.470048 |       0.595073 |   0.562424 |
| k-d_tree_pandas      |     0.461918 |       0.401909 |   0.592022 |
| k-d_tree_sklearn     |     0.469105 |       1.02861  |   1.07395  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470824 |       0.513528 |   0.482817 |
| Bori_Aron_solution-1 |     0.468182 |       0.779182 |   0.553618 |
| k-d_tree_polars      |     0.470507 |       0.571455 |   0.567515 |
| barab-szabi-1        |     0.466707 |       0.56866  |   0.584604 |
| k-d_tree_pandas      |     0.476759 |       0.510126 |   0.74169  |
| k-d_tree_sklearn     |     0.46899  |       1.25906  |   1.16249  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463619 |       0.724099 |   0.507986 |
| Bori_Aron_solution-1 |     0.462455 |       1.413    |   0.574976 |
| k-d_tree_polars      |     0.465052 |       0.914518 |   0.89923  |
| barab-szabi-1        |     0.464966 |       0.919306 |   0.964582 |
| k-d_tree_pandas      |     0.464087 |       0.791106 |   1.16339  |
| k-d_tree_sklearn     |     0.463814 |       2.08394  |   1.20239  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468477 |        5.07884 |   0.767782 |
| Bori_Aron_solution-1 |     0.456859 |       10.989   |   0.811983 |
| k-d_tree_sklearn     |     0.469917 |       16.8933  |   1.30328  |
| barab-szabi-1        |     0.463276 |        5.31314 |   6.61839  |
| k-d_tree_polars      |     0.463755 |        5.38091 |   6.64002  |
| k-d_tree_pandas      |     0.463294 |        4.34571 |   6.9588   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460721 |        73.5103 |    2.88509 |
| k-d_tree_sklearn     |     0.870829 |       242.133  |    4.40454 |
| Bori_Aron_solution-1 |     0.462369 |       154.626  |   15.2652  |