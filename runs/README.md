# 2024-12-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.7508   |       1e-06    |   0.364881 |
| barab-szabi-2        |     0.625434 |       0.397214 |   0.387139 |
| barab-szabi-1        |     0.618386 |       0.40264  |   0.393622 |
| k-d_tree_polars      |     0.627615 |       0.410831 |   0.394753 |
| Bori_Aron_solution-1 |     0.609046 |       0.520474 |   0.513999 |
| k-d_tree_pandas      |     0.618344 |       0.383673 |   0.52404  |
| k-d_tree_sklearn     |    10.4307   |       1.00458  |   0.969646 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623411 |       0.40542  |   0.387778 |
| k-d_tree_polars      |     0.624614 |       0.409549 |   0.402359 |
| barab-szabi-1        |     0.630618 |       0.418923 |   0.403144 |
| Bori_Aron_solution-1 |     0.614457 |       0.536728 |   0.522262 |
| k-d_tree_pandas      |     0.614327 |       0.392594 |   0.541286 |
| k-d_tree_sklearn     |     0.627205 |       0.899662 |   0.982139 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625795 |       0.413892 |   0.403224 |
| barab-szabi-1        |     0.614602 |       0.42797  |   0.422565 |
| k-d_tree_polars      |     0.638184 |       0.440587 |   0.430156 |
| Bori_Aron_solution-1 |     0.610783 |       0.566394 |   0.530749 |
| k-d_tree_pandas      |     0.617776 |       0.404635 |   0.592729 |
| k-d_tree_sklearn     |     0.624712 |       0.9704   |   1.05405  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619277 |       0.464103 |   0.432721 |
| k-d_tree_polars      |     0.62273  |       0.544122 |   0.515748 |
| barab-szabi-1        |     0.611207 |       0.542093 |   0.532011 |
| Bori_Aron_solution-1 |     0.620167 |       0.749225 |   0.5548   |
| k-d_tree_pandas      |     0.623378 |       0.487315 |   0.715348 |
| k-d_tree_sklearn     |     0.626166 |       1.19917  |   1.07228  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618948 |       0.723459 |   0.46911  |
| Bori_Aron_solution-1 |     0.618742 |       1.42432  |   0.582184 |
| k-d_tree_polars      |     0.619129 |       0.855077 |   0.867138 |
| barab-szabi-1        |     0.610442 |       0.865582 |   0.915578 |
| k-d_tree_pandas      |     0.632717 |       0.745959 |   1.17416  |
| k-d_tree_sklearn     |     0.625639 |       2.11338  |   1.18898  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617366 |        5.75139 |   0.754007 |
| Bori_Aron_solution-1 |     0.611419 |       10.8961  |   0.815808 |
| k-d_tree_sklearn     |     0.631595 |       16.1652  |   1.2543   |
| barab-szabi-1        |     0.638833 |        4.89474 |   6.62693  |
| k-d_tree_polars      |     0.614269 |        4.8668  |   6.63022  |
| k-d_tree_pandas      |     0.61656  |        3.90763 |   7.11737  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.637713 |        70.6248 |    2.96711 |
| k-d_tree_sklearn     |     0.64034  |       225.825  |    4.23397 |
| Bori_Aron_solution-1 |     0.659878 |       150.841  |   18.4995  |