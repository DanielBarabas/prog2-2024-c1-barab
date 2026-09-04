# 2026-09-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.96065  |       1e-06    |   0.419372 |
| barab-szabi-2        |     0.475626 |       0.451328 |   0.451892 |
| k-d_tree_polars      |     0.467207 |       0.408966 |   0.460315 |
| Bori_Aron_solution-1 |     0.453677 |       0.54365  |   0.543729 |
| k-d_tree_pandas      |     0.459723 |       0.391516 |   0.555074 |
| barab-szabi-1        |     8.69608  |       0.464504 |   0.640111 |
| k-d_tree_sklearn     |     2.97305  |       1.23304  |   1.09303  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487088 |       0.458516 |   0.453015 |
| k-d_tree_polars      |     0.488971 |       0.42763  |   0.453376 |
| barab-szabi-1        |     0.475101 |       0.428546 |   0.459875 |
| k-d_tree_pandas      |     0.4828   |       0.394026 |   0.562462 |
| Bori_Aron_solution-1 |     0.470758 |       0.579346 |   0.571492 |
| k-d_tree_sklearn     |     0.479949 |       1.02441  |   1.1189   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48748  |       0.46574  |   0.47081  |
| k-d_tree_polars      |     0.479572 |       0.458252 |   0.48109  |
| barab-szabi-1        |     0.481844 |       0.455933 |   0.485628 |
| Bori_Aron_solution-1 |     0.470178 |       0.602972 |   0.554465 |
| k-d_tree_pandas      |     0.479499 |       0.431292 |   0.6142   |
| k-d_tree_sklearn     |     0.487149 |       1.05398  |   1.12101  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495373 |       0.519243 |   0.486233 |
| k-d_tree_polars      |     0.50698  |       0.603836 |   0.589893 |
| barab-szabi-1        |     0.488575 |       0.600797 |   0.595553 |
| Bori_Aron_solution-1 |     0.486063 |       0.82366  |   0.600527 |
| k-d_tree_pandas      |     0.504036 |       0.520913 |   0.770949 |
| k-d_tree_sklearn     |     0.494767 |       1.31266  |   1.21137  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479466 |       0.767347 |   0.542432 |
| Bori_Aron_solution-1 |     0.483313 |       1.44479  |   0.5829   |
| k-d_tree_polars      |     0.474922 |       0.942323 |   0.950322 |
| barab-szabi-1        |     0.473365 |       0.93445  |   0.982234 |
| k-d_tree_pandas      |     0.494601 |       0.812405 |   1.19779  |
| k-d_tree_sklearn     |     0.492898 |       2.1477   |   1.25827  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473904 |        5.27511 |   0.7857   |
| Bori_Aron_solution-1 |     0.472227 |       11.01    |   0.833192 |
| k-d_tree_sklearn     |     0.48179  |       16.9418  |   1.32534  |
| barab-szabi-1        |     0.503076 |        5.26734 |   6.75356  |
| k-d_tree_polars      |     0.479166 |        5.26088 |   6.76246  |
| k-d_tree_pandas      |     0.475583 |        4.30552 |   7.12267  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561851 |        74.7578 |    3.00799 |
| k-d_tree_sklearn     |     0.799169 |       241.145  |    3.95677 |
| Bori_Aron_solution-1 |     0.471937 |       149.319  |   22.9599  |