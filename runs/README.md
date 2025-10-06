# 2025-10-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.569675 |       0.426201 |   0.444273 |
| k-d_tree_polars      |     0.581635 |       0.429937 |   0.45841  |
| barab-szabi-2        |     0.81679  |       0.753329 |   0.471356 |
| Bori_Aron_solution-1 |     0.5666   |       0.57843  |   0.573492 |
| k-d_tree_pandas      |     8.52172  |       0.444935 |   0.811052 |
| solution-1           |     8.1123   |       1e-06    |   0.8698   |
| k-d_tree_sklearn     |     3.16743  |       1.27905  |   1.07828  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.559047 |       0.441046 |   0.443468 |
| k-d_tree_polars      |     0.550066 |       0.421784 |   0.447856 |
| barab-szabi-2        |     0.576954 |       0.442358 |   0.452411 |
| Bori_Aron_solution-1 |     0.549201 |       0.57758  |   0.559038 |
| k-d_tree_pandas      |     0.57746  |       0.441408 |   0.664856 |
| k-d_tree_sklearn     |     0.55779  |       1.03671  |   1.1052   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556593 |       0.456051 |   0.451421 |
| k-d_tree_polars      |     0.566566 |       0.47178  |   0.474444 |
| barab-szabi-1        |     0.581568 |       0.457924 |   0.495892 |
| k-d_tree_pandas      |     0.549342 |       0.423837 |   0.61752  |
| Bori_Aron_solution-1 |     0.551788 |       0.619374 |   0.634922 |
| k-d_tree_sklearn     |     0.563559 |       1.09244  |   1.28349  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569811 |       0.531725 |   0.50374  |
| Bori_Aron_solution-1 |     0.544192 |       0.816583 |   0.573893 |
| k-d_tree_polars      |     0.577621 |       0.582202 |   0.57519  |
| barab-szabi-1        |     0.567174 |       0.610603 |   0.621969 |
| k-d_tree_pandas      |     0.550979 |       0.516484 |   0.803806 |
| k-d_tree_sklearn     |     0.588372 |       1.34799  |   1.2583   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57562  |       0.827018 |   0.537814 |
| Bori_Aron_solution-1 |     0.597317 |       1.54906  |   0.634029 |
| barab-szabi-1        |     0.578264 |       0.970852 |   0.971388 |
| k-d_tree_polars      |     0.551636 |       0.998314 |   0.982812 |
| k-d_tree_pandas      |     0.567649 |       0.849343 |   1.22352  |
| k-d_tree_sklearn     |     0.592586 |       2.16194  |   1.2783   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586535 |        5.44483 |   0.763795 |
| Bori_Aron_solution-1 |     0.541716 |       11.3941  |   0.862162 |
| k-d_tree_sklearn     |     0.589219 |       17.255   |   1.38979  |
| k-d_tree_polars      |     0.551029 |        5.7131  |   6.58372  |
| barab-szabi-1        |     0.578687 |        5.6121  |   6.6152   |
| k-d_tree_pandas      |     0.569299 |        4.57992 |   7.24884  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561229 |        74.2705 |    2.75188 |
| k-d_tree_sklearn     |     0.566022 |       242.102  |    4.15116 |
| Bori_Aron_solution-1 |     0.770255 |       153.403  |   17.4167  |