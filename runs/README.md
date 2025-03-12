# 2025-03-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560762 |       0.407938 |   0.408416 |
| k-d_tree_polars      |     0.571285 |       0.417952 |   0.424754 |
| barab-szabi-1        |     0.563152 |       0.403621 |   0.427976 |
| Bori_Aron_solution-1 |     0.550134 |       0.546075 |   0.550514 |
| solution-1           |     7.87379  |       1e-06    |   0.655518 |
| k-d_tree_pandas      |     8.16644  |       0.486933 |   0.699721 |
| k-d_tree_sklearn     |     3.27208  |       1.19453  |   1.05531  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.586139 |       0.41565  |   0.419073 |
| barab-szabi-1        |     0.58357  |       0.421861 |   0.435451 |
| barab-szabi-2        |     0.576248 |       0.421866 |   0.510325 |
| k-d_tree_pandas      |     0.581615 |       0.402706 |   0.569541 |
| Bori_Aron_solution-1 |     0.582642 |       0.566929 |   0.571184 |
| k-d_tree_sklearn     |     0.580317 |       0.97921  |   1.08185  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585248 |       0.484365 |   0.435723 |
| k-d_tree_polars      |     0.579381 |       0.561287 |   0.442311 |
| barab-szabi-1        |     0.580309 |       0.442527 |   0.444941 |
| Bori_Aron_solution-1 |     0.566532 |       0.591867 |   0.558121 |
| k-d_tree_pandas      |     0.573701 |       0.411313 |   0.604496 |
| k-d_tree_sklearn     |     0.577932 |       1.02862  |   1.0831   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57434  |       0.496318 |   0.457555 |
| k-d_tree_polars      |     0.578682 |       0.543826 |   0.53827  |
| barab-szabi-1        |     0.577584 |       0.547143 |   0.549893 |
| Bori_Aron_solution-1 |     0.577449 |       0.770366 |   0.569939 |
| k-d_tree_pandas      |     0.572323 |       0.488357 |   0.745603 |
| k-d_tree_sklearn     |     0.579633 |       1.23136  |   1.14274  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583926 |       0.743683 |   0.500427 |
| Bori_Aron_solution-1 |     0.560473 |       1.38009  |   0.58401  |
| k-d_tree_polars      |     0.562643 |       0.871549 |   0.886412 |
| barab-szabi-1        |     0.557673 |       0.856816 |   0.929074 |
| k-d_tree_pandas      |     0.568336 |       0.743716 |   1.17312  |
| k-d_tree_sklearn     |     0.582001 |       2.08501  |   1.21032  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560343 |        5.3395  |   0.777421 |
| Bori_Aron_solution-1 |     0.555415 |       10.5013  |   0.872808 |
| k-d_tree_sklearn     |     0.573417 |       16.2298  |   1.32454  |
| barab-szabi-1        |     0.562026 |        4.9511  |   6.51362  |
| k-d_tree_polars      |     0.56449  |        4.95324 |   6.59419  |
| k-d_tree_pandas      |     0.562148 |        3.77338 |   7.03324  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.813792 |         75.888 |    3.42509 |
| k-d_tree_sklearn     |     0.672739 |        240.045 |    4.27015 |
| Bori_Aron_solution-1 |     0.563105 |        154.511 |   16.3705  |