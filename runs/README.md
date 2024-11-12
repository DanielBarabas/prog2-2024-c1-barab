# 2024-11-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.614442 |       0.395005 |   0.386613 |
| barab-szabi-2        |     0.634083 |       0.402702 |   0.394708 |
| k-d_tree_polars      |     0.650994 |       0.408223 |   0.399142 |
| solution-1           |     7.64069  |       1e-06    |   0.504328 |
| Bori_Aron_solution-1 |     0.614496 |       0.525836 |   0.531353 |
| k-d_tree_pandas      |     0.668897 |       0.388484 |   0.538041 |
| k-d_tree_sklearn     |    10.5091   |       1.06965  |   0.98537  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.638592 |       0.42142  |   0.404819 |
| k-d_tree_polars      |     0.639928 |       0.417626 |   0.408303 |
| barab-szabi-2        |     0.646402 |       0.42802  |   0.411768 |
| Bori_Aron_solution-1 |     0.626895 |       0.546339 |   0.538093 |
| k-d_tree_pandas      |     0.653756 |       0.413524 |   0.570721 |
| k-d_tree_sklearn     |     0.651619 |       0.929922 |   0.999039 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.657286 |       0.412822 |   0.417142 |
| barab-szabi-1        |     0.642881 |       0.458047 |   0.429898 |
| k-d_tree_polars      |     0.648942 |       0.449399 |   0.432401 |
| Bori_Aron_solution-1 |     0.632558 |       0.591662 |   0.559468 |
| k-d_tree_pandas      |     0.680492 |       0.419125 |   0.611958 |
| k-d_tree_sklearn     |     0.681888 |       1.06536  |   1.10399  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631603 |       0.491897 |   0.449488 |
| k-d_tree_polars      |     0.664369 |       0.564663 |   0.525901 |
| barab-szabi-1        |     0.63623  |       0.564652 |   0.562888 |
| Bori_Aron_solution-1 |     0.654359 |       0.783199 |   0.565464 |
| k-d_tree_pandas      |     0.642703 |       0.504641 |   0.753121 |
| k-d_tree_sklearn     |     0.645665 |       1.20273  |   1.11303  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.644439 |       0.747007 |   0.576079 |
| Bori_Aron_solution-1 |     0.635705 |       1.43846  |   0.578473 |
| k-d_tree_polars      |     0.663116 |       0.882471 |   0.926077 |
| barab-szabi-1        |     0.647878 |       0.899565 |   0.93995  |
| k-d_tree_pandas      |     0.642551 |       0.761044 |   1.19243  |
| k-d_tree_sklearn     |     0.655514 |       2.10554  |   1.21378  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627301 |        5.41828 |   0.733537 |
| Bori_Aron_solution-1 |     0.645621 |       10.4377  |   0.80807  |
| k-d_tree_sklearn     |     0.633209 |       16.8751  |   1.28349  |
| k-d_tree_polars      |     0.639774 |        4.81053 |   6.48078  |
| barab-szabi-1        |     0.632323 |        4.85055 |   6.62641  |
| k-d_tree_pandas      |     0.604575 |        3.81275 |   6.8007   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.648003 |        74.0801 |    2.91467 |
| k-d_tree_sklearn     |     0.624358 |       228.861  |    4.2424  |
| Bori_Aron_solution-1 |     0.642674 |       145.972  |   17.8515  |