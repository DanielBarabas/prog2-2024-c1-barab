# 2025-02-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.622989 |       0.406187 |   0.411196 |
| barab-szabi-1        |     0.592703 |       0.41561  |   0.424837 |
| barab-szabi-2        |     4.43087  |       0.471948 |   0.438373 |
| Bori_Aron_solution-1 |     4.97028  |       0.80706  |   0.47431  |
| solution-1           |     7.72239  |       1e-06    |   0.548605 |
| k-d_tree_pandas      |     0.595954 |       0.38941  |   0.554194 |
| k-d_tree_sklearn     |     3.33567  |       1.28995  |   1.02721  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.626138 |       0.417562 |   0.41353  |
| barab-szabi-2        |     0.594716 |       0.409446 |   0.414941 |
| barab-szabi-1        |     0.59079  |       0.419072 |   0.418877 |
| k-d_tree_pandas      |     0.590388 |       0.392856 |   0.559705 |
| Bori_Aron_solution-1 |     0.583163 |       0.558622 |   0.559923 |
| k-d_tree_sklearn     |     0.602706 |       0.989259 |   1.0436   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58876  |       0.421034 |   0.41937  |
| k-d_tree_polars      |     0.594383 |       0.436785 |   0.439672 |
| barab-szabi-1        |     0.597258 |       0.440881 |   0.444886 |
| Bori_Aron_solution-1 |     0.585524 |       0.5949   |   0.569907 |
| k-d_tree_pandas      |     0.596289 |       0.410945 |   0.602587 |
| k-d_tree_sklearn     |     0.590426 |       0.999701 |   1.05671  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590235 |       0.486388 |   0.446198 |
| k-d_tree_polars      |     0.593381 |       0.543197 |   0.528715 |
| barab-szabi-1        |     0.588521 |       0.546772 |   0.543146 |
| Bori_Aron_solution-1 |     0.589966 |       0.765935 |   0.566911 |
| k-d_tree_pandas      |     0.596019 |       0.509992 |   0.732041 |
| k-d_tree_sklearn     |     0.596924 |       1.23557  |   1.10749  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605948 |       0.744115 |   0.500209 |
| Bori_Aron_solution-1 |     0.586859 |       1.38032  |   0.611969 |
| k-d_tree_polars      |     0.585429 |       0.875986 |   0.881751 |
| barab-szabi-1        |     0.584996 |       0.880764 |   0.908445 |
| k-d_tree_pandas      |     0.585685 |       0.743023 |   1.17988  |
| k-d_tree_sklearn     |     0.613432 |       2.06009  |   1.19241  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586081 |        5.44596 |   0.737514 |
| Bori_Aron_solution-1 |     0.57475  |       10.805   |   0.88933  |
| k-d_tree_sklearn     |     0.589504 |       16.4351  |   1.31125  |
| k-d_tree_polars      |     0.585195 |        4.96112 |   6.75338  |
| barab-szabi-1        |     0.592764 |        4.92365 |   6.86005  |
| k-d_tree_pandas      |     0.586586 |        3.86855 |   7.25223  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.831408 |        72.8921 |    3.73388 |
| k-d_tree_sklearn     |     0.659814 |       230.589  |    4.20653 |
| Bori_Aron_solution-1 |     0.587445 |       153.045  |   16.3555  |