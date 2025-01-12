# 2025-01-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.71126  |       1e-06    |   0.359968 |
| barab-szabi-2        |     0.571788 |       0.407819 |   0.394477 |
| k-d_tree_polars      |     0.580549 |       0.396829 |   0.39841  |
| barab-szabi-1        |     0.571825 |       0.402581 |   0.402186 |
| Bori_Aron_solution-1 |     0.577051 |       0.528495 |   0.531204 |
| k-d_tree_pandas      |     8.28623  |       0.447732 |   0.638213 |
| k-d_tree_sklearn     |     3.10074  |       1.01854  |   1.01109  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.597679 |       0.402043 |   0.395334 |
| barab-szabi-1        |     0.5936   |       0.407643 |   0.403103 |
| k-d_tree_polars      |     0.586621 |       0.405176 |   0.415926 |
| Bori_Aron_solution-1 |     0.574869 |       0.542471 |   0.536626 |
| k-d_tree_pandas      |     0.580981 |       0.409521 |   0.558696 |
| k-d_tree_sklearn     |     0.586044 |       0.947242 |   1.04539  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586418 |       0.412929 |   0.408341 |
| barab-szabi-1        |     0.582511 |       0.42869  |   0.430513 |
| k-d_tree_polars      |     0.584677 |       0.429235 |   0.431279 |
| Bori_Aron_solution-1 |     0.589183 |       0.575217 |   0.537216 |
| k-d_tree_pandas      |     0.582831 |       0.41508  |   0.594447 |
| k-d_tree_sklearn     |     0.588052 |       0.983765 |   1.11798  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589538 |       0.474953 |   0.442356 |
| k-d_tree_polars      |     0.588503 |       0.530244 |   0.524769 |
| barab-szabi-1        |     0.58837  |       0.538342 |   0.534705 |
| Bori_Aron_solution-1 |     0.579597 |       0.740158 |   0.544109 |
| k-d_tree_pandas      |     0.58473  |       0.475229 |   0.718093 |
| k-d_tree_sklearn     |     0.591465 |       1.20291  |   1.09967  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580023 |       0.716408 |   0.474903 |
| Bori_Aron_solution-1 |     0.578822 |       1.37504  |   0.57461  |
| k-d_tree_polars      |     0.578589 |       0.857391 |   0.878702 |
| barab-szabi-1        |     0.587951 |       0.852182 |   0.909499 |
| k-d_tree_pandas      |     0.582007 |       0.73939  |   1.1585   |
| k-d_tree_sklearn     |     0.585723 |       2.01616  |   1.18743  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588539 |        5.27334 |   0.734685 |
| Bori_Aron_solution-1 |     0.576356 |       10.5344  |   0.864262 |
| k-d_tree_sklearn     |     0.586321 |       15.8856  |   1.29378  |
| k-d_tree_polars      |     0.585364 |        4.75421 |   6.54791  |
| barab-szabi-1        |     0.582225 |        4.80151 |   6.56609  |
| k-d_tree_pandas      |     0.583734 |        3.78171 |   6.96751  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588025 |        75.5375 |    2.92763 |
| k-d_tree_sklearn     |     0.60368  |       227.736  |    4.49393 |
| Bori_Aron_solution-1 |     0.665983 |       146.239  |   19.0799  |