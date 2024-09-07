# 2024-09-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61919  |       0.389696 |   0.390045 |
| barab-szabi-1        |     0.613388 |       0.395278 |   0.394268 |
| Bori_Aron_solution-1 |     4.71869  |       0.589347 |   0.452898 |
| k-d_tree_polars      |     4.63079  |       0.464743 |   0.454334 |
| solution-1           |     8.04122  |       1e-06    |   0.495971 |
| k-d_tree_pandas      |     0.596001 |       0.376448 |   0.530081 |
| k-d_tree_sklearn     |     3.2367   |       1.03584  |   0.705358 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598135 |       0.385167 |   0.385836 |
| k-d_tree_polars      |     0.604664 |       0.396892 |   0.390189 |
| barab-szabi-1        |     0.615779 |       0.403272 |   0.390339 |
| Bori_Aron_solution-1 |     0.653036 |       0.563491 |   0.518201 |
| k-d_tree_pandas      |     0.611074 |       0.378702 |   0.537542 |
| k-d_tree_sklearn     |     0.617645 |       0.89248  |   0.692445 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604745 |       0.406085 |   0.394755 |
| k-d_tree_polars      |     0.614789 |       0.427809 |   0.420144 |
| barab-szabi-1        |     0.602569 |       0.420607 |   0.420942 |
| Bori_Aron_solution-1 |     0.608867 |       0.575114 |   0.54922  |
| k-d_tree_pandas      |     0.60937  |       0.416422 |   0.567242 |
| k-d_tree_sklearn     |     0.610004 |       0.929516 |   0.717674 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.601562 |       0.462085 |   0.424176 |
| k-d_tree_polars      |     0.600358 |       0.528792 |   0.512292 |
| barab-szabi-1        |     0.609577 |       0.524801 |   0.522883 |
| Bori_Aron_solution-1 |     0.603152 |       0.733738 |   0.530997 |
| k-d_tree_pandas      |     0.611368 |       0.467357 |   0.70179  |
| k-d_tree_sklearn     |     0.608055 |       1.13454  |   0.774636 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606343 |       0.708972 |   0.460891 |
| Bori_Aron_solution-1 |     0.607533 |       1.3869   |   0.560932 |
| k-d_tree_polars      |     0.598138 |       0.849813 |   0.856147 |
| k-d_tree_sklearn     |     0.604504 |       1.95248  |   0.858309 |
| barab-szabi-1        |     0.600863 |       0.847604 |   0.891249 |
| k-d_tree_pandas      |     0.604917 |       0.740253 |   1.13859  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603464 |        5.30082 |   0.724088 |
| Bori_Aron_solution-1 |     0.595804 |       10.7329  |   0.816177 |
| k-d_tree_sklearn     |     0.607147 |       15.9533  |   0.971994 |
| k-d_tree_polars      |     0.605895 |        4.91623 |   6.47437  |
| barab-szabi-1        |     0.61182  |        4.82185 |   6.63551  |
| k-d_tree_pandas      |     0.604816 |        3.89375 |   6.87279  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.687465 |         70.748 |    2.96282 |
| k-d_tree_sklearn     |     0.951332 |        227.787 |    3.90222 |
| Bori_Aron_solution-1 |     0.597199 |        147.258 |   18.5528  |