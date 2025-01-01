# 2025-01-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.61365  |       0.399026 |   0.388286 |
| barab-szabi-2        |     0.624518 |       0.392178 |   0.391686 |
| barab-szabi-1        |     0.619303 |       0.405126 |   0.393966 |
| solution-1           |     7.75365  |       1e-06    |   0.42795  |
| Bori_Aron_solution-1 |     0.60664  |       0.519295 |   0.528897 |
| k-d_tree_pandas      |     0.629228 |       0.381697 |   0.52897  |
| k-d_tree_sklearn     |    10.698    |       1.10787  |   0.977711 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617394 |       0.391232 |   0.389442 |
| barab-szabi-1        |     0.612475 |       0.412233 |   0.393668 |
| k-d_tree_polars      |     0.614166 |       0.40238  |   0.398172 |
| Bori_Aron_solution-1 |     0.607223 |       0.532382 |   0.526911 |
| k-d_tree_pandas      |     0.62907  |       0.396961 |   0.531339 |
| k-d_tree_sklearn     |     0.621489 |       0.890329 |   0.966574 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.628792 |       0.405927 |   0.400829 |
| k-d_tree_polars      |     0.616675 |       0.434585 |   0.419562 |
| barab-szabi-1        |     0.617115 |       0.433838 |   0.424107 |
| Bori_Aron_solution-1 |     0.607593 |       0.565457 |   0.5283   |
| k-d_tree_pandas      |     0.615562 |       0.404089 |   0.571303 |
| k-d_tree_sklearn     |     0.625735 |       0.939975 |   0.985604 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612288 |       0.470605 |   0.43431  |
| k-d_tree_polars      |     0.617237 |       0.539388 |   0.521481 |
| barab-szabi-1        |     0.610829 |       0.538308 |   0.528583 |
| Bori_Aron_solution-1 |     0.610289 |       0.741753 |   0.539598 |
| k-d_tree_pandas      |     0.612333 |       0.484564 |   0.703608 |
| k-d_tree_sklearn     |     0.621516 |       1.15737  |   1.06252  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617639 |       0.725399 |   0.475324 |
| Bori_Aron_solution-1 |     0.611055 |       1.39062  |   0.560089 |
| k-d_tree_polars      |     0.62237  |       0.864785 |   0.861171 |
| barab-szabi-1        |     0.614634 |       0.854131 |   0.907476 |
| k-d_tree_pandas      |     0.606202 |       0.749268 |   1.1305   |
| k-d_tree_sklearn     |     0.626251 |       1.98679  |   1.13442  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618441 |        5.2792  |   0.719538 |
| Bori_Aron_solution-1 |     0.613489 |       10.5548  |   0.809333 |
| k-d_tree_sklearn     |     0.620789 |       15.8483  |   1.23954  |
| barab-szabi-1        |     0.621544 |        4.87659 |   6.46305  |
| k-d_tree_polars      |     0.617921 |        4.8942  |   6.47518  |
| k-d_tree_pandas      |     0.619572 |        3.90231 |   6.89339  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.648508 |        73.3195 |    2.81987 |
| k-d_tree_sklearn     |     0.61884  |       230.377  |    4.2174  |
| Bori_Aron_solution-1 |     0.633887 |       149.256  |   17.3841  |