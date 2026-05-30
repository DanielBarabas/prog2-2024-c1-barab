# 2026-05-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574941 |       0.44743  |   0.451405 |
| k-d_tree_polars      |     0.475791 |       0.414572 |   0.453519 |
| solution-1           |     8.74602  |       1e-06    |   0.457327 |
| k-d_tree_pandas      |     0.471255 |       0.395794 |   0.562835 |
| Bori_Aron_solution-1 |     0.457906 |       0.558264 |   0.564667 |
| barab-szabi-1        |     9.28735  |       0.483738 |   0.617969 |
| k-d_tree_sklearn     |     3.13678  |       1.18685  |   1.09835  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.477508 |       0.421309 |   0.449199 |
| barab-szabi-2        |     0.476045 |       0.444985 |   0.449629 |
| barab-szabi-1        |     0.480308 |       0.412297 |   0.456163 |
| Bori_Aron_solution-1 |     0.470911 |       0.566778 |   0.554722 |
| k-d_tree_pandas      |     0.47974  |       0.4025   |   0.576854 |
| k-d_tree_sklearn     |     0.474376 |       0.989574 |   1.10029  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473595 |       0.456375 |   0.45999  |
| k-d_tree_polars      |     0.47526  |       0.447169 |   0.481421 |
| barab-szabi-1        |     0.471146 |       0.450808 |   0.482653 |
| Bori_Aron_solution-1 |     0.467094 |       0.60899  |   0.562976 |
| k-d_tree_pandas      |     0.476008 |       0.415461 |   0.602724 |
| k-d_tree_sklearn     |     0.479807 |       1.04746  |   1.10115  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48341  |       0.507497 |   0.493343 |
| Bori_Aron_solution-1 |     0.46923  |       0.778949 |   0.564907 |
| k-d_tree_polars      |     0.475248 |       0.587047 |   0.583957 |
| barab-szabi-1        |     0.47288  |       0.565138 |   0.589457 |
| k-d_tree_pandas      |     0.475493 |       0.510082 |   0.759156 |
| k-d_tree_sklearn     |     0.481546 |       1.29076  |   1.16104  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474293 |       0.741762 |   0.523115 |
| Bori_Aron_solution-1 |     0.473297 |       1.46828  |   0.598498 |
| k-d_tree_polars      |     0.475306 |       0.939956 |   0.945958 |
| barab-szabi-1        |     0.47261  |       0.934528 |   0.978814 |
| k-d_tree_pandas      |     0.473404 |       0.850765 |   1.19567  |
| k-d_tree_sklearn     |     0.477885 |       2.1505   |   1.2368   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470348 |        5.06467 |   0.754198 |
| Bori_Aron_solution-1 |     0.461715 |       10.9912  |   0.819656 |
| k-d_tree_sklearn     |     0.483166 |       16.9982  |   1.31653  |
| k-d_tree_polars      |     0.476511 |        5.5258  |   6.67855  |
| barab-szabi-1        |     0.471007 |        5.51898 |   6.70631  |
| k-d_tree_pandas      |     0.478438 |        4.4606  |   7.06571  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476716 |        71.6433 |    2.78779 |
| k-d_tree_sklearn     |     0.804543 |       239.534  |    3.93684 |
| Bori_Aron_solution-1 |     0.481084 |       148.189  |   26.1674  |