# 2025-03-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.563189 |       0.407768 |   0.42041  |
| barab-szabi-2        |     0.561366 |       0.428734 |   0.438536 |
| barab-szabi-1        |     0.567892 |       0.433055 |   0.499187 |
| Bori_Aron_solution-1 |     0.571729 |       0.560793 |   0.559715 |
| solution-1           |     7.5259   |       1e-06    |   0.568298 |
| k-d_tree_pandas      |     7.97246  |       0.459771 |   0.751007 |
| k-d_tree_sklearn     |     3.02078  |       1.2145   |   1.11917  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.580254 |       0.426594 |   0.421375 |
| barab-szabi-2        |     0.577773 |       0.419462 |   0.422911 |
| barab-szabi-1        |     0.587339 |       0.417717 |   0.425804 |
| k-d_tree_pandas      |     0.593507 |       0.396859 |   0.595544 |
| Bori_Aron_solution-1 |     0.568131 |       0.580268 |   0.612807 |
| k-d_tree_sklearn     |     0.585537 |       1.02994  |   1.12279  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.597035 |       0.448981 |   0.454378 |
| barab-szabi-2        |     0.578133 |       0.441616 |   0.457572 |
| barab-szabi-1        |     0.589939 |       0.453501 |   0.461384 |
| Bori_Aron_solution-1 |     0.574235 |       0.673328 |   0.60524  |
| k-d_tree_pandas      |     0.591709 |       0.41416  |   0.614326 |
| k-d_tree_sklearn     |     0.617477 |       1.04037  |   1.10039  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590637 |       0.49619  |   0.460226 |
| k-d_tree_polars      |     0.600785 |       0.551997 |   0.551678 |
| barab-szabi-1        |     0.592911 |       0.586747 |   0.601923 |
| Bori_Aron_solution-1 |     0.596133 |       0.832723 |   0.622116 |
| k-d_tree_pandas      |     0.609305 |       0.522074 |   0.772367 |
| k-d_tree_sklearn     |     0.588314 |       1.25709  |   1.15759  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.583343 |       1.43023  |   0.609754 |
| barab-szabi-2        |     0.57444  |       0.804569 |   0.610439 |
| k-d_tree_polars      |     0.588029 |       0.872285 |   0.907051 |
| barab-szabi-1        |     0.572989 |       0.884786 |   0.99322  |
| k-d_tree_pandas      |     0.576636 |       0.758732 |   1.2065   |
| k-d_tree_sklearn     |     0.598058 |       2.11855  |   1.25071  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.582755 |        5.35372 |   0.746462 |
| Bori_Aron_solution-1 |     0.563342 |       10.6639  |   0.884415 |
| k-d_tree_sklearn     |     0.571622 |       16.3206  |   1.33494  |
| k-d_tree_polars      |     0.574293 |        4.9234  |   6.66225  |
| barab-szabi-1        |     0.574672 |        4.9173  |   6.68009  |
| k-d_tree_pandas      |     0.585181 |        3.84253 |   7.07368  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.899845 |        76.0069 |    3.46388 |
| k-d_tree_sklearn     |     0.696236 |       237.818  |    4.27724 |
| Bori_Aron_solution-1 |     0.570445 |       155.764  |   14.0605  |