# 2026-01-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.933185 |       0.408141 |   0.433045 |
| barab-szabi-2        |     0.966414 |       0.561152 |   0.436745 |
| k-d_tree_polars      |     0.53407  |       0.402683 |   0.439217 |
| Bori_Aron_solution-1 |     0.52533  |       0.543853 |   0.548658 |
| solution-1           |     9.04061  |       1e-06    |   0.63352  |
| k-d_tree_pandas      |     9.96913  |       0.433102 |   0.708855 |
| k-d_tree_sklearn     |     3.87639  |       1.09315  |   1.05658  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535348 |       0.440347 |   0.434416 |
| k-d_tree_polars      |     0.533454 |       0.408417 |   0.44115  |
| barab-szabi-1        |     0.594411 |       0.418807 |   0.443469 |
| Bori_Aron_solution-1 |     0.52263  |       0.553247 |   0.545454 |
| k-d_tree_pandas      |     0.530786 |       0.387916 |   0.553829 |
| k-d_tree_sklearn     |     0.537822 |       0.988441 |   1.07513  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534457 |       0.447596 |   0.442963 |
| k-d_tree_polars      |     0.528685 |       0.434422 |   0.464139 |
| barab-szabi-1        |     0.533381 |       0.440326 |   0.467261 |
| Bori_Aron_solution-1 |     0.532962 |       0.594409 |   0.550156 |
| k-d_tree_pandas      |     0.528478 |       0.409844 |   0.595518 |
| k-d_tree_sklearn     |     0.537616 |       1.03131  |   1.08905  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55861  |       0.510977 |   0.478861 |
| Bori_Aron_solution-1 |     0.530202 |       0.778153 |   0.558515 |
| k-d_tree_polars      |     0.53151  |       0.560337 |   0.561779 |
| barab-szabi-1        |     0.531725 |       0.55737  |   0.572142 |
| k-d_tree_pandas      |     0.526253 |       0.491025 |   0.731045 |
| k-d_tree_sklearn     |     0.535667 |       1.25654  |   1.13439  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536149 |       0.741786 |   0.51118  |
| Bori_Aron_solution-1 |     0.523346 |       1.46071  |   0.583475 |
| k-d_tree_polars      |     0.531452 |       0.932973 |   0.920505 |
| barab-szabi-1        |     0.531391 |       0.927471 |   0.947665 |
| k-d_tree_pandas      |     0.531543 |       0.815929 |   1.18215  |
| k-d_tree_sklearn     |     0.538884 |       2.1318   |   1.21984  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534293 |        5.24676 |   0.764881 |
| Bori_Aron_solution-1 |     0.527914 |       11.3605  |   0.840162 |
| k-d_tree_sklearn     |     0.540619 |       17.2529  |   1.32036  |
| barab-szabi-1        |     0.542229 |        5.62607 |   6.81964  |
| k-d_tree_polars      |     0.529397 |        5.4999  |   6.87155  |
| k-d_tree_pandas      |     0.530528 |        4.33347 |   7.20537  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530728 |        78.9948 |    2.81331 |
| k-d_tree_sklearn     |     0.556681 |       243.723  |    4.11886 |
| Bori_Aron_solution-1 |     0.63898  |       154.775  |   18.6064  |