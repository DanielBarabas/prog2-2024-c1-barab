# 2025-06-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563676 |       0.425807 |   0.419649 |
| k-d_tree_polars      |     1.00998  |       0.416908 |   0.4374   |
| Bori_Aron_solution-1 |     0.676631 |       0.55506  |   0.553547 |
| k-d_tree_pandas      |     0.571773 |       0.433186 |   0.559548 |
| solution-1           |     7.98459  |       1e-06    |   0.579506 |
| barab-szabi-1        |     8.34191  |       0.480055 |   0.6559   |
| k-d_tree_sklearn     |     3.16128  |       1.23258  |   1.10358  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.568431 |       0.424785 |   0.436316 |
| barab-szabi-1        |     0.564494 |       0.417456 |   0.437656 |
| barab-szabi-2        |     0.56776  |       0.436186 |   0.440434 |
| Bori_Aron_solution-1 |     0.571744 |       0.573876 |   0.554095 |
| k-d_tree_pandas      |     0.571404 |       0.405932 |   0.581666 |
| k-d_tree_sklearn     |     0.572747 |       1.01118  |   1.12266  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57195  |       0.455491 |   0.459835 |
| barab-szabi-1        |     0.575257 |       0.461711 |   0.463341 |
| k-d_tree_polars      |     0.569215 |       0.450881 |   0.478914 |
| Bori_Aron_solution-1 |     0.564309 |       0.618429 |   0.57595  |
| k-d_tree_pandas      |     0.572915 |       0.420504 |   0.618925 |
| k-d_tree_sklearn     |     0.579096 |       1.06448  |   1.2315   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.573365 |       0.513237 |   0.478095 |
| k-d_tree_polars      |     0.575423 |       0.561103 |   0.566874 |
| barab-szabi-1        |     0.579241 |       0.579344 |   0.578482 |
| Bori_Aron_solution-1 |     0.563586 |       0.787353 |   0.587506 |
| k-d_tree_pandas      |     0.574954 |       0.510882 |   0.761435 |
| k-d_tree_sklearn     |     0.591978 |       1.29282  |   1.18474  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586291 |       0.78182  |   0.562639 |
| Bori_Aron_solution-1 |     0.569133 |       1.45372  |   0.614201 |
| k-d_tree_polars      |     0.571491 |       0.894522 |   0.947096 |
| barab-szabi-1        |     0.576197 |       0.90135  |   0.987809 |
| k-d_tree_pandas      |     0.578968 |       0.784947 |   1.23911  |
| k-d_tree_sklearn     |     0.597525 |       2.22768  |   1.28827  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583212 |        5.60011 |   0.749378 |
| Bori_Aron_solution-1 |     0.559105 |       10.7786  |   0.843509 |
| k-d_tree_sklearn     |     0.572313 |       17.2199  |   1.36598  |
| k-d_tree_polars      |     0.582992 |        4.99506 |   6.78359  |
| barab-szabi-1        |     0.575924 |        5.03877 |   7.11804  |
| k-d_tree_pandas      |     0.581955 |        3.96895 |   7.37704  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.628408 |        74.5136 |    2.85493 |
| k-d_tree_sklearn     |     0.73933  |       238.985  |    3.99206 |
| Bori_Aron_solution-1 |     0.566807 |       144.972  |   17.4177  |