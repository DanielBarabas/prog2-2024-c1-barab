# 2026-08-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.497548 |       0.454292 |   0.457997 |
| solution-1           |     8.95295  |       1e-06    |   0.462223 |
| barab-szabi-2        |     0.49511  |       0.463069 |   0.469328 |
| Bori_Aron_solution-1 |     0.947018 |       0.577222 |   0.582367 |
| k-d_tree_pandas      |     0.48563  |       0.401835 |   0.587158 |
| k-d_tree_polars      |     9.19569  |       0.496704 |   0.622282 |
| k-d_tree_sklearn     |     3.58577  |       1.22582  |   1.18071  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.500202 |       0.460847 |   0.469332 |
| k-d_tree_polars      |     0.491971 |       0.45656  |   0.481636 |
| barab-szabi-2        |     0.51951  |       0.50344  |   0.483256 |
| Bori_Aron_solution-1 |     0.496751 |       0.611967 |   0.574344 |
| k-d_tree_pandas      |     0.497779 |       0.416097 |   0.603845 |
| k-d_tree_sklearn     |     0.50056  |       1.08679  |   1.19214  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.486156 |       0.476102 |   0.485351 |
| k-d_tree_polars      |     0.506996 |       0.49619  |   0.499583 |
| barab-szabi-2        |     0.490157 |       0.472591 |   0.50056  |
| Bori_Aron_solution-1 |     0.487458 |       0.6316   |   0.576663 |
| k-d_tree_pandas      |     0.481987 |       0.425011 |   0.618749 |
| k-d_tree_sklearn     |     0.490306 |       1.08658  |   1.13512  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487101 |       0.531941 |   0.484505 |
| Bori_Aron_solution-1 |     0.473676 |       0.792749 |   0.571281 |
| k-d_tree_polars      |     0.497769 |       0.581079 |   0.576274 |
| barab-szabi-1        |     0.474248 |       0.582222 |   0.613831 |
| k-d_tree_pandas      |     0.481761 |       0.501012 |   0.73176  |
| k-d_tree_sklearn     |     0.485912 |       1.32563  |   1.17327  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476092 |       0.796322 |   0.614993 |
| Bori_Aron_solution-1 |     0.495401 |       1.53075  |   0.6369   |
| k-d_tree_polars      |     0.493405 |       0.909396 |   1.01683  |
| barab-szabi-1        |     0.506691 |       0.934041 |   1.07828  |
| k-d_tree_pandas      |     0.512453 |       0.767742 |   1.1946   |
| k-d_tree_sklearn     |     0.512697 |       2.40554  |   1.31045  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.494592 |        6.15824 |   0.779853 |
| Bori_Aron_solution-1 |     0.501282 |       11.5345  |   0.808935 |
| k-d_tree_sklearn     |     0.468261 |       19.212   |   1.3523   |
| barab-szabi-1        |     0.489661 |        5.19925 |   8.01723  |
| k-d_tree_polars      |     0.495505 |        5.0777  |   8.03266  |
| k-d_tree_pandas      |     0.490295 |        4.07413 |   8.42159  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567611 |        81.1116 |    2.87901 |
| k-d_tree_sklearn     |     0.813422 |       269.575  |    3.579   |
| Bori_Aron_solution-1 |     0.497555 |       160.585  |   25.2608  |