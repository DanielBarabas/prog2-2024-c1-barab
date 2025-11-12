# 2025-11-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535232 |       0.520261 |   0.449424 |
| solution-1           |     7.44002  |       1e-06    |   0.451228 |
| barab-szabi-1        |     0.56505  |       0.428504 |   0.452306 |
| k-d_tree_polars      |     0.549528 |       0.422044 |   0.467841 |
| Bori_Aron_solution-1 |     0.556297 |       0.583849 |   0.59565  |
| k-d_tree_pandas      |     8.46896  |       0.464968 |   0.692772 |
| k-d_tree_sklearn     |     3.23034  |       1.26324  |   1.07902  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.546429 |       0.424499 |   0.438059 |
| barab-szabi-1        |     0.551435 |       0.416777 |   0.449672 |
| barab-szabi-2        |     0.568327 |       0.467543 |   0.461799 |
| Bori_Aron_solution-1 |     0.528788 |       0.575954 |   0.584848 |
| k-d_tree_pandas      |     0.566788 |       0.463116 |   0.619187 |
| k-d_tree_sklearn     |     0.561708 |       1.0705   |   1.14234  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541534 |       0.456607 |   0.47024  |
| k-d_tree_polars      |     0.570574 |       0.477656 |   0.503843 |
| barab-szabi-1        |     0.558569 |       0.483427 |   0.506578 |
| Bori_Aron_solution-1 |     0.560084 |       0.643424 |   0.600289 |
| k-d_tree_pandas      |     0.569177 |       0.447878 |   0.637707 |
| k-d_tree_sklearn     |     0.564161 |       1.0998   |   1.22671  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56078  |       0.533571 |   0.508116 |
| k-d_tree_polars      |     0.584973 |       0.598693 |   0.589972 |
| barab-szabi-1        |     0.56418  |       0.595684 |   0.605778 |
| Bori_Aron_solution-1 |     0.559326 |       0.845408 |   0.616621 |
| k-d_tree_pandas      |     0.564771 |       0.545286 |   0.794919 |
| k-d_tree_sklearn     |     0.565449 |       1.34997  |   1.28379  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562419 |       0.812088 |   0.600465 |
| Bori_Aron_solution-1 |     0.556772 |       1.54302  |   0.633852 |
| k-d_tree_polars      |     0.557793 |       0.955865 |   0.981334 |
| barab-szabi-1        |     0.600718 |       0.950351 |   1.01623  |
| k-d_tree_pandas      |     0.571503 |       0.836172 |   1.25981  |
| k-d_tree_sklearn     |     0.564852 |       2.29082  |   1.33506  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560279 |        5.68738 |   0.811475 |
| Bori_Aron_solution-1 |     0.555794 |       11.6012  |   0.871939 |
| k-d_tree_sklearn     |     0.58017  |       18.0996  |   1.45529  |
| k-d_tree_polars      |     0.566822 |        5.52051 |   6.92197  |
| barab-szabi-1        |     0.580753 |        5.48048 |   7.0759   |
| k-d_tree_pandas      |     0.563524 |        4.49095 |   7.6088   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558199 |        75.7818 |    2.93369 |
| k-d_tree_sklearn     |     0.559515 |       253.511  |    4.27098 |
| Bori_Aron_solution-1 |     0.665611 |       156.696  |   15.3095  |