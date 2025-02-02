# 2025-02-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.17055  |       1e-06    |   0.363617 |
| barab-szabi-2        |     7.66778  |       0.595387 |   0.398341 |
| k-d_tree_polars      |     0.577604 |       0.403298 |   0.402266 |
| barab-szabi-1        |     0.588427 |       0.403185 |   0.404956 |
| k-d_tree_pandas      |     0.596313 |       0.39469  |   0.540321 |
| Bori_Aron_solution-1 |     0.586545 |       0.544439 |   0.541828 |
| k-d_tree_sklearn     |     2.91237  |       1.22375  |   1.03371  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.589667 |       0.416927 |   0.40586  |
| barab-szabi-2        |     0.613205 |       0.410339 |   0.406936 |
| barab-szabi-1        |     0.589831 |       0.411241 |   0.412866 |
| Bori_Aron_solution-1 |     0.609977 |       0.548083 |   0.538448 |
| k-d_tree_pandas      |     0.591422 |       0.395213 |   0.551841 |
| k-d_tree_sklearn     |     0.591589 |       0.94961  |   1.04189  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587796 |       0.427224 |   0.41854  |
| barab-szabi-1        |     0.59114  |       0.433884 |   0.439616 |
| k-d_tree_polars      |     0.594555 |       0.434558 |   0.44216  |
| Bori_Aron_solution-1 |     0.614955 |       0.581258 |   0.54249  |
| k-d_tree_pandas      |     0.594485 |       0.407779 |   0.589497 |
| k-d_tree_sklearn     |     0.605705 |       0.997912 |   1.0493   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607722 |       0.483555 |   0.453244 |
| k-d_tree_polars      |     0.593974 |       0.543698 |   0.535979 |
| barab-szabi-1        |     0.591478 |       0.539615 |   0.539124 |
| Bori_Aron_solution-1 |     0.584039 |       0.745487 |   0.549274 |
| k-d_tree_pandas      |     0.592136 |       0.481807 |   0.734098 |
| k-d_tree_sklearn     |     0.597996 |       1.23903  |   1.12087  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.592948 |       0.730866 |   0.48138  |
| Bori_Aron_solution-1 |     0.585077 |       1.39361  |   0.582242 |
| k-d_tree_polars      |     0.587671 |       0.867983 |   0.894486 |
| barab-szabi-1        |     0.595595 |       0.869886 |   0.929909 |
| k-d_tree_pandas      |     0.617562 |       0.744345 |   1.16945  |
| k-d_tree_sklearn     |     0.596452 |       2.04777  |   1.2333   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590075 |        5.62695 |   0.740854 |
| Bori_Aron_solution-1 |     0.58334  |       10.9657  |   0.871161 |
| k-d_tree_sklearn     |     0.599086 |       16.7954  |   1.31846  |
| k-d_tree_polars      |     0.593407 |        4.92828 |   6.90396  |
| barab-szabi-1        |     0.59254  |        4.90929 |   6.92313  |
| k-d_tree_pandas      |     0.597037 |        3.81858 |   7.31906  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58959  |        74.2521 |    2.9509  |
| k-d_tree_sklearn     |     0.610236 |       228.52   |    4.45567 |
| Bori_Aron_solution-1 |     0.667951 |       150.984  |   17.322   |