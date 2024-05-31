# 2024-05-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.80049  |       0.398432 |   0.342968 |
| barab-szabi-2        |     5.22853  |       0.348889 |   0.344126 |
| barab-szabi-1        |     0.790857 |       0.400424 |   0.346596 |
| solution-1           |     8.36428  |       1e-06    |   0.394384 |
| Bori_Aron_solution-1 |     4.67151  |       0.408709 |   0.404366 |
| k-d_tree_pandas      |     0.791923 |       0.380428 |   0.480463 |
| k-d_tree_sklearn     |     3.46985  |       0.991307 |   0.676803 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.782373 |       0.345751 |   0.337821 |
| k-d_tree_polars      |     0.783786 |       0.408251 |   0.3479   |
| barab-szabi-1        |     0.79153  |       0.40556  |   0.351032 |
| Bori_Aron_solution-1 |     0.7805   |       0.477411 |   0.470918 |
| k-d_tree_pandas      |     0.788943 |       0.386643 |   0.496381 |
| k-d_tree_sklearn     |     0.816786 |       0.847579 |   0.675754 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.788544 |       0.359694 |   0.364889 |
| k-d_tree_polars      |     0.791496 |       0.431726 |   0.372701 |
| barab-szabi-1        |     0.788011 |       0.432735 |   0.378172 |
| Bori_Aron_solution-1 |     0.777977 |       0.516669 |   0.474396 |
| k-d_tree_pandas      |     0.797102 |       0.408648 |   0.523936 |
| k-d_tree_sklearn     |     0.798516 |       0.897776 |   0.701288 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.780402 |       0.422995 |   0.387714 |
| k-d_tree_polars      |     0.798745 |       0.54086  |   0.481603 |
| Bori_Aron_solution-1 |     0.787206 |       0.710102 |   0.488192 |
| barab-szabi-1        |     0.792162 |       0.561381 |   0.49216  |
| k-d_tree_pandas      |     0.809146 |       0.514898 |   0.673644 |
| k-d_tree_sklearn     |     0.793872 |       1.12252  |   0.765295 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.785829 |       0.673009 |   0.426997 |
| Bori_Aron_solution-1 |     0.780551 |       1.34206  |   0.515096 |
| k-d_tree_polars      |     0.784124 |       0.868618 |   0.822791 |
| barab-szabi-1        |     0.791131 |       0.869305 |   0.860952 |
| k-d_tree_sklearn     |     0.794791 |       1.93576  |   0.870665 |
| k-d_tree_pandas      |     0.781632 |       0.762691 |   1.08874  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.784694 |        5.24726 |   0.729883 |
| Bori_Aron_solution-1 |     0.781048 |       10.6755  |   0.769057 |
| k-d_tree_sklearn     |     0.804055 |       15.8766  |   1.03539  |
| k-d_tree_polars      |     0.787946 |        4.96469 |   6.44158  |
| barab-szabi-1        |     0.782096 |        4.942   |   6.45496  |
| k-d_tree_pandas      |     0.791855 |        4.01901 |   6.76969  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.1114   |        71.4162 |    3.94636 |
| k-d_tree_sklearn     |     0.866016 |       227.195  |    4.56004 |
| Bori_Aron_solution-1 |     0.782345 |       152.366  |   18.632   |