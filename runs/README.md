# 2026-05-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.466969 |       0.418964 |   0.435412 |
| barab-szabi-2        |     0.47339  |       0.444155 |   0.438852 |
| solution-1           |     7.60011  |       1e-06    |   0.459351 |
| k-d_tree_pandas      |     0.469895 |       0.389032 |   0.547744 |
| barab-szabi-1        |     8.23556  |       0.460361 |   0.576341 |
| Bori_Aron_solution-1 |     0.519645 |       0.583995 |   0.619511 |
| k-d_tree_sklearn     |     3.01979  |       1.2029   |   1.10106  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473693 |       0.438958 |   0.430385 |
| barab-szabi-1        |     0.494065 |       0.414103 |   0.43064  |
| k-d_tree_polars      |     0.472302 |       0.411318 |   0.438089 |
| Bori_Aron_solution-1 |     0.468047 |       0.559697 |   0.550824 |
| k-d_tree_pandas      |     0.480525 |       0.391089 |   0.566242 |
| k-d_tree_sklearn     |     0.478174 |       0.985906 |   1.10895  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.46995  |       0.441491 |   0.439785 |
| barab-szabi-1        |     0.466218 |       0.438963 |   0.462285 |
| k-d_tree_polars      |     0.478641 |       0.445082 |   0.463877 |
| Bori_Aron_solution-1 |     0.46401  |       0.614498 |   0.571891 |
| k-d_tree_pandas      |     0.486046 |       0.415514 |   0.608547 |
| k-d_tree_sklearn     |     0.487494 |       1.06156  |   1.10989  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478211 |       0.510158 |   0.468214 |
| barab-szabi-1        |     0.474694 |       0.561684 |   0.570993 |
| k-d_tree_polars      |     0.473957 |       0.571143 |   0.573606 |
| Bori_Aron_solution-1 |     0.464089 |       0.793073 |   0.585625 |
| k-d_tree_pandas      |     0.485283 |       0.502412 |   0.727239 |
| k-d_tree_sklearn     |     0.481927 |       1.2868   |   1.15037  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480213 |       0.770841 |   0.532637 |
| Bori_Aron_solution-1 |     0.475212 |       1.52176  |   0.592138 |
| k-d_tree_polars      |     0.481825 |       0.923563 |   0.98839  |
| barab-szabi-1        |     0.47376  |       0.922673 |   1.02081  |
| k-d_tree_pandas      |     0.479983 |       0.78738  |   1.19611  |
| k-d_tree_sklearn     |     0.485989 |       2.23572  |   1.21688  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466817 |        5.6557  |   0.716366 |
| Bori_Aron_solution-1 |     0.4726   |       11.732   |   0.835373 |
| k-d_tree_sklearn     |     0.477356 |       17.9453  |   1.30272  |
| barab-szabi-1        |     0.475819 |        5.26401 |   7.39863  |
| k-d_tree_polars      |     0.467571 |        5.19524 |   7.46858  |
| k-d_tree_pandas      |     0.471888 |        4.23086 |   7.85984  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486004 |        77.1368 |    2.35732 |
| k-d_tree_sklearn     |     0.486631 |       262.683  |    3.10108 |
| Bori_Aron_solution-1 |     0.465475 |       153.735  |   24.6439  |