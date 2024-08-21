# 2024-08-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.10368  |       1e-06    |   0.376601 |
| barab-szabi-1        |     0.627115 |       0.39405  |   0.389154 |
| barab-szabi-2        |     8.90579  |       0.490828 |   0.392215 |
| k-d_tree_polars      |     0.604526 |       0.410339 |   0.397075 |
| Bori_Aron_solution-1 |     0.606317 |       0.515376 |   0.526283 |
| k-d_tree_pandas      |     0.606323 |       0.423544 |   0.531629 |
| k-d_tree_sklearn     |     3.2078   |       0.932357 |   0.723273 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616261 |       0.391595 |   0.382408 |
| k-d_tree_polars      |     0.621467 |       0.40991  |   0.397858 |
| barab-szabi-1        |     0.61786  |       0.408888 |   0.399154 |
| Bori_Aron_solution-1 |     0.620727 |       0.540417 |   0.534932 |
| k-d_tree_pandas      |     0.619464 |       0.383054 |   0.53512  |
| k-d_tree_sklearn     |     0.635209 |       0.907288 |   0.712883 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620294 |       0.403047 |   0.404473 |
| barab-szabi-1        |     0.616277 |       0.431876 |   0.426885 |
| k-d_tree_polars      |     0.650151 |       0.430936 |   0.44101  |
| Bori_Aron_solution-1 |     0.616635 |       0.576087 |   0.538965 |
| k-d_tree_pandas      |     0.616308 |       0.404218 |   0.589304 |
| k-d_tree_sklearn     |     0.62438  |       0.964856 |   0.738925 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617208 |       0.475819 |   0.436654 |
| k-d_tree_polars      |     0.631354 |       0.53399  |   0.516414 |
| Bori_Aron_solution-1 |     0.607482 |       0.786261 |   0.538723 |
| barab-szabi-1        |     0.618713 |       0.537211 |   0.542558 |
| k-d_tree_pandas      |     0.622736 |       0.487348 |   0.730565 |
| k-d_tree_sklearn     |     0.633026 |       1.24065  |   0.79714  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611736 |       0.733625 |   0.477609 |
| Bori_Aron_solution-1 |     0.609708 |       1.41331  |   0.567707 |
| k-d_tree_polars      |     0.615554 |       0.857092 |   0.852151 |
| k-d_tree_sklearn     |     0.624217 |       1.96737  |   0.872202 |
| barab-szabi-1        |     0.609071 |       0.848483 |   0.899822 |
| k-d_tree_pandas      |     0.620684 |       0.740387 |   1.14673  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609371 |        5.40845 |   0.713877 |
| Bori_Aron_solution-1 |     0.60014  |       10.7216  |   0.915265 |
| k-d_tree_sklearn     |     0.610101 |       16.0221  |   0.975746 |
| barab-szabi-1        |     0.668473 |        4.85462 |   6.74557  |
| k-d_tree_polars      |     0.62292  |        4.86137 |   6.75191  |
| k-d_tree_pandas      |     0.606414 |        3.95146 |   7.27337  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610174 |        69.7985 |    2.90795 |
| k-d_tree_sklearn     |     0.639382 |       235.088  |    4.25492 |
| Bori_Aron_solution-1 |     0.821934 |       151.056  |   16.7129  |