# 2024-04-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.34771  |       1e-06    |   0.369703 |
| k-d_tree_polars      |     0.755424 |       0.410677 |   0.376398 |
| barab-szabi-1        |     0.75222  |       0.40915  |   0.378424 |
| barab-szabi-2        |     0.726743 |       0.391195 |   0.38466  |
| Bori_Aron_solution-1 |     0.725604 |       0.560449 |   0.568011 |
| k-d_tree_pandas      |     8.85836  |       0.420735 |   0.571058 |
| k-d_tree_sklearn     |     3.43178  |       0.930731 |   0.7426   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.761269 |       0.378881 |   0.374527 |
| k-d_tree_polars      |     0.751209 |       0.414467 |   0.375883 |
| barab-szabi-1        |     0.743227 |       0.4174   |   0.389975 |
| Bori_Aron_solution-1 |     0.742495 |       0.518962 |   0.504741 |
| k-d_tree_pandas      |     0.761303 |       0.421716 |   0.54081  |
| k-d_tree_sklearn     |     0.777209 |       0.971931 |   0.726735 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.73664  |       0.386947 |   0.382607 |
| barab-szabi-1        |     0.751411 |       0.431345 |   0.402767 |
| k-d_tree_polars      |     0.738688 |       0.433647 |   0.4105   |
| Bori_Aron_solution-1 |     0.738641 |       0.561143 |   0.514131 |
| k-d_tree_pandas      |     0.768454 |       0.408684 |   0.559218 |
| k-d_tree_sklearn     |     0.772199 |       0.918409 |   0.7148   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.756159 |       0.447119 |   0.410154 |
| barab-szabi-1        |     0.744592 |       0.546327 |   0.511133 |
| k-d_tree_polars      |     0.75332  |       0.547637 |   0.522554 |
| Bori_Aron_solution-1 |     0.736319 |       0.745682 |   0.529924 |
| k-d_tree_pandas      |     0.762948 |       0.488664 |   0.704495 |
| k-d_tree_sklearn     |     0.762839 |       1.12517  |   0.775702 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.747093 |       0.69875  |   0.478776 |
| Bori_Aron_solution-1 |     0.748541 |       1.38391  |   0.548008 |
| k-d_tree_polars      |     0.758152 |       0.850707 |   0.871749 |
| k-d_tree_sklearn     |     0.756938 |       1.93187  |   0.888264 |
| barab-szabi-1        |     0.76347  |       0.882317 |   0.900271 |
| k-d_tree_pandas      |     0.758255 |       0.751539 |   1.14166  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.752086 |        5.35564 |   0.797225 |
| Bori_Aron_solution-1 |     0.754446 |       10.7178  |   0.814954 |
| k-d_tree_sklearn     |     0.746537 |       16.717   |   1.08924  |
| k-d_tree_polars      |     0.764361 |        4.82397 |   6.76425  |
| barab-szabi-1        |     0.74674  |        4.87534 |   6.80134  |
| k-d_tree_pandas      |     0.752257 |        3.89669 |   7.02811  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.767196 |        71.9985 |    3.67061 |
| k-d_tree_sklearn     |     0.971305 |       226.713  |    4.93391 |
| Bori_Aron_solution-1 |     0.87545  |       139.789  |   18.1517  |