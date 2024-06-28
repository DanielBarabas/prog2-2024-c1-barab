# 2024-06-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536155 |       0.383443 |   0.38024  |
| k-d_tree_polars      |     0.541868 |       0.391314 |   0.392271 |
| barab-szabi-1        |     0.555382 |       0.401114 |   0.394274 |
| solution-1           |     7.87745  |       1e-06    |   0.431312 |
| Bori_Aron_solution-1 |     0.530638 |       0.515128 |   0.514362 |
| k-d_tree_pandas      |     8.22585  |       0.393343 |   0.597376 |
| k-d_tree_sklearn     |     3.11912  |       0.961373 |   0.723658 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54875  |       0.386272 |   0.383064 |
| barab-szabi-1        |     0.578443 |       0.400997 |   0.396728 |
| k-d_tree_polars      |     0.571008 |       0.413248 |   0.39877  |
| Bori_Aron_solution-1 |     0.556944 |       0.536633 |   0.523043 |
| k-d_tree_pandas      |     0.563167 |       0.383375 |   0.529965 |
| k-d_tree_sklearn     |     0.555393 |       0.927405 |   0.73634  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555863 |       0.403693 |   0.401677 |
| barab-szabi-1        |     0.566746 |       0.421221 |   0.418905 |
| k-d_tree_polars      |     0.550297 |       0.424688 |   0.420403 |
| Bori_Aron_solution-1 |     0.549455 |       0.598719 |   0.523157 |
| k-d_tree_pandas      |     0.565379 |       0.405238 |   0.581351 |
| k-d_tree_sklearn     |     0.560268 |       0.969604 |   0.770777 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.592054 |       0.482527 |   0.448836 |
| k-d_tree_polars      |     0.55136  |       0.53206  |   0.52037  |
| barab-szabi-1        |     0.567538 |       0.53867  |   0.540522 |
| Bori_Aron_solution-1 |     0.551093 |       0.781618 |   0.574414 |
| k-d_tree_pandas      |     0.551825 |       0.47662  |   0.701061 |
| k-d_tree_sklearn     |     0.569522 |       1.19189  |   0.84226  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563655 |       0.731936 |   0.514203 |
| Bori_Aron_solution-1 |     0.573368 |       1.42042  |   0.557961 |
| k-d_tree_polars      |     0.564845 |       0.873314 |   0.913674 |
| k-d_tree_sklearn     |     0.561416 |       2.05702  |   0.954648 |
| barab-szabi-1        |     0.568252 |       0.871799 |   0.966784 |
| k-d_tree_pandas      |     0.558388 |       0.741109 |   1.18981  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554247 |        5.62824 |   0.765693 |
| Bori_Aron_solution-1 |     0.547849 |       10.9321  |   0.869255 |
| k-d_tree_sklearn     |     0.562598 |       16.6892  |   1.16155  |
| k-d_tree_polars      |     0.563468 |        4.84094 |   6.72004  |
| barab-szabi-1        |     0.59117  |        4.82422 |   6.88301  |
| k-d_tree_pandas      |     0.57346  |        3.88615 |   7.09751  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.759728 |        74.6784 |    4.01268 |
| k-d_tree_sklearn     |     0.634366 |       231.694  |    4.55905 |
| Bori_Aron_solution-1 |     0.557778 |       155.241  |   16.3142  |