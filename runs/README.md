# 2025-06-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.80261  |       1e-06    |   0.396398 |
| k-d_tree_polars      |     0.551839 |       0.409975 |   0.42467  |
| barab-szabi-2        |     0.565378 |       0.420331 |   0.425206 |
| barab-szabi-1        |     8.15562  |       0.441234 |   0.473551 |
| k-d_tree_pandas      |     0.558997 |       0.384771 |   0.55381  |
| Bori_Aron_solution-1 |     0.538806 |       0.556025 |   0.567869 |
| k-d_tree_sklearn     |     3.00189  |       1.01863  |   1.05358  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569291 |       0.437357 |   0.424146 |
| k-d_tree_polars      |     0.55799  |       0.416159 |   0.428365 |
| barab-szabi-1        |     0.555099 |       0.410184 |   0.43188  |
| Bori_Aron_solution-1 |     0.566583 |       0.585527 |   0.558327 |
| k-d_tree_pandas      |     0.559412 |       0.395531 |   0.578569 |
| k-d_tree_sklearn     |     0.56338  |       0.991298 |   1.07519  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554923 |       0.435259 |   0.432719 |
| k-d_tree_polars      |     0.561713 |       0.450088 |   0.458086 |
| barab-szabi-1        |     0.55702  |       0.439883 |   0.461385 |
| Bori_Aron_solution-1 |     0.57253  |       0.598988 |   0.568328 |
| k-d_tree_pandas      |     0.553995 |       0.420724 |   0.601775 |
| k-d_tree_sklearn     |     0.570001 |       1.04617  |   1.11025  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557333 |       0.511642 |   0.47354  |
| k-d_tree_polars      |     0.562922 |       0.577542 |   0.566429 |
| barab-szabi-1        |     0.558329 |       0.555113 |   0.575501 |
| Bori_Aron_solution-1 |     0.563509 |       0.791008 |   0.583194 |
| k-d_tree_pandas      |     0.574484 |       0.508432 |   0.756989 |
| k-d_tree_sklearn     |     0.572042 |       1.29078  |   1.1703   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563692 |       0.753393 |   0.501703 |
| Bori_Aron_solution-1 |     0.553799 |       1.47191  |   0.607419 |
| k-d_tree_polars      |     0.559656 |       0.884271 |   0.921552 |
| barab-szabi-1        |     0.574838 |       0.891355 |   0.965528 |
| k-d_tree_pandas      |     0.57031  |       0.774957 |   1.20326  |
| k-d_tree_sklearn     |     0.571051 |       2.13135  |   1.29813  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559239 |        5.33668 |   0.727269 |
| Bori_Aron_solution-1 |     0.550108 |       10.8544  |   0.873112 |
| k-d_tree_sklearn     |     0.570062 |       16.4859  |   1.34067  |
| k-d_tree_polars      |     0.559593 |        5.0203  |   6.62363  |
| barab-szabi-1        |     0.560207 |        4.94023 |   6.68025  |
| k-d_tree_pandas      |     0.558395 |        3.98839 |   7.0709   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623642 |        72.3466 |    2.78218 |
| k-d_tree_sklearn     |     0.819628 |       237.005  |    4.27369 |
| Bori_Aron_solution-1 |     0.562201 |       145.3    |   17.8431  |