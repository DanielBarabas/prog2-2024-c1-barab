# 2026-01-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.565261 |       0.430479 |   0.460113 |
| barab-szabi-1        |     0.555644 |       0.469638 |   0.460793 |
| solution-1           |     7.74416  |       1e-06    |   0.466656 |
| barab-szabi-2        |     0.534582 |       0.518622 |   0.467854 |
| Bori_Aron_solution-1 |     0.555698 |       0.610245 |   0.623971 |
| k-d_tree_pandas      |     8.31184  |       0.459718 |   0.671012 |
| k-d_tree_sklearn     |     3.03252  |       1.15328  |   1.14974  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.54066  |       0.421305 |   0.448947 |
| k-d_tree_polars      |     0.53762  |       0.420943 |   0.450509 |
| barab-szabi-2        |     0.548855 |       0.445462 |   0.4599   |
| Bori_Aron_solution-1 |     0.53963  |       0.586628 |   0.580761 |
| k-d_tree_pandas      |     0.56493  |       0.427329 |   0.607079 |
| k-d_tree_sklearn     |     0.561033 |       1.01457  |   1.10952  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551678 |       0.456892 |   0.458411 |
| barab-szabi-1        |     0.54284  |       0.445673 |   0.477063 |
| k-d_tree_polars      |     0.553894 |       0.461462 |   0.478706 |
| Bori_Aron_solution-1 |     0.548108 |       0.625866 |   0.570752 |
| k-d_tree_pandas      |     0.546885 |       0.433442 |   0.631761 |
| k-d_tree_sklearn     |     0.54545  |       1.05346  |   1.12561  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547107 |       0.524982 |   0.525287 |
| Bori_Aron_solution-1 |     0.530849 |       0.798129 |   0.588514 |
| k-d_tree_polars      |     0.578287 |       0.575933 |   0.590038 |
| barab-szabi-1        |     0.569321 |       0.603679 |   0.605956 |
| k-d_tree_pandas      |     0.555162 |       0.527066 |   0.770426 |
| k-d_tree_sklearn     |     0.560646 |       1.3414   |   1.27519  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541618 |       0.766872 |   0.561398 |
| Bori_Aron_solution-1 |     0.551883 |       1.50036  |   0.608798 |
| k-d_tree_polars      |     0.544008 |       0.908244 |   0.949763 |
| barab-szabi-1        |     0.566892 |       0.9353   |   0.995184 |
| k-d_tree_pandas      |     0.551356 |       0.823967 |   1.22351  |
| k-d_tree_sklearn     |     0.566707 |       2.27438  |   1.33535  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561853 |        5.23608 |   0.759377 |
| Bori_Aron_solution-1 |     0.545294 |       11.2833  |   0.855009 |
| k-d_tree_sklearn     |     0.551273 |       17.5449  |   1.3603   |
| barab-szabi-1        |     0.543759 |        5.44467 |   6.80486  |
| k-d_tree_polars      |     0.543909 |        5.40891 |   6.82949  |
| k-d_tree_pandas      |     0.553399 |        4.54413 |   7.31664  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546773 |        81.4594 |    2.76878 |
| k-d_tree_sklearn     |     0.568443 |       241.174  |    4.26819 |
| Bori_Aron_solution-1 |     0.712074 |       150.138  |   18.3119  |