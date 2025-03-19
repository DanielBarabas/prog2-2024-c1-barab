# 2025-03-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577616 |       0.428541 |   0.422187 |
| k-d_tree_polars      |     0.575335 |       0.419772 |   0.437888 |
| barab-szabi-1        |     0.579256 |       0.41469  |   0.46959  |
| solution-1           |     7.27496  |       1e-06    |   0.492217 |
| Bori_Aron_solution-1 |     0.550186 |       0.580235 |   0.572213 |
| k-d_tree_pandas      |     7.56458  |       0.42548  |   0.701087 |
| k-d_tree_sklearn     |     2.9804   |       1.10012  |   1.12311  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.595631 |       0.433614 |   0.433136 |
| barab-szabi-1        |     0.589833 |       0.443323 |   0.43565  |
| k-d_tree_polars      |     0.598522 |       0.449067 |   0.436096 |
| Bori_Aron_solution-1 |     0.578818 |       0.576253 |   0.578229 |
| k-d_tree_pandas      |     0.580952 |       0.422075 |   0.583544 |
| k-d_tree_sklearn     |     0.596484 |       1.04201  |   1.14545  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579795 |       0.442735 |   0.444449 |
| k-d_tree_polars      |     0.592474 |       0.467391 |   0.462954 |
| barab-szabi-1        |     0.585611 |       0.484846 |   0.46826  |
| Bori_Aron_solution-1 |     0.58796  |       0.630215 |   0.571211 |
| k-d_tree_pandas      |     0.590508 |       0.431414 |   0.63128  |
| k-d_tree_sklearn     |     0.598271 |       1.08068  |   1.14665  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.594923 |       0.504642 |   0.46337  |
| k-d_tree_polars      |     0.599064 |       0.569291 |   0.55356  |
| barab-szabi-1        |     0.595992 |       0.574928 |   0.584749 |
| Bori_Aron_solution-1 |     0.585227 |       0.794369 |   0.619538 |
| k-d_tree_pandas      |     0.580531 |       0.513024 |   0.772982 |
| k-d_tree_sklearn     |     0.613633 |       1.30302  |   1.18505  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585222 |       0.793459 |   0.547993 |
| Bori_Aron_solution-1 |     0.585087 |       1.47488  |   0.622886 |
| k-d_tree_polars      |     0.600388 |       0.898372 |   0.922014 |
| barab-szabi-1        |     0.595078 |       0.894603 |   0.975295 |
| k-d_tree_pandas      |     0.616888 |       0.790308 |   1.25381  |
| k-d_tree_sklearn     |     0.593721 |       2.17634  |   1.29251  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590102 |        5.82403 |   0.79803  |
| Bori_Aron_solution-1 |     0.585678 |       11.1512  |   0.901193 |
| k-d_tree_sklearn     |     0.581016 |       17.7769  |   1.40065  |
| barab-szabi-1        |     0.598967 |        4.97932 |   7.08971  |
| k-d_tree_polars      |     0.588705 |        4.97508 |   7.21447  |
| k-d_tree_pandas      |     0.596499 |        3.88178 |   7.51778  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.712963 |        78.5545 |    3.62116 |
| k-d_tree_sklearn     |     0.633695 |       244.116  |    4.27618 |
| Bori_Aron_solution-1 |     0.590155 |       155.474  |   16.3532  |