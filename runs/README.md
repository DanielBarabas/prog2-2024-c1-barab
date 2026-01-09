# 2026-01-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528214 |       0.481553 |   0.419506 |
| k-d_tree_polars      |     0.486121 |       0.390232 |   0.424864 |
| barab-szabi-1        |     0.492226 |       0.396467 |   0.426049 |
| solution-1           |     7.61587  |       1e-06    |   0.429679 |
| Bori_Aron_solution-1 |     0.489874 |       0.538928 |   0.529429 |
| k-d_tree_pandas      |     8.55358  |       0.396629 |   0.678658 |
| k-d_tree_sklearn     |     3.01285  |       1.02872  |   0.993344 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491382 |       0.420182 |   0.409054 |
| barab-szabi-1        |     0.487514 |       0.396801 |   0.424416 |
| k-d_tree_polars      |     0.49349  |       0.399078 |   0.429757 |
| Bori_Aron_solution-1 |     0.487305 |       0.541242 |   0.529567 |
| k-d_tree_pandas      |     0.490465 |       0.375985 |   0.534928 |
| k-d_tree_sklearn     |     0.493719 |       0.925552 |   1.01627  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.489009 |       0.444656 |   0.438919 |
| k-d_tree_polars      |     0.487254 |       0.421396 |   0.443484 |
| barab-szabi-1        |     0.48911  |       0.423776 |   0.446531 |
| Bori_Aron_solution-1 |     0.496304 |       0.569332 |   0.533805 |
| k-d_tree_pandas      |     0.483613 |       0.392237 |   0.576989 |
| k-d_tree_sklearn     |     0.499825 |       1.0169   |   1.03731  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48968  |       0.49554  |   0.458872 |
| k-d_tree_polars      |     0.491074 |       0.537373 |   0.537784 |
| barab-szabi-1        |     0.488928 |       0.541581 |   0.545345 |
| Bori_Aron_solution-1 |     0.488057 |       0.74145  |   0.563155 |
| k-d_tree_pandas      |     0.490681 |       0.480152 |   0.692107 |
| k-d_tree_sklearn     |     0.495032 |       1.20399  |   1.1011   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48978  |       0.724396 |   0.53348  |
| Bori_Aron_solution-1 |     0.48488  |       1.30921  |   0.566113 |
| k-d_tree_polars      |     0.490399 |       0.858843 |   0.848563 |
| barab-szabi-1        |     0.491834 |       0.864908 |   0.886048 |
| k-d_tree_pandas      |     0.505518 |       0.730293 |   1.07267  |
| k-d_tree_sklearn     |     0.496992 |       1.99458  |   1.14336  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486542 |        4.97894 |   0.719763 |
| Bori_Aron_solution-1 |     0.486328 |       10.0916  |   0.936601 |
| k-d_tree_sklearn     |     0.501802 |       14.5704  |   1.30747  |
| barab-szabi-1        |     0.491821 |        4.93289 |   6.16901  |
| k-d_tree_polars      |     0.479797 |        4.9324  |   6.2545   |
| k-d_tree_pandas      |     0.489348 |        3.85162 |   6.51398  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486486 |         75.57  |    2.86799 |
| k-d_tree_sklearn     |     0.507236 |        179.536 |    4.44234 |
| Bori_Aron_solution-1 |     0.615527 |        137.026 |   16.3823  |