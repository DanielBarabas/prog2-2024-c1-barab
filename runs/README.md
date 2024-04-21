# 2024-04-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.693805 |       0.335575 |   0.329751 |
| k-d_tree_polars      |     0.71241  |       0.39347  |   0.337011 |
| barab-szabi-1        |     8.377    |       0.442665 |   0.380826 |
| solution-1           |     8.17148  |       1e-06    |   0.442535 |
| Bori_Aron_solution-1 |     0.693043 |       0.466044 |   0.46647  |
| k-d_tree_pandas      |     0.703534 |       0.375599 |   0.473771 |
| k-d_tree_sklearn     |     3.27866  |       0.950003 |   0.649527 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.729444 |       0.343262 |   0.332063 |
| k-d_tree_polars      |     0.732926 |       0.407326 |   0.344804 |
| barab-szabi-1        |     0.759074 |       0.402903 |   0.346089 |
| Bori_Aron_solution-1 |     0.724812 |       0.477969 |   0.474537 |
| k-d_tree_pandas      |     0.727941 |       0.38431  |   0.4772   |
| k-d_tree_sklearn     |     0.77273  |       0.829052 |   0.651863 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.729573 |       0.359975 |   0.352688 |
| k-d_tree_polars      |     0.729607 |       0.423292 |   0.3675   |
| barab-szabi-1        |     0.744398 |       0.434161 |   0.368169 |
| Bori_Aron_solution-1 |     0.721486 |       0.520594 |   0.482718 |
| k-d_tree_pandas      |     0.731857 |       0.400918 |   0.538587 |
| k-d_tree_sklearn     |     0.750465 |       0.889246 |   0.676558 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.735863 |       0.427301 |   0.38654  |
| k-d_tree_polars      |     0.732954 |       0.555318 |   0.468981 |
| barab-szabi-1        |     0.72859  |       0.551901 |   0.478848 |
| Bori_Aron_solution-1 |     0.721614 |       0.693493 |   0.485801 |
| k-d_tree_pandas      |     0.739486 |       0.492687 |   0.658614 |
| k-d_tree_sklearn     |     0.750782 |       1.11813  |   0.752329 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.743159 |       0.685031 |   0.436011 |
| Bori_Aron_solution-1 |     0.725786 |       1.37394  |   0.524745 |
| k-d_tree_polars      |     0.73641  |       0.868342 |   0.841113 |
| barab-szabi-1        |     0.738546 |       0.851415 |   0.869293 |
| k-d_tree_sklearn     |     0.766298 |       1.9747   |   0.871412 |
| k-d_tree_pandas      |     0.740264 |       0.756479 |   1.10674  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.727085 |        5.21671 |   0.738771 |
| Bori_Aron_solution-1 |     0.735525 |       10.5134  |   0.764478 |
| k-d_tree_sklearn     |     0.734462 |       15.8592  |   1.05087  |
| k-d_tree_polars      |     0.732888 |        4.82931 |   6.49378  |
| barab-szabi-1        |     0.744429 |        4.83411 |   6.67793  |
| k-d_tree_pandas      |     0.732958 |        3.84496 |   6.72353  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.939739 |        71.4787 |    3.51347 |
| k-d_tree_sklearn     |     0.81355  |       228.009  |    4.80293 |
| Bori_Aron_solution-1 |     0.754062 |       150.603  |   17.9669  |