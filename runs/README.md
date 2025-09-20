# 2025-09-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.18594  |       1.1625   |   0.439079 |
| barab-szabi-1        |     0.541358 |       0.410352 |   0.440202 |
| k-d_tree_polars      |     0.573032 |       0.416558 |   0.440486 |
| k-d_tree_pandas      |     0.538866 |       0.396397 |   0.564738 |
| Bori_Aron_solution-1 |     0.529838 |       0.559076 |   0.567282 |
| solution-1           |     7.63112  |       1e-06    |   0.715363 |
| k-d_tree_sklearn     |     3.08788  |       1.30361  |   1.07948  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551518 |       0.438275 |   0.437116 |
| k-d_tree_polars      |     0.554485 |       0.417062 |   0.44045  |
| barab-szabi-1        |     0.55349  |       0.417892 |   0.441823 |
| Bori_Aron_solution-1 |     0.550283 |       0.565367 |   0.561631 |
| k-d_tree_pandas      |     0.556408 |       0.39371  |   0.573639 |
| k-d_tree_sklearn     |     0.555286 |       0.99868  |   1.13945  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563849 |       0.452311 |   0.454185 |
| k-d_tree_polars      |     0.557087 |       0.445734 |   0.463035 |
| barab-szabi-1        |     0.550495 |       0.447183 |   0.464183 |
| Bori_Aron_solution-1 |     0.555492 |       0.604051 |   0.563063 |
| k-d_tree_pandas      |     0.560505 |       0.417485 |   0.618437 |
| k-d_tree_sklearn     |     0.553302 |       1.03824  |   1.11846  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552017 |       0.511753 |   0.478909 |
| k-d_tree_polars      |     0.546826 |       0.559297 |   0.564182 |
| barab-szabi-1        |     0.555302 |       0.555897 |   0.577097 |
| Bori_Aron_solution-1 |     0.542033 |       0.776505 |   0.577409 |
| k-d_tree_pandas      |     0.559012 |       0.493354 |   0.745626 |
| k-d_tree_sklearn     |     0.559494 |       1.28706  |   1.18377  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558824 |       0.766294 |   0.519729 |
| Bori_Aron_solution-1 |     0.545541 |       1.43609  |   0.595962 |
| k-d_tree_polars      |     0.551318 |       0.898666 |   0.926348 |
| barab-szabi-1        |     0.547899 |       0.897879 |   0.965415 |
| k-d_tree_pandas      |     0.54903  |       0.769399 |   1.20095  |
| k-d_tree_sklearn     |     0.557895 |       2.14091  |   1.24389  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54485  |        5.45705 |   0.768363 |
| Bori_Aron_solution-1 |     0.548311 |       10.8342  |   0.853918 |
| k-d_tree_sklearn     |     0.560554 |       16.7523  |   1.35085  |
| k-d_tree_polars      |     0.554017 |        5.06266 |   6.75796  |
| barab-szabi-1        |     0.551676 |        5.05706 |   6.763    |
| k-d_tree_pandas      |     0.552907 |        3.96214 |   7.1367   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552072 |        76.0224 |    2.74847 |
| k-d_tree_sklearn     |     1.12795  |       238.777  |    4.0648  |
| Bori_Aron_solution-1 |     0.549568 |       144.821  |   17.2856  |