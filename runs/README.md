# 2026-02-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.568995 |       0.442037 |   0.467455 |
| barab-szabi-2        |     0.555419 |       0.544389 |   0.474591 |
| barab-szabi-1        |     0.576225 |       0.459413 |   0.47464  |
| solution-1           |     7.79658  |       1e-06    |   0.495756 |
| Bori_Aron_solution-1 |     0.563378 |       0.624066 |   0.599468 |
| k-d_tree_pandas      |     8.7658   |       0.455112 |   0.686779 |
| k-d_tree_sklearn     |     3.12864  |       1.19556  |   1.22144  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.576943 |       0.467654 |   0.475982 |
| k-d_tree_polars      |     0.574184 |       0.453317 |   0.479204 |
| barab-szabi-1        |     0.571774 |       0.467586 |   0.481962 |
| Bori_Aron_solution-1 |     0.572305 |       0.590691 |   0.599673 |
| k-d_tree_pandas      |     0.568871 |       0.42943  |   0.614572 |
| k-d_tree_sklearn     |     0.568479 |       1.07052  |   1.23461  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.568798 |       0.487352 |   0.487676 |
| k-d_tree_polars      |     0.585958 |       0.48634  |   0.511563 |
| barab-szabi-1        |     0.567965 |       0.482476 |   0.524269 |
| Bori_Aron_solution-1 |     0.579024 |       0.687925 |   0.610991 |
| k-d_tree_pandas      |     0.563823 |       0.451841 |   0.666669 |
| k-d_tree_sklearn     |     0.57231  |       1.10747  |   1.21917  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552242 |       0.558277 |   0.540824 |
| Bori_Aron_solution-1 |     0.56668  |       0.8424   |   0.611366 |
| barab-szabi-1        |     0.556554 |       0.609149 |   0.618223 |
| k-d_tree_polars      |     0.569288 |       0.608489 |   0.632336 |
| k-d_tree_pandas      |     0.564269 |       0.536345 |   0.785563 |
| k-d_tree_sklearn     |     0.586998 |       1.39252  |   1.26331  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589352 |       0.811419 |   0.630457 |
| Bori_Aron_solution-1 |     0.570739 |       1.651    |   0.701281 |
| k-d_tree_polars      |     0.575678 |       0.98655  |   1.02025  |
| barab-szabi-1        |     0.563208 |       0.967341 |   1.04484  |
| k-d_tree_pandas      |     0.580403 |       0.836359 |   1.32135  |
| k-d_tree_sklearn     |     0.558368 |       2.34908  |   1.32856  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605961 |        5.78955 |   0.859095 |
| Bori_Aron_solution-1 |     0.582696 |       11.8559  |   0.935228 |
| k-d_tree_sklearn     |     0.575463 |       19.4797  |   1.54219  |
| barab-szabi-1        |     0.596407 |        5.55992 |   7.34375  |
| k-d_tree_polars      |     0.589803 |        5.58117 |   7.4128   |
| k-d_tree_pandas      |     0.599383 |        4.44956 |   7.80821  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598176 |        76.1588 |     2.9367 |
| k-d_tree_sklearn     |     0.557114 |       253.094  |     4.2294 |
| Bori_Aron_solution-1 |     0.673939 |       152.28   |    18.0497 |