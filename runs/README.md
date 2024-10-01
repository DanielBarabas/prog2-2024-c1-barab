# 2024-10-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.96014  |       1e-06    |   0.367405 |
| barab-szabi-2        |     0.669117 |       0.396748 |   0.386966 |
| barab-szabi-1        |     0.611997 |       0.420097 |   0.397558 |
| k-d_tree_polars      |     0.61545  |       0.419973 |   0.40946  |
| Bori_Aron_solution-1 |     4.56323  |       0.574823 |   0.474874 |
| k-d_tree_pandas      |     4.70188  |       0.418061 |   0.540696 |
| k-d_tree_sklearn     |     3.07932  |       1.01328  |   1.00288  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.639418 |       0.397864 |   0.393794 |
| k-d_tree_polars      |     0.639685 |       0.447172 |   0.398072 |
| barab-szabi-1        |     0.633392 |       0.416166 |   0.400458 |
| Bori_Aron_solution-1 |     0.624999 |       0.574169 |   0.544859 |
| k-d_tree_pandas      |     0.621306 |       0.393331 |   0.567709 |
| k-d_tree_sklearn     |     0.626204 |       0.962174 |   0.999326 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632607 |       0.405854 |   0.42431  |
| barab-szabi-1        |     0.6558   |       0.439475 |   0.430749 |
| k-d_tree_polars      |     0.655566 |       0.441072 |   0.437072 |
| Bori_Aron_solution-1 |     0.621675 |       0.582982 |   0.54685  |
| k-d_tree_pandas      |     0.633655 |       0.411322 |   0.588889 |
| k-d_tree_sklearn     |     0.623811 |       0.964597 |   1.01794  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623677 |       0.471076 |   0.433728 |
| k-d_tree_polars      |     0.646337 |       0.546565 |   0.528425 |
| barab-szabi-1        |     0.622662 |       0.550357 |   0.530188 |
| Bori_Aron_solution-1 |     0.617559 |       0.747845 |   0.558186 |
| k-d_tree_pandas      |     0.614802 |       0.487149 |   0.758234 |
| k-d_tree_sklearn     |     0.615755 |       1.18834  |   1.10694  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.643004 |       0.740982 |   0.485981 |
| Bori_Aron_solution-1 |     0.619637 |       1.40421  |   0.614972 |
| k-d_tree_polars      |     0.633048 |       0.850066 |   0.8744   |
| barab-szabi-1        |     0.627189 |       0.888825 |   0.960807 |
| k-d_tree_pandas      |     0.637849 |       0.769639 |   1.17314  |
| k-d_tree_sklearn     |     0.643474 |       2.08813  |   1.21566  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.674    |        6.45848 |   0.745383 |
| Bori_Aron_solution-1 |     0.639236 |       11.4105  |   0.840826 |
| k-d_tree_sklearn     |     0.65225  |       19.3142  |   1.38485  |
| k-d_tree_pandas      |     0.612785 |        3.90283 |   7.81379  |
| k-d_tree_polars      |     0.625648 |        4.88474 |   7.91338  |
| barab-szabi-1        |     0.641537 |        4.96772 |   7.9475   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.723893 |        86.9622 |    4.12241 |
| k-d_tree_sklearn     |     0.843073 |       263.909  |    4.56461 |
| Bori_Aron_solution-1 |     0.626129 |       168.195  |   15.1468  |