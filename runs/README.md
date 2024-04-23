# 2024-04-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.708276 |       0.403212 |   0.340051 |
| barab-szabi-2        |     0.708098 |       0.338392 |   0.343954 |
| barab-szabi-1        |     8.43267  |       0.548466 |   0.356266 |
| k-d_tree_pandas      |     0.703681 |       0.384372 |   0.475693 |
| Bori_Aron_solution-1 |     0.695799 |       0.469674 |   0.4863   |
| solution-1           |     8.09368  |       1e-06    |   0.521636 |
| k-d_tree_sklearn     |     3.17695  |       1.04988  |   0.646063 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732902 |       0.344836 |   0.335341 |
| barab-szabi-1        |     0.734518 |       0.408088 |   0.34365  |
| k-d_tree_polars      |     0.732039 |       0.407614 |   0.344663 |
| Bori_Aron_solution-1 |     0.740986 |       0.477312 |   0.478032 |
| k-d_tree_pandas      |     0.731111 |       0.391721 |   0.47968  |
| k-d_tree_sklearn     |     0.740612 |       0.843282 |   0.655937 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.737538 |       0.36188  |   0.352922 |
| barab-szabi-1        |     0.732119 |       0.429532 |   0.373883 |
| k-d_tree_polars      |     0.762337 |       0.432759 |   0.376419 |
| Bori_Aron_solution-1 |     0.715711 |       0.514917 |   0.479223 |
| k-d_tree_pandas      |     0.727263 |       0.407743 |   0.554291 |
| k-d_tree_sklearn     |     0.766162 |       0.886009 |   0.682995 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732223 |       0.428908 |   0.391786 |
| k-d_tree_polars      |     0.745041 |       0.555275 |   0.485706 |
| barab-szabi-1        |     0.728509 |       0.544767 |   0.487335 |
| Bori_Aron_solution-1 |     0.725395 |       0.692588 |   0.503608 |
| k-d_tree_pandas      |     0.72909  |       0.485235 |   0.663378 |
| k-d_tree_sklearn     |     0.765646 |       1.15319  |   0.752505 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.736674 |       0.70333  |   0.443679 |
| Bori_Aron_solution-1 |     0.723398 |       1.33997  |   0.515036 |
| k-d_tree_polars      |     0.733554 |       0.861471 |   0.836452 |
| barab-szabi-1        |     0.73226  |       0.847895 |   0.863023 |
| k-d_tree_sklearn     |     0.739702 |       1.92657  |   0.869407 |
| k-d_tree_pandas      |     0.748643 |       0.74188  |   1.0958   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.731863 |        5.85224 |   0.760409 |
| Bori_Aron_solution-1 |     0.749797 |       11.2398  |   0.818922 |
| k-d_tree_sklearn     |     0.743363 |       16.4482  |   1.05092  |
| k-d_tree_pandas      |     0.771295 |        3.83712 |   6.96288  |
| k-d_tree_polars      |     0.779131 |        4.81283 |   6.98703  |
| barab-szabi-1        |     0.730492 |        4.91962 |   7.05073  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.02327  |        75.5732 |    3.93336 |
| k-d_tree_sklearn     |     0.86096  |       235.891  |    4.82049 |
| Bori_Aron_solution-1 |     0.720596 |       150.355  |   16.5843  |