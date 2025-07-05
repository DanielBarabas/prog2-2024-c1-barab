# 2025-07-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580014 |       0.463423 |   0.450001 |
| barab-szabi-1        |     0.585752 |       0.44139  |   0.452438 |
| k-d_tree_polars      |     0.596057 |       0.4241   |   0.454658 |
| solution-1           |     8.49204  |       1e-06    |   0.461273 |
| k-d_tree_pandas      |     0.57952  |       0.407329 |   0.575758 |
| Bori_Aron_solution-1 |     0.587434 |       0.586501 |   0.607667 |
| k-d_tree_sklearn     |    10.8347   |       1.29774  |   1.12606  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611212 |       0.446412 |   0.451372 |
| barab-szabi-1        |     0.606881 |       0.447469 |   0.458097 |
| k-d_tree_polars      |     0.585175 |       0.442191 |   0.462949 |
| Bori_Aron_solution-1 |     0.573108 |       0.590935 |   0.581228 |
| k-d_tree_pandas      |     0.583477 |       0.429819 |   0.610729 |
| k-d_tree_sklearn     |     0.585876 |       1.01558  |   1.15139  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.578384 |       0.472342 |   0.467245 |
| barab-szabi-1        |     0.586704 |       0.45859  |   0.477994 |
| k-d_tree_polars      |     0.577913 |       0.459516 |   0.479683 |
| Bori_Aron_solution-1 |     0.581206 |       0.619088 |   0.584581 |
| k-d_tree_pandas      |     0.571969 |       0.482208 |   0.633507 |
| k-d_tree_sklearn     |     0.596166 |       1.08998  |   1.1796   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581859 |       0.526835 |   0.495186 |
| k-d_tree_polars      |     0.582846 |       0.57662  |   0.571439 |
| barab-szabi-1        |     0.604147 |       0.590265 |   0.601571 |
| Bori_Aron_solution-1 |     0.58152  |       0.807334 |   0.615358 |
| k-d_tree_pandas      |     0.586264 |       0.510377 |   0.785836 |
| k-d_tree_sklearn     |     0.584937 |       1.31912  |   1.23173  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588251 |       0.813721 |   0.621584 |
| Bori_Aron_solution-1 |     0.583113 |       1.49759  |   0.629341 |
| k-d_tree_polars      |     0.582764 |       0.92688  |   0.974516 |
| barab-szabi-1        |     0.602319 |       0.910639 |   1.01975  |
| k-d_tree_pandas      |     0.599921 |       0.794513 |   1.27947  |
| k-d_tree_sklearn     |     0.59209  |       2.29405  |   1.30997  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561483 |        5.55883 |   0.749949 |
| Bori_Aron_solution-1 |     0.564213 |       11.2316  |   0.909456 |
| k-d_tree_sklearn     |     0.576536 |       17.5286  |   1.37207  |
| k-d_tree_polars      |     0.567236 |        5.00343 |   6.88319  |
| barab-szabi-1        |     0.575392 |        4.99842 |   6.92013  |
| k-d_tree_pandas      |     0.56506  |        3.96968 |   7.28881  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.615723 |       236.006  |    4.04708 |
| barab-szabi-2        |     0.61274  |        85.4962 |    5.44727 |
| Bori_Aron_solution-1 |     0.768348 |       145.908  |   17.1377  |