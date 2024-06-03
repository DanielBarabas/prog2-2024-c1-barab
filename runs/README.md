# 2024-06-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.801903 |       0.411443 |   0.347104 |
| barab-szabi-2        |     4.7657   |       0.447459 |   0.348044 |
| k-d_tree_polars      |     0.798508 |       0.407335 |   0.351153 |
| Bori_Aron_solution-1 |     4.71508  |       0.42803  |   0.425866 |
| solution-1           |     8.35783  |       1e-06    |   0.468961 |
| k-d_tree_pandas      |     0.805454 |       0.389378 |   0.485947 |
| k-d_tree_sklearn     |     3.40315  |       1.03954  |   0.67781  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.794744 |       0.355059 |   0.351499 |
| k-d_tree_polars      |     0.835994 |       0.420034 |   0.356756 |
| barab-szabi-1        |     0.80197  |       0.419952 |   0.357147 |
| Bori_Aron_solution-1 |     0.786005 |       0.490972 |   0.477448 |
| k-d_tree_pandas      |     0.818037 |       0.3959   |   0.499716 |
| k-d_tree_sklearn     |     0.811349 |       0.869724 |   0.688212 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.797174 |       0.366084 |   0.361517 |
| barab-szabi-1        |     0.820977 |       0.449324 |   0.389763 |
| k-d_tree_polars      |     0.799466 |       0.440292 |   0.397381 |
| Bori_Aron_solution-1 |     0.796497 |       0.533401 |   0.494343 |
| k-d_tree_pandas      |     0.805908 |       0.410896 |   0.542846 |
| k-d_tree_sklearn     |     0.809868 |       0.939816 |   0.746694 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.794339 |       0.423852 |   0.392095 |
| k-d_tree_polars      |     0.793322 |       0.543421 |   0.479919 |
| barab-szabi-1        |     0.796085 |       0.542622 |   0.483993 |
| Bori_Aron_solution-1 |     0.79666  |       0.706662 |   0.502442 |
| k-d_tree_pandas      |     0.798906 |       0.484594 |   0.658381 |
| k-d_tree_sklearn     |     0.802261 |       1.13054  |   0.766465 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.799718 |       0.691792 |   0.436971 |
| Bori_Aron_solution-1 |     0.777778 |       1.38691  |   0.530026 |
| k-d_tree_polars      |     0.798239 |       0.878408 |   0.846419 |
| barab-szabi-1        |     0.796479 |       0.88247  |   0.885094 |
| k-d_tree_sklearn     |     0.806736 |       2.00982  |   0.889995 |
| k-d_tree_pandas      |     0.80644  |       0.767725 |   1.12316  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.814527 |        5.32527 |   0.755477 |
| Bori_Aron_solution-1 |     0.792875 |       10.8461  |   0.783659 |
| k-d_tree_sklearn     |     0.810564 |       16.7308  |   1.065    |
| k-d_tree_polars      |     0.786504 |        4.98706 |   6.42391  |
| barab-szabi-1        |     0.804693 |        5.05404 |   6.68544  |
| k-d_tree_pandas      |     0.81976  |        4.01428 |   6.72019  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.15857  |        75.6512 |    3.93896 |
| k-d_tree_sklearn     |     0.917892 |       228.509  |    4.60069 |
| Bori_Aron_solution-1 |     0.773108 |       151.342  |   17.0825  |