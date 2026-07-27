# 2026-07-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.60444  |       1e-06    |   0.428957 |
| barab-szabi-2        |     0.468303 |       0.43942  |   0.445327 |
| barab-szabi-1        |     0.467509 |       0.418177 |   0.479155 |
| k-d_tree_pandas      |     0.476631 |       0.388147 |   0.559418 |
| Bori_Aron_solution-1 |     0.457496 |       0.563627 |   0.563741 |
| k-d_tree_polars      |     9.55987  |       0.480695 |   0.594914 |
| k-d_tree_sklearn     |     3.13182  |       1.17924  |   1.10616  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.49804  |       0.432542 |   0.451799 |
| barab-szabi-2        |     0.467834 |       0.480785 |   0.454281 |
| barab-szabi-1        |     0.477896 |       0.431902 |   0.459474 |
| Bori_Aron_solution-1 |     0.461411 |       0.566032 |   0.556762 |
| k-d_tree_pandas      |     0.484493 |       0.394453 |   0.563478 |
| k-d_tree_sklearn     |     0.48064  |       1.04621  |   1.10072  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478931 |       0.454772 |   0.46062  |
| k-d_tree_polars      |     0.498445 |       0.472415 |   0.472398 |
| barab-szabi-1        |     0.482216 |       0.460473 |   0.482429 |
| Bori_Aron_solution-1 |     0.476918 |       0.62514  |   0.549348 |
| k-d_tree_pandas      |     0.480058 |       0.4355   |   0.618639 |
| k-d_tree_sklearn     |     0.476058 |       1.10084  |   1.12482  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472223 |       0.529795 |   0.477398 |
| Bori_Aron_solution-1 |     0.471288 |       0.784924 |   0.567001 |
| k-d_tree_polars      |     0.474459 |       0.582706 |   0.569534 |
| barab-szabi-1        |     0.471233 |       0.570711 |   0.608452 |
| k-d_tree_pandas      |     0.469646 |       0.498279 |   0.724696 |
| k-d_tree_sklearn     |     0.482414 |       1.29442  |   1.1799   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474421 |       0.761585 |   0.531944 |
| Bori_Aron_solution-1 |     0.473555 |       1.47062  |   0.584602 |
| k-d_tree_polars      |     0.518328 |       0.903294 |   0.964336 |
| barab-szabi-1        |     0.471494 |       0.918446 |   0.992221 |
| k-d_tree_pandas      |     0.470752 |       0.767517 |   1.18397  |
| k-d_tree_sklearn     |     0.475083 |       2.18041  |   1.22722  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471077 |        5.77772 |   0.754534 |
| Bori_Aron_solution-1 |     0.490343 |       11.7466  |   0.817727 |
| k-d_tree_sklearn     |     0.477242 |       18.0891  |   1.27631  |
| k-d_tree_polars      |     0.464963 |        5.0425  |   7.9184   |
| barab-szabi-1        |     0.481313 |        5.1245  |   8.0899   |
| k-d_tree_pandas      |     0.505963 |        4.09506 |   8.11377  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583022 |        87.5983 |    2.87597 |
| k-d_tree_sklearn     |     0.724043 |       266.936  |    3.6812  |
| Bori_Aron_solution-1 |     0.479571 |       162.197  |   15.1081  |