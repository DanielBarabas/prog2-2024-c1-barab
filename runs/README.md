# 2026-08-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.499478 |       0.461205 |   0.460718 |
| barab-szabi-1        |     0.49445  |       0.432748 |   0.461876 |
| solution-1           |     7.98313  |       1e-06    |   0.489037 |
| k-d_tree_pandas      |     0.49166  |       0.405998 |   0.57606  |
| Bori_Aron_solution-1 |     0.467857 |       0.620394 |   0.608183 |
| k-d_tree_polars      |     9.3003   |       0.506097 |   0.642364 |
| k-d_tree_sklearn     |     3.81326  |       1.18802  |   1.15037  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.504286 |       0.459894 |   0.472596 |
| barab-szabi-2        |     0.505934 |       0.481351 |   0.479542 |
| k-d_tree_polars      |     0.508616 |       0.457007 |   0.480908 |
| Bori_Aron_solution-1 |     0.491992 |       0.597299 |   0.571691 |
| k-d_tree_pandas      |     0.491218 |       0.439731 |   0.595664 |
| k-d_tree_sklearn     |     0.502456 |       1.09387  |   1.14186  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.506084 |       0.478881 |   0.501311 |
| barab-szabi-1        |     0.526783 |       0.485941 |   0.51156  |
| k-d_tree_polars      |     0.502807 |       0.51959  |   0.521288 |
| Bori_Aron_solution-1 |     0.503086 |       0.629462 |   0.590031 |
| k-d_tree_pandas      |     0.514581 |       0.44422  |   0.638283 |
| k-d_tree_sklearn     |     0.509896 |       1.15757  |   1.26055  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48998  |       0.536888 |   0.508893 |
| k-d_tree_polars      |     0.510278 |       0.618963 |   0.598042 |
| Bori_Aron_solution-1 |     0.491007 |       0.8139   |   0.60647  |
| barab-szabi-1        |     0.492625 |       0.598559 |   0.616302 |
| k-d_tree_pandas      |     0.497088 |       0.524006 |   0.769344 |
| k-d_tree_sklearn     |     0.503151 |       1.36082  |   1.24989  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.501134 |       0.790867 |   0.596493 |
| Bori_Aron_solution-1 |     0.481311 |       1.4912   |   0.617794 |
| k-d_tree_polars      |     0.496147 |       0.958351 |   0.967365 |
| barab-szabi-1        |     0.49716  |       0.956263 |   1.00969  |
| k-d_tree_pandas      |     0.504119 |       0.835207 |   1.24502  |
| k-d_tree_sklearn     |     0.496021 |       2.27973  |   1.31467  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.504458 |       11.7428  |   0.860538 |
| barab-szabi-2        |     0.535523 |        5.96334 |   0.876104 |
| k-d_tree_sklearn     |     0.51413  |       18.9968  |   1.47943  |
| barab-szabi-1        |     0.501411 |        5.47982 |   7.34883  |
| k-d_tree_polars      |     0.495901 |        5.43595 |   7.55411  |
| k-d_tree_pandas      |     0.492447 |        4.44066 |   7.93536  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625696 |        81.4541 |    3.41912 |
| k-d_tree_sklearn     |     0.81569  |       250.374  |    4.2423  |
| Bori_Aron_solution-1 |     0.493547 |       159.434  |   22.7298  |