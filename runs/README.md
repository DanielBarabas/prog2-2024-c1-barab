# 2026-02-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.485686 |       0.39754  |   0.437343 |
| k-d_tree_polars      |     0.506217 |       0.399838 |   0.452932 |
| barab-szabi-2        |     0.513792 |       0.571638 |   0.481134 |
| solution-1           |     7.66616  |       1e-06    |   0.503663 |
| Bori_Aron_solution-1 |     0.533808 |       0.549081 |   0.559194 |
| k-d_tree_pandas      |     8.21746  |       0.430369 |   0.71977  |
| k-d_tree_sklearn     |     3.18097  |       1.08161  |   1.05302  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488297 |       0.435708 |   0.429509 |
| barab-szabi-1        |     0.490447 |       0.411437 |   0.436824 |
| k-d_tree_polars      |     0.486998 |       0.405586 |   0.43866  |
| k-d_tree_pandas      |     0.488224 |       0.392627 |   0.559807 |
| Bori_Aron_solution-1 |     0.484067 |       0.564067 |   0.564114 |
| k-d_tree_sklearn     |     0.494679 |       0.988487 |   1.05404  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484904 |       0.440953 |   0.445086 |
| barab-szabi-1        |     0.486776 |       0.433109 |   0.461915 |
| k-d_tree_polars      |     0.4853   |       0.437952 |   0.477517 |
| Bori_Aron_solution-1 |     0.490472 |       0.590176 |   0.556929 |
| k-d_tree_pandas      |     0.490232 |       0.414587 |   0.601144 |
| k-d_tree_sklearn     |     0.492483 |       1.03928  |   1.07214  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530524 |       0.527168 |   0.496977 |
| Bori_Aron_solution-1 |     0.494032 |       0.827009 |   0.574366 |
| k-d_tree_polars      |     0.521975 |       0.582421 |   0.584692 |
| barab-szabi-1        |     0.530637 |       0.606076 |   0.603221 |
| k-d_tree_pandas      |     0.496864 |       0.50968  |   0.778343 |
| k-d_tree_sklearn     |     0.519325 |       1.31436  |   1.20725  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.520388 |       0.801064 |   0.577282 |
| Bori_Aron_solution-1 |     0.495428 |       1.52936  |   0.626019 |
| k-d_tree_polars      |     0.533503 |       0.974303 |   0.954109 |
| barab-szabi-1        |     0.528902 |       0.997309 |   1.02853  |
| k-d_tree_pandas      |     0.500272 |       0.853442 |   1.28572  |
| k-d_tree_sklearn     |     0.526499 |       2.32474  |   1.34934  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.508154 |        5.68397 |   0.807879 |
| Bori_Aron_solution-1 |     0.515914 |       12.1953  |   0.928428 |
| k-d_tree_sklearn     |     0.510306 |       18.93    |   1.37823  |
| k-d_tree_polars      |     0.515002 |        5.55868 |   7.08177  |
| barab-szabi-1        |     0.503909 |        5.56385 |   7.30373  |
| k-d_tree_pandas      |     0.510245 |        4.47143 |   7.52017  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532854 |        80.4851 |    2.81297 |
| k-d_tree_sklearn     |     0.528448 |       244.866  |    4.11509 |
| Bori_Aron_solution-1 |     0.615818 |       156.865  |   18.2411  |