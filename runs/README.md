# 2026-01-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.55215  |       0.413936 |   0.442063 |
| k-d_tree_polars      |     0.54499  |       0.418312 |   0.443433 |
| barab-szabi-2        |     0.535976 |       0.674595 |   0.449218 |
| solution-1           |     8.45919  |       1e-06    |   0.574265 |
| Bori_Aron_solution-1 |     0.531581 |       0.563277 |   0.574342 |
| k-d_tree_pandas      |     9.72552  |       0.424889 |   0.73414  |
| k-d_tree_sklearn     |     3.42637  |       1.19772  |   1.11634  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.537918 |       0.412902 |   0.441342 |
| k-d_tree_polars      |     0.550606 |       0.434667 |   0.444788 |
| barab-szabi-2        |     0.535596 |       0.451979 |   0.470564 |
| Bori_Aron_solution-1 |     0.535171 |       0.557243 |   0.548881 |
| k-d_tree_pandas      |     0.541069 |       0.392075 |   0.557798 |
| k-d_tree_sklearn     |     0.565588 |       0.990573 |   1.09105  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552204 |       0.454913 |   0.456862 |
| k-d_tree_polars      |     0.538202 |       0.442955 |   0.477686 |
| barab-szabi-1        |     0.537753 |       0.443491 |   0.494218 |
| Bori_Aron_solution-1 |     0.540902 |       0.608354 |   0.561513 |
| k-d_tree_pandas      |     0.537094 |       0.424312 |   0.628508 |
| k-d_tree_sklearn     |     0.542437 |       1.0293   |   1.17847  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535825 |       0.507318 |   0.483468 |
| k-d_tree_polars      |     0.537277 |       0.585871 |   0.570592 |
| Bori_Aron_solution-1 |     0.525082 |       0.790698 |   0.571764 |
| barab-szabi-1        |     0.539011 |       0.576296 |   0.576149 |
| k-d_tree_pandas      |     0.553689 |       0.50558  |   0.752322 |
| k-d_tree_sklearn     |     0.543458 |       1.35339  |   1.18761  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544769 |       0.730306 |   0.518049 |
| Bori_Aron_solution-1 |     0.527982 |       1.50753  |   0.637362 |
| k-d_tree_polars      |     0.543316 |       0.939143 |   0.933902 |
| barab-szabi-1        |     0.565914 |       0.935879 |   0.967474 |
| k-d_tree_pandas      |     0.531757 |       0.821495 |   1.1748   |
| k-d_tree_sklearn     |     0.53359  |       2.22575  |   1.28196  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535905 |        5.26807 |   0.807537 |
| Bori_Aron_solution-1 |     0.53101  |       11.3888  |   0.860537 |
| k-d_tree_sklearn     |     0.543174 |       17.564   |   1.36337  |
| k-d_tree_polars      |     0.53415  |        5.65425 |   6.6064   |
| barab-szabi-1        |     0.537457 |        5.68713 |   6.72065  |
| k-d_tree_pandas      |     0.542551 |        4.34327 |   7.15186  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550814 |        82.0303 |    2.97064 |
| k-d_tree_sklearn     |     0.569366 |       249.206  |    4.25698 |
| Bori_Aron_solution-1 |     0.683207 |       150.441  |   17.8372  |