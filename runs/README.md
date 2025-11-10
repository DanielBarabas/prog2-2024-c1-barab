# 2025-11-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527321 |       0.63051  |   0.444873 |
| k-d_tree_polars      |     0.553762 |       0.428123 |   0.454561 |
| barab-szabi-1        |     0.570031 |       0.434243 |   0.457206 |
| solution-1           |     8.13826  |       1e-06    |   0.573878 |
| Bori_Aron_solution-1 |     0.555881 |       0.579919 |   0.581737 |
| k-d_tree_pandas      |    10.0489   |       0.445527 |   0.685814 |
| k-d_tree_sklearn     |     3.39808  |       1.26268  |   1.18142  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.547122 |       0.411273 |   0.433995 |
| barab-szabi-1        |     0.537888 |       0.424893 |   0.444377 |
| barab-szabi-2        |     0.557869 |       0.440232 |   0.445624 |
| Bori_Aron_solution-1 |     0.545381 |       0.564991 |   0.571856 |
| k-d_tree_pandas      |     0.552595 |       0.411848 |   0.578185 |
| k-d_tree_sklearn     |     0.543771 |       1.05405  |   1.09507  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544011 |       0.45735  |   0.450423 |
| k-d_tree_polars      |     0.551351 |       0.46766  |   0.471221 |
| barab-szabi-1        |     0.57513  |       0.497319 |   0.483389 |
| k-d_tree_pandas      |     0.549216 |       0.428609 |   0.626488 |
| Bori_Aron_solution-1 |     0.561755 |       0.65314  |   0.62811  |
| k-d_tree_sklearn     |     0.560939 |       1.08951  |   1.15902  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550506 |       0.519472 |   0.483202 |
| k-d_tree_polars      |     0.575799 |       0.580226 |   0.565388 |
| Bori_Aron_solution-1 |     0.53097  |       0.812369 |   0.582768 |
| barab-szabi-1        |     0.527096 |       0.564211 |   0.595152 |
| k-d_tree_pandas      |     0.576915 |       0.527883 |   0.791393 |
| k-d_tree_sklearn     |     0.54282  |       1.30318  |   1.19188  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553914 |       0.754711 |   0.499422 |
| Bori_Aron_solution-1 |     0.52065  |       1.48657  |   0.5951   |
| k-d_tree_polars      |     0.544275 |       0.922724 |   0.917585 |
| barab-szabi-1        |     0.532827 |       0.94053  |   0.971904 |
| k-d_tree_pandas      |     0.563411 |       0.826395 |   1.21963  |
| k-d_tree_sklearn     |     0.538382 |       2.18503  |   1.23486  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540862 |        5.21387 |   0.745483 |
| Bori_Aron_solution-1 |     0.521983 |       11.1938  |   0.851808 |
| k-d_tree_sklearn     |     0.540848 |       17.6505  |   1.39665  |
| k-d_tree_polars      |     0.533609 |        5.38798 |   6.4682   |
| barab-szabi-1        |     0.549671 |        5.32465 |   6.53933  |
| k-d_tree_pandas      |     0.542519 |        4.53275 |   7.15235  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533178 |        72.7847 |    2.71156 |
| k-d_tree_sklearn     |     0.543471 |       247.153  |    4.21711 |
| Bori_Aron_solution-1 |     0.629447 |       149.246  |   17.2295  |