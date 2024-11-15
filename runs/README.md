# 2024-11-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.761886 |       0.389145 |   0.386578 |
| k-d_tree_polars      |     1.08936  |       0.410042 |   0.388544 |
| barab-szabi-1        |     0.618816 |       0.398264 |   0.390297 |
| Bori_Aron_solution-1 |     0.611099 |       0.525362 |   0.521405 |
| solution-1           |     8.28119  |       1e-06    |   0.523842 |
| k-d_tree_pandas      |     0.620944 |       0.40601  |   0.545897 |
| k-d_tree_sklearn     |    10.938    |       1.2532   |   0.967147 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.647959 |       0.393899 |   0.389299 |
| barab-szabi-1        |     0.6333   |       0.406928 |   0.395604 |
| k-d_tree_polars      |     0.635501 |       0.421242 |   0.406547 |
| k-d_tree_pandas      |     0.619965 |       0.390127 |   0.536931 |
| Bori_Aron_solution-1 |     0.617474 |       0.558305 |   0.554283 |
| k-d_tree_sklearn     |     0.618172 |       0.966714 |   1.00219  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610356 |       0.401988 |   0.40775  |
| barab-szabi-1        |     0.627707 |       0.445623 |   0.424045 |
| k-d_tree_polars      |     0.619702 |       0.432552 |   0.444117 |
| Bori_Aron_solution-1 |     0.609897 |       0.569219 |   0.54391  |
| k-d_tree_pandas      |     0.630327 |       0.405995 |   0.579694 |
| k-d_tree_sklearn     |     0.621401 |       0.957545 |   1.00852  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621753 |       0.46994  |   0.427793 |
| k-d_tree_polars      |     0.617265 |       0.541761 |   0.520487 |
| barab-szabi-1        |     0.617744 |       0.54033  |   0.535432 |
| Bori_Aron_solution-1 |     0.618845 |       0.762633 |   0.550524 |
| k-d_tree_pandas      |     0.63176  |       0.510204 |   0.760289 |
| k-d_tree_sklearn     |     0.631119 |       1.19561  |   1.05469  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.638802 |       0.745146 |   0.518212 |
| Bori_Aron_solution-1 |     0.633361 |       1.43813  |   0.587663 |
| k-d_tree_polars      |     0.631145 |       0.887162 |   0.91146  |
| barab-szabi-1        |     0.633755 |       0.879518 |   0.946527 |
| k-d_tree_sklearn     |     0.641729 |       2.08388  |   1.17449  |
| k-d_tree_pandas      |     0.655979 |       0.775358 |   1.1999   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625904 |        5.59399 |   0.731064 |
| Bori_Aron_solution-1 |     0.634729 |       11.2011  |   0.834328 |
| k-d_tree_sklearn     |     0.640925 |       17.0063  |   1.30255  |
| barab-szabi-1        |     0.628473 |        4.88002 |   6.76825  |
| k-d_tree_polars      |     0.627361 |        4.90241 |   6.85645  |
| k-d_tree_pandas      |     0.620839 |        3.89257 |   7.23647  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.665985 |        74.0798 |    3.01996 |
| k-d_tree_sklearn     |     0.6294   |       231.558  |    4.19992 |
| Bori_Aron_solution-1 |     0.641019 |       149.864  |   18.1455  |