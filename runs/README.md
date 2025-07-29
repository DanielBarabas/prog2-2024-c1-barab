# 2025-07-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.547725 |       0.405035 |   0.422371 |
| barab-szabi-2        |     7.64747  |       0.610909 |   0.423053 |
| k-d_tree_polars      |     0.563306 |       0.409102 |   0.429528 |
| solution-1           |     7.31168  |       1e-06    |   0.452703 |
| Bori_Aron_solution-1 |     0.531147 |       0.560978 |   0.549417 |
| k-d_tree_pandas      |     0.558409 |       0.389561 |   0.600723 |
| k-d_tree_sklearn     |     2.93085  |       1.12421  |   1.06161  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563446 |       0.421285 |   0.425551 |
| k-d_tree_polars      |     0.560811 |       0.413157 |   0.430143 |
| barab-szabi-1        |     0.557672 |       0.41665  |   0.434477 |
| Bori_Aron_solution-1 |     0.545768 |       0.552066 |   0.546558 |
| k-d_tree_pandas      |     0.562344 |       0.395334 |   0.563584 |
| k-d_tree_sklearn     |     0.554072 |       0.981876 |   1.06644  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569778 |       0.435642 |   0.439392 |
| k-d_tree_polars      |     0.552315 |       0.434639 |   0.456352 |
| barab-szabi-1        |     0.566682 |       0.440416 |   0.458834 |
| Bori_Aron_solution-1 |     0.548691 |       0.587029 |   0.554179 |
| k-d_tree_pandas      |     0.560182 |       0.412744 |   0.621037 |
| k-d_tree_sklearn     |     0.58711  |       1.03003  |   1.08579  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559986 |       0.514096 |   0.464719 |
| k-d_tree_polars      |     0.557577 |       0.557978 |   0.549271 |
| Bori_Aron_solution-1 |     0.550499 |       0.771117 |   0.564038 |
| barab-szabi-1        |     0.559397 |       0.566322 |   0.572304 |
| k-d_tree_pandas      |     0.555547 |       0.48501  |   0.736859 |
| k-d_tree_sklearn     |     0.557562 |       1.25435  |   1.14169  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55823  |       0.74668  |   0.497192 |
| Bori_Aron_solution-1 |     0.546364 |       1.41767  |   0.600161 |
| k-d_tree_polars      |     0.553836 |       0.89173  |   0.903007 |
| barab-szabi-1        |     0.555072 |       0.890909 |   0.942411 |
| k-d_tree_pandas      |     0.555445 |       0.753977 |   1.17241  |
| k-d_tree_sklearn     |     0.562592 |       2.06261  |   1.22247  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552101 |        5.36802 |   0.747675 |
| Bori_Aron_solution-1 |     0.550648 |       10.7201  |   0.855141 |
| k-d_tree_sklearn     |     0.562849 |       16.3965  |   1.31945  |
| k-d_tree_polars      |     0.554619 |        5.05764 |   6.64156  |
| barab-szabi-1        |     0.557784 |        5.04506 |   6.67082  |
| k-d_tree_pandas      |     0.559673 |        3.90898 |   7.03941  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55192  |        71.1341 |    2.64379 |
| k-d_tree_sklearn     |     0.686778 |       230.861  |    4.02426 |
| Bori_Aron_solution-1 |     0.556523 |       140.747  |   18.3409  |