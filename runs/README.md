# 2025-05-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539341 |       0.42472  |   0.432263 |
| barab-szabi-1        |     0.530661 |       0.429858 |   0.435363 |
| solution-1           |     7.87913  |       1e-06    |   0.47479  |
| k-d_tree_polars      |     4.04039  |       0.421422 |   0.485571 |
| Bori_Aron_solution-1 |     4.51292  |       0.688306 |   0.534167 |
| k-d_tree_pandas      |     0.540167 |       0.434752 |   0.571299 |
| k-d_tree_sklearn     |     3.16069  |       1.19198  |   1.1014   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.521289 |       0.414321 |   0.414282 |
| barab-szabi-1        |     0.521982 |       0.408894 |   0.417415 |
| k-d_tree_polars      |     0.516029 |       0.410884 |   0.419801 |
| k-d_tree_pandas      |     0.546576 |       0.399513 |   0.553974 |
| Bori_Aron_solution-1 |     0.520404 |       0.585129 |   0.571916 |
| k-d_tree_sklearn     |     0.523766 |       0.995332 |   1.04372  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.523261 |       0.44104  |   0.429539 |
| barab-szabi-1        |     0.550188 |       0.441746 |   0.470167 |
| k-d_tree_polars      |     0.55969  |       0.47024  |   0.470737 |
| Bori_Aron_solution-1 |     0.517596 |       0.595448 |   0.585044 |
| k-d_tree_pandas      |     0.526386 |       0.407264 |   0.596023 |
| k-d_tree_sklearn     |     0.524111 |       1.0274   |   1.06982  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.517879 |       0.490678 |   0.461882 |
| k-d_tree_polars      |     0.523709 |       0.556749 |   0.546935 |
| barab-szabi-1        |     0.524904 |       0.554419 |   0.552029 |
| Bori_Aron_solution-1 |     0.517249 |       0.765143 |   0.5577   |
| k-d_tree_pandas      |     0.521136 |       0.495412 |   0.740687 |
| k-d_tree_sklearn     |     0.525266 |       1.23898  |   1.13186  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539085 |       0.732491 |   0.499005 |
| Bori_Aron_solution-1 |     0.517053 |       1.41447  |   0.585441 |
| k-d_tree_polars      |     0.522689 |       0.882525 |   0.91006  |
| barab-szabi-1        |     0.524212 |       0.88511  |   0.962608 |
| k-d_tree_pandas      |     0.537134 |       0.782615 |   1.23261  |
| k-d_tree_sklearn     |     0.54883  |       2.25655  |   1.30222  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.518352 |        5.62688 |   0.791797 |
| Bori_Aron_solution-1 |     0.515082 |       10.5623  |   0.872784 |
| k-d_tree_sklearn     |     0.541412 |       16.2977  |   1.30809  |
| barab-szabi-1        |     0.519682 |        5.13142 |   6.60021  |
| k-d_tree_polars      |     0.517766 |        5.04521 |   6.64868  |
| k-d_tree_pandas      |     0.529837 |        3.95956 |   7.08358  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.596216 |        72.9365 |    2.75831 |
| k-d_tree_sklearn     |     0.711365 |       233.167  |    4.25709 |
| Bori_Aron_solution-1 |     0.558913 |       150.333  |   15.6357  |