# 2026-08-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.93837  |       1e-06    |   0.428359 |
| barab-szabi-1        |     0.47455  |       0.446484 |   0.454183 |
| barab-szabi-2        |     5.04057  |       0.512716 |   0.455552 |
| k-d_tree_polars      |     0.465735 |       0.439679 |   0.463383 |
| Bori_Aron_solution-1 |     4.82674  |       0.775845 |   0.50786  |
| k-d_tree_pandas      |     0.476211 |       0.410354 |   0.590673 |
| k-d_tree_sklearn     |     3.11148  |       1.36748  |   1.22471  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.482021 |       0.430968 |   0.446532 |
| barab-szabi-2        |     0.487986 |       0.45349  |   0.451672 |
| k-d_tree_polars      |     0.475545 |       0.425362 |   0.455128 |
| Bori_Aron_solution-1 |     0.49182  |       0.583285 |   0.563489 |
| k-d_tree_pandas      |     0.47721  |       0.398898 |   0.5659   |
| k-d_tree_sklearn     |     0.492164 |       1.01819  |   1.07972  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474751 |       0.476945 |   0.451514 |
| k-d_tree_polars      |     0.480355 |       0.465989 |   0.46549  |
| barab-szabi-1        |     0.4773   |       0.467754 |   0.474621 |
| Bori_Aron_solution-1 |     0.463238 |       0.610211 |   0.559438 |
| k-d_tree_pandas      |     0.475583 |       0.426288 |   0.600854 |
| k-d_tree_sklearn     |     0.472296 |       1.0597   |   1.11764  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485002 |       0.521108 |   0.479539 |
| k-d_tree_polars      |     0.474148 |       0.566537 |   0.570481 |
| Bori_Aron_solution-1 |     0.470609 |       0.802828 |   0.586036 |
| barab-szabi-1        |     0.464606 |       0.562079 |   0.586441 |
| k-d_tree_pandas      |     0.470316 |       0.494929 |   0.720597 |
| k-d_tree_sklearn     |     0.476552 |       1.30634  |   1.14467  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484416 |       0.782305 |   0.566936 |
| Bori_Aron_solution-1 |     0.467762 |       1.48306  |   0.595393 |
| k-d_tree_polars      |     0.475045 |       0.90563  |   0.973053 |
| barab-szabi-1        |     0.476768 |       0.894217 |   1.00661  |
| k-d_tree_sklearn     |     0.481532 |       2.18256  |   1.18893  |
| k-d_tree_pandas      |     0.480735 |       0.771433 |   1.19735  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481716 |        5.50025 |   0.718555 |
| Bori_Aron_solution-1 |     0.46189  |       11.2523  |   0.823357 |
| k-d_tree_sklearn     |     0.464418 |       16.493   |   1.24775  |
| k-d_tree_polars      |     0.457397 |        5.08216 |   7.20395  |
| barab-szabi-1        |     0.464856 |        5.0963  |   7.21702  |
| k-d_tree_pandas      |     0.467175 |        4.02135 |   7.51325  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.670462 |        77.2832 |    2.54044 |
| k-d_tree_sklearn     |     0.552927 |       259.965  |    3.30303 |
| Bori_Aron_solution-1 |     0.45752  |       150.605  |   22.5454  |