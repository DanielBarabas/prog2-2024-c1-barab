# 2024-06-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.52351  |       0.357674 |   0.344991 |
| barab-szabi-1        |     0.798074 |       0.405047 |   0.347965 |
| k-d_tree_polars      |     0.808615 |       0.403606 |   0.348889 |
| solution-1           |     8.26944  |       1e-06    |   0.364541 |
| Bori_Aron_solution-1 |     4.62253  |       0.415058 |   0.411556 |
| k-d_tree_pandas      |     0.798533 |       0.38531  |   0.487402 |
| k-d_tree_sklearn     |     3.30717  |       0.988738 |   0.681604 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.796091 |       0.350332 |   0.345048 |
| barab-szabi-1        |     0.814241 |       0.414797 |   0.356761 |
| k-d_tree_polars      |     0.820467 |       0.411438 |   0.362298 |
| Bori_Aron_solution-1 |     0.788547 |       0.489278 |   0.483485 |
| k-d_tree_pandas      |     0.796222 |       0.389277 |   0.493185 |
| k-d_tree_sklearn     |     0.814543 |       0.8625   |   0.67984  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.794193 |       0.434677 |   0.37366  |
| barab-szabi-2        |     0.788508 |       0.36412  |   0.383332 |
| barab-szabi-1        |     0.802308 |       0.441114 |   0.384052 |
| Bori_Aron_solution-1 |     0.788024 |       0.520911 |   0.471762 |
| k-d_tree_pandas      |     0.832582 |       0.413888 |   0.530875 |
| k-d_tree_sklearn     |     0.803193 |       0.941986 |   0.716972 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.783357 |       0.422161 |   0.389    |
| k-d_tree_polars      |     0.791178 |       0.541316 |   0.475633 |
| Bori_Aron_solution-1 |     0.781547 |       0.696955 |   0.485445 |
| barab-szabi-1        |     0.786348 |       0.542641 |   0.493792 |
| k-d_tree_pandas      |     0.805128 |       0.480467 |   0.661762 |
| k-d_tree_sklearn     |     0.804495 |       1.11847  |   0.762648 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.791029 |       0.700381 |   0.445855 |
| Bori_Aron_solution-1 |     0.780426 |       1.37274  |   0.514873 |
| k-d_tree_sklearn     |     0.807783 |       1.94727  |   0.862522 |
| k-d_tree_polars      |     0.790521 |       0.895042 |   0.869363 |
| barab-szabi-1        |     0.795137 |       0.872762 |   0.872029 |
| k-d_tree_pandas      |     0.791387 |       0.775719 |   1.11392  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.792046 |        5.43395 |   0.747384 |
| Bori_Aron_solution-1 |     0.810678 |       10.8472  |   0.772239 |
| k-d_tree_sklearn     |     0.824834 |       16.686   |   1.06177  |
| k-d_tree_polars      |     0.796834 |        4.97152 |   6.60599  |
| k-d_tree_pandas      |     0.815628 |        3.98868 |   6.88109  |
| barab-szabi-1        |     0.812465 |        5.00589 |   6.88554  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.06986  |        73.1822 |    3.3017  |
| k-d_tree_sklearn     |     0.916671 |       224.727  |    4.49905 |
| Bori_Aron_solution-1 |     0.785641 |       154.572  |   15.0139  |