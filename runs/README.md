# 2024-06-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.799299 |       0.408335 |   0.345595 |
| barab-szabi-2        |     4.74466  |       0.469725 |   0.352309 |
| k-d_tree_polars      |     0.807149 |       0.414153 |   0.353832 |
| Bori_Aron_solution-1 |     5.00849  |       0.415792 |   0.404864 |
| k-d_tree_pandas      |     0.802064 |       0.391723 |   0.490635 |
| k-d_tree_sklearn     |     3.61145  |       1.1158   |   0.671955 |
| solution-1           |     9.2344   |       1e-06    |   0.769948 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.807419 |       0.410157 |   0.352142 |
| barab-szabi-2        |     0.831207 |       0.365273 |   0.358855 |
| barab-szabi-1        |     0.810321 |       0.431976 |   0.375505 |
| k-d_tree_pandas      |     0.801336 |       0.407701 |   0.494525 |
| Bori_Aron_solution-1 |     0.786812 |       0.488049 |   0.497643 |
| k-d_tree_sklearn     |     0.821155 |       0.883365 |   0.69457  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.803601 |       0.371006 |   0.367247 |
| k-d_tree_polars      |     0.794307 |       0.444169 |   0.380085 |
| barab-szabi-1        |     0.813087 |       0.449934 |   0.388801 |
| Bori_Aron_solution-1 |     0.796963 |       0.530494 |   0.484531 |
| k-d_tree_pandas      |     0.797959 |       0.418191 |   0.559061 |
| k-d_tree_sklearn     |     0.805933 |       0.923494 |   0.729517 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.792086 |       0.42758  |   0.39273  |
| k-d_tree_polars      |     0.792619 |       0.555744 |   0.471581 |
| Bori_Aron_solution-1 |     0.786578 |       0.712719 |   0.501909 |
| barab-szabi-1        |     0.803591 |       0.552647 |   0.548863 |
| k-d_tree_pandas      |     0.805063 |       0.491788 |   0.660731 |
| k-d_tree_sklearn     |     0.806904 |       1.13809  |   0.77379  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.80622  |       0.691574 |   0.466338 |
| Bori_Aron_solution-1 |     0.785755 |       1.36697  |   0.532077 |
| k-d_tree_polars      |     0.794953 |       0.87138  |   0.839978 |
| k-d_tree_sklearn     |     0.807386 |       2.01785  |   0.880019 |
| barab-szabi-1        |     0.79442  |       0.892233 |   0.897116 |
| k-d_tree_pandas      |     0.806985 |       0.760798 |   1.11188  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.801322 |        5.37725 |   0.716191 |
| Bori_Aron_solution-1 |     0.789397 |       10.8167  |   0.77115  |
| k-d_tree_sklearn     |     0.803336 |       16.3924  |   1.04985  |
| barab-szabi-1        |     0.798477 |        4.95313 |   6.59634  |
| k-d_tree_polars      |     0.797138 |        4.95195 |   6.70997  |
| k-d_tree_pandas      |     0.803339 |        4.03941 |   6.93171  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.0607   |        73.6008 |    4.00026 |
| k-d_tree_sklearn     |     0.913201 |       228.784  |    4.56519 |
| Bori_Aron_solution-1 |     0.781614 |       152.469  |   16.8308  |