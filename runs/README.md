# 2024-08-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.93345  |       0.510631 |   0.395271 |
| k-d_tree_polars      |     0.609837 |       0.399207 |   0.399674 |
| barab-szabi-1        |     0.604537 |       0.407809 |   0.401808 |
| solution-1           |     7.63356  |       1e-06    |   0.425063 |
| k-d_tree_pandas      |     0.621945 |       0.4192   |   0.527469 |
| Bori_Aron_solution-1 |     0.622491 |       0.540158 |   0.536739 |
| k-d_tree_sklearn     |     2.96839  |       0.968    |   0.723713 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.626939 |       0.411489 |   0.400491 |
| barab-szabi-2        |     0.632416 |       0.404675 |   0.403069 |
| barab-szabi-1        |     0.61711  |       0.427177 |   0.419171 |
| Bori_Aron_solution-1 |     0.623962 |       0.542192 |   0.543511 |
| k-d_tree_pandas      |     0.629551 |       0.386483 |   0.547877 |
| k-d_tree_sklearn     |     0.645295 |       0.943722 |   0.717558 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625514 |       0.403356 |   0.416235 |
| k-d_tree_polars      |     0.625463 |       0.441717 |   0.428395 |
| barab-szabi-1        |     0.625004 |       0.451433 |   0.43196  |
| Bori_Aron_solution-1 |     0.61636  |       0.580005 |   0.55322  |
| k-d_tree_pandas      |     0.639685 |       0.417799 |   0.590142 |
| k-d_tree_sklearn     |     0.622244 |       0.983146 |   0.767793 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.635045 |       0.479416 |   0.435922 |
| k-d_tree_polars      |     0.629792 |       0.546345 |   0.529828 |
| barab-szabi-1        |     0.62268  |       0.545179 |   0.537981 |
| Bori_Aron_solution-1 |     0.627479 |       0.765069 |   0.540687 |
| k-d_tree_pandas      |     0.623509 |       0.488142 |   0.745533 |
| k-d_tree_sklearn     |     0.629349 |       1.22094  |   0.79607  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619733 |       0.730334 |   0.473713 |
| Bori_Aron_solution-1 |     0.61957  |       1.41792  |   0.578547 |
| k-d_tree_polars      |     0.619637 |       0.882459 |   0.886447 |
| k-d_tree_sklearn     |     0.621694 |       2.02596  |   0.895114 |
| barab-szabi-1        |     0.616099 |       0.888597 |   0.923199 |
| k-d_tree_pandas      |     0.623509 |       0.77588  |   1.17891  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.630369 |        6.02586 |   0.829694 |
| Bori_Aron_solution-1 |     0.610602 |       11.3891  |   0.90147  |
| k-d_tree_sklearn     |     0.646003 |       17.4525  |   1.01004  |
| k-d_tree_polars      |     0.627669 |        5.03261 |   7.30819  |
| barab-szabi-1        |     0.624756 |        4.88515 |   7.39989  |
| k-d_tree_pandas      |     0.632011 |        3.95834 |   7.58152  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627432 |        88.0882 |    3.82439 |
| k-d_tree_sklearn     |     0.662011 |       264.137  |    4.13252 |
| Bori_Aron_solution-1 |     0.69454  |       163.174  |   17.5062  |