# 2024-03-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.707532 |       0.561519 |   0.358225 |
| k-d_tree_polars      |     0.739963 |       0.413023 |   0.366984 |
| barab-szabi-1        |     0.726362 |       0.408211 |   0.367055 |
| Bori_Aron_solution-1 |     0.699814 |       0.526785 |   0.506104 |
| k-d_tree_sklearn     |     3.47497  |       1.16871  |   0.674751 |
| solution-1           |     9.74932  |       1e-06    |   0.688557 |
| k-d_tree_pandas      |     8.62309  |       0.450675 |   0.787514 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.736402 |       0.371252 |   0.364356 |
| k-d_tree_polars      |     0.73534  |       0.418211 |   0.365416 |
| barab-szabi-1        |     0.7363   |       0.415894 |   0.368744 |
| k-d_tree_pandas      |     0.739428 |       0.404296 |   0.511173 |
| Bori_Aron_solution-1 |     0.723459 |       0.51333  |   0.513548 |
| k-d_tree_sklearn     |     0.74191  |       0.888803 |   0.686852 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.739885 |       0.384243 |   0.374657 |
| barab-szabi-1        |     0.729709 |       0.428092 |   0.401463 |
| k-d_tree_polars      |     0.745429 |       0.436343 |   0.407574 |
| Bori_Aron_solution-1 |     0.752939 |       0.553772 |   0.503346 |
| k-d_tree_pandas      |     0.73547  |       0.404423 |   0.559806 |
| k-d_tree_sklearn     |     0.769133 |       0.916738 |   0.704888 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.737222 |       0.446886 |   0.429211 |
| k-d_tree_polars      |     0.736721 |       0.558231 |   0.49399  |
| barab-szabi-1        |     0.742926 |       0.548642 |   0.508921 |
| Bori_Aron_solution-1 |     0.735747 |       0.730628 |   0.526136 |
| k-d_tree_pandas      |     0.733907 |       0.49841  |   0.689246 |
| k-d_tree_sklearn     |     0.749618 |       1.13309  |   0.781501 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732336 |       0.678264 |   0.442377 |
| Bori_Aron_solution-1 |     0.723093 |       1.36134  |   0.538078 |
| k-d_tree_polars      |     0.728766 |       0.863145 |   0.825557 |
| k-d_tree_sklearn     |     0.739369 |       1.91948  |   0.858903 |
| barab-szabi-1        |     0.724379 |       0.871542 |   0.872983 |
| k-d_tree_pandas      |     0.74071  |       0.759905 |   1.12424  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.72488  |        5.40021 |   0.747985 |
| Bori_Aron_solution-1 |     0.723593 |       10.8149  |   0.803987 |
| k-d_tree_sklearn     |     0.742421 |       16.6347  |   1.08238  |
| k-d_tree_polars      |     0.734355 |        4.9738  |   6.64799  |
| barab-szabi-1        |     0.735805 |        4.86625 |   6.65222  |
| k-d_tree_pandas      |     0.729099 |        3.99924 |   7.01617  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.744534 |        71.8193 |    3.70899 |
| k-d_tree_sklearn     |     0.905238 |       227.845  |    4.79601 |
| Bori_Aron_solution-1 |     0.811041 |       146.09   |   14.2098  |