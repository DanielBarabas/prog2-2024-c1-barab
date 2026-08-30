# 2026-08-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.68692  |       1e-06    |   0.405425 |
| barab-szabi-2        |     4.97974  |       0.484596 |   0.437731 |
| k-d_tree_polars      |     0.457031 |       0.417493 |   0.438167 |
| barab-szabi-1        |     0.453483 |       0.419895 |   0.44369  |
| Bori_Aron_solution-1 |     5.12785  |       0.655795 |   0.4736   |
| k-d_tree_pandas      |     0.463639 |       0.38859  |   0.543426 |
| k-d_tree_sklearn     |     3.22029  |       1.11389  |   1.05128  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.46226  |       0.422441 |   0.441471 |
| barab-szabi-2        |     0.461762 |       0.43711  |   0.441762 |
| k-d_tree_polars      |     0.463553 |       0.419459 |   0.446562 |
| Bori_Aron_solution-1 |     0.461761 |       0.544036 |   0.555443 |
| k-d_tree_pandas      |     0.463576 |       0.389007 |   0.572632 |
| k-d_tree_sklearn     |     0.470112 |       0.998065 |   1.07363  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462335 |       0.452317 |   0.444649 |
| barab-szabi-1        |     0.463201 |       0.452016 |   0.468941 |
| k-d_tree_polars      |     0.465277 |       0.450994 |   0.469421 |
| Bori_Aron_solution-1 |     0.457551 |       0.594468 |   0.544647 |
| k-d_tree_pandas      |     0.464041 |       0.405738 |   0.578367 |
| k-d_tree_sklearn     |     0.469793 |       1.03214  |   1.07366  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462223 |       0.51164  |   0.475492 |
| Bori_Aron_solution-1 |     0.457227 |       0.777134 |   0.562333 |
| k-d_tree_polars      |     0.464004 |       0.572432 |   0.565139 |
| barab-szabi-1        |     0.462508 |       0.558945 |   0.575964 |
| k-d_tree_pandas      |     0.460853 |       0.489331 |   0.713271 |
| k-d_tree_sklearn     |     0.464196 |       1.27289  |   1.11694  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462928 |       0.759706 |   0.507904 |
| Bori_Aron_solution-1 |     0.453725 |       1.45278  |   0.576724 |
| k-d_tree_polars      |     0.465394 |       0.911446 |   0.939207 |
| barab-szabi-1        |     0.462618 |       0.909051 |   0.987102 |
| k-d_tree_sklearn     |     0.465638 |       2.1053   |   1.15841  |
| k-d_tree_pandas      |     0.465265 |       0.771898 |   1.16429  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460625 |        5.68246 |   0.741882 |
| Bori_Aron_solution-1 |     0.458995 |       11.4265  |   0.808176 |
| k-d_tree_sklearn     |     0.466751 |       17.131   |   1.2356   |
| barab-szabi-1        |     0.461297 |        5.1933  |   7.54678  |
| k-d_tree_polars      |     0.463213 |        5.09807 |   7.56948  |
| k-d_tree_pandas      |     0.461081 |        4.0422  |   7.91016  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.72429  |        81.4658 |    2.81759 |
| k-d_tree_sklearn     |     0.566826 |       263.23   |    3.28442 |
| Bori_Aron_solution-1 |     0.456832 |       165.822  |   15.9877  |