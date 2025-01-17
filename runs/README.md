# 2025-01-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.03842  |       0.554945 |   0.398296 |
| barab-szabi-1        |     1.04068  |       0.403233 |   0.401029 |
| k-d_tree_polars      |     0.604276 |       0.409362 |   0.401527 |
| Bori_Aron_solution-1 |     0.585648 |       0.547054 |   0.536552 |
| solution-1           |     8.1708   |       1e-06    |   0.596688 |
| k-d_tree_pandas      |     8.5154   |       0.468845 |   0.77749  |
| k-d_tree_sklearn     |     3.51839  |       1.22264  |   1.01983  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591665 |       0.404768 |   0.400925 |
| k-d_tree_polars      |     0.591993 |       0.41354  |   0.404702 |
| barab-szabi-1        |     0.589117 |       0.408059 |   0.421038 |
| k-d_tree_pandas      |     0.589612 |       0.389022 |   0.546062 |
| Bori_Aron_solution-1 |     0.580464 |       0.54658  |   0.555304 |
| k-d_tree_sklearn     |     0.589973 |       0.941968 |   1.02188  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604643 |       0.413694 |   0.415712 |
| k-d_tree_polars      |     0.587401 |       0.44138  |   0.431551 |
| barab-szabi-1        |     0.592787 |       0.445222 |   0.451579 |
| Bori_Aron_solution-1 |     0.585505 |       0.579016 |   0.546846 |
| k-d_tree_pandas      |     0.588965 |       0.418352 |   0.610819 |
| k-d_tree_sklearn     |     0.592868 |       1.00023  |   1.05629  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.592638 |       0.479348 |   0.439238 |
| k-d_tree_polars      |     0.586102 |       0.544911 |   0.527531 |
| barab-szabi-1        |     0.585148 |       0.537573 |   0.543675 |
| Bori_Aron_solution-1 |     0.580768 |       0.754058 |   0.551303 |
| k-d_tree_pandas      |     0.592527 |       0.485099 |   0.740714 |
| k-d_tree_sklearn     |     0.590492 |       1.20791  |   1.10965  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.596256 |       0.725676 |   0.476324 |
| Bori_Aron_solution-1 |     0.585506 |       1.38072  |   0.583693 |
| k-d_tree_polars      |     0.588495 |       0.864893 |   0.890078 |
| barab-szabi-1        |     0.589067 |       0.872708 |   0.927432 |
| k-d_tree_pandas      |     0.593647 |       0.755868 |   1.19215  |
| k-d_tree_sklearn     |     0.586968 |       2.05824  |   1.2034   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589887 |        5.45201 |   0.729389 |
| Bori_Aron_solution-1 |     0.597417 |       10.975   |   0.916227 |
| k-d_tree_sklearn     |     0.593531 |       16.7224  |   1.32997  |
| barab-szabi-1        |     0.591213 |        4.91204 |   6.67443  |
| k-d_tree_polars      |     0.593425 |        4.96436 |   6.772    |
| k-d_tree_pandas      |     0.602537 |        3.85771 |   7.1054   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625292 |        77.2324 |    2.98355 |
| k-d_tree_sklearn     |     0.615854 |       231.344  |    4.49817 |
| Bori_Aron_solution-1 |     0.707886 |       150.836  |   18.4425  |