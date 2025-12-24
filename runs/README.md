# 2025-12-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.527695 |       0.401892 |   0.430516 |
| barab-szabi-2        |     0.904176 |       0.534992 |   0.434083 |
| k-d_tree_polars      |     0.534247 |       0.406795 |   0.43742  |
| solution-1           |     8.07891  |       1e-06    |   0.481299 |
| Bori_Aron_solution-1 |     0.525788 |       0.550033 |   0.551008 |
| k-d_tree_pandas      |     8.7728   |       0.436768 |   0.665656 |
| k-d_tree_sklearn     |     3.07685  |       1.09306  |   1.09276  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525623 |       0.433461 |   0.430419 |
| k-d_tree_polars      |     0.531051 |       0.411487 |   0.432922 |
| barab-szabi-1        |     0.548003 |       0.411877 |   0.442708 |
| Bori_Aron_solution-1 |     0.519728 |       0.552634 |   0.552208 |
| k-d_tree_pandas      |     0.527425 |       0.391694 |   0.559227 |
| k-d_tree_sklearn     |     0.53981  |       0.98826  |   1.06695  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527899 |       0.448611 |   0.448401 |
| k-d_tree_polars      |     0.528778 |       0.436914 |   0.461214 |
| barab-szabi-1        |     0.530075 |       0.43373  |   0.46419  |
| Bori_Aron_solution-1 |     0.525431 |       0.594048 |   0.557497 |
| k-d_tree_pandas      |     0.530439 |       0.417253 |   0.604755 |
| k-d_tree_sklearn     |     0.530891 |       1.01946  |   1.17541  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52753  |       0.499869 |   0.479213 |
| k-d_tree_polars      |     0.53368  |       0.557798 |   0.55647  |
| Bori_Aron_solution-1 |     0.523654 |       0.785487 |   0.563616 |
| barab-szabi-1        |     0.52803  |       0.556496 |   0.57083  |
| k-d_tree_pandas      |     0.529319 |       0.504515 |   0.732249 |
| k-d_tree_sklearn     |     0.529807 |       1.2775   |   1.13109  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532499 |       0.739053 |   0.513189 |
| Bori_Aron_solution-1 |     0.522871 |       1.46175  |   0.590258 |
| k-d_tree_polars      |     0.531337 |       0.902262 |   0.914527 |
| barab-szabi-1        |     0.52978  |       0.925258 |   0.958759 |
| k-d_tree_pandas      |     0.532283 |       0.814502 |   1.18261  |
| k-d_tree_sklearn     |     0.524792 |       2.10383  |   1.22668  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529856 |        5.04606 |   0.731737 |
| Bori_Aron_solution-1 |     0.527799 |       11.0594  |   0.837854 |
| k-d_tree_sklearn     |     0.532647 |       16.426   |   1.30157  |
| k-d_tree_polars      |     0.533582 |        5.39881 |   6.52225  |
| barab-szabi-1        |     0.527889 |        5.44943 |   6.52571  |
| k-d_tree_pandas      |     0.526924 |        4.47602 |   6.89509  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536838 |        77.2666 |    2.59622 |
| k-d_tree_sklearn     |     0.540186 |       234.672  |    4.08912 |
| Bori_Aron_solution-1 |     0.659552 |       157.651  |   13.2417  |