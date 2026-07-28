# 2026-07-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.47226  |       1e-06    |   0.386196 |
| barab-szabi-2        |     0.462076 |       0.424734 |   0.431675 |
| barab-szabi-1        |     0.457582 |       0.401794 |   0.437425 |
| k-d_tree_polars      |     9.26927  |       0.544812 |   0.501846 |
| Bori_Aron_solution-1 |     0.44545  |       0.523349 |   0.528733 |
| k-d_tree_pandas      |     0.461209 |       0.374689 |   0.533482 |
| k-d_tree_sklearn     |     3.59603  |       1.094    |   1.03051  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.460032 |       0.412891 |   0.429766 |
| barab-szabi-2        |     0.459915 |       0.430599 |   0.44259  |
| barab-szabi-1        |     0.466656 |       0.41308  |   0.442616 |
| Bori_Aron_solution-1 |     0.451631 |       0.541862 |   0.528994 |
| k-d_tree_pandas      |     0.458071 |       0.381928 |   0.539043 |
| k-d_tree_sklearn     |     0.467625 |       0.988626 |   1.04415  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.458292 |       0.440713 |   0.441197 |
| barab-szabi-1        |     0.461757 |       0.441206 |   0.4618   |
| k-d_tree_polars      |     0.459915 |       0.442896 |   0.465371 |
| Bori_Aron_solution-1 |     0.457995 |       0.578258 |   0.538465 |
| k-d_tree_pandas      |     0.461349 |       0.403662 |   0.571612 |
| k-d_tree_sklearn     |     0.462855 |       1.01466  |   1.05404  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.457231 |       0.503861 |   0.463158 |
| Bori_Aron_solution-1 |     0.474382 |       0.765884 |   0.549755 |
| k-d_tree_polars      |     0.473728 |       0.555069 |   0.556177 |
| barab-szabi-1        |     0.46109  |       0.55276  |   0.576613 |
| k-d_tree_pandas      |     0.460904 |       0.484439 |   0.698428 |
| k-d_tree_sklearn     |     0.462995 |       1.24059  |   1.08213  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.46239  |       0.745374 |   0.5093   |
| Bori_Aron_solution-1 |     0.463833 |       1.48361  |   0.574533 |
| k-d_tree_polars      |     0.465767 |       0.895465 |   0.957891 |
| barab-szabi-1        |     0.467772 |       0.89866  |   0.981789 |
| k-d_tree_sklearn     |     0.470836 |       2.09771  |   1.14243  |
| k-d_tree_pandas      |     0.461932 |       0.767115 |   1.15668  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460889 |        5.46677 |   0.730623 |
| Bori_Aron_solution-1 |     0.455727 |       11.0679  |   0.798608 |
| k-d_tree_sklearn     |     0.462363 |       16.6492  |   1.24249  |
| k-d_tree_polars      |     0.469051 |        5.11764 |   7.22528  |
| barab-szabi-1        |     0.468967 |        4.95267 |   7.23434  |
| k-d_tree_pandas      |     0.463704 |        4.06266 |   7.60883  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553414 |        76.1628 |    2.44765 |
| k-d_tree_sklearn     |     0.787913 |       253.314  |    3.26986 |
| Bori_Aron_solution-1 |     0.476483 |       157.972  |   15.6486  |