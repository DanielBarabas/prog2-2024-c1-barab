# 2026-03-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.448697 |       0.40993  |   0.410547 |
| solution-1           |     7.20151  |       1e-06    |   0.426007 |
| k-d_tree_polars      |     0.447515 |       0.392668 |   0.430562 |
| k-d_tree_pandas      |     0.461807 |       0.376107 |   0.532583 |
| Bori_Aron_solution-1 |     0.433586 |       0.529509 |   0.539673 |
| barab-szabi-1        |     8.16499  |       0.458569 |   0.555784 |
| k-d_tree_sklearn     |     2.82329  |       1.06758  |   1.03623  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47056  |       0.434867 |   0.431107 |
| k-d_tree_polars      |     0.449894 |       0.405795 |   0.43574  |
| barab-szabi-1        |     0.464593 |       0.451756 |   0.456187 |
| Bori_Aron_solution-1 |     0.458224 |       0.550175 |   0.531263 |
| k-d_tree_pandas      |     0.47186  |       0.379103 |   0.550018 |
| k-d_tree_sklearn     |     0.45869  |       0.944039 |   1.00043  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.453041 |       0.433282 |   0.430412 |
| k-d_tree_polars      |     0.490298 |       0.414377 |   0.44178  |
| barab-szabi-1        |     0.462007 |       0.414109 |   0.450042 |
| Bori_Aron_solution-1 |     0.45046  |       0.573323 |   0.5374   |
| k-d_tree_pandas      |     0.460992 |       0.400388 |   0.571559 |
| k-d_tree_sklearn     |     0.455249 |       0.997366 |   1.01707  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.452343 |       0.483865 |   0.445395 |
| k-d_tree_polars      |     0.445207 |       0.529272 |   0.514817 |
| barab-szabi-1        |     0.455485 |       0.542474 |   0.535975 |
| Bori_Aron_solution-1 |     0.443054 |       0.722669 |   0.540047 |
| k-d_tree_pandas      |     0.445928 |       0.457611 |   0.682342 |
| k-d_tree_sklearn     |     0.46346  |       1.16037  |   1.04606  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.446997 |       0.689166 |   0.504459 |
| Bori_Aron_solution-1 |     0.452671 |       1.31141  |   0.571069 |
| k-d_tree_polars      |     0.508465 |       0.856828 |   0.819805 |
| barab-szabi-1        |     0.453463 |       0.852245 |   0.863893 |
| k-d_tree_pandas      |     0.464568 |       0.711443 |   1.06334  |
| k-d_tree_sklearn     |     0.440643 |       2.00653  |   1.12705  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456758 |        4.89057 |   0.693773 |
| Bori_Aron_solution-1 |     0.483761 |        9.80659 |   0.857171 |
| k-d_tree_sklearn     |     0.451492 |       14.6362  |   1.32988  |
| k-d_tree_polars      |     0.448956 |        4.79275 |   5.9239   |
| barab-szabi-1        |     0.448849 |        4.812   |   5.99296  |
| k-d_tree_pandas      |     0.448258 |        3.7296  |   6.28807  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.453628 |        66.6524 |    2.49704 |
| k-d_tree_sklearn     |     0.76262  |       182.766  |    3.82876 |
| Bori_Aron_solution-1 |     0.441263 |       134.114  |   23.6419  |