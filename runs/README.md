# 2026-02-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.90946  |       1e-06    |   0.363852 |
| barab-szabi-2        |     0.479403 |       0.447467 |   0.426009 |
| barab-szabi-1        |     0.492088 |       0.409967 |   0.433433 |
| k-d_tree_polars      |     0.494087 |       0.40651  |   0.443897 |
| Bori_Aron_solution-1 |     0.490334 |       0.547409 |   0.550749 |
| k-d_tree_pandas      |     8.39331  |       0.414155 |   0.581981 |
| k-d_tree_sklearn     |     3.26842  |       1.11168  |   1.06655  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.490929 |       0.439706 |   0.431492 |
| k-d_tree_polars      |     0.491595 |       0.411869 |   0.437736 |
| barab-szabi-1        |     0.488971 |       0.414497 |   0.443723 |
| Bori_Aron_solution-1 |     0.481565 |       0.558636 |   0.551238 |
| k-d_tree_pandas      |     0.49724  |       0.390355 |   0.557845 |
| k-d_tree_sklearn     |     0.49238  |       0.99068  |   1.07548  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486138 |       0.45094  |   0.446343 |
| k-d_tree_polars      |     0.492582 |       0.440657 |   0.461665 |
| barab-szabi-1        |     0.49665  |       0.440503 |   0.467953 |
| k-d_tree_pandas      |     0.501933 |       0.41133  |   0.595815 |
| Bori_Aron_solution-1 |     0.486438 |       0.592848 |   0.598299 |
| k-d_tree_sklearn     |     0.49875  |       1.02664  |   1.12547  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.493562 |       0.508958 |   0.47517  |
| k-d_tree_polars      |     0.49087  |       0.56141  |   0.561264 |
| Bori_Aron_solution-1 |     0.48477  |       0.780525 |   0.565987 |
| barab-szabi-1        |     0.493928 |       0.562328 |   0.572061 |
| k-d_tree_pandas      |     0.489892 |       0.500746 |   0.742759 |
| k-d_tree_sklearn     |     0.515258 |       1.27567  |   1.14344  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487737 |       0.741889 |   0.50463  |
| Bori_Aron_solution-1 |     0.482142 |       1.47158  |   0.597432 |
| k-d_tree_polars      |     0.489193 |       0.938492 |   0.925833 |
| barab-szabi-1        |     0.522721 |       0.939301 |   0.975662 |
| k-d_tree_pandas      |     0.493233 |       0.814742 |   1.19491  |
| k-d_tree_sklearn     |     0.494878 |       2.27167  |   1.30028  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.517511 |        5.34274 |   0.756924 |
| Bori_Aron_solution-1 |     0.479726 |       11.3161  |   0.843678 |
| k-d_tree_sklearn     |     0.495752 |       17.3177  |   1.33998  |
| k-d_tree_polars      |     0.488425 |        5.62843 |   6.76081  |
| barab-szabi-1        |     0.496812 |        5.59404 |   6.8717   |
| k-d_tree_pandas      |     0.489735 |        4.4912  |   7.26088  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.489275 |        73.8966 |    2.83586 |
| k-d_tree_sklearn     |     0.500397 |       243.997  |    4.087   |
| Bori_Aron_solution-1 |     0.610646 |       151.82   |   18.0731  |