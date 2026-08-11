# 2026-08-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469304 |       0.429793 |   0.43581  |
| barab-szabi-1        |     0.472534 |       0.424122 |   0.450532 |
| solution-1           |     8.3845   |       1e-06    |   0.462766 |
| Bori_Aron_solution-1 |     0.458995 |       0.577664 |   0.568244 |
| k-d_tree_pandas      |     0.473792 |       0.39017  |   0.57001  |
| k-d_tree_polars      |     9.31453  |       0.476161 |   0.806029 |
| k-d_tree_sklearn     |     3.08472  |       1.23127  |   1.08794  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.464468 |       0.424597 |   0.443579 |
| barab-szabi-2        |     0.498172 |       0.469396 |   0.465264 |
| barab-szabi-1        |     0.48842  |       0.444163 |   0.470806 |
| Bori_Aron_solution-1 |     0.477352 |       0.598994 |   0.559298 |
| k-d_tree_pandas      |     0.498759 |       0.445008 |   0.623828 |
| k-d_tree_sklearn     |     0.491415 |       1.05421  |   1.13725  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.499364 |       0.460015 |   0.482893 |
| barab-szabi-1        |     0.494899 |       0.485248 |   0.485629 |
| barab-szabi-2        |     0.492964 |       0.477562 |   0.490372 |
| Bori_Aron_solution-1 |     0.489459 |       0.640516 |   0.59317  |
| k-d_tree_pandas      |     0.492315 |       0.4362   |   0.632279 |
| k-d_tree_sklearn     |     0.499494 |       1.14046  |   1.2037   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473354 |       0.518803 |   0.484619 |
| Bori_Aron_solution-1 |     0.478244 |       0.788379 |   0.573073 |
| barab-szabi-1        |     0.48137  |       0.569015 |   0.582244 |
| k-d_tree_polars      |     0.493674 |       0.613458 |   0.585328 |
| k-d_tree_pandas      |     0.471999 |       0.498916 |   0.718072 |
| k-d_tree_sklearn     |     0.505523 |       1.27769  |   1.15877  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.46556  |       0.770555 |   0.582975 |
| Bori_Aron_solution-1 |     0.475399 |       1.4626   |   0.593254 |
| barab-szabi-1        |     0.469473 |       0.917435 |   0.98173  |
| k-d_tree_polars      |     0.478166 |       0.974208 |   1.00537  |
| k-d_tree_sklearn     |     0.491952 |       2.10942  |   1.16447  |
| k-d_tree_pandas      |     0.466691 |       0.76088  |   1.17029  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487521 |        5.8125  |   0.73826  |
| Bori_Aron_solution-1 |     0.471887 |       11.4398  |   0.844099 |
| k-d_tree_sklearn     |     0.501023 |       18.0743  |   1.34689  |
| barab-szabi-1        |     0.498908 |        5.23384 |   7.61291  |
| k-d_tree_polars      |     0.481583 |        5.0836  |   7.61378  |
| k-d_tree_pandas      |     0.496803 |        3.97024 |   7.95916  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536193 |        79.5332 |    2.66101 |
| k-d_tree_sklearn     |     0.645428 |       258.099  |    3.34273 |
| Bori_Aron_solution-1 |     0.481295 |       156.228  |   23.5565  |