# 2025-07-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.00811  |       0.791815 |   0.420628 |
| k-d_tree_polars      |     0.553815 |       0.405023 |   0.424588 |
| barab-szabi-1        |     0.538898 |       0.40673  |   0.426621 |
| Bori_Aron_solution-1 |     0.528629 |       0.54493  |   0.543461 |
| k-d_tree_pandas      |     0.556113 |       0.388893 |   0.594389 |
| solution-1           |     8.14929  |       1e-06    |   0.603544 |
| k-d_tree_sklearn     |     3.10104  |       1.17999  |   1.04998  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563643 |       0.42524  |   0.422418 |
| k-d_tree_polars      |     0.557026 |       0.409384 |   0.430401 |
| barab-szabi-1        |     0.561347 |       0.422392 |   0.443174 |
| Bori_Aron_solution-1 |     0.544913 |       0.556899 |   0.554634 |
| k-d_tree_pandas      |     0.560225 |       0.395682 |   0.562418 |
| k-d_tree_sklearn     |     0.560132 |       1.03205  |   1.04532  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566114 |       0.440037 |   0.442466 |
| barab-szabi-1        |     0.564089 |       0.4396   |   0.453669 |
| k-d_tree_polars      |     0.553359 |       0.435796 |   0.454278 |
| Bori_Aron_solution-1 |     0.557368 |       0.591387 |   0.58012  |
| k-d_tree_pandas      |     0.556367 |       0.416687 |   0.60167  |
| k-d_tree_sklearn     |     0.575953 |       1.03015  |   1.0864   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551027 |       0.498402 |   0.463911 |
| k-d_tree_polars      |     0.560862 |       0.555681 |   0.552407 |
| barab-szabi-1        |     0.557913 |       0.588813 |   0.565845 |
| Bori_Aron_solution-1 |     0.548277 |       0.770998 |   0.568283 |
| k-d_tree_pandas      |     0.558742 |       0.495922 |   0.737775 |
| k-d_tree_sklearn     |     0.562027 |       1.28882  |   1.16227  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55096  |       0.747802 |   0.503416 |
| Bori_Aron_solution-1 |     0.546771 |       1.41723  |   0.594217 |
| k-d_tree_polars      |     0.558132 |       0.883155 |   0.916008 |
| barab-szabi-1        |     0.560482 |       0.870879 |   0.942944 |
| k-d_tree_pandas      |     0.565328 |       0.765166 |   1.18853  |
| k-d_tree_sklearn     |     0.555871 |       2.09283  |   1.21244  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552288 |        5.2042  |   0.715579 |
| Bori_Aron_solution-1 |     0.552971 |       10.6364  |   0.833035 |
| k-d_tree_sklearn     |     0.563103 |       16.1835  |   1.31527  |
| k-d_tree_polars      |     0.560677 |        4.98948 |   6.56292  |
| barab-szabi-1        |     0.551294 |        4.96923 |   6.56647  |
| k-d_tree_pandas      |     0.550855 |        3.89064 |   6.95498  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563222 |        73.4074 |    2.67918 |
| k-d_tree_sklearn     |     0.729719 |       225.901  |    3.96719 |
| Bori_Aron_solution-1 |     0.588093 |       141.972  |   18.813   |