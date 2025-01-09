# 2025-01-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.63825  |       1e-06    |   0.38935  |
| barab-szabi-1        |     0.595057 |       0.434124 |   0.415091 |
| barab-szabi-2        |     0.601427 |       0.428652 |   0.419999 |
| k-d_tree_polars      |     0.610609 |       0.430707 |   0.423066 |
| Bori_Aron_solution-1 |     0.642078 |       0.601471 |   0.590239 |
| k-d_tree_pandas      |     8.11974  |       0.417286 |   0.615801 |
| k-d_tree_sklearn     |     3.07338  |       1.07824  |   1.09078  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.61459  |       0.44596  |   0.423028 |
| barab-szabi-1        |     0.655778 |       0.486212 |   0.444783 |
| barab-szabi-2        |     0.653911 |       0.445922 |   0.46721  |
| Bori_Aron_solution-1 |     0.617172 |       0.596928 |   0.556089 |
| k-d_tree_pandas      |     0.65058  |       0.442257 |   0.600042 |
| k-d_tree_sklearn     |     0.628002 |       1.0336   |   1.11352  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612018 |       0.437966 |   0.42242  |
| k-d_tree_polars      |     0.61691  |       0.448782 |   0.441541 |
| barab-szabi-1        |     0.613706 |       0.469848 |   0.461714 |
| Bori_Aron_solution-1 |     0.595321 |       0.598495 |   0.592238 |
| k-d_tree_pandas      |     0.630383 |       0.434105 |   0.612676 |
| k-d_tree_sklearn     |     0.621923 |       1.04997  |   1.12108  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610811 |       0.510977 |   0.47204  |
| k-d_tree_polars      |     0.650511 |       0.562331 |   0.547042 |
| barab-szabi-1        |     0.627311 |       0.545449 |   0.558258 |
| Bori_Aron_solution-1 |     0.604659 |       0.770277 |   0.592872 |
| k-d_tree_pandas      |     0.625928 |       0.523118 |   0.753116 |
| k-d_tree_sklearn     |     0.60714  |       1.24772  |   1.17094  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605822 |       0.738022 |   0.509691 |
| Bori_Aron_solution-1 |     0.60647  |       1.41882  |   0.617535 |
| k-d_tree_polars      |     0.609566 |       0.892997 |   0.910331 |
| barab-szabi-1        |     0.598241 |       0.887729 |   0.957722 |
| k-d_tree_pandas      |     0.607244 |       0.766195 |   1.19892  |
| k-d_tree_sklearn     |     0.623123 |       2.09234  |   1.25133  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607937 |        5.86343 |   0.8048   |
| Bori_Aron_solution-1 |     0.63286  |       11.0001  |   0.905578 |
| k-d_tree_sklearn     |     0.618855 |       17.4747  |   1.39795  |
| barab-szabi-1        |     0.617865 |        4.87534 |   7.19722  |
| k-d_tree_polars      |     0.621047 |        4.8922  |   7.21435  |
| k-d_tree_pandas      |     0.62442  |        3.8726  |   7.39905  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.653565 |        77.2574 |    3.17118 |
| k-d_tree_sklearn     |     0.630321 |       235.024  |    4.59259 |
| Bori_Aron_solution-1 |     0.731138 |       147.353  |   19.0594  |