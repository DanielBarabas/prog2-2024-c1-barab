# 2024-03-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.726363 |       0.404999 |   0.361064 |
| k-d_tree_polars      |     0.750861 |       0.401675 |   0.361523 |
| barab-szabi-2        |     0.725553 |       0.572811 |   0.363778 |
| Bori_Aron_solution-1 |     0.702033 |       0.506661 |   0.504736 |
| solution-1           |     9.15285  |       1e-06    |   0.679096 |
| k-d_tree_sklearn     |     3.32811  |       1.09666  |   0.679564 |
| k-d_tree_pandas      |     9.11786  |       0.486345 |   0.784521 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.75391  |       0.42728  |   0.372211 |
| barab-szabi-2        |     0.734275 |       0.368627 |   0.374645 |
| k-d_tree_polars      |     0.745311 |       0.433239 |   0.376515 |
| Bori_Aron_solution-1 |     0.728441 |       0.517218 |   0.503877 |
| k-d_tree_pandas      |     0.733757 |       0.387107 |   0.511622 |
| k-d_tree_sklearn     |     0.755441 |       0.874476 |   0.681137 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.731105 |       0.384713 |   0.378533 |
| k-d_tree_polars      |     0.741345 |       0.435385 |   0.398093 |
| barab-szabi-1        |     0.745414 |       0.434632 |   0.404612 |
| Bori_Aron_solution-1 |     0.736041 |       0.584124 |   0.528829 |
| k-d_tree_pandas      |     0.73146  |       0.409631 |   0.575768 |
| k-d_tree_sklearn     |     0.754785 |       0.962546 |   0.711497 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.730101 |       0.447817 |   0.415555 |
| k-d_tree_polars      |     0.728348 |       0.53875  |   0.488979 |
| barab-szabi-1        |     0.734294 |       0.552257 |   0.502072 |
| Bori_Aron_solution-1 |     0.736695 |       0.757493 |   0.511177 |
| k-d_tree_pandas      |     0.744849 |       0.490131 |   0.688586 |
| k-d_tree_sklearn     |     0.740675 |       1.13349  |   0.768193 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.743666 |       0.688154 |   0.446741 |
| Bori_Aron_solution-1 |     0.729139 |       1.41443  |   0.55449  |
| k-d_tree_polars      |     0.744188 |       0.869032 |   0.859738 |
| k-d_tree_sklearn     |     0.751564 |       1.96659  |   0.871758 |
| barab-szabi-1        |     0.739355 |       0.877974 |   0.881817 |
| k-d_tree_pandas      |     0.753477 |       0.764239 |   1.1281   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.73068  |        5.39309 |   0.766411 |
| Bori_Aron_solution-1 |     0.737285 |       10.8713  |   0.799402 |
| k-d_tree_sklearn     |     0.741378 |       16.633   |   1.06963  |
| k-d_tree_polars      |     0.739682 |        4.94868 |   6.79421  |
| k-d_tree_pandas      |     0.729956 |        3.9773  |   6.91925  |
| barab-szabi-1        |     0.746777 |        4.95251 |   6.92253  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.736653 |        73.8527 |    4.01994 |
| k-d_tree_sklearn     |     0.961011 |       245.71   |    4.91397 |
| Bori_Aron_solution-1 |     0.897797 |       150.54   |   13.9223  |