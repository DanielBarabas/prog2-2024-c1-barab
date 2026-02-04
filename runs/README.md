# 2026-02-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.500906 |       0.400593 |   0.431523 |
| k-d_tree_polars      |     0.493448 |       0.40062  |   0.442223 |
| barab-szabi-2        |     0.49006  |       0.51337  |   0.4573   |
| solution-1           |     7.54531  |       1e-06    |   0.460493 |
| Bori_Aron_solution-1 |     0.495366 |       0.553226 |   0.560287 |
| k-d_tree_pandas      |     8.60303  |       0.401261 |   0.652451 |
| k-d_tree_sklearn     |     2.9568   |       1.1134   |   1.05182  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.497665 |       0.404306 |   0.438328 |
| barab-szabi-2        |     0.519613 |       0.454058 |   0.442634 |
| k-d_tree_polars      |     0.505813 |       0.412643 |   0.449337 |
| Bori_Aron_solution-1 |     0.487177 |       0.554236 |   0.559184 |
| k-d_tree_pandas      |     0.516265 |       0.413458 |   0.592763 |
| k-d_tree_sklearn     |     0.512151 |       1.006    |   1.06942  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.514508 |       0.464959 |   0.46212  |
| k-d_tree_polars      |     0.499792 |       0.453454 |   0.467446 |
| barab-szabi-1        |     0.509417 |       0.455839 |   0.474731 |
| Bori_Aron_solution-1 |     0.495791 |       0.600435 |   0.548753 |
| k-d_tree_pandas      |     0.49921  |       0.410761 |   0.628331 |
| k-d_tree_sklearn     |     0.511163 |       1.04478  |   1.10699  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.510874 |       0.514646 |   0.485656 |
| k-d_tree_polars      |     0.521379 |       0.586319 |   0.556711 |
| barab-szabi-1        |     0.498146 |       0.562944 |   0.558823 |
| Bori_Aron_solution-1 |     0.496504 |       0.760622 |   0.572049 |
| k-d_tree_pandas      |     0.503745 |       0.5056   |   0.744615 |
| k-d_tree_sklearn     |     0.501451 |       1.24321  |   1.13667  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.509096 |       0.738079 |   0.541386 |
| Bori_Aron_solution-1 |     0.496758 |       1.40765  |   0.629387 |
| k-d_tree_polars      |     0.497829 |       0.886741 |   0.903207 |
| barab-szabi-1        |     0.49717  |       0.878539 |   0.922811 |
| k-d_tree_pandas      |     0.50009  |       0.750431 |   1.16451  |
| k-d_tree_sklearn     |     0.503563 |       2.09438  |   1.17915  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49581  |        5.35727 |   0.735104 |
| Bori_Aron_solution-1 |     0.493619 |       10.3373  |   0.965818 |
| k-d_tree_sklearn     |     0.513578 |       15.1936  |   1.32384  |
| barab-szabi-1        |     0.498424 |        4.94675 |   6.43382  |
| k-d_tree_polars      |     0.497875 |        4.96216 |   6.49671  |
| k-d_tree_pandas      |     0.520266 |        3.89265 |   6.90295  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5126   |        71.3516 |    2.90138 |
| k-d_tree_sklearn     |     0.506938 |       190.262  |    4.39833 |
| Bori_Aron_solution-1 |     0.625384 |       139.63   |   18.6102  |