# 2025-07-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549466 |       0.417753 |   0.419509 |
| barab-szabi-1        |     0.559963 |       0.402661 |   0.419612 |
| k-d_tree_polars      |     0.552656 |       0.400871 |   0.42338  |
| solution-1           |     7.2693   |       1e-06    |   0.43608  |
| Bori_Aron_solution-1 |     0.546224 |       0.544695 |   0.538579 |
| k-d_tree_pandas      |     0.553537 |       0.382225 |   0.552703 |
| k-d_tree_sklearn     |    10.0445   |       1.23103  |   1.07596  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552623 |       0.422803 |   0.421114 |
| k-d_tree_polars      |     0.552351 |       0.409719 |   0.427399 |
| barab-szabi-1        |     0.551466 |       0.413571 |   0.427622 |
| Bori_Aron_solution-1 |     0.544297 |       0.5551   |   0.544298 |
| k-d_tree_pandas      |     0.564507 |       0.383341 |   0.554173 |
| k-d_tree_sklearn     |     0.584588 |       0.979544 |   1.05732  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54552  |       0.436172 |   0.432875 |
| barab-szabi-1        |     0.550597 |       0.430714 |   0.451661 |
| k-d_tree_polars      |     0.553179 |       0.434729 |   0.474316 |
| Bori_Aron_solution-1 |     0.554818 |       0.609709 |   0.550554 |
| k-d_tree_pandas      |     0.575444 |       0.406385 |   0.602233 |
| k-d_tree_sklearn     |     0.554083 |       1.00271  |   1.08119  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550884 |       0.492919 |   0.464374 |
| k-d_tree_polars      |     0.554535 |       0.546608 |   0.554401 |
| Bori_Aron_solution-1 |     0.547893 |       0.760119 |   0.558359 |
| barab-szabi-1        |     0.559869 |       0.547294 |   0.55942  |
| k-d_tree_pandas      |     0.555866 |       0.486277 |   0.732133 |
| k-d_tree_sklearn     |     0.551998 |       1.24585  |   1.12139  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556316 |       0.738571 |   0.495964 |
| Bori_Aron_solution-1 |     0.577648 |       1.38779  |   0.585868 |
| k-d_tree_polars      |     0.556262 |       0.876871 |   0.905303 |
| barab-szabi-1        |     0.55073  |       0.875654 |   0.932215 |
| k-d_tree_pandas      |     0.550866 |       0.75803  |   1.17352  |
| k-d_tree_sklearn     |     0.557737 |       2.05586  |   1.21008  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551384 |        5.13504 |   0.74335  |
| Bori_Aron_solution-1 |     0.545089 |       10.5192  |   0.838949 |
| k-d_tree_sklearn     |     0.558575 |       15.7493  |   1.30921  |
| k-d_tree_polars      |     0.55651  |        4.98057 |   6.47629  |
| barab-szabi-1        |     0.558391 |        4.95916 |   6.49497  |
| k-d_tree_pandas      |     0.549855 |        3.96406 |   6.92086  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563489 |        79.9366 |    2.84848 |
| k-d_tree_sklearn     |     0.55462  |       230.198  |    3.93324 |
| Bori_Aron_solution-1 |     0.582125 |       141.703  |   18.2677  |