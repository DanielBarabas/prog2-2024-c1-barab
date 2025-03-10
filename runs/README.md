# 2025-03-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590042 |       0.427381 |   0.421261 |
| k-d_tree_polars      |     0.589055 |       0.421661 |   0.421922 |
| solution-1           |     7.34262  |       1e-06    |   0.461482 |
| barab-szabi-1        |     0.585871 |       0.426556 |   0.474235 |
| Bori_Aron_solution-1 |     0.587418 |       0.554463 |   0.559365 |
| k-d_tree_pandas      |     7.91331  |       0.457375 |   0.723147 |
| k-d_tree_sklearn     |     3.24701  |       1.13221  |   1.0469   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.596803 |       0.416423 |   0.41537  |
| barab-szabi-1        |     0.604893 |       0.429515 |   0.418967 |
| k-d_tree_polars      |     0.601584 |       0.418684 |   0.479486 |
| Bori_Aron_solution-1 |     0.598261 |       0.562282 |   0.560379 |
| k-d_tree_pandas      |     0.622043 |       0.411777 |   0.566186 |
| k-d_tree_sklearn     |     0.602904 |       0.98104  |   1.05536  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607074 |       0.441039 |   0.431929 |
| k-d_tree_polars      |     0.599432 |       0.450325 |   0.449119 |
| barab-szabi-1        |     0.605115 |       0.443813 |   0.455974 |
| Bori_Aron_solution-1 |     0.60558  |       0.607223 |   0.561337 |
| k-d_tree_pandas      |     0.602113 |       0.414932 |   0.608193 |
| k-d_tree_sklearn     |     0.602583 |       1.03716  |   1.10996  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.593479 |       0.49107  |   0.453305 |
| k-d_tree_polars      |     0.609875 |       0.553251 |   0.544652 |
| barab-szabi-1        |     0.600569 |       0.556477 |   0.556073 |
| Bori_Aron_solution-1 |     0.608057 |       0.780843 |   0.575855 |
| k-d_tree_pandas      |     0.603756 |       0.490351 |   0.749458 |
| k-d_tree_sklearn     |     0.606899 |       1.25847  |   1.14754  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.595292 |       0.749961 |   0.495117 |
| Bori_Aron_solution-1 |     0.595554 |       1.40196  |   0.606991 |
| k-d_tree_polars      |     0.603037 |       0.883799 |   0.89755  |
| barab-szabi-1        |     0.59613  |       0.880281 |   0.936056 |
| k-d_tree_pandas      |     0.603155 |       0.752381 |   1.18798  |
| k-d_tree_sklearn     |     0.605908 |       2.10233  |   1.26811  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.594736 |        5.55236 |   0.747278 |
| Bori_Aron_solution-1 |     0.593176 |       10.7285  |   0.889279 |
| k-d_tree_sklearn     |     0.603978 |       16.7627  |   1.34071  |
| k-d_tree_polars      |     0.593298 |        4.95075 |   6.71732  |
| barab-szabi-1        |     0.597711 |        4.97001 |   6.76642  |
| k-d_tree_pandas      |     0.607401 |        3.85692 |   7.23185  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.807168 |        75.4476 |    3.55032 |
| k-d_tree_sklearn     |     0.673394 |       236.039  |    4.17707 |
| Bori_Aron_solution-1 |     0.594392 |       157.744  |   15.8321  |