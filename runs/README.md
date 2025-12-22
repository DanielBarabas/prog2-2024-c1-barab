# 2025-12-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.641453 |       0.835274 |   0.454195 |
| barab-szabi-1        |     0.563581 |       0.422249 |   0.454406 |
| k-d_tree_polars      |     0.547119 |       0.408328 |   0.469198 |
| Bori_Aron_solution-1 |     0.526051 |       0.555091 |   0.556647 |
| k-d_tree_pandas      |    10.6512   |       0.491467 |   1.04777  |
| solution-1           |     9.81832  |       1e-06    |   1.09683  |
| k-d_tree_sklearn     |     3.57557  |       1.65673  |   1.09852  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.537205 |       0.418841 |   0.438734 |
| barab-szabi-2        |     0.542059 |       0.438983 |   0.439379 |
| k-d_tree_polars      |     0.534637 |       0.416013 |   0.443951 |
| Bori_Aron_solution-1 |     0.527511 |       0.563897 |   0.552444 |
| k-d_tree_pandas      |     0.537517 |       0.404027 |   0.57028  |
| k-d_tree_sklearn     |     0.553379 |       0.98996  |   1.08191  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528112 |       0.463234 |   0.464938 |
| k-d_tree_polars      |     0.545596 |       0.449637 |   0.469065 |
| barab-szabi-1        |     0.540455 |       0.449509 |   0.47097  |
| Bori_Aron_solution-1 |     0.530651 |       0.6054   |   0.598983 |
| k-d_tree_pandas      |     0.535571 |       0.436944 |   0.60812  |
| k-d_tree_sklearn     |     0.539263 |       1.03532  |   1.11469  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529529 |       0.511349 |   0.475221 |
| k-d_tree_polars      |     0.535468 |       0.572739 |   0.575604 |
| barab-szabi-1        |     0.534614 |       0.568448 |   0.581678 |
| Bori_Aron_solution-1 |     0.544089 |       0.806569 |   0.591105 |
| k-d_tree_pandas      |     0.542207 |       0.505668 |   0.742498 |
| k-d_tree_sklearn     |     0.529999 |       1.2677   |   1.16631  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54578  |       0.769007 |   0.556859 |
| Bori_Aron_solution-1 |     0.534686 |       1.47259  |   0.592524 |
| k-d_tree_polars      |     0.548191 |       0.934463 |   0.92178  |
| barab-szabi-1        |     0.544655 |       0.94505  |   1.03071  |
| k-d_tree_pandas      |     0.546834 |       0.828614 |   1.23031  |
| k-d_tree_sklearn     |     0.549096 |       2.23611  |   1.27443  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537683 |        5.27788 |   0.793363 |
| Bori_Aron_solution-1 |     0.520707 |       11.1872  |   0.84596  |
| k-d_tree_sklearn     |     0.538034 |       16.9971  |   1.32579  |
| k-d_tree_polars      |     0.530365 |        5.37837 |   6.74451  |
| barab-szabi-1        |     0.532641 |        5.38955 |   6.81906  |
| k-d_tree_pandas      |     0.534764 |        4.49371 |   7.21078  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528666 |        79.9431 |    2.81534 |
| k-d_tree_sklearn     |     0.53338  |       237.291  |    4.06143 |
| Bori_Aron_solution-1 |     0.644467 |       150.95   |   18.1711  |