# 2024-12-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.56369  |       1e-06    |   0.358174 |
| barab-szabi-1        |     0.626485 |       0.40601  |   0.390748 |
| k-d_tree_polars      |     0.619945 |       0.404151 |   0.393088 |
| barab-szabi-2        |     0.61109  |       0.394235 |   0.397146 |
| Bori_Aron_solution-1 |     0.611293 |       0.527248 |   0.521521 |
| k-d_tree_pandas      |     0.615167 |       0.377481 |   0.526039 |
| k-d_tree_sklearn     |    10.5336   |       1.02077  |   0.98456  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615999 |       0.392635 |   0.39183  |
| k-d_tree_polars      |     0.615599 |       0.40925  |   0.393093 |
| barab-szabi-1        |     0.615425 |       0.443368 |   0.40264  |
| k-d_tree_pandas      |     0.6149   |       0.385788 |   0.539303 |
| Bori_Aron_solution-1 |     0.617774 |       0.530442 |   0.541234 |
| k-d_tree_sklearn     |     0.624462 |       0.937585 |   0.980308 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607165 |       0.403054 |   0.408657 |
| k-d_tree_polars      |     0.614916 |       0.433667 |   0.421463 |
| barab-szabi-1        |     0.643418 |       0.432558 |   0.434539 |
| Bori_Aron_solution-1 |     0.605689 |       0.581377 |   0.527151 |
| k-d_tree_pandas      |     0.620289 |       0.406789 |   0.581559 |
| k-d_tree_sklearn     |     0.633113 |       0.936507 |   1.0276   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613018 |       0.480613 |   0.437417 |
| k-d_tree_polars      |     0.61958  |       0.538219 |   0.528134 |
| barab-szabi-1        |     0.612512 |       0.54598  |   0.529082 |
| Bori_Aron_solution-1 |     0.611132 |       0.747492 |   0.541732 |
| k-d_tree_pandas      |     0.621512 |       0.488836 |   0.703139 |
| k-d_tree_sklearn     |     0.627964 |       1.17035  |   1.06162  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617892 |       0.718412 |   0.469151 |
| Bori_Aron_solution-1 |     0.625078 |       1.39358  |   0.571311 |
| k-d_tree_polars      |     0.616303 |       0.866056 |   0.877138 |
| barab-szabi-1        |     0.61363  |       0.876776 |   0.91022  |
| k-d_tree_sklearn     |     0.624436 |       2.00632  |   1.1403   |
| k-d_tree_pandas      |     0.616711 |       0.75779  |   1.14468  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617921 |        5.37129 |   0.728515 |
| Bori_Aron_solution-1 |     0.614372 |       10.7922  |   0.83041  |
| k-d_tree_sklearn     |     0.615186 |       16.2181  |   1.24785  |
| k-d_tree_polars      |     0.624411 |        4.87406 |   6.60385  |
| barab-szabi-1        |     0.625562 |        4.95044 |   6.60729  |
| k-d_tree_pandas      |     0.615155 |        3.88022 |   7.00771  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.647394 |        71.7657 |    2.8895  |
| k-d_tree_sklearn     |     0.617988 |       224.394  |    4.20115 |
| Bori_Aron_solution-1 |     0.644636 |       156.095  |   16.6735  |