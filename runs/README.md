# 2025-05-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.519271 |       0.407205 |   0.415687 |
| barab-szabi-2        |     0.534004 |       0.41413  |   0.417458 |
| k-d_tree_polars      |     4.03059  |       0.433106 |   0.426544 |
| Bori_Aron_solution-1 |     4.61418  |       0.692221 |   0.507919 |
| k-d_tree_pandas      |     0.511046 |       0.388751 |   0.55229  |
| solution-1           |     7.81233  |       1e-06    |   0.562937 |
| k-d_tree_sklearn     |     3.03245  |       1.08476  |   1.03483  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.523154 |       0.41119  |   0.41276  |
| k-d_tree_polars      |     0.522594 |       0.410489 |   0.420609 |
| barab-szabi-1        |     0.528786 |       0.411871 |   0.427435 |
| Bori_Aron_solution-1 |     0.514395 |       0.57368  |   0.546008 |
| k-d_tree_pandas      |     0.524305 |       0.395125 |   0.562165 |
| k-d_tree_sklearn     |     0.536851 |       0.966406 |   1.05216  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.522789 |       0.42698  |   0.431551 |
| k-d_tree_polars      |     0.51979  |       0.437419 |   0.44268  |
| barab-szabi-1        |     0.521174 |       0.438325 |   0.450206 |
| Bori_Aron_solution-1 |     0.512242 |       0.5914   |   0.558697 |
| k-d_tree_pandas      |     0.520801 |       0.409641 |   0.6099   |
| k-d_tree_sklearn     |     0.528722 |       1.01284  |   1.06357  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540561 |       0.500059 |   0.460051 |
| k-d_tree_polars      |     0.528558 |       0.558325 |   0.546271 |
| barab-szabi-1        |     0.534051 |       0.555674 |   0.561397 |
| Bori_Aron_solution-1 |     0.534868 |       0.763624 |   0.564131 |
| k-d_tree_pandas      |     0.530021 |       0.501904 |   0.758045 |
| k-d_tree_sklearn     |     0.534601 |       1.27269  |   1.18049  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.514407 |       0.719511 |   0.484936 |
| Bori_Aron_solution-1 |     0.529859 |       1.41529  |   0.597978 |
| k-d_tree_polars      |     0.522565 |       0.885144 |   0.890142 |
| barab-szabi-1        |     0.52137  |       0.880157 |   0.932881 |
| k-d_tree_pandas      |     0.517121 |       0.76257  |   1.17377  |
| k-d_tree_sklearn     |     0.534671 |       2.06338  |   1.19547  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.519356 |        5.35226 |   0.746714 |
| Bori_Aron_solution-1 |     0.507186 |       10.5165  |   0.888077 |
| k-d_tree_sklearn     |     0.544706 |       16.4682  |   1.34209  |
| k-d_tree_polars      |     0.518985 |        5.00543 |   6.41981  |
| barab-szabi-1        |     0.51788  |        5.10528 |   6.75494  |
| k-d_tree_pandas      |     0.542024 |        4.0238  |   7.17764  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579058 |        74.9064 |    2.85353 |
| k-d_tree_sklearn     |     0.759821 |       232.534  |    4.23    |
| Bori_Aron_solution-1 |     0.526885 |       147.649  |   17.6082  |