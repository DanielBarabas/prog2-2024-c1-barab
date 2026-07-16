# 2026-07-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.64322  |       1e-06    |   0.412835 |
| k-d_tree_polars      |     0.475605 |       0.423685 |   0.442707 |
| barab-szabi-2        |     0.478428 |       0.456364 |   0.474663 |
| k-d_tree_pandas      |     0.474467 |       0.42327  |   0.561894 |
| Bori_Aron_solution-1 |     0.472154 |       0.578424 |   0.58948  |
| barab-szabi-1        |     8.21787  |       1.04013  |   0.60177  |
| k-d_tree_sklearn     |     3.55583  |       1.23896  |   1.10176  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.475984 |       0.451042 |   0.453129 |
| barab-szabi-2        |     0.484214 |       0.459593 |   0.454089 |
| k-d_tree_polars      |     0.48204  |       0.43803  |   0.454149 |
| Bori_Aron_solution-1 |     0.479289 |       0.562822 |   0.556437 |
| k-d_tree_pandas      |     0.477236 |       0.403495 |   0.564337 |
| k-d_tree_sklearn     |     0.482682 |       1.02832  |   1.12318  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487885 |       0.453111 |   0.45899  |
| k-d_tree_polars      |     0.496773 |       0.474218 |   0.483198 |
| barab-szabi-1        |     0.49488  |       0.450106 |   0.484844 |
| Bori_Aron_solution-1 |     0.473956 |       0.596017 |   0.55931  |
| k-d_tree_pandas      |     0.479071 |       0.417151 |   0.619074 |
| k-d_tree_sklearn     |     0.480426 |       1.086    |   1.12154  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483785 |       0.521904 |   0.489487 |
| k-d_tree_polars      |     0.481809 |       0.585939 |   0.572281 |
| Bori_Aron_solution-1 |     0.484078 |       0.791284 |   0.576888 |
| barab-szabi-1        |     0.480787 |       0.598135 |   0.59588  |
| k-d_tree_pandas      |     0.480933 |       0.50351  |   0.732208 |
| k-d_tree_sklearn     |     0.491096 |       1.29318  |   1.14627  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477196 |       0.787843 |   0.53871  |
| Bori_Aron_solution-1 |     0.471819 |       1.47248  |   0.609945 |
| k-d_tree_polars      |     0.485774 |       0.91131  |   0.952813 |
| barab-szabi-1        |     0.475234 |       0.911953 |   1.00407  |
| k-d_tree_sklearn     |     0.477148 |       2.13248  |   1.15476  |
| k-d_tree_pandas      |     0.467991 |       0.75757  |   1.18601  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473062 |        5.49207 |   0.730531 |
| Bori_Aron_solution-1 |     0.47054  |       11.1893  |   0.802586 |
| k-d_tree_sklearn     |     0.486718 |       17.0848  |   1.28956  |
| barab-szabi-1        |     0.479027 |        5.15629 |   7.4248   |
| k-d_tree_polars      |     0.484682 |        5.10838 |   7.46879  |
| k-d_tree_pandas      |     0.502393 |        4.04582 |   7.72004  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.657499 |       269.787  |    3.57329 |
| barab-szabi-2        |     0.476255 |        79.1227 |    4.27546 |
| Bori_Aron_solution-1 |     0.468053 |       157.26   |   18.1682  |