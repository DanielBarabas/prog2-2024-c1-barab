# 2024-09-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.620132 |       0.401078 |   0.396233 |
| barab-szabi-2        |     0.6214   |       0.401484 |   0.409244 |
| solution-1           |     7.43916  |       1e-06    |   0.442705 |
| k-d_tree_polars      |     4.10494  |       0.475162 |   0.4503   |
| Bori_Aron_solution-1 |     4.3329   |       0.68415  |   0.459187 |
| k-d_tree_pandas      |     0.602234 |       0.383983 |   0.540131 |
| k-d_tree_sklearn     |     3.02375  |       1.06788  |   0.974329 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61609  |       0.399386 |   0.393888 |
| k-d_tree_polars      |     0.618284 |       0.406737 |   0.400761 |
| barab-szabi-1        |     0.612971 |       0.402412 |   0.404104 |
| Bori_Aron_solution-1 |     0.611549 |       0.5364   |   0.531121 |
| k-d_tree_pandas      |     0.621387 |       0.385253 |   0.546797 |
| k-d_tree_sklearn     |     0.619836 |       0.898736 |   0.98317  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617251 |       0.405212 |   0.401852 |
| k-d_tree_polars      |     0.630763 |       0.428792 |   0.422005 |
| barab-szabi-1        |     0.623127 |       0.429067 |   0.427449 |
| Bori_Aron_solution-1 |     0.610879 |       0.566338 |   0.52872  |
| k-d_tree_pandas      |     0.617273 |       0.4012   |   0.585002 |
| k-d_tree_sklearn     |     0.633451 |       0.962898 |   1.03174  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613443 |       0.470168 |   0.437377 |
| k-d_tree_polars      |     0.62342  |       0.538601 |   0.525583 |
| barab-szabi-1        |     0.6126   |       0.533452 |   0.530421 |
| Bori_Aron_solution-1 |     0.612975 |       0.752171 |   0.545519 |
| k-d_tree_pandas      |     0.628685 |       0.478661 |   0.72295  |
| k-d_tree_sklearn     |     0.622261 |       1.16798  |   1.04568  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616254 |       0.714595 |   0.462518 |
| Bori_Aron_solution-1 |     0.607756 |       1.38897  |   0.566618 |
| k-d_tree_polars      |     0.617423 |       0.850835 |   0.860249 |
| barab-szabi-1        |     0.617313 |       0.857431 |   0.903587 |
| k-d_tree_sklearn     |     0.625888 |       1.97843  |   1.14304  |
| k-d_tree_pandas      |     0.613711 |       0.745968 |   1.15669  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614684 |        5.34167 |   0.741545 |
| Bori_Aron_solution-1 |     0.611144 |       10.7623  |   0.830033 |
| k-d_tree_sklearn     |     0.616091 |       16.1757  |   1.27706  |
| barab-szabi-1        |     0.61664  |        4.8452  |   6.55948  |
| k-d_tree_polars      |     0.619596 |        4.87748 |   6.63861  |
| k-d_tree_pandas      |     0.611992 |        3.8844  |   6.99512  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.775136 |        70.6736 |    3.82869 |
| k-d_tree_sklearn     |     1.04798  |       226.479  |    4.50885 |
| Bori_Aron_solution-1 |     0.606875 |       153.338  |   15.5323  |