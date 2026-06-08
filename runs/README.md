# 2026-06-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.54222  |       2e-06    |   0.441391 |
| k-d_tree_polars      |     0.510009 |       0.480662 |   0.469722 |
| barab-szabi-2        |     0.527464 |       0.484864 |   0.473173 |
| barab-szabi-1        |     9.18108  |       0.479978 |   0.572999 |
| Bori_Aron_solution-1 |     0.51388  |       0.613985 |   0.629675 |
| k-d_tree_pandas      |     0.500003 |       0.438544 |   0.631782 |
| k-d_tree_sklearn     |     3.46078  |       1.26798  |   1.22793  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619232 |       0.523269 |   0.480482 |
| k-d_tree_polars      |     0.507059 |       0.460918 |   0.485067 |
| barab-szabi-1        |     0.516422 |       0.495375 |   0.490492 |
| Bori_Aron_solution-1 |     0.536112 |       0.610317 |   0.617169 |
| k-d_tree_pandas      |     0.520917 |       0.454866 |   0.634775 |
| k-d_tree_sklearn     |     0.514665 |       1.12945  |   1.24031  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.512344 |       0.493647 |   0.507029 |
| barab-szabi-2        |     0.550664 |       0.500604 |   0.512954 |
| barab-szabi-1        |     0.538291 |       0.524591 |   0.564278 |
| Bori_Aron_solution-1 |     0.511722 |       0.692773 |   0.615845 |
| k-d_tree_pandas      |     0.543258 |       0.455502 |   0.671732 |
| k-d_tree_sklearn     |     0.523258 |       1.21096  |   1.25831  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530449 |       0.579023 |   0.51747  |
| k-d_tree_polars      |     0.547957 |       0.618525 |   0.623282 |
| barab-szabi-1        |     0.580762 |       0.606667 |   0.630795 |
| Bori_Aron_solution-1 |     0.507141 |       0.875083 |   0.646331 |
| k-d_tree_pandas      |     0.543556 |       0.551744 |   0.794522 |
| k-d_tree_sklearn     |     0.524476 |       1.43708  |   1.30724  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.506909 |       1.58108  |   0.668603 |
| barab-szabi-2        |     0.538344 |       0.871605 |   0.718342 |
| k-d_tree_polars      |     0.523475 |       0.948833 |   1.07771  |
| barab-szabi-1        |     0.523777 |       0.985939 |   1.11793  |
| k-d_tree_pandas      |     0.511457 |       0.861676 |   1.30808  |
| k-d_tree_sklearn     |     0.547685 |       2.50486  |   1.3755   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525918 |        6.2156  |   0.790223 |
| Bori_Aron_solution-1 |     0.513155 |       12.3221  |   0.906115 |
| k-d_tree_sklearn     |     0.52646  |       19.5229  |   1.40493  |
| k-d_tree_polars      |     0.544899 |        5.46099 |   8.11451  |
| barab-szabi-1        |     0.519993 |        5.36443 |   8.15701  |
| k-d_tree_pandas      |     0.512159 |        4.2505  |   8.44781  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547813 |        83.1154 |    2.62211 |
| k-d_tree_sklearn     |     0.781309 |       273.178  |    3.59457 |
| Bori_Aron_solution-1 |     0.520236 |       157.405  |   21.6929  |