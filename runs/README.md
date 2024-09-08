# 2024-09-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.45162  |       1e-06    |   0.351706 |
| barab-szabi-2        |     0.608529 |       0.386226 |   0.387043 |
| barab-szabi-1        |     0.609971 |       0.397257 |   0.393366 |
| k-d_tree_polars      |     4.11847  |       0.419905 |   0.393624 |
| Bori_Aron_solution-1 |     4.38404  |       0.501845 |   0.452504 |
| k-d_tree_pandas      |     0.608414 |       0.378109 |   0.524703 |
| k-d_tree_sklearn     |     3.0095   |       0.969588 |   0.701621 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605598 |       0.389686 |   0.386817 |
| k-d_tree_polars      |     0.603476 |       0.403363 |   0.39158  |
| barab-szabi-1        |     0.610518 |       0.4051   |   0.394948 |
| Bori_Aron_solution-1 |     0.606248 |       0.53859  |   0.526923 |
| k-d_tree_pandas      |     0.610494 |       0.384857 |   0.527113 |
| k-d_tree_sklearn     |     0.616137 |       0.904648 |   0.701028 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615245 |       0.405447 |   0.403023 |
| barab-szabi-1        |     0.609252 |       0.422876 |   0.419368 |
| k-d_tree_polars      |     0.608368 |       0.425068 |   0.422431 |
| Bori_Aron_solution-1 |     0.601883 |       0.571355 |   0.526235 |
| k-d_tree_pandas      |     0.605671 |       0.400171 |   0.575871 |
| k-d_tree_sklearn     |     0.615134 |       0.941845 |   0.72654  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609045 |       0.467766 |   0.427191 |
| barab-szabi-1        |     0.613696 |       0.537562 |   0.529904 |
| k-d_tree_polars      |     0.613161 |       0.529126 |   0.531775 |
| Bori_Aron_solution-1 |     0.615906 |       0.741025 |   0.536835 |
| k-d_tree_pandas      |     0.61239  |       0.478064 |   0.711509 |
| k-d_tree_sklearn     |     0.608706 |       1.14589  |   0.779039 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603595 |       0.711598 |   0.464888 |
| Bori_Aron_solution-1 |     0.606354 |       1.38524  |   0.565775 |
| k-d_tree_sklearn     |     0.613641 |       1.97121  |   0.864747 |
| barab-szabi-1        |     0.606048 |       0.846828 |   0.904435 |
| k-d_tree_polars      |     0.614141 |       0.848813 |   0.931922 |
| k-d_tree_pandas      |     0.607239 |       0.735655 |   1.13793  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611195 |        5.29166 |   0.737535 |
| Bori_Aron_solution-1 |     0.605272 |       10.6845  |   0.827842 |
| k-d_tree_sklearn     |     0.610618 |       16.0247  |   0.991037 |
| barab-szabi-1        |     0.606907 |        4.83264 |   6.52974  |
| k-d_tree_polars      |     0.613405 |        4.84671 |   6.53207  |
| k-d_tree_pandas      |     0.620644 |        3.88123 |   6.92684  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.684781 |        70.9649 |    3.11212 |
| k-d_tree_sklearn     |     0.820051 |       226.89   |    3.90671 |
| Bori_Aron_solution-1 |     0.595964 |       147.035  |   18.2083  |