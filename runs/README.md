# 2025-09-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.76365  |       1e-06    |   0.418714 |
| barab-szabi-2        |     8.10243  |       0.591054 |   0.420327 |
| k-d_tree_polars      |     0.530409 |       0.398514 |   0.421171 |
| barab-szabi-1        |     0.525727 |       0.404329 |   0.42326  |
| Bori_Aron_solution-1 |     0.518489 |       0.544549 |   0.53811  |
| k-d_tree_pandas      |     0.528387 |       0.442584 |   0.555993 |
| k-d_tree_sklearn     |     2.99784  |       1.05509  |   1.06934  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.548594 |       0.412106 |   0.429256 |
| barab-szabi-2        |     0.548154 |       0.423067 |   0.429518 |
| barab-szabi-1        |     0.544861 |       0.419006 |   0.4409   |
| Bori_Aron_solution-1 |     0.540392 |       0.556939 |   0.552981 |
| k-d_tree_pandas      |     0.544485 |       0.39291  |   0.568186 |
| k-d_tree_sklearn     |     0.550683 |       0.972702 |   1.06605  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545817 |       0.443    |   0.442303 |
| barab-szabi-1        |     0.542369 |       0.435532 |   0.462082 |
| k-d_tree_polars      |     0.545534 |       0.44189  |   0.473912 |
| Bori_Aron_solution-1 |     0.536696 |       0.594819 |   0.547364 |
| k-d_tree_pandas      |     0.547387 |       0.41243  |   0.609711 |
| k-d_tree_sklearn     |     0.544143 |       1.01469  |   1.07432  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543661 |       0.502934 |   0.466159 |
| k-d_tree_polars      |     0.539877 |       0.54729  |   0.547719 |
| Bori_Aron_solution-1 |     0.534067 |       0.765266 |   0.552407 |
| barab-szabi-1        |     0.537576 |       0.544985 |   0.568071 |
| k-d_tree_pandas      |     0.541754 |       0.484721 |   0.734568 |
| k-d_tree_sklearn     |     0.544648 |       1.23709  |   1.11682  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540311 |       0.744861 |   0.497897 |
| Bori_Aron_solution-1 |     0.531405 |       1.39279  |   0.587099 |
| k-d_tree_polars      |     0.539749 |       0.880152 |   0.908554 |
| barab-szabi-1        |     0.554682 |       0.907764 |   0.988077 |
| k-d_tree_pandas      |     0.539497 |       0.757315 |   1.17346  |
| k-d_tree_sklearn     |     0.558951 |       2.09187  |   1.21989  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557129 |        5.24205 |   0.754579 |
| Bori_Aron_solution-1 |     0.563205 |       10.8987  |   0.88372  |
| k-d_tree_sklearn     |     0.549109 |       15.6017  |   1.31817  |
| barab-szabi-1        |     0.54675  |        5.01326 |   6.31459  |
| k-d_tree_polars      |     0.571073 |        5.03715 |   6.57951  |
| k-d_tree_pandas      |     0.576955 |        3.91054 |   7.10431  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539034 |        76.3623 |    2.75986 |
| k-d_tree_sklearn     |     0.685581 |       229.392  |    4.0238  |
| Bori_Aron_solution-1 |     0.586962 |       146.596  |   17.0487  |