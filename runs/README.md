# 2026-03-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.495125 |       0.42009  |   0.439876 |
| barab-szabi-2        |     0.807555 |       0.456872 |   0.461783 |
| solution-1           |     8.05267  |       1e-06    |   0.501868 |
| Bori_Aron_solution-1 |     0.498212 |       0.572663 |   0.564861 |
| k-d_tree_pandas      |     0.509881 |       0.410651 |   0.571007 |
| barab-szabi-1        |     8.65137  |       0.46725  |   0.686135 |
| k-d_tree_sklearn     |     2.97876  |       1.15149  |   1.09902  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.496236 |       0.41994  |   0.442854 |
| barab-szabi-2        |     0.507216 |       0.443907 |   0.449735 |
| k-d_tree_polars      |     0.504265 |       0.425742 |   0.459244 |
| Bori_Aron_solution-1 |     0.497928 |       0.57316  |   0.564965 |
| k-d_tree_pandas      |     0.50693  |       0.405593 |   0.586468 |
| k-d_tree_sklearn     |     0.504084 |       1.00687  |   1.12177  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.515123 |       0.466394 |   0.466658 |
| k-d_tree_polars      |     0.499665 |       0.450952 |   0.472568 |
| barab-szabi-1        |     0.516379 |       0.460217 |   0.483513 |
| Bori_Aron_solution-1 |     0.498774 |       0.619025 |   0.572827 |
| k-d_tree_pandas      |     0.502643 |       0.4232   |   0.620223 |
| k-d_tree_sklearn     |     0.51616  |       1.06791  |   1.11082  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.502524 |       0.527557 |   0.503635 |
| k-d_tree_polars      |     0.502341 |       0.571853 |   0.559389 |
| barab-szabi-1        |     0.495465 |       0.568971 |   0.580477 |
| Bori_Aron_solution-1 |     0.510786 |       0.808516 |   0.583377 |
| k-d_tree_pandas      |     0.50234  |       0.512053 |   0.730276 |
| k-d_tree_sklearn     |     0.497673 |       1.27072  |   1.13845  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49105  |       0.743253 |   0.505255 |
| Bori_Aron_solution-1 |     0.491734 |       1.55862  |   0.607159 |
| k-d_tree_polars      |     0.514415 |       0.973571 |   0.94916  |
| barab-szabi-1        |     0.492547 |       0.936639 |   0.971204 |
| k-d_tree_pandas      |     0.508955 |       0.833726 |   1.23257  |
| k-d_tree_sklearn     |     0.52871  |       2.26544  |   1.2683   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.503971 |        5.28018 |   0.735991 |
| Bori_Aron_solution-1 |     0.51298  |       11.3519  |   0.837149 |
| k-d_tree_sklearn     |     0.49988  |       17.7571  |   1.35122  |
| k-d_tree_polars      |     0.501996 |        5.61932 |   6.68061  |
| barab-szabi-1        |     0.512504 |        5.53549 |   7.04254  |
| k-d_tree_pandas      |     0.499311 |        4.36721 |   7.12347  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527324 |        72.5846 |    2.58281 |
| k-d_tree_sklearn     |     0.873089 |       246.346  |    3.92674 |
| Bori_Aron_solution-1 |     0.512942 |       152.707  |   14.8129  |