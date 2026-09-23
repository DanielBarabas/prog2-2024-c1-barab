# 2026-09-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.414685 |       0.420971 |   0.421322 |
| k-d_tree_polars      |     0.414451 |       0.38864  |   0.424159 |
| Bori_Aron_solution-1 |     0.40636  |       0.504563 |   0.50551  |
| k-d_tree_pandas      |     0.412599 |       0.361129 |   0.512899 |
| solution-1           |     7.12797  |       1e-06    |   0.585306 |
| barab-szabi-1        |     9.27522  |       0.519966 |   0.626945 |
| k-d_tree_sklearn     |     2.85847  |       1.18402  |   0.982461 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.461197 |       0.443622 |   0.423084 |
| k-d_tree_polars      |     0.429958 |       0.39754  |   0.430566 |
| barab-szabi-2        |     0.425506 |       0.451892 |   0.439734 |
| Bori_Aron_solution-1 |     0.420119 |       0.519145 |   0.514414 |
| k-d_tree_pandas      |     0.422257 |       0.368371 |   0.516736 |
| k-d_tree_sklearn     |     0.434842 |       0.896607 |   1.0383   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.419177 |       0.430013 |   0.415186 |
| k-d_tree_polars      |     0.426676 |       0.421311 |   0.448014 |
| barab-szabi-1        |     0.424585 |       0.430096 |   0.45013  |
| Bori_Aron_solution-1 |     0.417527 |       0.551989 |   0.517481 |
| k-d_tree_pandas      |     0.423733 |       0.389619 |   0.555737 |
| k-d_tree_sklearn     |     0.423877 |       1.00185  |   0.9924   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.418517 |       0.483158 |   0.458201 |
| k-d_tree_polars      |     0.422583 |       0.544053 |   0.527532 |
| Bori_Aron_solution-1 |     0.416517 |       0.746119 |   0.528023 |
| barab-szabi-1        |     0.421685 |       0.535341 |   0.534396 |
| k-d_tree_pandas      |     0.421164 |       0.462287 |   0.65549  |
| k-d_tree_sklearn     |     0.433279 |       1.17878  |   1.02053  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.423204 |       0.695431 |   0.490142 |
| Bori_Aron_solution-1 |     0.420234 |       1.28993  |   0.559664 |
| k-d_tree_polars      |     0.423038 |       0.894484 |   0.838911 |
| barab-szabi-1        |     0.417895 |       0.896059 |   0.869355 |
| k-d_tree_pandas      |     0.422265 |       0.712225 |   1.03612  |
| k-d_tree_sklearn     |     0.426399 |       1.989    |   1.0834   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.421919 |        4.30511 |   0.672518 |
| Bori_Aron_solution-1 |     0.413781 |        9.3957  |   0.8533   |
| k-d_tree_sklearn     |     0.426655 |       14.3188  |   1.19084  |
| k-d_tree_polars      |     0.424314 |        5.13949 |   5.69944  |
| barab-szabi-1        |     0.418592 |        5.34658 |   5.73052  |
| k-d_tree_pandas      |     0.425019 |        3.68149 |   6.07476  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.688302 |        65.4442 |    2.45246 |
| k-d_tree_sklearn     |     0.572141 |       179.42   |    3.72438 |
| Bori_Aron_solution-1 |     0.411843 |       172.612  |   27.0243  |