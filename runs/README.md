# 2025-08-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.538619 |       0.399925 |   0.419082 |
| barab-szabi-2        |     0.527727 |       0.416759 |   0.4242   |
| solution-1           |     7.332    |       1e-06    |   0.437224 |
| barab-szabi-1        |     0.525337 |       0.414376 |   0.473713 |
| Bori_Aron_solution-1 |     0.528382 |       0.536388 |   0.542799 |
| k-d_tree_pandas      |     8.19959  |       0.419862 |   0.643267 |
| k-d_tree_sklearn     |     3.15339  |       1.19865  |   1.04574  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536964 |       0.418893 |   0.424788 |
| k-d_tree_polars      |     0.539702 |       0.408766 |   0.428966 |
| barab-szabi-1        |     0.536476 |       0.409944 |   0.432047 |
| Bori_Aron_solution-1 |     0.533499 |       0.548384 |   0.537627 |
| k-d_tree_pandas      |     0.544001 |       0.443187 |   0.549282 |
| k-d_tree_sklearn     |     0.54323  |       0.967336 |   1.05921  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537181 |       0.430729 |   0.441236 |
| barab-szabi-1        |     0.539777 |       0.430861 |   0.45435  |
| k-d_tree_polars      |     0.540121 |       0.432343 |   0.455581 |
| Bori_Aron_solution-1 |     0.53175  |       0.59024  |   0.55033  |
| k-d_tree_pandas      |     0.53863  |       0.41201  |   0.596061 |
| k-d_tree_sklearn     |     0.543535 |       1.04851  |   1.07653  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540978 |       0.493879 |   0.464072 |
| k-d_tree_polars      |     0.540085 |       0.546045 |   0.549124 |
| Bori_Aron_solution-1 |     0.531883 |       0.757951 |   0.554585 |
| barab-szabi-1        |     0.544263 |       0.549879 |   0.567378 |
| k-d_tree_pandas      |     0.543878 |       0.484214 |   0.726484 |
| k-d_tree_sklearn     |     0.538666 |       1.23703  |   1.14852  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535062 |       0.740459 |   0.497565 |
| Bori_Aron_solution-1 |     0.533257 |       1.40223  |   0.583027 |
| k-d_tree_polars      |     0.539593 |       0.885367 |   0.899039 |
| barab-szabi-1        |     0.541388 |       0.885569 |   0.944442 |
| k-d_tree_pandas      |     0.541356 |       0.763524 |   1.17087  |
| k-d_tree_sklearn     |     0.543801 |       2.06029  |   1.20264  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540204 |        5.24731 |   0.742214 |
| Bori_Aron_solution-1 |     0.533356 |       10.5721  |   0.847485 |
| k-d_tree_sklearn     |     0.548717 |       15.9512  |   1.31466  |
| barab-szabi-1        |     0.537724 |        5.01145 |   6.51494  |
| k-d_tree_polars      |     0.540757 |        4.9915  |   6.51847  |
| k-d_tree_pandas      |     0.533849 |        3.94382 |   6.90798  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539469 |        72.3327 |    2.81006 |
| k-d_tree_sklearn     |     0.550451 |       232.875  |    4.16412 |
| Bori_Aron_solution-1 |     0.61024  |       150.531  |   15.0344  |