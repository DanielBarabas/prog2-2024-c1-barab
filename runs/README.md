# 2024-04-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.742193 |       0.406612 |   0.345885 |
| barab-szabi-2        |     0.736823 |       0.346808 |   0.358968 |
| k-d_tree_pandas      |     0.71058  |       0.394483 |   0.494391 |
| k-d_tree_polars      |     8.67233  |       0.550245 |   0.511694 |
| Bori_Aron_solution-1 |     0.743442 |       0.492496 |   0.515969 |
| k-d_tree_sklearn     |     3.41522  |       1.2418   |   0.677448 |
| solution-1           |     8.33994  |       1e-06    |   0.760535 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.745498 |       0.3573   |   0.344731 |
| k-d_tree_polars      |     0.74626  |       0.425606 |   0.350212 |
| barab-szabi-1        |     0.740022 |       0.409721 |   0.356971 |
| k-d_tree_pandas      |     0.742594 |       0.387557 |   0.499668 |
| Bori_Aron_solution-1 |     0.726001 |       0.508301 |   0.518593 |
| k-d_tree_sklearn     |     0.750306 |       0.884018 |   0.696591 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.741095 |       0.373196 |   0.373583 |
| k-d_tree_polars      |     0.75495  |       0.44645  |   0.38171  |
| barab-szabi-1        |     0.762417 |       0.447838 |   0.404053 |
| Bori_Aron_solution-1 |     0.737035 |       0.541342 |   0.497045 |
| k-d_tree_pandas      |     0.741403 |       0.434309 |   0.559159 |
| k-d_tree_sklearn     |     0.760387 |       0.887887 |   0.712288 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.744692 |       0.431783 |   0.386435 |
| k-d_tree_polars      |     0.755951 |       0.557323 |   0.481514 |
| barab-szabi-1        |     0.736327 |       0.556696 |   0.495024 |
| Bori_Aron_solution-1 |     0.745096 |       0.705048 |   0.501046 |
| k-d_tree_pandas      |     0.765497 |       0.481758 |   0.666781 |
| k-d_tree_sklearn     |     0.746344 |       1.13166  |   0.763894 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.735949 |       0.705012 |   0.450945 |
| Bori_Aron_solution-1 |     0.758797 |       1.41564  |   0.542464 |
| k-d_tree_sklearn     |     0.756661 |       1.93646  |   0.851263 |
| k-d_tree_polars      |     0.741326 |       0.88452  |   0.8655   |
| barab-szabi-1        |     0.752433 |       0.887179 |   0.910546 |
| k-d_tree_pandas      |     0.754164 |       0.761062 |   1.11636  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.929419 |        5.29057 |   0.723426 |
| Bori_Aron_solution-1 |     0.730951 |       10.9987  |   0.795776 |
| k-d_tree_sklearn     |     0.741099 |       17.0543  |   1.08811  |
| barab-szabi-1        |     0.731488 |        4.76615 |   6.65666  |
| k-d_tree_polars      |     0.758607 |        4.85384 |   6.7532   |
| k-d_tree_pandas      |     0.745565 |        3.90565 |   7.29083  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.87823  |        75.7855 |    3.88676 |
| k-d_tree_sklearn     |     0.75919  |       245.364  |    5.17893 |
| Bori_Aron_solution-1 |     0.793031 |       143.059  |   16.0423  |