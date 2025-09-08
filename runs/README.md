# 2025-09-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.52939  |       1.11788  |   0.417552 |
| k-d_tree_polars      |     0.522165 |       0.400175 |   0.418625 |
| barab-szabi-1        |     0.525741 |       0.398445 |   0.420276 |
| Bori_Aron_solution-1 |     0.516499 |       0.538563 |   0.538702 |
| k-d_tree_pandas      |     0.522731 |       0.380813 |   0.540958 |
| solution-1           |     7.1612   |       1e-06    |   0.708094 |
| k-d_tree_sklearn     |     2.95865  |       1.38528  |   1.03724  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.535403 |       0.404934 |   0.42759  |
| k-d_tree_polars      |     0.542322 |       0.413271 |   0.428978 |
| barab-szabi-2        |     0.536869 |       0.424158 |   0.500118 |
| Bori_Aron_solution-1 |     0.543508 |       0.54722  |   0.537083 |
| k-d_tree_pandas      |     0.538674 |       0.384075 |   0.548546 |
| k-d_tree_sklearn     |     0.540297 |       0.95704  |   1.05056  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53469  |       0.462155 |   0.435997 |
| barab-szabi-1        |     0.539434 |       0.436228 |   0.459856 |
| k-d_tree_polars      |     0.545098 |       0.450169 |   0.462055 |
| Bori_Aron_solution-1 |     0.532723 |       0.586566 |   0.551584 |
| k-d_tree_pandas      |     0.542496 |       0.409897 |   0.591996 |
| k-d_tree_sklearn     |     0.547903 |       1.02144  |   1.07309  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547347 |       0.498154 |   0.465296 |
| k-d_tree_polars      |     0.533099 |       0.546463 |   0.548687 |
| barab-szabi-1        |     0.534332 |       0.541699 |   0.560455 |
| Bori_Aron_solution-1 |     0.529855 |       0.759563 |   0.567223 |
| k-d_tree_pandas      |     0.536551 |       0.483324 |   0.730901 |
| k-d_tree_sklearn     |     0.538764 |       1.22851  |   1.12203  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534306 |       0.739744 |   0.494982 |
| Bori_Aron_solution-1 |     0.530857 |       1.39315  |   0.576308 |
| k-d_tree_polars      |     0.542617 |       0.883502 |   0.914116 |
| barab-szabi-1        |     0.540059 |       0.889657 |   0.953892 |
| k-d_tree_pandas      |     0.535846 |       0.758567 |   1.19071  |
| k-d_tree_sklearn     |     0.542012 |       2.09427  |   1.21659  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541363 |        5.35403 |   0.737768 |
| Bori_Aron_solution-1 |     0.535423 |       10.7199  |   0.837531 |
| k-d_tree_sklearn     |     0.543123 |       16.4996  |   1.30165  |
| barab-szabi-1        |     0.539233 |        5.01906 |   6.65175  |
| k-d_tree_polars      |     0.538579 |        4.92626 |   6.67361  |
| k-d_tree_pandas      |     0.53423  |        3.91479 |   6.95509  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544631 |        73.1385 |    2.66231 |
| k-d_tree_sklearn     |     1.14281  |       229.063  |    3.94281 |
| Bori_Aron_solution-1 |     0.538407 |       139.203  |   18.2237  |