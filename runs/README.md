# 2024-08-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.17037  |       1e-06    |   0.37437  |
| barab-szabi-2        |     0.565153 |       0.410633 |   0.400427 |
| k-d_tree_polars      |     0.595503 |       0.420516 |   0.412376 |
| barab-szabi-1        |     8.52066  |       0.444414 |   0.462648 |
| k-d_tree_pandas      |     0.588015 |       0.396466 |   0.550711 |
| Bori_Aron_solution-1 |     0.569994 |       0.562705 |   0.561779 |
| k-d_tree_sklearn     |     3.08385  |       0.957688 |   0.750656 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586076 |       0.413733 |   0.399904 |
| k-d_tree_polars      |     0.575757 |       0.43253  |   0.402843 |
| barab-szabi-1        |     0.573252 |       0.438668 |   0.408933 |
| Bori_Aron_solution-1 |     0.578416 |       0.565431 |   0.566247 |
| k-d_tree_pandas      |     0.585863 |       0.402071 |   0.575101 |
| k-d_tree_sklearn     |     0.579695 |       0.942606 |   0.732824 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587885 |       0.414496 |   0.415174 |
| k-d_tree_polars      |     0.583475 |       0.455846 |   0.444019 |
| barab-szabi-1        |     0.596163 |       0.481633 |   0.451893 |
| Bori_Aron_solution-1 |     0.579186 |       0.5787   |   0.543772 |
| k-d_tree_pandas      |     0.564214 |       0.41884  |   0.594406 |
| k-d_tree_sklearn     |     0.582891 |       0.990427 |   0.759507 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569112 |       0.473879 |   0.436571 |
| k-d_tree_polars      |     0.584418 |       0.549786 |   0.529955 |
| barab-szabi-1        |     0.59014  |       0.5429   |   0.533896 |
| Bori_Aron_solution-1 |     0.567497 |       0.76944  |   0.546917 |
| k-d_tree_pandas      |     0.568985 |       0.488187 |   0.726895 |
| k-d_tree_sklearn     |     0.571401 |       1.18852  |   0.799684 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570452 |       0.7341   |   0.487893 |
| Bori_Aron_solution-1 |     0.566463 |       1.42687  |   0.605454 |
| k-d_tree_sklearn     |     0.583394 |       2.05196  |   0.900188 |
| k-d_tree_polars      |     0.58276  |       0.862945 |   0.906051 |
| barab-szabi-1        |     0.580583 |       0.875681 |   0.953982 |
| k-d_tree_pandas      |     0.582496 |       0.774965 |   1.16912  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581733 |        5.82342 |   0.751473 |
| Bori_Aron_solution-1 |     0.57674  |       11.2408  |   0.869118 |
| k-d_tree_sklearn     |     0.586761 |       17.6905  |   1.01379  |
| barab-szabi-1        |     0.584236 |        4.89859 |   6.93791  |
| k-d_tree_polars      |     0.577057 |        4.93727 |   7.10216  |
| k-d_tree_pandas      |     0.58427  |        3.92047 |   7.58165  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579699 |        74.5169 |    3.02129 |
| k-d_tree_sklearn     |     0.592295 |       233.297  |    4.01317 |
| Bori_Aron_solution-1 |     0.692832 |       150.684  |   15.795   |