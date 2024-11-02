# 2024-11-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.613315 |       0.39533  |   0.38521  |
| barab-szabi-2        |     0.615884 |       0.396412 |   0.385428 |
| barab-szabi-1        |     0.614239 |       0.39985  |   0.393658 |
| solution-1           |     7.49023  |       1e-06    |   0.405826 |
| Bori_Aron_solution-1 |     0.606806 |       0.515806 |   0.522651 |
| k-d_tree_pandas      |     0.62182  |       0.386393 |   0.534207 |
| k-d_tree_sklearn     |    10.273    |       1.09684  |   0.963179 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61249  |       0.394884 |   0.387972 |
| barab-szabi-1        |     0.608594 |       0.401716 |   0.389217 |
| k-d_tree_polars      |     0.609654 |       0.40841  |   0.392842 |
| Bori_Aron_solution-1 |     0.618002 |       0.52503  |   0.519277 |
| k-d_tree_pandas      |     0.614685 |       0.383564 |   0.526423 |
| k-d_tree_sklearn     |     0.627056 |       0.881768 |   0.983977 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615248 |       0.402658 |   0.398871 |
| k-d_tree_polars      |     0.612921 |       0.4292   |   0.418551 |
| barab-szabi-1        |     0.619388 |       0.425898 |   0.43242  |
| Bori_Aron_solution-1 |     0.608266 |       0.557874 |   0.515426 |
| k-d_tree_pandas      |     0.610687 |       0.405244 |   0.56885  |
| k-d_tree_sklearn     |     0.621286 |       0.931007 |   0.978392 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609902 |       0.461902 |   0.428106 |
| k-d_tree_polars      |     0.608413 |       0.528762 |   0.514115 |
| barab-szabi-1        |     0.615968 |       0.53455  |   0.529505 |
| Bori_Aron_solution-1 |     0.602091 |       0.738935 |   0.540572 |
| k-d_tree_pandas      |     0.607954 |       0.479164 |   0.700751 |
| k-d_tree_sklearn     |     0.642212 |       1.14949  |   1.04797  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614862 |       0.723688 |   0.461165 |
| Bori_Aron_solution-1 |     0.604381 |       1.37867  |   0.557141 |
| k-d_tree_polars      |     0.613573 |       0.869415 |   0.870341 |
| barab-szabi-1        |     0.61091  |       0.856535 |   0.916533 |
| k-d_tree_sklearn     |     0.619619 |       1.98298  |   1.13467  |
| k-d_tree_pandas      |     0.617479 |       0.748451 |   1.1379   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616188 |        5.24165 |   0.767175 |
| Bori_Aron_solution-1 |     0.609685 |       10.5501  |   0.822183 |
| k-d_tree_sklearn     |     0.612952 |       16.0664  |   1.24859  |
| barab-szabi-1        |     0.623207 |        4.81426 |   6.41873  |
| k-d_tree_polars      |     0.624772 |        4.92485 |   6.46237  |
| k-d_tree_pandas      |     0.619592 |        3.897   |   6.84422  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.624783 |        72.4459 |    2.98581 |
| k-d_tree_sklearn     |     0.62246  |       226.62   |    4.26593 |
| Bori_Aron_solution-1 |     0.61701  |       147.796  |   15.9184  |