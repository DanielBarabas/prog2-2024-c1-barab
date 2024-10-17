# 2024-10-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.630688 |       0.398367 |   0.390445 |
| barab-szabi-1        |     0.632233 |       0.408013 |   0.395097 |
| k-d_tree_polars      |     0.629222 |       0.43828  |   0.398028 |
| solution-1           |     7.88022  |       1e-06    |   0.403622 |
| k-d_tree_pandas      |     0.643219 |       0.39066  |   0.531713 |
| Bori_Aron_solution-1 |     0.621985 |       0.543941 |   0.543834 |
| k-d_tree_sklearn     |    10.3581   |       1.16782  |   1.00956  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621669 |       0.413048 |   0.395234 |
| k-d_tree_polars      |     0.625939 |       0.405509 |   0.397608 |
| barab-szabi-1        |     0.630143 |       0.41743  |   0.408018 |
| Bori_Aron_solution-1 |     0.622525 |       0.545235 |   0.525771 |
| k-d_tree_pandas      |     0.627942 |       0.390529 |   0.606278 |
| k-d_tree_sklearn     |     0.635032 |       0.934053 |   1.00107  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.648048 |       0.414915 |   0.413255 |
| k-d_tree_polars      |     0.630146 |       0.444087 |   0.420297 |
| barab-szabi-1        |     0.631665 |       0.440048 |   0.436042 |
| Bori_Aron_solution-1 |     0.619983 |       0.577914 |   0.535939 |
| k-d_tree_pandas      |     0.664603 |       0.413295 |   0.593766 |
| k-d_tree_sklearn     |     0.645052 |       0.968071 |   1.00288  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.630834 |       0.477878 |   0.436893 |
| k-d_tree_polars      |     0.633116 |       0.546857 |   0.520921 |
| barab-szabi-1        |     0.630297 |       0.545943 |   0.53548  |
| Bori_Aron_solution-1 |     0.621888 |       0.757747 |   0.55135  |
| k-d_tree_pandas      |     0.625345 |       0.495071 |   0.732902 |
| k-d_tree_sklearn     |     0.635274 |       1.20311  |   1.07109  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619575 |       0.728967 |   0.492828 |
| Bori_Aron_solution-1 |     0.6304   |       1.41587  |   0.584603 |
| k-d_tree_polars      |     0.644083 |       0.87498  |   0.876413 |
| barab-szabi-1        |     0.629441 |       0.873851 |   0.923626 |
| k-d_tree_pandas      |     0.625166 |       0.777379 |   1.18321  |
| k-d_tree_sklearn     |     0.634617 |       2.04891  |   1.18677  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629822 |        5.47203 |   0.716396 |
| Bori_Aron_solution-1 |     0.610256 |       10.9318  |   0.820847 |
| k-d_tree_sklearn     |     0.636062 |       17.0447  |   1.28983  |
| barab-szabi-1        |     0.621711 |        4.90655 |   6.65706  |
| k-d_tree_polars      |     0.63297  |        4.92889 |   6.86274  |
| k-d_tree_pandas      |     0.642721 |        3.943   |   7.22176  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626945 |        72.7888 |    2.99112 |
| k-d_tree_sklearn     |     0.637676 |       232.166  |    4.28989 |
| Bori_Aron_solution-1 |     0.654185 |       152.637  |   17.5702  |