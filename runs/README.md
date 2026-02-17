# 2026-02-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.498629 |       0.417479 |   0.444003 |
| barab-szabi-2        |     0.495054 |       0.471628 |   0.448537 |
| solution-1           |     9.0704   |       2e-06    |   0.49246  |
| Bori_Aron_solution-1 |     0.496394 |       0.578528 |   0.561712 |
| k-d_tree_pandas      |     0.49479  |       0.402581 |   0.569511 |
| barab-szabi-1        |     9.80665  |       0.460012 |   0.593524 |
| k-d_tree_sklearn     |     3.24888  |       1.15868  |   1.12328  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.505646 |       0.452144 |   0.441649 |
| barab-szabi-1        |     0.504399 |       0.426515 |   0.45603  |
| k-d_tree_polars      |     0.507787 |       0.421035 |   0.465075 |
| Bori_Aron_solution-1 |     0.49971  |       0.592474 |   0.563193 |
| k-d_tree_pandas      |     0.522093 |       0.420134 |   0.603119 |
| k-d_tree_sklearn     |     0.519224 |       1.03991  |   1.13396  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.50281  |       0.457133 |   0.481046 |
| barab-szabi-2        |     0.509481 |       0.4643   |   0.491835 |
| k-d_tree_polars      |     0.509555 |       0.473825 |   0.495464 |
| Bori_Aron_solution-1 |     0.523532 |       0.615544 |   0.569026 |
| k-d_tree_pandas      |     0.50733  |       0.434794 |   0.717633 |
| k-d_tree_sklearn     |     0.53145  |       1.08923  |   1.13192  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.512392 |       0.532217 |   0.492015 |
| barab-szabi-1        |     0.512879 |       0.586434 |   0.591504 |
| Bori_Aron_solution-1 |     0.512329 |       0.815834 |   0.601751 |
| k-d_tree_polars      |     0.544986 |       0.607183 |   0.607672 |
| k-d_tree_pandas      |     0.527546 |       0.522065 |   0.761218 |
| k-d_tree_sklearn     |     0.521486 |       1.30387  |   1.21242  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.503821 |       0.769363 |   0.534184 |
| Bori_Aron_solution-1 |     0.503961 |       1.53415  |   0.619775 |
| k-d_tree_polars      |     0.508235 |       0.952487 |   0.961189 |
| barab-szabi-1        |     0.510141 |       0.957885 |   1.01286  |
| k-d_tree_pandas      |     0.519017 |       0.820524 |   1.22203  |
| k-d_tree_sklearn     |     0.498599 |       2.20582  |   1.2488   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.514534 |        5.27654 |   0.778109 |
| Bori_Aron_solution-1 |     0.498303 |       11.3845  |   0.85601  |
| k-d_tree_sklearn     |     0.520405 |       17.24    |   1.37457  |
| k-d_tree_polars      |     0.503792 |        5.53971 |   6.81582  |
| barab-szabi-1        |     0.507745 |        5.45729 |   6.82013  |
| k-d_tree_pandas      |     0.50931  |        4.37631 |   7.28101  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.512019 |        73.4973 |    2.80738 |
| k-d_tree_sklearn     |     0.91277  |       242.452  |    3.93927 |
| Bori_Aron_solution-1 |     0.504397 |       147.299  |   25.6125  |