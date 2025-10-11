# 2025-10-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567434 |       0.77196  |   0.44536  |
| k-d_tree_polars      |     0.580298 |       0.43304  |   0.459509 |
| barab-szabi-1        |     0.626369 |       0.439358 |   0.459667 |
| Bori_Aron_solution-1 |     0.571443 |       0.580966 |   0.587674 |
| solution-1           |     7.72439  |       1e-06    |   0.906237 |
| k-d_tree_pandas      |     8.26499  |       0.474077 |   0.97326  |
| k-d_tree_sklearn     |     3.15984  |       1.40122  |   1.17492  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587481 |       0.464533 |   0.467305 |
| barab-szabi-1        |     0.57794  |       0.453109 |   0.472345 |
| k-d_tree_polars      |     0.585996 |       0.445143 |   0.484567 |
| k-d_tree_pandas      |     0.582808 |       0.431171 |   0.610458 |
| Bori_Aron_solution-1 |     0.583187 |       0.610829 |   0.627807 |
| k-d_tree_sklearn     |     0.584131 |       1.0837   |   1.1726   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579655 |       0.469827 |   0.469512 |
| k-d_tree_polars      |     0.582685 |       0.469842 |   0.485039 |
| barab-szabi-1        |     0.600338 |       0.471957 |   0.496379 |
| Bori_Aron_solution-1 |     0.583215 |       0.640677 |   0.594516 |
| k-d_tree_pandas      |     0.57697  |       0.440702 |   0.638448 |
| k-d_tree_sklearn     |     0.58475  |       1.15766  |   1.18945  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581467 |       0.539033 |   0.50609  |
| k-d_tree_polars      |     0.579664 |       0.58756  |   0.589406 |
| barab-szabi-1        |     0.581908 |       0.588901 |   0.596121 |
| Bori_Aron_solution-1 |     0.571234 |       0.839758 |   0.601762 |
| k-d_tree_pandas      |     0.580245 |       0.550559 |   0.783195 |
| k-d_tree_sklearn     |     0.583498 |       1.35599  |   1.22657  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577121 |       0.795308 |   0.617314 |
| Bori_Aron_solution-1 |     0.575952 |       1.55157  |   0.624722 |
| k-d_tree_polars      |     0.58637  |       0.991295 |   0.984381 |
| barab-szabi-1        |     0.579657 |       0.971255 |   1.02108  |
| k-d_tree_pandas      |     0.578098 |       0.843712 |   1.24822  |
| k-d_tree_sklearn     |     0.59433  |       2.30259  |   1.31702  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583714 |        5.77797 |   0.787824 |
| Bori_Aron_solution-1 |     0.571239 |       11.8115  |   0.898889 |
| k-d_tree_sklearn     |     0.58593  |       18.6071  |   1.42601  |
| barab-szabi-1        |     0.584971 |        5.72902 |   7.14626  |
| k-d_tree_polars      |     0.593969 |        5.73857 |   7.21357  |
| k-d_tree_pandas      |     0.584215 |        4.65661 |   7.5408   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577852 |         79.019 |    2.85725 |
| k-d_tree_sklearn     |     0.581385 |        250.434 |    4.19565 |
| Bori_Aron_solution-1 |     0.807023 |        154.803 |   17.0197  |