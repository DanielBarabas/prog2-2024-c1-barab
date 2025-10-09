# 2025-10-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.554297 |       0.403786 |   0.42609  |
| barab-szabi-2        |     0.529239 |       0.60236  |   0.429729 |
| barab-szabi-1        |     0.546406 |       0.434251 |   0.441055 |
| solution-1           |     7.63538  |       1e-06    |   0.544867 |
| Bori_Aron_solution-1 |     0.534853 |       0.543116 |   0.549352 |
| k-d_tree_pandas      |     8.04513  |       0.440649 |   0.74451  |
| k-d_tree_sklearn     |     3.14682  |       1.15531  |   1.05482  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.550467 |       0.427061 |   0.438679 |
| barab-szabi-2        |     0.549937 |       0.426313 |   0.439032 |
| barab-szabi-1        |     0.550555 |       0.41903  |   0.44456  |
| Bori_Aron_solution-1 |     0.547288 |       0.561354 |   0.550347 |
| k-d_tree_pandas      |     0.547282 |       0.400555 |   0.558034 |
| k-d_tree_sklearn     |     0.560647 |       1.01291  |   1.07526  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549761 |       0.446571 |   0.450085 |
| barab-szabi-1        |     0.5556   |       0.452894 |   0.460454 |
| k-d_tree_polars      |     0.549928 |       0.453588 |   0.466923 |
| Bori_Aron_solution-1 |     0.546821 |       0.610574 |   0.574564 |
| k-d_tree_pandas      |     0.546695 |       0.417201 |   0.62125  |
| k-d_tree_sklearn     |     0.556035 |       1.02425  |   1.088    |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544043 |       0.500587 |   0.468993 |
| k-d_tree_polars      |     0.54939  |       0.579298 |   0.559375 |
| Bori_Aron_solution-1 |     0.542084 |       0.794018 |   0.563799 |
| barab-szabi-1        |     0.562265 |       0.604166 |   0.579048 |
| k-d_tree_pandas      |     0.555146 |       0.511322 |   0.741269 |
| k-d_tree_sklearn     |     0.554425 |       1.28618  |   1.14998  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550232 |       0.76908  |   0.507738 |
| Bori_Aron_solution-1 |     0.548711 |       1.47934  |   0.591446 |
| k-d_tree_polars      |     0.547134 |       0.952481 |   0.925125 |
| barab-szabi-1        |     0.554018 |       0.960672 |   0.964562 |
| k-d_tree_pandas      |     0.550308 |       0.807459 |   1.20267  |
| k-d_tree_sklearn     |     0.553687 |       2.16243  |   1.21993  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547678 |        5.36636 |   0.735443 |
| Bori_Aron_solution-1 |     0.544353 |       11.3838  |   0.860814 |
| k-d_tree_sklearn     |     0.549295 |       16.8847  |   1.33624  |
| k-d_tree_polars      |     0.552375 |        5.63998 |   6.67385  |
| barab-szabi-1        |     0.545907 |        5.73836 |   6.72655  |
| k-d_tree_pandas      |     0.549409 |        4.59161 |   7.07089  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557238 |        72.6784 |    2.65555 |
| k-d_tree_sklearn     |     0.561212 |       236.317  |    4.31497 |
| Bori_Aron_solution-1 |     0.800363 |       147.667  |   18.8716  |