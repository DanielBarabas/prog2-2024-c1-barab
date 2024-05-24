# 2024-05-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     5.00023  |       0.355952 |   0.358868 |
| solution-1           |     8.37746  |       1e-06    |   0.36492  |
| barab-szabi-1        |     0.851408 |       0.433452 |   0.373041 |
| k-d_tree_polars      |     0.834434 |       0.42666  |   0.375381 |
| Bori_Aron_solution-1 |     4.71541  |       0.415181 |   0.412465 |
| k-d_tree_pandas      |     0.831397 |       0.416916 |   0.518652 |
| k-d_tree_sklearn     |     3.64097  |       1.17054  |   0.722673 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.808437 |       0.416579 |   0.352809 |
| barab-szabi-1        |     0.818596 |       0.430025 |   0.368043 |
| barab-szabi-2        |     0.81133  |       0.368312 |   0.373549 |
| k-d_tree_pandas      |     0.846032 |       0.406091 |   0.505925 |
| Bori_Aron_solution-1 |     0.841114 |       0.535548 |   0.514137 |
| k-d_tree_sklearn     |     0.840957 |       0.919998 |   0.744519 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.793311 |       0.358526 |   0.359446 |
| k-d_tree_polars      |     0.797668 |       0.43759  |   0.379365 |
| barab-szabi-1        |     0.800178 |       0.436605 |   0.40753  |
| Bori_Aron_solution-1 |     0.786686 |       0.532398 |   0.500775 |
| k-d_tree_pandas      |     0.797558 |       0.409468 |   0.531579 |
| k-d_tree_sklearn     |     0.799782 |       0.906498 |   0.725215 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.796037 |       0.435095 |   0.396538 |
| k-d_tree_polars      |     0.828686 |       0.56801  |   0.494963 |
| Bori_Aron_solution-1 |     0.799852 |       0.72436  |   0.504383 |
| barab-szabi-1        |     0.813799 |       0.562371 |   0.505912 |
| k-d_tree_pandas      |     0.813385 |       0.516587 |   0.683328 |
| k-d_tree_sklearn     |     0.815665 |       1.1571   |   0.778089 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.828068 |       1.41537  |   0.559241 |
| barab-szabi-2        |     0.822293 |       0.730886 |   0.573364 |
| k-d_tree_polars      |     0.807376 |       0.898177 |   0.837977 |
| barab-szabi-1        |     0.793848 |       0.873278 |   0.875297 |
| k-d_tree_sklearn     |     0.883297 |       1.99839  |   0.892729 |
| k-d_tree_pandas      |     0.793615 |       0.774485 |   1.10719  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.795296 |        5.79245 |   0.759526 |
| Bori_Aron_solution-1 |     0.81427  |       10.9202  |   0.765212 |
| k-d_tree_sklearn     |     0.856834 |       17.9548  |   1.11564  |
| k-d_tree_polars      |     0.819407 |        4.97964 |   7.02886  |
| barab-szabi-1        |     0.8471   |        4.97678 |   7.15033  |
| k-d_tree_pandas      |     0.829675 |        4.02911 |   7.34493  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.939964 |        71.0876 |    3.56096 |
| k-d_tree_sklearn     |     0.862346 |       223.028  |    4.37372 |
| Bori_Aron_solution-1 |     0.85039  |       154.171  |   14.8117  |