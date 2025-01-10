# 2025-01-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.585126 |       0.40182  |   0.398848 |
| barab-szabi-2        |     0.577211 |       0.496689 |   0.401967 |
| k-d_tree_polars      |     0.600683 |       0.409745 |   0.402674 |
| Bori_Aron_solution-1 |     0.584311 |       0.549441 |   0.543377 |
| solution-1           |     7.85199  |       1e-06    |   0.631467 |
| k-d_tree_pandas      |     8.1373   |       0.431413 |   0.730307 |
| k-d_tree_sklearn     |     3.05897  |       1.21747  |   1.0619   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.597435 |       0.417051 |   0.405701 |
| barab-szabi-1        |     0.594826 |       0.415139 |   0.420015 |
| k-d_tree_polars      |     0.62929  |       0.433498 |   0.433289 |
| k-d_tree_pandas      |     0.60143  |       0.393521 |   0.558975 |
| Bori_Aron_solution-1 |     0.615516 |       0.57761  |   0.577479 |
| k-d_tree_sklearn     |     0.616152 |       0.984789 |   1.0948   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634076 |       0.437368 |   0.43423  |
| k-d_tree_polars      |     0.606952 |       0.45025  |   0.446829 |
| barab-szabi-1        |     0.602703 |       0.442013 |   0.45555  |
| Bori_Aron_solution-1 |     0.616918 |       0.613365 |   0.569054 |
| k-d_tree_pandas      |     0.609591 |       0.425546 |   0.629609 |
| k-d_tree_sklearn     |     0.610081 |       1.01389  |   1.13735  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60841  |       0.494368 |   0.470202 |
| k-d_tree_polars      |     0.635897 |       0.553524 |   0.562404 |
| barab-szabi-1        |     0.612968 |       0.56093  |   0.568794 |
| Bori_Aron_solution-1 |     0.609997 |       0.78367  |   0.592076 |
| k-d_tree_pandas      |     0.618303 |       0.526517 |   0.757371 |
| k-d_tree_sklearn     |     0.6196   |       1.28863  |   1.18183  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.611797 |       1.46325  |   0.639672 |
| barab-szabi-2        |     0.611613 |       0.771924 |   0.660171 |
| k-d_tree_polars      |     0.593179 |       0.887612 |   0.928682 |
| barab-szabi-1        |     0.621398 |       0.876389 |   0.963767 |
| k-d_tree_sklearn     |     0.615566 |       2.10371  |   1.21136  |
| k-d_tree_pandas      |     0.613399 |       0.783902 |   1.22809  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603755 |        5.59774 |   0.768409 |
| Bori_Aron_solution-1 |     0.595354 |       10.5621  |   0.868663 |
| k-d_tree_sklearn     |     0.621133 |       16.8639  |   1.31231  |
| k-d_tree_polars      |     0.602915 |        4.7768  |   6.79292  |
| barab-szabi-1        |     0.607435 |        4.83991 |   6.98845  |
| k-d_tree_pandas      |     0.638592 |        3.86726 |   7.19258  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589254 |         76.811 |     3.0091 |
| k-d_tree_sklearn     |     0.618882 |        236.473 |     4.526  |
| Bori_Aron_solution-1 |     0.740237 |        148.534 |    18.1958 |