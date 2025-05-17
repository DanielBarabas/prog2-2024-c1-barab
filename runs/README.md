# 2025-05-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552867 |       0.414765 |   0.411667 |
| k-d_tree_polars      |     0.543012 |       0.405338 |   0.415165 |
| solution-1           |     7.56756  |       1e-06    |   0.479468 |
| Bori_Aron_solution-1 |     0.531756 |       0.542195 |   0.542058 |
| k-d_tree_pandas      |     0.558336 |       0.38827  |   0.552559 |
| barab-szabi-1        |     7.8883   |       0.529255 |   0.592803 |
| k-d_tree_sklearn     |     3.02672  |       1.07588  |   1.03195  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550393 |       0.414752 |   0.414717 |
| barab-szabi-1        |     0.554085 |       0.412475 |   0.415855 |
| k-d_tree_polars      |     0.554039 |       0.41217  |   0.422662 |
| Bori_Aron_solution-1 |     0.547651 |       0.552894 |   0.544534 |
| k-d_tree_pandas      |     0.557428 |       0.395904 |   0.560697 |
| k-d_tree_sklearn     |     0.560114 |       0.96691  |   1.0405   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554054 |       0.429471 |   0.425848 |
| k-d_tree_polars      |     0.552664 |       0.435585 |   0.444918 |
| barab-szabi-1        |     0.554962 |       0.435844 |   0.449685 |
| Bori_Aron_solution-1 |     0.552185 |       0.611043 |   0.55266  |
| k-d_tree_pandas      |     0.552971 |       0.406217 |   0.613252 |
| k-d_tree_sklearn     |     0.5566   |       1.01687  |   1.07213  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547657 |       0.483721 |   0.452322 |
| k-d_tree_polars      |     0.556702 |       0.545839 |   0.540624 |
| barab-szabi-1        |     0.552855 |       0.548275 |   0.551702 |
| Bori_Aron_solution-1 |     0.546466 |       0.762752 |   0.560766 |
| k-d_tree_pandas      |     0.549568 |       0.484141 |   0.728071 |
| k-d_tree_sklearn     |     0.556514 |       1.23271  |   1.11357  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547198 |       0.717226 |   0.482747 |
| Bori_Aron_solution-1 |     0.543157 |       1.38509  |   0.584926 |
| k-d_tree_polars      |     0.551628 |       0.872797 |   0.878059 |
| barab-szabi-1        |     0.548099 |       0.878311 |   0.917915 |
| k-d_tree_pandas      |     0.547687 |       0.757256 |   1.15929  |
| k-d_tree_sklearn     |     0.553518 |       2.02347  |   1.20663  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55244  |        5.54754 |   0.735885 |
| Bori_Aron_solution-1 |     0.542634 |       10.7826  |   0.87033  |
| k-d_tree_sklearn     |     0.552647 |       16.4013  |   1.3017   |
| barab-szabi-1        |     0.550284 |        4.96945 |   6.67061  |
| k-d_tree_polars      |     0.545085 |        4.91516 |   6.67744  |
| k-d_tree_pandas      |     0.547811 |        3.93937 |   7.15236  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598613 |        70.3913 |    2.70147 |
| k-d_tree_sklearn     |     0.68619  |       227.7    |    4.27759 |
| Bori_Aron_solution-1 |     0.545808 |       142.071  |   15.6641  |