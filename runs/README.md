# 2025-07-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.548523 |       0.395315 |   0.414011 |
| barab-szabi-2        |     7.95512  |       0.588477 |   0.416697 |
| solution-1           |     7.34748  |       1e-06    |   0.425358 |
| barab-szabi-1        |     0.538166 |       0.395051 |   0.465944 |
| Bori_Aron_solution-1 |     0.532608 |       0.540552 |   0.535063 |
| k-d_tree_pandas      |     0.547739 |       0.378146 |   0.538154 |
| k-d_tree_sklearn     |     2.96729  |       1.15162  |   1.02844  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544625 |       0.415954 |   0.413985 |
| k-d_tree_polars      |     0.547675 |       0.412422 |   0.421057 |
| barab-szabi-1        |     0.547332 |       0.408354 |   0.425156 |
| Bori_Aron_solution-1 |     0.540493 |       0.541148 |   0.53913  |
| k-d_tree_pandas      |     0.544339 |       0.382831 |   0.550838 |
| k-d_tree_sklearn     |     0.550509 |       0.952624 |   1.02951  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549302 |       0.432352 |   0.437399 |
| k-d_tree_polars      |     0.549554 |       0.432323 |   0.446606 |
| barab-szabi-1        |     0.549456 |       0.429445 |   0.453813 |
| Bori_Aron_solution-1 |     0.544694 |       0.583973 |   0.543627 |
| k-d_tree_pandas      |     0.546437 |       0.401085 |   0.613308 |
| k-d_tree_sklearn     |     0.549913 |       1.02814  |   1.08342  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56417  |       0.499457 |   0.464646 |
| k-d_tree_polars      |     0.549925 |       0.544305 |   0.544469 |
| Bori_Aron_solution-1 |     0.546453 |       0.762213 |   0.561124 |
| barab-szabi-1        |     0.556159 |       0.546482 |   0.56349  |
| k-d_tree_pandas      |     0.553057 |       0.488232 |   0.73385  |
| k-d_tree_sklearn     |     0.553842 |       1.22511  |   1.11389  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550342 |       0.731526 |   0.490515 |
| Bori_Aron_solution-1 |     0.543149 |       1.38306  |   0.576541 |
| k-d_tree_polars      |     0.550458 |       0.902003 |   0.902238 |
| barab-szabi-1        |     0.546826 |       0.880522 |   0.926828 |
| k-d_tree_pandas      |     0.558272 |       0.75805  |   1.17902  |
| k-d_tree_sklearn     |     0.55358  |       2.04945  |   1.1965   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547376 |        5.17816 |   0.741146 |
| Bori_Aron_solution-1 |     0.553565 |       10.5759  |   0.83951  |
| k-d_tree_sklearn     |     0.555315 |       15.6306  |   1.28562  |
| barab-szabi-1        |     0.554778 |        4.97834 |   6.46826  |
| k-d_tree_polars      |     0.549572 |        5.0492  |   6.54041  |
| k-d_tree_pandas      |     0.550215 |        3.95378 |   6.79184  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547233 |        73.8632 |    2.71383 |
| k-d_tree_sklearn     |     0.747116 |       227.648  |    3.93297 |
| Bori_Aron_solution-1 |     0.570491 |       146.361  |   17.6902  |