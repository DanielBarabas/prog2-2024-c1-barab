# 2026-09-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.327694 |       0.323142 |   0.321945 |
| k-d_tree_polars      |     0.320138 |       0.299046 |   0.339764 |
| Bori_Aron_solution-1 |     0.312118 |       0.397259 |   0.397771 |
| k-d_tree_pandas      |     0.31777  |       0.276983 |   0.39929  |
| solution-1           |     6.41872  |       1e-06    |   0.550961 |
| k-d_tree_sklearn     |     2.63654  |       0.878722 |   0.769345 |
| barab-szabi-1        |     8.53914  |       0.387684 |   0.87819  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.3273   |       0.314717 |   0.337479 |
| barab-szabi-2        |     0.326627 |       0.390357 |   0.365974 |
| k-d_tree_polars      |     0.363203 |       0.326756 |   0.372467 |
| Bori_Aron_solution-1 |     0.322742 |       0.400162 |   0.409483 |
| k-d_tree_pandas      |     0.321127 |       0.293877 |   0.430663 |
| k-d_tree_sklearn     |     0.360161 |       0.730837 |   0.840452 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.323417 |       0.342917 |   0.339439 |
| barab-szabi-2        |     0.323225 |       0.342606 |   0.34698  |
| barab-szabi-1        |     0.326519 |       0.341328 |   0.359779 |
| Bori_Aron_solution-1 |     0.323353 |       0.422615 |   0.394549 |
| k-d_tree_pandas      |     0.326225 |       0.329682 |   0.470759 |
| k-d_tree_sklearn     |     0.324756 |       0.784232 |   0.775917 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.324984 |       0.381348 |   0.378279 |
| k-d_tree_polars      |     0.368057 |       0.422698 |   0.402205 |
| Bori_Aron_solution-1 |     0.317281 |       0.541054 |   0.410368 |
| barab-szabi-1        |     0.323282 |       0.421142 |   0.420778 |
| k-d_tree_pandas      |     0.321523 |       0.361012 |   0.510821 |
| k-d_tree_sklearn     |     0.327019 |       0.917899 |   0.818148 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.364943 |       0.581319 |   0.405122 |
| Bori_Aron_solution-1 |     0.320805 |       1.01217  |   0.441373 |
| k-d_tree_polars      |     0.328089 |       0.795363 |   0.662536 |
| barab-szabi-1        |     0.322847 |       0.850868 |   0.686767 |
| k-d_tree_pandas      |     0.337023 |       0.544563 |   0.808304 |
| k-d_tree_sklearn     |     0.327937 |       1.50682  |   0.87051  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.351633 |        3.83691 |   0.619947 |
| Bori_Aron_solution-1 |     0.319755 |        7.6459  |   0.767512 |
| k-d_tree_sklearn     |     0.338689 |       12.2744  |   0.950858 |
| k-d_tree_polars      |     0.320448 |        4.15438 |   5.06601  |
| barab-szabi-1        |     0.323254 |        4.29685 |   5.12847  |
| k-d_tree_pandas      |     0.32687  |        2.78542 |   5.40673  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     1.00769  |       162.043  |    5.45645 |
| barab-szabi-2        |     2.09655  |        59.1236 |    6.18124 |
| Bori_Aron_solution-1 |     0.314713 |       146.386  |   85.2252  |