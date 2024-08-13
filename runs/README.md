# 2024-08-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.30174  |       0.811433 |   0.389372 |
| k-d_tree_polars      |     0.614859 |       0.405373 |   0.396953 |
| barab-szabi-1        |     0.637602 |       0.408943 |   0.403943 |
| k-d_tree_pandas      |     0.601992 |       0.440345 |   0.535394 |
| Bori_Aron_solution-1 |     0.614891 |       0.532353 |   0.541502 |
| solution-1           |     8.18101  |       1e-06    |   0.576202 |
| k-d_tree_sklearn     |     3.37271  |       1.21599  |   0.719998 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.643365 |       0.395766 |   0.394054 |
| barab-szabi-1        |     0.620533 |       0.432358 |   0.400175 |
| k-d_tree_polars      |     0.61993  |       0.407457 |   0.400737 |
| Bori_Aron_solution-1 |     0.616999 |       0.538121 |   0.532859 |
| k-d_tree_pandas      |     0.621673 |       0.385981 |   0.541898 |
| k-d_tree_sklearn     |     0.634993 |       0.905477 |   0.712056 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625319 |       0.401548 |   0.401253 |
| k-d_tree_polars      |     0.628358 |       0.431827 |   0.418813 |
| barab-szabi-1        |     0.650329 |       0.436249 |   0.427078 |
| Bori_Aron_solution-1 |     0.607695 |       0.568469 |   0.537701 |
| k-d_tree_pandas      |     0.620252 |       0.40345  |   0.573989 |
| k-d_tree_sklearn     |     0.625036 |       0.953309 |   0.735817 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622284 |       0.464682 |   0.427789 |
| k-d_tree_polars      |     0.619574 |       0.543358 |   0.515974 |
| barab-szabi-1        |     0.611792 |       0.537659 |   0.524522 |
| Bori_Aron_solution-1 |     0.612585 |       0.75333  |   0.54948  |
| k-d_tree_pandas      |     0.616408 |       0.483727 |   0.718269 |
| k-d_tree_sklearn     |     0.614616 |       1.18615  |   0.789149 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626212 |       0.742703 |   0.483812 |
| Bori_Aron_solution-1 |     0.632776 |       1.44378  |   0.603769 |
| k-d_tree_polars      |     0.636181 |       0.879073 |   0.902985 |
| k-d_tree_sklearn     |     0.661033 |       2.14325  |   0.931796 |
| barab-szabi-1        |     0.647524 |       0.90455  |   0.978573 |
| k-d_tree_pandas      |     0.633055 |       0.758758 |   1.17364  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.6422   |        5.62908 |   0.773215 |
| Bori_Aron_solution-1 |     0.601972 |       10.7639  |   0.840279 |
| k-d_tree_sklearn     |     0.619109 |       15.422   |   0.974572 |
| barab-szabi-1        |     0.621218 |        4.90137 |   6.55666  |
| k-d_tree_polars      |     0.627559 |        4.92981 |   6.61956  |
| k-d_tree_pandas      |     0.648033 |        3.8838  |   7.09402  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614406 |        75.9699 |    3.04537 |
| k-d_tree_sklearn     |     0.646852 |       228.238  |    3.84156 |
| Bori_Aron_solution-1 |     0.691566 |       143.458  |   18.6682  |