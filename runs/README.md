# 2025-07-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554096 |       0.426152 |   0.428969 |
| barab-szabi-1        |     0.562385 |       0.411174 |   0.429202 |
| solution-1           |     7.86714  |       1e-06    |   0.454004 |
| k-d_tree_polars      |     0.560898 |       0.413836 |   0.463241 |
| Bori_Aron_solution-1 |     0.558282 |       0.56963  |   0.552237 |
| k-d_tree_pandas      |     0.564621 |       0.382149 |   0.554113 |
| k-d_tree_sklearn     |    10.7268   |       1.28449  |   1.08017  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558162 |       0.425484 |   0.430353 |
| k-d_tree_polars      |     0.557709 |       0.415525 |   0.430752 |
| barab-szabi-1        |     0.556572 |       0.40965  |   0.431381 |
| k-d_tree_pandas      |     0.553562 |       0.393772 |   0.562016 |
| Bori_Aron_solution-1 |     0.552927 |       0.559957 |   0.576882 |
| k-d_tree_sklearn     |     0.559855 |       0.990079 |   1.08134  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555926 |       0.439017 |   0.444995 |
| k-d_tree_polars      |     0.560863 |       0.436625 |   0.458426 |
| barab-szabi-1        |     0.557359 |       0.43923  |   0.463954 |
| Bori_Aron_solution-1 |     0.551108 |       0.59878  |   0.559266 |
| k-d_tree_pandas      |     0.557469 |       0.418323 |   0.602046 |
| k-d_tree_sklearn     |     0.56128  |       1.0314   |   1.0905   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557969 |       0.505938 |   0.467077 |
| k-d_tree_polars      |     0.554631 |       0.542748 |   0.548415 |
| barab-szabi-1        |     0.560643 |       0.543608 |   0.560399 |
| Bori_Aron_solution-1 |     0.55025  |       0.764387 |   0.572315 |
| k-d_tree_pandas      |     0.568237 |       0.491786 |   0.734678 |
| k-d_tree_sklearn     |     0.567182 |       1.25327  |   1.15537  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557922 |       0.745455 |   0.505551 |
| Bori_Aron_solution-1 |     0.550565 |       1.42205  |   0.592112 |
| k-d_tree_polars      |     0.556395 |       0.880603 |   0.908233 |
| barab-szabi-1        |     0.552018 |       0.874089 |   0.951564 |
| k-d_tree_pandas      |     0.562281 |       0.763509 |   1.17233  |
| k-d_tree_sklearn     |     0.562762 |       2.10811  |   1.22625  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559289 |        5.47542 |   0.748206 |
| Bori_Aron_solution-1 |     0.555187 |       10.7782  |   0.849261 |
| k-d_tree_sklearn     |     0.561721 |       16.8782  |   1.31452  |
| barab-szabi-1        |     0.560398 |        4.98823 |   6.77637  |
| k-d_tree_polars      |     0.560853 |        5.04738 |   6.80652  |
| k-d_tree_pandas      |     0.561134 |        3.95689 |   7.22559  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.553902 |       232.875  |    3.91582 |
| barab-szabi-2        |     0.5714   |        77.9233 |    4.09332 |
| Bori_Aron_solution-1 |     0.569456 |       141.1    |   18.1878  |