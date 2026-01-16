# 2026-01-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.554606 |       0.421188 |   0.433762 |
| barab-szabi-1        |     0.552814 |       0.422886 |   0.46685  |
| solution-1           |     8.37454  |       2e-06    |   0.46937  |
| barab-szabi-2        |     0.565444 |       0.558406 |   0.50146  |
| Bori_Aron_solution-1 |     0.553153 |       0.575828 |   0.570044 |
| k-d_tree_pandas      |     9.15118  |       0.469285 |   0.740418 |
| k-d_tree_sklearn     |     3.38105  |       1.17081  |   1.25551  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.548999 |       0.445741 |   0.464238 |
| barab-szabi-2        |     0.569958 |       0.491751 |   0.476013 |
| k-d_tree_polars      |     0.56219  |       0.437349 |   0.482283 |
| k-d_tree_pandas      |     0.572796 |       0.446064 |   0.611553 |
| Bori_Aron_solution-1 |     0.566988 |       0.616824 |   0.649016 |
| k-d_tree_sklearn     |     0.588004 |       1.08536  |   1.1501   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574311 |       0.48161  |   0.489375 |
| k-d_tree_polars      |     0.594434 |       0.489594 |   0.496818 |
| barab-szabi-1        |     0.572647 |       0.487269 |   0.50946  |
| Bori_Aron_solution-1 |     0.549703 |       0.60578  |   0.57564  |
| k-d_tree_pandas      |     0.572117 |       0.458258 |   0.654768 |
| k-d_tree_sklearn     |     0.577204 |       1.16606  |   1.29917  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539493 |       0.525975 |   0.47626  |
| k-d_tree_polars      |     0.531032 |       0.56914  |   0.565731 |
| Bori_Aron_solution-1 |     0.527865 |       0.798957 |   0.573028 |
| barab-szabi-1        |     0.541067 |       0.577801 |   0.580849 |
| k-d_tree_pandas      |     0.535347 |       0.51295  |   0.738602 |
| k-d_tree_sklearn     |     0.544019 |       1.36665  |   1.17536  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533781 |       0.770744 |   0.513121 |
| Bori_Aron_solution-1 |     0.532399 |       1.50774  |   0.595504 |
| k-d_tree_polars      |     0.533842 |       0.912872 |   0.962757 |
| barab-szabi-1        |     0.531186 |       0.922473 |   0.997467 |
| k-d_tree_sklearn     |     0.532929 |       2.19     |   1.17895  |
| k-d_tree_pandas      |     0.532808 |       0.808491 |   1.1981   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52254  |        5.63871 |   0.764669 |
| Bori_Aron_solution-1 |     0.525595 |       11.6942  |   0.85892  |
| k-d_tree_sklearn     |     0.538352 |       17.3947  |   1.32504  |
| k-d_tree_polars      |     0.556942 |        5.09772 |   7.5915   |
| k-d_tree_pandas      |     0.538531 |        4.17609 |   7.8339   |
| barab-szabi-1        |     0.557655 |        5.20835 |   7.8773   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533508 |        87.3769 |    2.73672 |
| k-d_tree_sklearn     |     0.543906 |       263.184  |    3.53485 |
| Bori_Aron_solution-1 |     0.624894 |       155.212  |   17.5783  |