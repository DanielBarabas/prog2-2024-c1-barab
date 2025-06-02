# 2025-06-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544047 |       0.406893 |   0.415112 |
| k-d_tree_polars      |     0.532341 |       0.406238 |   0.41667  |
| Bori_Aron_solution-1 |     0.524828 |       0.538701 |   0.5366   |
| solution-1           |     7.96843  |       1e-06    |   0.541797 |
| k-d_tree_pandas      |     0.548957 |       0.382491 |   0.543782 |
| barab-szabi-1        |     7.89208  |       0.431485 |   0.616823 |
| k-d_tree_sklearn     |     3.00602  |       1.59664  |   1.02734  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54356  |       0.409277 |   0.416333 |
| k-d_tree_polars      |     0.546086 |       0.409293 |   0.42286  |
| barab-szabi-1        |     0.546184 |       0.406558 |   0.424225 |
| Bori_Aron_solution-1 |     0.541002 |       0.548544 |   0.537271 |
| k-d_tree_pandas      |     0.547504 |       0.384915 |   0.548647 |
| k-d_tree_sklearn     |     0.55261  |       0.958313 |   1.0323   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543424 |       0.430248 |   0.428214 |
| k-d_tree_polars      |     0.547539 |       0.427216 |   0.442262 |
| barab-szabi-1        |     0.53952  |       0.425212 |   0.447903 |
| Bori_Aron_solution-1 |     0.546511 |       0.580262 |   0.541129 |
| k-d_tree_pandas      |     0.542092 |       0.401562 |   0.590932 |
| k-d_tree_sklearn     |     0.549688 |       0.991178 |   1.05069  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547436 |       0.486408 |   0.459038 |
| k-d_tree_polars      |     0.540519 |       0.537655 |   0.540877 |
| Bori_Aron_solution-1 |     0.536811 |       0.754145 |   0.546809 |
| barab-szabi-1        |     0.550856 |       0.535607 |   0.551153 |
| k-d_tree_pandas      |     0.540205 |       0.480088 |   0.720523 |
| k-d_tree_sklearn     |     0.546339 |       1.21206  |   1.09741  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541629 |       0.738905 |   0.48267  |
| Bori_Aron_solution-1 |     0.530785 |       1.39772  |   0.577971 |
| k-d_tree_polars      |     0.545058 |       0.859949 |   0.900585 |
| barab-szabi-1        |     0.543123 |       0.859185 |   0.92873  |
| k-d_tree_pandas      |     0.548433 |       0.74897  |   1.1663   |
| k-d_tree_sklearn     |     0.547372 |       2.0109   |   1.19485  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541614 |        5.11611 |   0.719094 |
| Bori_Aron_solution-1 |     0.539483 |       10.3246  |   0.854218 |
| k-d_tree_sklearn     |     0.549766 |       15.5671  |   1.30544  |
| k-d_tree_polars      |     0.536698 |        4.84063 |   6.2811   |
| barab-szabi-1        |     0.547843 |        4.85799 |   6.36359  |
| k-d_tree_pandas      |     0.543034 |        3.90964 |   6.74655  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631815 |        81.4605 |    4.28221 |
| k-d_tree_sklearn     |     0.710685 |       246.228  |    4.41046 |
| Bori_Aron_solution-1 |     0.538367 |       141.176  |   16.8035  |