# 2024-04-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.76069  |       0.362951 |   0.35323  |
| barab-szabi-1        |     0.778042 |       0.420616 |   0.357097 |
| k-d_tree_polars      |     8.26444  |       0.467236 |   0.402682 |
| k-d_tree_pandas      |     0.715502 |       0.388044 |   0.493033 |
| Bori_Aron_solution-1 |     0.734203 |       0.492298 |   0.498281 |
| solution-1           |     8.22785  |       1e-06    |   0.510822 |
| k-d_tree_sklearn     |     3.21895  |       1.08942  |   0.698642 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.768881 |       0.44207  |   0.356018 |
| barab-szabi-1        |     0.756693 |       0.434525 |   0.372093 |
| barab-szabi-2        |     0.795134 |       0.366826 |   0.373711 |
| k-d_tree_pandas      |     0.752821 |       0.400166 |   0.510574 |
| Bori_Aron_solution-1 |     0.747133 |       0.503884 |   0.516447 |
| k-d_tree_sklearn     |     0.767958 |       0.880926 |   0.712349 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.762101 |       0.366792 |   0.36039  |
| barab-szabi-1        |     0.761232 |       0.45041  |   0.39645  |
| k-d_tree_polars      |     0.767793 |       0.459463 |   0.401124 |
| Bori_Aron_solution-1 |     0.738925 |       0.559064 |   0.52546  |
| k-d_tree_pandas      |     0.771014 |       0.444078 |   0.544437 |
| k-d_tree_sklearn     |     0.776018 |       0.995445 |   0.699243 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.784427 |       0.433338 |   0.387933 |
| k-d_tree_polars      |     0.751995 |       0.540576 |   0.488039 |
| barab-szabi-1        |     0.755453 |       0.567482 |   0.500836 |
| Bori_Aron_solution-1 |     0.745072 |       0.70679  |   0.516931 |
| k-d_tree_pandas      |     0.747498 |       0.488244 |   0.687867 |
| k-d_tree_sklearn     |     0.761981 |       1.15923  |   0.762616 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.754311 |       0.702048 |   0.517581 |
| Bori_Aron_solution-1 |     0.749873 |       1.40803  |   0.541093 |
| k-d_tree_polars      |     0.74245  |       0.861579 |   0.861967 |
| k-d_tree_sklearn     |     0.769953 |       2.0143   |   0.866261 |
| barab-szabi-1        |     0.736218 |       0.890278 |   0.919393 |
| k-d_tree_pandas      |     0.779877 |       0.773303 |   1.13569  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.760074 |        5.93343 |   0.798465 |
| Bori_Aron_solution-1 |     0.743755 |       11.2085  |   0.807721 |
| k-d_tree_sklearn     |     0.786463 |       17.7238  |   1.09903  |
| k-d_tree_polars      |     0.750151 |        4.78357 |   7.15269  |
| barab-szabi-1        |     0.755132 |        4.966   |   7.31836  |
| k-d_tree_pandas      |     0.746691 |        3.92564 |   7.48949  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.828103 |         79.793 |    3.95424 |
| k-d_tree_sklearn     |     0.754471 |        246.674 |    5.2196  |
| Bori_Aron_solution-1 |     0.81361  |        152.068 |   14.5509  |