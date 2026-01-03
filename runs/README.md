# 2026-01-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.55391  |       1e-06    |   0.380443 |
| barab-szabi-2        |     0.532517 |       0.470753 |   0.44298  |
| barab-szabi-1        |     0.550971 |       0.428826 |   0.450948 |
| k-d_tree_polars      |     0.549848 |       0.425978 |   0.451014 |
| Bori_Aron_solution-1 |     0.549849 |       0.566564 |   0.580323 |
| k-d_tree_pandas      |     8.59516  |       0.428068 |   0.651478 |
| k-d_tree_sklearn     |     3.0031   |       1.06659  |   1.13227  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580559 |       0.454529 |   0.446712 |
| k-d_tree_polars      |     0.54802  |       0.4226   |   0.453302 |
| barab-szabi-1        |     0.542021 |       0.434411 |   0.478193 |
| Bori_Aron_solution-1 |     0.544764 |       0.577663 |   0.592093 |
| k-d_tree_pandas      |     0.547478 |       0.405895 |   0.61688  |
| k-d_tree_sklearn     |     0.547556 |       1.02874  |   1.13411  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544451 |       0.463732 |   0.465268 |
| barab-szabi-1        |     0.540069 |       0.461622 |   0.480135 |
| k-d_tree_polars      |     0.55604  |       0.464138 |   0.481251 |
| Bori_Aron_solution-1 |     0.539003 |       0.611814 |   0.574745 |
| k-d_tree_pandas      |     0.553793 |       0.431837 |   0.622902 |
| k-d_tree_sklearn     |     0.555179 |       1.07659  |   1.15928  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543715 |       0.521117 |   0.494117 |
| k-d_tree_polars      |     0.541812 |       0.583843 |   0.580074 |
| Bori_Aron_solution-1 |     0.551435 |       0.817937 |   0.589589 |
| barab-szabi-1        |     0.551946 |       0.578347 |   0.591976 |
| k-d_tree_pandas      |     0.549667 |       0.530423 |   0.759308 |
| k-d_tree_sklearn     |     0.547104 |       1.30709  |   1.20373  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538864 |       0.777185 |   0.548664 |
| Bori_Aron_solution-1 |     0.542027 |       1.51972  |   0.604909 |
| k-d_tree_polars      |     0.539829 |       0.958781 |   0.968179 |
| barab-szabi-1        |     0.554394 |       0.961152 |   1.00299  |
| k-d_tree_pandas      |     0.543599 |       0.83646  |   1.22462  |
| k-d_tree_sklearn     |     0.5522   |       2.24768  |   1.28165  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550013 |        5.68257 |   0.796287 |
| Bori_Aron_solution-1 |     0.543938 |       11.7621  |   0.898619 |
| k-d_tree_sklearn     |     0.56651  |       18.1764  |   1.4268   |
| barab-szabi-1        |     0.560762 |        5.52645 |   7.1053   |
| k-d_tree_polars      |     0.555303 |        5.4986  |   7.11112  |
| k-d_tree_pandas      |     0.549855 |        4.47734 |   7.50315  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546395 |         84.206 |    2.87646 |
| k-d_tree_sklearn     |     0.563472 |        258.39  |    4.41376 |
| Bori_Aron_solution-1 |     0.750764 |        155.505 |   18.3149  |