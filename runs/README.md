# 2024-05-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     6.71563  |       0.365726 |   0.345553 |
| k-d_tree_polars      |     0.793146 |       0.404219 |   0.348819 |
| barab-szabi-1        |     0.794366 |       0.405771 |   0.349336 |
| solution-1           |     8.12756  |       1e-06    |   0.355675 |
| Bori_Aron_solution-1 |     5.01049  |       0.420251 |   0.424393 |
| k-d_tree_pandas      |     0.792196 |       0.410244 |   0.482985 |
| k-d_tree_sklearn     |     3.5187   |       0.957345 |   0.682104 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.800362 |       0.413054 |   0.347625 |
| barab-szabi-2        |     0.793213 |       0.37778  |   0.350031 |
| barab-szabi-1        |     0.800203 |       0.412255 |   0.352516 |
| Bori_Aron_solution-1 |     0.778089 |       0.487927 |   0.478372 |
| k-d_tree_pandas      |     0.788065 |       0.387295 |   0.487559 |
| k-d_tree_sklearn     |     0.800606 |       0.863371 |   0.689991 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.804399 |       0.36104  |   0.355682 |
| k-d_tree_polars      |     0.793092 |       0.436369 |   0.379145 |
| barab-szabi-1        |     0.789956 |       0.433527 |   0.384677 |
| Bori_Aron_solution-1 |     0.77669  |       0.523786 |   0.476942 |
| k-d_tree_pandas      |     0.793519 |       0.409169 |   0.528001 |
| k-d_tree_sklearn     |     0.792974 |       0.896694 |   0.705953 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.798958 |       0.422808 |   0.392647 |
| k-d_tree_polars      |     0.803337 |       0.544513 |   0.480052 |
| barab-szabi-1        |     0.795853 |       0.552518 |   0.488216 |
| Bori_Aron_solution-1 |     0.787221 |       0.702504 |   0.493969 |
| k-d_tree_pandas      |     0.796981 |       0.491552 |   0.671741 |
| k-d_tree_sklearn     |     0.793074 |       1.15217  |   0.780452 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.804791 |       0.69396  |   0.441301 |
| Bori_Aron_solution-1 |     0.785319 |       1.3618   |   0.528283 |
| k-d_tree_polars      |     0.779552 |       0.871975 |   0.840299 |
| k-d_tree_sklearn     |     0.813511 |       1.93739  |   0.870436 |
| barab-szabi-1        |     0.791581 |       0.860211 |   0.876183 |
| k-d_tree_pandas      |     0.785984 |       0.755398 |   1.07593  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.779464 |        5.51102 |   0.749937 |
| Bori_Aron_solution-1 |     0.778507 |       10.6233  |   0.766969 |
| k-d_tree_sklearn     |     0.808257 |       15.7047  |   1.03676  |
| barab-szabi-1        |     0.782214 |        4.95308 |   6.35737  |
| k-d_tree_polars      |     0.789143 |        4.97541 |   6.6934   |
| k-d_tree_pandas      |     0.775549 |        3.9757  |   6.78392  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.0061   |        73.3205 |    3.71916 |
| k-d_tree_sklearn     |     0.850539 |       227.858  |    4.44253 |
| Bori_Aron_solution-1 |     0.786747 |       154.12   |   16.5009  |