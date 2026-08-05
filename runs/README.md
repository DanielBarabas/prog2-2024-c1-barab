# 2026-08-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.48121  |       1e-06    |   0.40044  |
| barab-szabi-2        |     0.460079 |       0.429198 |   0.424485 |
| barab-szabi-1        |     0.459445 |       0.402404 |   0.438589 |
| k-d_tree_polars      |     8.43122  |       0.451659 |   0.519968 |
| Bori_Aron_solution-1 |     0.460672 |       0.527152 |   0.525991 |
| k-d_tree_pandas      |     0.464584 |       0.375737 |   0.534381 |
| k-d_tree_sklearn     |     2.95137  |       1.10376  |   1.04112  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460623 |       0.427152 |   0.427641 |
| barab-szabi-1        |     0.459556 |       0.433222 |   0.438315 |
| k-d_tree_polars      |     0.459116 |       0.423966 |   0.475111 |
| Bori_Aron_solution-1 |     0.455412 |       0.53529  |   0.532316 |
| k-d_tree_pandas      |     0.458997 |       0.382023 |   0.537558 |
| k-d_tree_sklearn     |     0.467027 |       0.975841 |   1.03914  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.459664 |       0.440246 |   0.432779 |
| barab-szabi-1        |     0.460742 |       0.45698  |   0.462976 |
| k-d_tree_polars      |     0.459936 |       0.445369 |   0.464315 |
| Bori_Aron_solution-1 |     0.456264 |       0.57751  |   0.53481  |
| k-d_tree_pandas      |     0.45923  |       0.396976 |   0.569623 |
| k-d_tree_sklearn     |     0.46554  |       1.02626  |   1.05574  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.459459 |       0.512003 |   0.464941 |
| Bori_Aron_solution-1 |     0.451596 |       0.766822 |   0.546438 |
| k-d_tree_polars      |     0.460764 |       0.552711 |   0.55858  |
| barab-szabi-1        |     0.459461 |       0.558551 |   0.574973 |
| k-d_tree_pandas      |     0.463654 |       0.481469 |   0.700376 |
| k-d_tree_sklearn     |     0.4628   |       1.25909  |   1.09968  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456385 |       0.753632 |   0.506296 |
| Bori_Aron_solution-1 |     0.453102 |       1.43563  |   0.564254 |
| k-d_tree_polars      |     0.458195 |       0.885013 |   0.946003 |
| barab-szabi-1        |     0.458898 |       0.879838 |   0.978209 |
| k-d_tree_sklearn     |     0.463317 |       2.08537  |   1.13683  |
| k-d_tree_pandas      |     0.460588 |       0.761271 |   1.15797  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456539 |        5.25381 |   0.692672 |
| Bori_Aron_solution-1 |     0.450889 |       10.9743  |   0.782178 |
| k-d_tree_sklearn     |     0.459003 |       16.2156  |   1.20642  |
| barab-szabi-1        |     0.45761  |        5.01997 |   7.14637  |
| k-d_tree_polars      |     0.456649 |        4.98652 |   7.14985  |
| k-d_tree_pandas      |     0.457802 |        3.98831 |   7.4913   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546605 |        73.7093 |    2.56184 |
| k-d_tree_sklearn     |     0.744337 |       248.823  |    3.37812 |
| Bori_Aron_solution-1 |     0.455261 |       150.444  |   21.8693  |