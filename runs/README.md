# 2025-04-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545463 |       0.404501 |   0.401633 |
| k-d_tree_polars      |     0.546045 |       0.397238 |   0.402381 |
| barab-szabi-1        |     0.544788 |       0.433667 |   0.450258 |
| Bori_Aron_solution-1 |     0.956869 |       0.527751 |   0.52755  |
| solution-1           |     8.00298  |       1e-06    |   0.595804 |
| k-d_tree_pandas      |     8.38478  |       0.488076 |   0.743832 |
| k-d_tree_sklearn     |     3.2243   |       1.19086  |   1.01318  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558689 |       0.411465 |   0.397813 |
| k-d_tree_polars      |     0.560167 |       0.40247  |   0.405794 |
| barab-szabi-1        |     0.557392 |       0.402471 |   0.408891 |
| Bori_Aron_solution-1 |     0.549419 |       0.559711 |   0.534537 |
| k-d_tree_pandas      |     0.560829 |       0.383295 |   0.548104 |
| k-d_tree_sklearn     |     0.586023 |       0.940557 |   1.0205   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559354 |       0.417227 |   0.428455 |
| k-d_tree_polars      |     0.556661 |       0.430014 |   0.440848 |
| barab-szabi-1        |     0.560308 |       0.427367 |   0.441117 |
| Bori_Aron_solution-1 |     0.552517 |       0.60339  |   0.534887 |
| k-d_tree_pandas      |     0.563997 |       0.404197 |   0.584489 |
| k-d_tree_sklearn     |     0.561334 |       0.997221 |   1.03742  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556336 |       0.480916 |   0.44079  |
| k-d_tree_polars      |     0.561657 |       0.532329 |   0.530589 |
| barab-szabi-1        |     0.559375 |       0.535713 |   0.544158 |
| Bori_Aron_solution-1 |     0.549948 |       0.747434 |   0.545516 |
| k-d_tree_pandas      |     0.559903 |       0.476193 |   0.7265   |
| k-d_tree_sklearn     |     0.561718 |       1.20141  |   1.09784  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557353 |       0.72277  |   0.475048 |
| Bori_Aron_solution-1 |     0.548735 |       1.36935  |   0.583188 |
| k-d_tree_polars      |     0.557769 |       0.860049 |   0.882161 |
| barab-szabi-1        |     0.556638 |       0.854311 |   0.915603 |
| k-d_tree_pandas      |     0.558167 |       0.732111 |   1.15431  |
| k-d_tree_sklearn     |     0.56154  |       2.01826  |   1.17333  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558907 |        5.31691 |   0.705264 |
| Bori_Aron_solution-1 |     0.554666 |       10.5468  |   0.866586 |
| k-d_tree_sklearn     |     0.560928 |       15.8573  |   1.296    |
| barab-szabi-1        |     0.561107 |        4.8909  |   6.59576  |
| k-d_tree_polars      |     0.558444 |        4.88145 |   6.61356  |
| k-d_tree_pandas      |     0.558275 |        3.79639 |   6.98978  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.673621 |        70.0404 |    2.64988 |
| k-d_tree_sklearn     |     0.61141  |       224.11   |    4.0784  |
| Bori_Aron_solution-1 |     0.554105 |       144.925  |   16.1344  |