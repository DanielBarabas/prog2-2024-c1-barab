# 2026-08-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.70806  |       1e-06    |   0.442786 |
| barab-szabi-1        |     0.464731 |       0.419934 |   0.44726  |
| barab-szabi-2        |     4.83413  |       0.513691 |   0.452626 |
| k-d_tree_polars      |     0.461799 |       0.435761 |   0.456524 |
| Bori_Aron_solution-1 |     4.4744   |       0.737774 |   0.490641 |
| k-d_tree_pandas      |     0.459895 |       0.384343 |   0.55233  |
| k-d_tree_sklearn     |     3.01129  |       1.12444  |   1.0831   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47523  |       0.454993 |   0.447255 |
| k-d_tree_polars      |     0.473508 |       0.425352 |   0.460929 |
| barab-szabi-1        |     0.473996 |       0.433259 |   0.46574  |
| Bori_Aron_solution-1 |     0.467012 |       0.557473 |   0.55393  |
| k-d_tree_pandas      |     0.472248 |       0.387036 |   0.557079 |
| k-d_tree_sklearn     |     0.475403 |       1.01066  |   1.08273  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469241 |       0.456345 |   0.462068 |
| k-d_tree_polars      |     0.473677 |       0.452904 |   0.478174 |
| barab-szabi-1        |     0.472414 |       0.456672 |   0.482982 |
| Bori_Aron_solution-1 |     0.46322  |       0.598335 |   0.549569 |
| k-d_tree_pandas      |     0.470775 |       0.409114 |   0.596777 |
| k-d_tree_sklearn     |     0.47643  |       1.08527  |   1.10115  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475183 |       0.523262 |   0.483041 |
| Bori_Aron_solution-1 |     0.473925 |       0.77457  |   0.559686 |
| k-d_tree_polars      |     0.474712 |       0.567753 |   0.579513 |
| barab-szabi-1        |     0.472288 |       0.578719 |   0.597566 |
| k-d_tree_pandas      |     0.470937 |       0.502804 |   0.74112  |
| k-d_tree_sklearn     |     0.473769 |       1.28629  |   1.15851  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469892 |       0.739345 |   0.526306 |
| Bori_Aron_solution-1 |     0.462784 |       1.43043  |   0.581142 |
| k-d_tree_polars      |     0.472373 |       0.924834 |   0.926114 |
| barab-szabi-1        |     0.473103 |       0.931787 |   0.958797 |
| k-d_tree_pandas      |     0.468326 |       0.807456 |   1.19363  |
| k-d_tree_sklearn     |     0.473104 |       2.13326  |   1.24492  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476406 |        5.11118 |   0.774933 |
| Bori_Aron_solution-1 |     0.47343  |       10.7791  |   0.811432 |
| k-d_tree_sklearn     |     0.496214 |       16.5996  |   1.32574  |
| k-d_tree_polars      |     0.472785 |        5.39992 |   6.61831  |
| barab-szabi-1        |     0.481696 |        5.30055 |   6.62959  |
| k-d_tree_pandas      |     0.473637 |        4.34018 |   7.00078  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.772801 |        75.1347 |    2.92282 |
| k-d_tree_sklearn     |     0.585997 |       246.022  |    3.78064 |
| Bori_Aron_solution-1 |     0.45938  |       158.998  |   16.0528  |