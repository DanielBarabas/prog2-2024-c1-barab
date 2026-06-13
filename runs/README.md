# 2026-06-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.457615 |       0.397061 |   0.435072 |
| barab-szabi-2        |     7.93851  |       0.753574 |   0.446203 |
| k-d_tree_polars      |     0.489917 |       0.521123 |   0.495367 |
| Bori_Aron_solution-1 |     0.454443 |       0.540213 |   0.542359 |
| k-d_tree_pandas      |     0.473198 |       0.377992 |   0.547072 |
| solution-1           |     7.28659  |       1e-06    |   0.561481 |
| k-d_tree_sklearn     |     2.93191  |       1.3304   |   1.05451  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465015 |       0.441177 |   0.437735 |
| k-d_tree_polars      |     0.468191 |       0.404483 |   0.444138 |
| barab-szabi-1        |     0.483509 |       0.40604  |   0.449347 |
| Bori_Aron_solution-1 |     0.46778  |       0.548282 |   0.538671 |
| k-d_tree_pandas      |     0.468124 |       0.38383  |   0.556733 |
| k-d_tree_sklearn     |     0.466209 |       0.962878 |   1.06614  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462945 |       0.4514   |   0.458256 |
| barab-szabi-1        |     0.470656 |       0.443184 |   0.470734 |
| k-d_tree_polars      |     0.466616 |       0.436119 |   0.474219 |
| Bori_Aron_solution-1 |     0.46152  |       0.588128 |   0.544344 |
| k-d_tree_pandas      |     0.470527 |       0.40705  |   0.599115 |
| k-d_tree_sklearn     |     0.475416 |       1.01039  |   1.0825   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467456 |       0.511758 |   0.478121 |
| Bori_Aron_solution-1 |     0.468771 |       0.768957 |   0.56272  |
| k-d_tree_polars      |     0.477874 |       0.558652 |   0.565053 |
| barab-szabi-1        |     0.470051 |       0.56194  |   0.580868 |
| k-d_tree_pandas      |     0.46686  |       0.497618 |   0.733169 |
| k-d_tree_sklearn     |     0.467219 |       1.24703  |   1.1317   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466503 |       0.724352 |   0.502178 |
| Bori_Aron_solution-1 |     0.462402 |       1.46283  |   0.579095 |
| k-d_tree_polars      |     0.46821  |       0.928116 |   0.912069 |
| barab-szabi-1        |     0.468841 |       0.921074 |   0.946876 |
| k-d_tree_pandas      |     0.469768 |       0.820345 |   1.16113  |
| k-d_tree_sklearn     |     0.471239 |       2.0981   |   1.21131  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467163 |        5.09304 |   0.771804 |
| Bori_Aron_solution-1 |     0.460982 |       11.0183  |   0.81167  |
| k-d_tree_sklearn     |     0.477182 |       16.5852  |   1.2946   |
| barab-szabi-1        |     0.46749  |        5.46942 |   6.58016  |
| k-d_tree_polars      |     0.466233 |        5.46935 |   6.73001  |
| k-d_tree_pandas      |     0.467322 |        4.41007 |   6.95321  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464355 |        70.9206 |    2.78722 |
| k-d_tree_sklearn     |     0.857737 |       236.803  |    3.98334 |
| Bori_Aron_solution-1 |     0.466601 |       151.205  |   15.9087  |