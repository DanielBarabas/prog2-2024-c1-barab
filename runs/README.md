# 2026-05-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.430302 |       0.392314 |   0.418833 |
| barab-szabi-2        |     0.436805 |       0.426555 |   0.42276  |
| k-d_tree_polars      |     0.436521 |       0.402603 |   0.426387 |
| solution-1           |     6.70271  |       1e-06    |   0.525036 |
| k-d_tree_pandas      |     0.435224 |       0.380086 |   0.53295  |
| Bori_Aron_solution-1 |     0.426433 |       0.540092 |   0.542204 |
| k-d_tree_sklearn     |     9.55485  |       1.52938  |   1.05139  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.433519 |       0.42068  |   0.418572 |
| k-d_tree_polars      |     0.433619 |       0.409121 |   0.429692 |
| barab-szabi-1        |     0.430396 |       0.402871 |   0.432405 |
| Bori_Aron_solution-1 |     0.432368 |       0.547463 |   0.539748 |
| k-d_tree_pandas      |     0.438116 |       0.384228 |   0.550675 |
| k-d_tree_sklearn     |     0.432434 |       0.948634 |   1.03205  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463257 |       0.438016 |   0.445162 |
| barab-szabi-1        |     0.434009 |       0.431532 |   0.453619 |
| k-d_tree_polars      |     0.439557 |       0.440466 |   0.459799 |
| Bori_Aron_solution-1 |     0.442932 |       0.593494 |   0.554834 |
| k-d_tree_pandas      |     0.437025 |       0.401845 |   0.584341 |
| k-d_tree_sklearn     |     0.440404 |       0.998136 |   1.04862  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.434911 |       0.501285 |   0.461569 |
| k-d_tree_polars      |     0.434089 |       0.538056 |   0.530232 |
| barab-szabi-1        |     0.434281 |       0.541922 |   0.532542 |
| Bori_Aron_solution-1 |     0.422761 |       0.732396 |   0.544096 |
| k-d_tree_pandas      |     0.430933 |       0.471931 |   0.696257 |
| k-d_tree_sklearn     |     0.43758  |       1.19543  |   1.08268  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.433266 |       0.739348 |   0.544088 |
| Bori_Aron_solution-1 |     0.426685 |       1.34823  |   0.580129 |
| k-d_tree_polars      |     0.435953 |       0.867886 |   0.910661 |
| barab-szabi-1        |     0.439483 |       0.871572 |   0.912746 |
| k-d_tree_pandas      |     0.439345 |       0.747048 |   1.09391  |
| k-d_tree_sklearn     |     0.426239 |       1.99191  |   1.18105  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.429212 |        5.10893 |   0.715824 |
| Bori_Aron_solution-1 |     0.441746 |       10.3148  |   0.894404 |
| k-d_tree_sklearn     |     0.447538 |       15.0124  |   1.25744  |
| k-d_tree_polars      |     0.430715 |        4.92155 |   6.33981  |
| barab-szabi-1        |     0.428424 |        4.91993 |   6.44218  |
| k-d_tree_pandas      |     0.438124 |        3.88691 |   6.63876  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.71429  |        68.2478 |    2.64503 |
| k-d_tree_sklearn     |     0.438875 |       178.583  |    3.93443 |
| Bori_Aron_solution-1 |     0.433384 |       138.978  |   15.2838  |