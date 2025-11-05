# 2025-11-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     1.01482  |       0.434127 |   0.4599   |
| barab-szabi-2        |     1.00809  |       1.28785  |   0.461735 |
| barab-szabi-1        |     1.01011  |       0.437292 |   0.467464 |
| Bori_Aron_solution-1 |     0.997825 |       0.584824 |   0.593761 |
| solution-1           |     8.21081  |       2e-06    |   1.08016  |
| k-d_tree_sklearn     |     3.74297  |       1.8644   |   1.17425  |
| k-d_tree_pandas      |     8.81477  |       0.501967 |   1.44246  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |      1.01217 |       0.44684  |   0.466423 |
| barab-szabi-2        |      1.0217  |       0.477407 |   0.494086 |
| k-d_tree_polars      |      1.01151 |       0.448295 |   0.514451 |
| k-d_tree_pandas      |      1.00723 |       0.420278 |   0.610628 |
| Bori_Aron_solution-1 |      1.00714 |       0.613149 |   0.611672 |
| k-d_tree_sklearn     |      1.01459 |       1.10017  |   1.16601  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565851 |       0.46864  |   0.47693  |
| k-d_tree_polars      |     0.575187 |       0.474566 |   0.505538 |
| barab-szabi-1        |     0.574193 |       0.47224  |   0.506633 |
| Bori_Aron_solution-1 |     0.552399 |       0.648248 |   0.598788 |
| k-d_tree_pandas      |     0.694364 |       0.445589 |   0.636875 |
| k-d_tree_sklearn     |     0.561926 |       1.08697  |   1.20209  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561859 |       0.550754 |   0.51837  |
| barab-szabi-1        |     0.554351 |       0.598751 |   0.598621 |
| k-d_tree_polars      |     0.563645 |       0.598396 |   0.611293 |
| Bori_Aron_solution-1 |     0.56124  |       0.843967 |   0.615112 |
| k-d_tree_pandas      |     0.566344 |       0.52619  |   0.779391 |
| k-d_tree_sklearn     |     0.568202 |       1.32778  |   1.2244   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.572768 |       0.806157 |   0.60162  |
| Bori_Aron_solution-1 |     0.553173 |       1.54191  |   0.657916 |
| k-d_tree_polars      |     0.563979 |       0.952145 |   0.970775 |
| barab-szabi-1        |     0.569762 |       0.96983  |   1.02138  |
| k-d_tree_pandas      |     0.58273  |       0.854063 |   1.27734  |
| k-d_tree_sklearn     |     0.567691 |       2.26326  |   1.34119  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559797 |        5.70886 |   0.82127  |
| Bori_Aron_solution-1 |     0.562724 |       11.5997  |   0.888146 |
| k-d_tree_sklearn     |     0.574239 |       18.3618  |   1.41419  |
| k-d_tree_polars      |     0.578722 |        5.52499 |   7.0982   |
| barab-szabi-1        |     0.577148 |        5.52876 |   7.16529  |
| k-d_tree_pandas      |     0.555033 |        4.5432  |   7.49857  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551504 |        77.0878 |    2.8459  |
| k-d_tree_sklearn     |     0.571032 |       252.642  |    4.45265 |
| Bori_Aron_solution-1 |     0.77401  |       152.535  |   18.0485  |