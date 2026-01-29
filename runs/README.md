# 2026-01-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.507003 |       0.489114 |   0.453933 |
| k-d_tree_polars      |     0.543389 |       0.418456 |   0.454183 |
| barab-szabi-1        |     0.544412 |       0.421574 |   0.459675 |
| solution-1           |     9.26853  |       1e-06    |   0.46851  |
| Bori_Aron_solution-1 |     0.541187 |       0.64773  |   0.575163 |
| k-d_tree_pandas      |     9.89928  |       0.445493 |   0.844885 |
| k-d_tree_sklearn     |     3.41428  |       1.1515   |   1.07449  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.523276 |       0.401518 |   0.437319 |
| barab-szabi-1        |     0.516308 |       0.409103 |   0.441247 |
| barab-szabi-2        |     0.543945 |       0.457925 |   0.458929 |
| Bori_Aron_solution-1 |     0.516042 |       0.554591 |   0.54137  |
| k-d_tree_pandas      |     0.542687 |       0.403203 |   0.586034 |
| k-d_tree_sklearn     |     0.543584 |       0.98627  |   1.08569  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.522232 |       0.446494 |   0.447263 |
| k-d_tree_polars      |     0.517831 |       0.438638 |   0.461766 |
| barab-szabi-1        |     0.519425 |       0.431242 |   0.463774 |
| Bori_Aron_solution-1 |     0.513488 |       0.584686 |   0.545943 |
| k-d_tree_pandas      |     0.515785 |       0.4102   |   0.595834 |
| k-d_tree_sklearn     |     0.532096 |       1.00594  |   1.06925  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530537 |       0.49843  |   0.4696   |
| Bori_Aron_solution-1 |     0.513928 |       0.774057 |   0.552172 |
| k-d_tree_polars      |     0.526908 |       0.557168 |   0.555418 |
| barab-szabi-1        |     0.516557 |       0.555239 |   0.567641 |
| k-d_tree_pandas      |     0.519135 |       0.492752 |   0.727551 |
| k-d_tree_sklearn     |     0.520622 |       1.24586  |   1.12296  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.520553 |       0.738363 |   0.50284  |
| Bori_Aron_solution-1 |     0.510543 |       1.43776  |   0.574041 |
| k-d_tree_polars      |     0.519137 |       0.929648 |   0.915285 |
| barab-szabi-1        |     0.521353 |       0.927995 |   0.949111 |
| k-d_tree_pandas      |     0.522883 |       0.778188 |   1.17228  |
| k-d_tree_sklearn     |     0.516709 |       2.10711  |   1.21247  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.521238 |        4.98408 |   0.7407   |
| Bori_Aron_solution-1 |     0.517267 |       11.0611  |   0.826275 |
| k-d_tree_sklearn     |     0.521462 |       16.5879  |   1.2941   |
| barab-szabi-1        |     0.51549  |        5.64296 |   6.41762  |
| k-d_tree_polars      |     0.519531 |        5.48083 |   6.56708  |
| k-d_tree_pandas      |     0.522274 |        4.4613  |   6.90748  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.518415 |        76.7933 |    2.61773 |
| k-d_tree_sklearn     |     0.534201 |       237.213  |    4.03927 |
| Bori_Aron_solution-1 |     0.631814 |       147.377  |   17.4659  |