# 2024-06-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.758117 |       0.386326 |   0.385446 |
| barab-szabi-1        |     0.809706 |       0.387567 |   0.388133 |
| k-d_tree_polars      |     0.750906 |       0.394167 |   0.401194 |
| Bori_Aron_solution-1 |     0.753972 |       0.533264 |   0.504348 |
| solution-1           |     8.31751  |       1e-06    |   0.557069 |
| k-d_tree_pandas      |     9.84335  |       0.440585 |   0.706416 |
| k-d_tree_sklearn     |     3.43244  |       0.980341 |   0.712314 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.808965 |       0.396378 |   0.391389 |
| k-d_tree_polars      |     0.806237 |       0.395177 |   0.398316 |
| barab-szabi-2        |     0.798887 |       0.389098 |   0.400372 |
| Bori_Aron_solution-1 |     0.787188 |       0.526968 |   0.507827 |
| k-d_tree_pandas      |     0.807912 |       0.379428 |   0.561471 |
| k-d_tree_sklearn     |     0.840693 |       0.965582 |   0.741112 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.807791 |       0.396514 |   0.396949 |
| k-d_tree_polars      |     0.799951 |       0.421118 |   0.418079 |
| barab-szabi-1        |     0.794768 |       0.419305 |   0.419668 |
| Bori_Aron_solution-1 |     0.788981 |       0.554705 |   0.535375 |
| k-d_tree_pandas      |     0.800097 |       0.38819  |   0.567028 |
| k-d_tree_sklearn     |     0.809813 |       0.938993 |   0.750154 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.793353 |       0.461663 |   0.428069 |
| k-d_tree_polars      |     0.80216  |       0.528468 |   0.514268 |
| Bori_Aron_solution-1 |     0.7931   |       0.741303 |   0.527852 |
| barab-szabi-1        |     0.805767 |       0.529768 |   0.529542 |
| k-d_tree_pandas      |     0.792819 |       0.476757 |   0.695457 |
| k-d_tree_sklearn     |     0.81866  |       1.2109   |   0.825393 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.79682  |       0.705421 |   0.465336 |
| Bori_Aron_solution-1 |     0.787475 |       1.38425  |   0.552406 |
| k-d_tree_polars      |     0.793619 |       0.860453 |   0.864256 |
| k-d_tree_sklearn     |     0.803878 |       1.99144  |   0.905734 |
| barab-szabi-1        |     0.798494 |       0.851246 |   0.906365 |
| k-d_tree_pandas      |     0.791497 |       0.769631 |   1.12636  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.796967 |        5.06928 |   0.757649 |
| Bori_Aron_solution-1 |     0.780749 |       10.5055  |   0.842357 |
| k-d_tree_sklearn     |     0.799047 |       16.3294  |   1.0756   |
| k-d_tree_polars      |     0.798337 |        4.97479 |   6.35356  |
| k-d_tree_pandas      |     0.800372 |        4.02849 |   6.71229  |
| barab-szabi-1        |     0.805943 |        4.98875 |   6.73835  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.13304  |        70.5358 |    3.76616 |
| k-d_tree_sklearn     |     0.926036 |       224.097  |    4.54845 |
| Bori_Aron_solution-1 |     0.827012 |       161.964  |   18.8544  |