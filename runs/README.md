# 2024-06-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.7111   |       0.356415 |   0.335777 |
| barab-szabi-1        |     0.789172 |       0.394    |   0.343453 |
| solution-1           |     7.99398  |       1e-06    |   0.356829 |
| k-d_tree_polars      |     0.786825 |       0.404349 |   0.358319 |
| Bori_Aron_solution-1 |     4.81158  |       0.403749 |   0.408551 |
| k-d_tree_pandas      |     0.784427 |       0.380709 |   0.473076 |
| k-d_tree_sklearn     |     3.32059  |       0.914554 |   0.667051 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.791976 |       0.352802 |   0.348037 |
| barab-szabi-1        |     0.788084 |       0.408287 |   0.350639 |
| k-d_tree_polars      |     0.822185 |       0.424462 |   0.354575 |
| Bori_Aron_solution-1 |     0.787505 |       0.484674 |   0.469772 |
| k-d_tree_pandas      |     0.787174 |       0.40783  |   0.513261 |
| k-d_tree_sklearn     |     0.80039  |       0.871634 |   0.671465 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.782257 |       0.3604   |   0.357291 |
| k-d_tree_polars      |     0.789057 |       0.431351 |   0.375456 |
| barab-szabi-1        |     0.780468 |       0.432199 |   0.377291 |
| Bori_Aron_solution-1 |     0.776431 |       0.518106 |   0.482352 |
| k-d_tree_pandas      |     0.787149 |       0.401368 |   0.526847 |
| k-d_tree_sklearn     |     0.811088 |       0.902889 |   0.712008 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.78082  |       0.422743 |   0.393243 |
| k-d_tree_polars      |     0.781547 |       0.538327 |   0.477325 |
| Bori_Aron_solution-1 |     0.78008  |       0.700806 |   0.488006 |
| barab-szabi-1        |     0.790893 |       0.553826 |   0.49701  |
| k-d_tree_pandas      |     0.799906 |       0.485893 |   0.659284 |
| k-d_tree_sklearn     |     0.791375 |       1.12121  |   0.770072 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.776576 |       0.671199 |   0.425198 |
| Bori_Aron_solution-1 |     0.783378 |       1.36631  |   0.507398 |
| k-d_tree_polars      |     0.784306 |       0.880398 |   0.833847 |
| barab-szabi-1        |     0.786937 |       0.866058 |   0.85856  |
| k-d_tree_sklearn     |     0.79503  |       1.92509  |   0.865686 |
| k-d_tree_pandas      |     0.781647 |       0.758922 |   1.08541  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.785376 |        5.46669 |   0.728194 |
| Bori_Aron_solution-1 |     0.78253  |       10.8237  |   0.768522 |
| k-d_tree_sklearn     |     0.794128 |       15.9373  |   1.03503  |
| k-d_tree_polars      |     0.791342 |        4.95433 |   6.53804  |
| barab-szabi-1        |     0.785945 |        5.0031  |   6.53919  |
| k-d_tree_pandas      |     0.78918  |        4.01704 |   6.85615  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.994232 |        71.3508 |    4.21032 |
| k-d_tree_sklearn     |     0.886814 |       228.915  |    4.47281 |
| Bori_Aron_solution-1 |     0.772394 |       156.131  |   14.5773  |