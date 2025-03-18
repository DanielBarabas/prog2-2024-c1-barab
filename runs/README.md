# 2025-03-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.76385  |       1e-06    |   0.404882 |
| k-d_tree_polars      |     0.593577 |       0.434938 |   0.430428 |
| barab-szabi-1        |     0.574019 |       0.420466 |   0.445488 |
| barab-szabi-2        |     0.568083 |       0.427983 |   0.449145 |
| Bori_Aron_solution-1 |     0.574881 |       0.57427  |   0.597891 |
| k-d_tree_pandas      |     8.16177  |       0.42269  |   0.619016 |
| k-d_tree_sklearn     |     3.02706  |       1.05441  |   1.10514  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611754 |       0.431138 |   0.434966 |
| barab-szabi-1        |     0.594215 |       0.445568 |   0.436913 |
| k-d_tree_polars      |     0.593545 |       0.452748 |   0.443964 |
| Bori_Aron_solution-1 |     0.576503 |       0.579221 |   0.569506 |
| k-d_tree_pandas      |     0.633787 |       0.40416  |   0.61468  |
| k-d_tree_sklearn     |     0.601483 |       1.03301  |   1.08277  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583419 |       0.45042  |   0.427744 |
| k-d_tree_polars      |     0.63265  |       0.452837 |   0.46925  |
| barab-szabi-1        |     0.587174 |       0.458525 |   0.477567 |
| Bori_Aron_solution-1 |     0.594959 |       0.632204 |   0.580227 |
| k-d_tree_pandas      |     0.600379 |       0.433209 |   0.618391 |
| k-d_tree_sklearn     |     0.588829 |       1.05691  |   1.10207  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.595061 |       0.525932 |   0.478422 |
| k-d_tree_polars      |     0.598433 |       0.563219 |   0.556612 |
| barab-szabi-1        |     0.600944 |       0.577909 |   0.571416 |
| Bori_Aron_solution-1 |     0.583644 |       0.784982 |   0.594499 |
| k-d_tree_pandas      |     0.588347 |       0.488105 |   0.761114 |
| k-d_tree_sklearn     |     0.606745 |       1.35966  |   1.21234  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604335 |       0.757802 |   0.512098 |
| Bori_Aron_solution-1 |     0.595902 |       1.45454  |   0.619001 |
| k-d_tree_polars      |     0.580838 |       0.916178 |   0.932882 |
| barab-szabi-1        |     0.599586 |       0.903152 |   0.971807 |
| k-d_tree_pandas      |     0.587246 |       0.767061 |   1.23643  |
| k-d_tree_sklearn     |     0.590987 |       2.34771  |   1.30342  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.594263 |        5.80517 |   0.798469 |
| Bori_Aron_solution-1 |     0.602803 |       11.1207  |   0.924279 |
| k-d_tree_sklearn     |     0.610063 |       17.9325  |   1.38132  |
| barab-szabi-1        |     0.586188 |        4.98141 |   7.19909  |
| k-d_tree_polars      |     0.60825  |        4.9694  |   7.34175  |
| k-d_tree_pandas      |     0.589867 |        3.75578 |   7.59237  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.758601 |        75.1775 |    3.06854 |
| k-d_tree_sklearn     |     0.653766 |       242.237  |    4.47898 |
| Bori_Aron_solution-1 |     0.571612 |       149.566  |   17.5974  |