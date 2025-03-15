# 2025-03-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.4781   |       1e-06    |   0.353856 |
| barab-szabi-2        |     0.541651 |       0.40062  |   0.397096 |
| k-d_tree_polars      |     0.547117 |       0.39347  |   0.406233 |
| barab-szabi-1        |     0.542899 |       0.398146 |   0.435333 |
| Bori_Aron_solution-1 |     0.535476 |       0.533037 |   0.529459 |
| k-d_tree_pandas      |     7.74371  |       0.395348 |   0.56743  |
| k-d_tree_sklearn     |     3.09774  |       0.962394 |   0.999182 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554251 |       0.401545 |   0.393069 |
| k-d_tree_polars      |     0.559575 |       0.404295 |   0.404209 |
| barab-szabi-1        |     0.558238 |       0.411678 |   0.447361 |
| Bori_Aron_solution-1 |     0.549248 |       0.545232 |   0.533608 |
| k-d_tree_pandas      |     0.559019 |       0.38387  |   0.541116 |
| k-d_tree_sklearn     |     0.561188 |       0.937357 |   1.01062  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560926 |       0.408873 |   0.409035 |
| k-d_tree_polars      |     0.551338 |       0.423614 |   0.444016 |
| barab-szabi-1        |     0.555866 |       0.427061 |   0.448452 |
| Bori_Aron_solution-1 |     0.549895 |       0.58008  |   0.541032 |
| k-d_tree_pandas      |     0.554802 |       0.397299 |   0.592823 |
| k-d_tree_sklearn     |     0.562382 |       0.975199 |   1.06133  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554701 |       0.480693 |   0.44708  |
| k-d_tree_polars      |     0.552894 |       0.547072 |   0.527615 |
| barab-szabi-1        |     0.565684 |       0.528276 |   0.532984 |
| Bori_Aron_solution-1 |     0.549885 |       0.7425   |   0.548674 |
| k-d_tree_pandas      |     0.556075 |       0.468047 |   0.71935  |
| k-d_tree_sklearn     |     0.560762 |       1.19374  |   1.0784   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558268 |       0.709595 |   0.4803   |
| Bori_Aron_solution-1 |     0.551184 |       1.3612   |   0.583486 |
| k-d_tree_polars      |     0.559726 |       0.871518 |   0.862197 |
| barab-szabi-1        |     0.560854 |       0.857415 |   0.907432 |
| k-d_tree_pandas      |     0.549547 |       0.732781 |   1.14921  |
| k-d_tree_sklearn     |     0.596291 |       2.03233  |   1.18355  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558284 |        5.15315 |   0.734949 |
| Bori_Aron_solution-1 |     0.555864 |       10.4239  |   0.867803 |
| k-d_tree_sklearn     |     0.55993  |       15.6271  |   1.29959  |
| k-d_tree_polars      |     0.562282 |        4.92825 |   6.40583  |
| barab-szabi-1        |     0.562269 |        4.91726 |   6.47355  |
| k-d_tree_pandas      |     0.556424 |        3.85534 |   6.81121  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.856193 |        70.5361 |    3.57843 |
| k-d_tree_sklearn     |     0.651798 |       225.627  |    4.19208 |
| Bori_Aron_solution-1 |     0.554666 |       153.938  |   16.1325  |