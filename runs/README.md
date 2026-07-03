# 2026-07-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.63447  |       1e-06    |   0.371578 |
| barab-szabi-2        |     8.5247   |       0.48879  |   0.441407 |
| k-d_tree_polars      |     0.465106 |       0.415257 |   0.446942 |
| barab-szabi-1        |     0.461206 |       0.4027   |   0.453038 |
| k-d_tree_pandas      |     0.47024  |       0.383613 |   0.542293 |
| Bori_Aron_solution-1 |     0.454775 |       0.541372 |   0.545891 |
| k-d_tree_sklearn     |     3.19518  |       1.09077  |   1.08864  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466888 |       0.439185 |   0.442372 |
| k-d_tree_polars      |     0.469663 |       0.418487 |   0.450422 |
| barab-szabi-1        |     0.46779  |       0.418869 |   0.454913 |
| Bori_Aron_solution-1 |     0.476432 |       0.552258 |   0.548093 |
| k-d_tree_pandas      |     0.478702 |       0.394676 |   0.563102 |
| k-d_tree_sklearn     |     0.47064  |       0.984568 |   1.08631  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476104 |       0.455153 |   0.460232 |
| barab-szabi-1        |     0.479014 |       0.465186 |   0.476347 |
| k-d_tree_polars      |     0.480689 |       0.451396 |   0.482863 |
| Bori_Aron_solution-1 |     0.48569  |       0.597038 |   0.557678 |
| k-d_tree_pandas      |     0.472952 |       0.413291 |   0.607376 |
| k-d_tree_sklearn     |     0.494352 |       1.06081  |   1.1279   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47346  |       0.515216 |   0.486478 |
| Bori_Aron_solution-1 |     0.467132 |       0.777996 |   0.572117 |
| k-d_tree_polars      |     0.474945 |       0.581876 |   0.572724 |
| barab-szabi-1        |     0.478154 |       0.577375 |   0.591698 |
| k-d_tree_pandas      |     0.470052 |       0.496499 |   0.737455 |
| k-d_tree_sklearn     |     0.484107 |       1.29046  |   1.13178  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467694 |       0.731824 |   0.509708 |
| Bori_Aron_solution-1 |     0.46202  |       1.43207  |   0.57754  |
| k-d_tree_polars      |     0.47034  |       0.919323 |   0.918056 |
| barab-szabi-1        |     0.467125 |       0.897452 |   0.961917 |
| k-d_tree_pandas      |     0.488543 |       0.813224 |   1.23553  |
| k-d_tree_sklearn     |     0.473869 |       2.15596  |   1.27638  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49013  |        4.9786  |    0.78839 |
| Bori_Aron_solution-1 |     0.467732 |       10.7542  |    0.8208  |
| k-d_tree_sklearn     |     0.482048 |       15.9606  |    1.29936 |
| k-d_tree_polars      |     0.479805 |        5.2597  |    6.47359 |
| barab-szabi-1        |     0.491383 |        5.36276 |    6.49383 |
| k-d_tree_pandas      |     0.469733 |        4.28062 |    6.81708 |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469378 |        70.0308 |    2.75128 |
| k-d_tree_sklearn     |     0.682084 |       244.59   |    4.14141 |
| Bori_Aron_solution-1 |     0.470933 |       148.523  |   17.8197  |