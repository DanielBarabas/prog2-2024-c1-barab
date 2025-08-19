# 2025-08-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.542246 |       0.443231 |   0.429738 |
| barab-szabi-1        |     0.531987 |       0.416095 |   0.446049 |
| solution-1           |     8.06943  |       1e-06    |   0.447246 |
| barab-szabi-2        |     0.534384 |       0.445047 |   0.448962 |
| Bori_Aron_solution-1 |     0.542092 |       0.546638 |   0.553373 |
| k-d_tree_pandas      |     8.4788   |       0.421327 |   0.688514 |
| k-d_tree_sklearn     |     3.23355  |       1.10451  |   1.069    |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548511 |       0.428535 |   0.431804 |
| k-d_tree_polars      |     0.545135 |       0.421375 |   0.43277  |
| barab-szabi-1        |     0.54384  |       0.419116 |   0.433885 |
| Bori_Aron_solution-1 |     0.543455 |       0.565271 |   0.547682 |
| k-d_tree_pandas      |     0.548947 |       0.400679 |   0.571388 |
| k-d_tree_sklearn     |     0.554064 |       0.982109 |   1.06667  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540055 |       0.439044 |   0.445248 |
| k-d_tree_polars      |     0.551111 |       0.441493 |   0.458136 |
| barab-szabi-1        |     0.544279 |       0.434171 |   0.462175 |
| Bori_Aron_solution-1 |     0.53576  |       0.595592 |   0.557042 |
| k-d_tree_pandas      |     0.545374 |       0.410115 |   0.609783 |
| k-d_tree_sklearn     |     0.557376 |       1.02278  |   1.0971   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54425  |       0.505604 |   0.469305 |
| k-d_tree_polars      |     0.546462 |       0.553194 |   0.554875 |
| Bori_Aron_solution-1 |     0.539228 |       0.767308 |   0.560817 |
| barab-szabi-1        |     0.547823 |       0.558897 |   0.570046 |
| k-d_tree_pandas      |     0.546363 |       0.503137 |   0.741995 |
| k-d_tree_sklearn     |     0.548024 |       1.25885  |   1.13784  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548323 |       0.752152 |   0.505052 |
| Bori_Aron_solution-1 |     0.542265 |       1.41339  |   0.585488 |
| k-d_tree_polars      |     0.551057 |       0.889602 |   0.916621 |
| barab-szabi-1        |     0.542579 |       0.894251 |   0.957062 |
| k-d_tree_pandas      |     0.542515 |       0.762505 |   1.18962  |
| k-d_tree_sklearn     |     0.548643 |       2.10675  |   1.21581  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546399 |        5.39196 |   0.765739 |
| Bori_Aron_solution-1 |     0.540486 |       10.7617  |   0.85271  |
| k-d_tree_sklearn     |     0.555398 |       16.4696  |   1.34737  |
| k-d_tree_polars      |     0.551523 |        5.06441 |   6.66578  |
| barab-szabi-1        |     0.554741 |        5.05603 |   6.69462  |
| k-d_tree_pandas      |     0.546372 |        3.89305 |   7.07387  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548445 |        71.8255 |    2.70459 |
| k-d_tree_sklearn     |     0.574258 |       229.494  |    4.29066 |
| Bori_Aron_solution-1 |     0.731858 |       141.398  |   17.9716  |