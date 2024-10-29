# 2024-10-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617383 |       0.392439 |   0.388917 |
| barab-szabi-1        |     0.614381 |       0.402952 |   0.389908 |
| k-d_tree_polars      |     0.616964 |       0.39778  |   0.392973 |
| solution-1           |     7.62125  |       2e-06    |   0.5279   |
| k-d_tree_pandas      |     0.616984 |       0.386179 |   0.528517 |
| Bori_Aron_solution-1 |     0.616338 |       0.528981 |   0.530978 |
| k-d_tree_sklearn     |    10.1209   |       1.21045  |   0.997793 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609803 |       0.387909 |   0.386882 |
| barab-szabi-1        |     0.609878 |       0.403082 |   0.396939 |
| k-d_tree_polars      |     0.611928 |       0.40773  |   0.398371 |
| k-d_tree_pandas      |     0.61887  |       0.380154 |   0.528005 |
| Bori_Aron_solution-1 |     0.613497 |       0.558626 |   0.528359 |
| k-d_tree_sklearn     |     0.629416 |       0.897733 |   0.99099  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.623405 |       0.426532 |   0.420397 |
| barab-szabi-1        |     0.610582 |       0.427269 |   0.421787 |
| barab-szabi-2        |     0.606911 |       0.400976 |   0.422033 |
| Bori_Aron_solution-1 |     0.633715 |       0.564692 |   0.521399 |
| k-d_tree_pandas      |     0.613828 |       0.40328  |   0.573045 |
| k-d_tree_sklearn     |     0.616859 |       0.930195 |   0.991689 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608469 |       0.466453 |   0.428261 |
| k-d_tree_polars      |     0.615834 |       0.538371 |   0.514405 |
| barab-szabi-1        |     0.612242 |       0.536624 |   0.532263 |
| Bori_Aron_solution-1 |     0.612022 |       0.748395 |   0.542229 |
| k-d_tree_pandas      |     0.622778 |       0.481647 |   0.704042 |
| k-d_tree_sklearn     |     0.61969  |       1.1556   |   1.04447  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607605 |       0.71941  |   0.477963 |
| Bori_Aron_solution-1 |     0.604616 |       1.39509  |   0.568617 |
| k-d_tree_polars      |     0.614307 |       0.86508  |   0.873647 |
| barab-szabi-1        |     0.609778 |       0.856586 |   0.91657  |
| k-d_tree_sklearn     |     0.617144 |       1.99639  |   1.14229  |
| k-d_tree_pandas      |     0.611011 |       0.752358 |   1.14391  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612915 |        5.48853 |   0.743447 |
| Bori_Aron_solution-1 |     0.618976 |       10.8218  |   0.818421 |
| k-d_tree_sklearn     |     0.617804 |       16.0978  |   1.23783  |
| k-d_tree_polars      |     0.609253 |        4.87512 |   6.6622   |
| barab-szabi-1        |     0.629503 |        4.90889 |   6.77291  |
| k-d_tree_pandas      |     0.624447 |        3.92044 |   6.99414  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.635483 |        73.0506 |    2.92972 |
| k-d_tree_sklearn     |     0.618325 |       226.242  |    4.16306 |
| Bori_Aron_solution-1 |     0.626892 |       147.81   |   18.0488  |