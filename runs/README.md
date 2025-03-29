# 2025-03-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545153 |       0.408103 |   0.400964 |
| solution-1           |     7.65777  |       1e-06    |   0.402997 |
| k-d_tree_polars      |     0.544614 |       0.398457 |   0.405728 |
| barab-szabi-1        |     0.546664 |       0.407995 |   0.438059 |
| Bori_Aron_solution-1 |     0.536119 |       0.535224 |   0.534495 |
| k-d_tree_pandas      |     7.90247  |       0.407355 |   0.628624 |
| k-d_tree_sklearn     |     2.98309  |       1.03228  |   1.06827  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558209 |       0.409212 |   0.402911 |
| barab-szabi-1        |     0.561664 |       0.407169 |   0.411044 |
| k-d_tree_polars      |     0.571731 |       0.405414 |   0.411869 |
| Bori_Aron_solution-1 |     0.551877 |       0.547427 |   0.538091 |
| k-d_tree_pandas      |     0.556789 |       0.384344 |   0.544967 |
| k-d_tree_sklearn     |     0.561495 |       0.945184 |   1.03208  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.556302 |       0.428194 |   0.432219 |
| barab-szabi-2        |     0.557621 |       0.420714 |   0.437832 |
| barab-szabi-1        |     0.559048 |       0.429921 |   0.454277 |
| Bori_Aron_solution-1 |     0.551375 |       0.580346 |   0.545587 |
| k-d_tree_pandas      |     0.559374 |       0.40074  |   0.594293 |
| k-d_tree_sklearn     |     0.565887 |       0.99512  |   1.05766  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560922 |       0.480858 |   0.44537  |
| k-d_tree_polars      |     0.558286 |       0.534312 |   0.53261  |
| barab-szabi-1        |     0.560781 |       0.533362 |   0.541411 |
| Bori_Aron_solution-1 |     0.551205 |       0.771418 |   0.556486 |
| k-d_tree_pandas      |     0.555793 |       0.471825 |   0.724548 |
| k-d_tree_sklearn     |     0.559563 |       1.20263  |   1.09394  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565505 |       0.731552 |   0.476282 |
| Bori_Aron_solution-1 |     0.549363 |       1.38331  |   0.58421  |
| k-d_tree_polars      |     0.560522 |       0.865637 |   0.885405 |
| barab-szabi-1        |     0.559705 |       0.862892 |   0.928647 |
| k-d_tree_pandas      |     0.559288 |       0.739792 |   1.16637  |
| k-d_tree_sklearn     |     0.56069  |       2.07616  |   1.19825  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562363 |        5.27419 |   0.713787 |
| Bori_Aron_solution-1 |     0.560769 |       10.5546  |   0.872942 |
| k-d_tree_sklearn     |     0.565738 |       15.7067  |   1.29133  |
| barab-szabi-1        |     0.562905 |        4.83818 |   6.51205  |
| k-d_tree_polars      |     0.561098 |        4.94011 |   6.574    |
| k-d_tree_pandas      |     0.560771 |        3.82909 |   6.95887  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.753112 |        74.5685 |    3.44701 |
| k-d_tree_sklearn     |     0.672345 |       227.483  |    4.3054  |
| Bori_Aron_solution-1 |     0.548788 |       162.176  |   14.8511  |