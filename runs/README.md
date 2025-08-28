# 2025-08-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.52694  |       0.409133 |   0.425592 |
| barab-szabi-1        |     0.531524 |       0.407022 |   0.427268 |
| barab-szabi-2        |     7.95819  |       1.10137  |   0.432135 |
| Bori_Aron_solution-1 |     0.524489 |       0.54427  |   0.547311 |
| k-d_tree_pandas      |     0.539826 |       0.385861 |   0.553499 |
| solution-1           |     7.53714  |       1e-06    |   0.835863 |
| k-d_tree_sklearn     |     3.04656  |       1.43301  |   1.06412  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.542147 |       0.412849 |   0.431639 |
| barab-szabi-1        |     0.552441 |       0.410792 |   0.432466 |
| barab-szabi-2        |     0.542608 |       0.422805 |   0.435374 |
| Bori_Aron_solution-1 |     0.535846 |       0.555778 |   0.554331 |
| k-d_tree_pandas      |     0.546501 |       0.391009 |   0.564767 |
| k-d_tree_sklearn     |     0.547189 |       0.9703   |   1.05738  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544608 |       0.441418 |   0.441752 |
| k-d_tree_polars      |     0.543468 |       0.448183 |   0.457559 |
| barab-szabi-1        |     0.544433 |       0.434287 |   0.459303 |
| Bori_Aron_solution-1 |     0.53361  |       0.58745  |   0.552883 |
| k-d_tree_pandas      |     0.542101 |       0.408255 |   0.599415 |
| k-d_tree_sklearn     |     0.547656 |       1.02762  |   1.08845  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549394 |       0.510253 |   0.472161 |
| k-d_tree_polars      |     0.543943 |       0.546442 |   0.551835 |
| Bori_Aron_solution-1 |     0.535657 |       0.75842  |   0.556616 |
| barab-szabi-1        |     0.542192 |       0.548764 |   0.563556 |
| k-d_tree_pandas      |     0.554026 |       0.488188 |   0.73607  |
| k-d_tree_sklearn     |     0.552513 |       1.25214  |   1.146    |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53924  |       0.736534 |   0.502523 |
| Bori_Aron_solution-1 |     0.537084 |       1.40329  |   0.583972 |
| k-d_tree_polars      |     0.540148 |       0.897694 |   0.897836 |
| barab-szabi-1        |     0.541203 |       0.893729 |   0.936147 |
| k-d_tree_pandas      |     0.547335 |       0.764365 |   1.17546  |
| k-d_tree_sklearn     |     0.54652  |       2.0833   |   1.21496  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545821 |        5.51572 |   0.755593 |
| Bori_Aron_solution-1 |     0.534697 |       10.8382  |   0.849181 |
| k-d_tree_sklearn     |     0.543381 |       16.7366  |   1.31309  |
| barab-szabi-1        |     0.54546  |        5.01481 |   6.76104  |
| k-d_tree_polars      |     0.542182 |        5.05065 |   6.9278   |
| k-d_tree_pandas      |     0.543903 |        4.00437 |   7.185    |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543427 |        73.0519 |    2.80672 |
| k-d_tree_sklearn     |     0.678849 |       236.251  |    4.01173 |
| Bori_Aron_solution-1 |     0.545348 |       143.058  |   18.1017  |