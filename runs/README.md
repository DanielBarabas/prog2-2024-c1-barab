# 2026-07-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.23119  |       1e-06    |   0.410069 |
| barab-szabi-2        |     8.53713  |       0.617392 |   0.440214 |
| k-d_tree_polars      |     0.459589 |       0.419194 |   0.449407 |
| barab-szabi-1        |     0.459171 |       0.416318 |   0.450074 |
| Bori_Aron_solution-1 |     0.454119 |       0.54225  |   0.548358 |
| k-d_tree_pandas      |     0.476086 |       0.386145 |   0.564141 |
| k-d_tree_sklearn     |     3.0204   |       1.09032  |   1.07821  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483615 |       0.442694 |   0.450725 |
| k-d_tree_polars      |     0.471424 |       0.427392 |   0.452117 |
| barab-szabi-1        |     0.469607 |       0.421595 |   0.459644 |
| Bori_Aron_solution-1 |     0.470103 |       0.556005 |   0.549498 |
| k-d_tree_pandas      |     0.465826 |       0.388199 |   0.555796 |
| k-d_tree_sklearn     |     0.496523 |       1.00558  |   1.09646  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467445 |       0.455887 |   0.461232 |
| barab-szabi-1        |     0.476116 |       0.456667 |   0.473775 |
| k-d_tree_polars      |     0.476854 |       0.446834 |   0.485404 |
| Bori_Aron_solution-1 |     0.465646 |       0.592322 |   0.55245  |
| k-d_tree_pandas      |     0.47836  |       0.424856 |   0.600457 |
| k-d_tree_sklearn     |     0.480519 |       1.05392  |   1.10825  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47443  |       0.519643 |   0.478796 |
| Bori_Aron_solution-1 |     0.466725 |       0.771858 |   0.561246 |
| k-d_tree_polars      |     0.478817 |       0.579587 |   0.570522 |
| barab-szabi-1        |     0.476042 |       0.571218 |   0.607343 |
| k-d_tree_pandas      |     0.477884 |       0.499243 |   0.743005 |
| k-d_tree_sklearn     |     0.480332 |       1.30763  |   1.16486  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47777  |       0.730727 |   0.522723 |
| Bori_Aron_solution-1 |     0.465675 |       1.41117  |   0.579135 |
| k-d_tree_polars      |     0.470861 |       0.936881 |   0.918545 |
| barab-szabi-1        |     0.467744 |       0.926953 |   0.949811 |
| k-d_tree_pandas      |     0.462965 |       0.804035 |   1.17914  |
| k-d_tree_sklearn     |     0.481617 |       2.13193  |   1.21656  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471782 |        5.22758 |   0.75123  |
| Bori_Aron_solution-1 |     0.462896 |       10.9092  |   0.822089 |
| k-d_tree_sklearn     |     0.469988 |       16.8462  |   1.31454  |
| barab-szabi-1        |     0.481761 |        5.37475 |   6.67923  |
| k-d_tree_polars      |     0.479511 |        5.34577 |   6.78542  |
| k-d_tree_pandas      |     0.471076 |        4.35711 |   7.14756  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478637 |        72.8981 |    2.83926 |
| k-d_tree_sklearn     |     0.621219 |       233.239  |    4.03411 |
| Bori_Aron_solution-1 |     0.49955  |       152.445  |   16.2798  |