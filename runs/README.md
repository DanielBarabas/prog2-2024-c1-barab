# 2026-04-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.84065  |       1e-06    |   0.39883  |
| k-d_tree_polars      |     0.472254 |       0.423938 |   0.441049 |
| barab-szabi-1        |     0.489492 |       0.414874 |   0.450114 |
| barab-szabi-2        |     0.477357 |       0.444205 |   0.45444  |
| Bori_Aron_solution-1 |     0.461103 |       0.564504 |   0.573675 |
| k-d_tree_pandas      |     0.488092 |       0.401341 |   0.578713 |
| k-d_tree_sklearn     |    10.4426   |       1.31437  |   1.11535  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476137 |       0.441402 |   0.444113 |
| barab-szabi-1        |     0.475702 |       0.418957 |   0.456656 |
| k-d_tree_polars      |     0.465734 |       0.449051 |   0.457433 |
| Bori_Aron_solution-1 |     0.464675 |       0.569742 |   0.561409 |
| k-d_tree_pandas      |     0.467883 |       0.401896 |   0.570925 |
| k-d_tree_sklearn     |     0.545434 |       1.01719  |   1.09022  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473869 |       0.456894 |   0.457217 |
| k-d_tree_polars      |     0.476872 |       0.471592 |   0.480263 |
| barab-szabi-1        |     0.480183 |       0.462297 |   0.490187 |
| Bori_Aron_solution-1 |     0.458667 |       0.610382 |   0.557436 |
| k-d_tree_pandas      |     0.480226 |       0.429204 |   0.611974 |
| k-d_tree_sklearn     |     0.475889 |       1.0542   |   1.13067  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.459325 |       0.515821 |   0.478822 |
| k-d_tree_polars      |     0.461277 |       0.568854 |   0.572851 |
| Bori_Aron_solution-1 |     0.476893 |       0.79011  |   0.574577 |
| barab-szabi-1        |     0.463126 |       0.574502 |   0.581602 |
| k-d_tree_pandas      |     0.46847  |       0.506634 |   0.746678 |
| k-d_tree_sklearn     |     0.49433  |       1.29978  |   1.16668  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472344 |       0.75958  |   0.518537 |
| Bori_Aron_solution-1 |     0.459137 |       1.51453  |   0.607108 |
| k-d_tree_polars      |     0.465199 |       0.941912 |   0.94572  |
| barab-szabi-1        |     0.472922 |       0.951337 |   0.988447 |
| k-d_tree_pandas      |     0.479122 |       0.852829 |   1.21607  |
| k-d_tree_sklearn     |     0.46884  |       2.19589  |   1.26454  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460807 |        5.17432 |   0.776971 |
| Bori_Aron_solution-1 |     0.503192 |       12.149   |   0.904987 |
| k-d_tree_sklearn     |     0.469542 |       20.1873  |   1.45198  |
| k-d_tree_polars      |     0.480147 |        5.59064 |   6.93598  |
| barab-szabi-1        |     0.461483 |        5.5574  |   7.25984  |
| k-d_tree_pandas      |     0.474115 |        4.50706 |   7.35432  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.714935 |        76.8565 |    3.62735 |
| k-d_tree_sklearn     |     0.468664 |       246.427  |    3.77475 |
| Bori_Aron_solution-1 |     0.465959 |       166.925  |   17.0279  |