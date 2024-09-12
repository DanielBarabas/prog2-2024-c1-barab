# 2024-09-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.51925  |       1e-06    |   0.36716  |
| barab-szabi-2        |     0.617184 |       0.394762 |   0.389752 |
| barab-szabi-1        |     0.620503 |       0.40193  |   0.400074 |
| k-d_tree_polars      |     4.24358  |       0.453529 |   0.412843 |
| Bori_Aron_solution-1 |     4.51315  |       0.565509 |   0.476306 |
| k-d_tree_pandas      |     0.619601 |       0.400262 |   0.560946 |
| k-d_tree_sklearn     |     2.96086  |       0.957493 |   0.97112  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625216 |       0.393419 |   0.394989 |
| k-d_tree_polars      |     0.616909 |       0.404825 |   0.398596 |
| barab-szabi-1        |     0.621189 |       0.411357 |   0.398694 |
| Bori_Aron_solution-1 |     0.645981 |       0.553077 |   0.536166 |
| k-d_tree_pandas      |     0.611593 |       0.391377 |   0.543064 |
| k-d_tree_sklearn     |     0.629689 |       0.909383 |   0.993791 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618549 |       0.409312 |   0.410155 |
| k-d_tree_polars      |     0.618819 |       0.436593 |   0.425128 |
| barab-szabi-1        |     0.617247 |       0.446249 |   0.430305 |
| Bori_Aron_solution-1 |     0.622234 |       0.568941 |   0.534948 |
| k-d_tree_pandas      |     0.621854 |       0.405059 |   0.590284 |
| k-d_tree_sklearn     |     0.627432 |       0.946455 |   1.03914  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619269 |       0.474301 |   0.432612 |
| k-d_tree_polars      |     0.647382 |       0.538819 |   0.523243 |
| barab-szabi-1        |     0.622245 |       0.545734 |   0.535016 |
| Bori_Aron_solution-1 |     0.621374 |       0.786106 |   0.573803 |
| k-d_tree_pandas      |     0.618617 |       0.488375 |   0.731617 |
| k-d_tree_sklearn     |     0.634051 |       1.23399  |   1.07034  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623249 |       0.747265 |   0.527978 |
| Bori_Aron_solution-1 |     0.622715 |       1.41516  |   0.599907 |
| k-d_tree_polars      |     0.627248 |       0.887208 |   0.897381 |
| barab-szabi-1        |     0.648176 |       0.882688 |   0.963984 |
| k-d_tree_sklearn     |     0.657    |       2.06262  |   1.16965  |
| k-d_tree_pandas      |     0.6277   |       0.753104 |   1.18821  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.637933 |        5.54568 |   0.779752 |
| Bori_Aron_solution-1 |     0.642253 |       11.0318  |   0.873229 |
| k-d_tree_sklearn     |     0.65059  |       16.3906  |   1.28992  |
| barab-szabi-1        |     0.637203 |        4.9224  |   6.76172  |
| k-d_tree_polars      |     0.641021 |        4.94511 |   6.98789  |
| k-d_tree_pandas      |     0.640186 |        3.88304 |   7.25494  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.705354 |        75.0233 |    3.18888 |
| k-d_tree_sklearn     |     1.02712  |       235.283  |    4.18459 |
| Bori_Aron_solution-1 |     0.623585 |       151.235  |   17.3248  |