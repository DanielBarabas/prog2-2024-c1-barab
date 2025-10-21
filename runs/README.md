# 2025-10-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.552835 |       0.415264 |   0.430107 |
| barab-szabi-2        |     0.530416 |       0.460001 |   0.434478 |
| solution-1           |     7.74871  |       1e-06    |   0.464308 |
| k-d_tree_polars      |     0.565628 |       0.420783 |   0.479801 |
| Bori_Aron_solution-1 |     0.555894 |       0.570814 |   0.574608 |
| k-d_tree_pandas      |     8.17783  |       0.440509 |   0.641441 |
| k-d_tree_sklearn     |     3.09123  |       1.10435  |   1.11567  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549217 |       0.426883 |   0.425503 |
| k-d_tree_polars      |     0.546293 |       0.416189 |   0.432614 |
| barab-szabi-1        |     0.543841 |       0.414683 |   0.439365 |
| Bori_Aron_solution-1 |     0.536458 |       0.552518 |   0.547336 |
| k-d_tree_pandas      |     0.584153 |       0.39836  |   0.55774  |
| k-d_tree_sklearn     |     0.54877  |       0.960821 |   1.06155  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542938 |       0.443226 |   0.436022 |
| k-d_tree_polars      |     0.542383 |       0.436023 |   0.458838 |
| barab-szabi-1        |     0.545727 |       0.437334 |   0.4627   |
| Bori_Aron_solution-1 |     0.533912 |       0.591432 |   0.54528  |
| k-d_tree_pandas      |     0.549106 |       0.412914 |   0.601204 |
| k-d_tree_sklearn     |     0.545848 |       1.00926  |   1.08488  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542399 |       0.510877 |   0.466972 |
| k-d_tree_polars      |     0.538403 |       0.557122 |   0.548548 |
| Bori_Aron_solution-1 |     0.538604 |       0.783468 |   0.563415 |
| barab-szabi-1        |     0.55329  |       0.565635 |   0.563794 |
| k-d_tree_pandas      |     0.540947 |       0.504245 |   0.732757 |
| k-d_tree_sklearn     |     0.544332 |       1.25382  |   1.12835  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548174 |       0.754    |   0.498449 |
| Bori_Aron_solution-1 |     0.532879 |       1.46605  |   0.591475 |
| k-d_tree_polars      |     0.541306 |       0.954323 |   0.904754 |
| barab-szabi-1        |     0.552687 |       0.953689 |   0.94028  |
| k-d_tree_pandas      |     0.547509 |       0.826461 |   1.17724  |
| k-d_tree_sklearn     |     0.547705 |       2.14687  |   1.21183  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540668 |        5.23484 |   0.750073 |
| Bori_Aron_solution-1 |     0.541888 |       11.2243  |   0.872974 |
| k-d_tree_sklearn     |     0.544971 |       16.6908  |   1.31213  |
| barab-szabi-1        |     0.543793 |        5.64642 |   6.48821  |
| k-d_tree_polars      |     0.540541 |        5.68959 |   6.51125  |
| k-d_tree_pandas      |     0.543469 |        4.62099 |   6.90306  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545353 |        75.4664 |    2.76529 |
| k-d_tree_sklearn     |     0.557757 |       244.624  |    4.17661 |
| Bori_Aron_solution-1 |     0.651264 |       158.761  |   18.2686  |