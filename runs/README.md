# 2024-05-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.70625  |       0.349061 |   0.341657 |
| k-d_tree_polars      |     0.700837 |       0.403764 |   0.346674 |
| barab-szabi-1        |     8.39889  |       0.466528 |   0.361928 |
| solution-1           |     7.87539  |       1e-06    |   0.36336  |
| Bori_Aron_solution-1 |     0.689714 |       0.472052 |   0.472579 |
| k-d_tree_pandas      |     0.724554 |       0.381875 |   0.484836 |
| k-d_tree_sklearn     |     3.22251  |       0.872771 |   0.660393 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.733708 |       0.413238 |   0.347819 |
| barab-szabi-1        |     0.736905 |       0.406704 |   0.347825 |
| barab-szabi-2        |     0.735291 |       0.348917 |   0.356125 |
| Bori_Aron_solution-1 |     0.735555 |       0.4855   |   0.476241 |
| k-d_tree_pandas      |     0.73138  |       0.435951 |   0.485594 |
| k-d_tree_sklearn     |     0.743914 |       0.862082 |   0.672379 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734739 |       0.37466  |   0.360861 |
| barab-szabi-1        |     0.736725 |       0.432015 |   0.377456 |
| k-d_tree_polars      |     0.734444 |       0.435967 |   0.379607 |
| Bori_Aron_solution-1 |     0.730535 |       0.523572 |   0.489422 |
| k-d_tree_pandas      |     0.79032  |       0.410532 |   0.525336 |
| k-d_tree_sklearn     |     0.736565 |       0.898865 |   0.695148 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732708 |       0.431709 |   0.38872  |
| k-d_tree_polars      |     0.745432 |       0.540545 |   0.481015 |
| barab-szabi-1        |     0.731087 |       0.540997 |   0.496386 |
| Bori_Aron_solution-1 |     0.727443 |       0.702368 |   0.497804 |
| k-d_tree_pandas      |     0.738781 |       0.48753  |   0.6719   |
| k-d_tree_sklearn     |     0.73999  |       1.10849  |   0.761397 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734817 |       0.690465 |   0.437356 |
| Bori_Aron_solution-1 |     0.725465 |       1.34584  |   0.512661 |
| k-d_tree_polars      |     0.733815 |       0.857928 |   0.83089  |
| k-d_tree_sklearn     |     0.744361 |       1.94429  |   0.857671 |
| barab-szabi-1        |     0.738685 |       0.859482 |   0.866073 |
| k-d_tree_pandas      |     0.73918  |       0.745687 |   1.10694  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.741427 |        5.37582 |   0.738731 |
| Bori_Aron_solution-1 |     0.724241 |       10.7746  |   0.775666 |
| k-d_tree_sklearn     |     0.753057 |       16.158   |   1.05762  |
| k-d_tree_polars      |     0.739573 |        4.86683 |   6.5969   |
| barab-szabi-1        |     0.73971  |        4.87591 |   6.62718  |
| k-d_tree_pandas      |     0.741606 |        3.92036 |   6.92835  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.917888 |        72.3671 |    3.71146 |
| k-d_tree_sklearn     |     0.813374 |       229.868  |    4.75129 |
| Bori_Aron_solution-1 |     0.727067 |       151.733  |   18.1953  |