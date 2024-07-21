# 2024-07-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.64222  |       1e-06    |   0.345432 |
| barab-szabi-2        |     0.541621 |       0.380395 |   0.37076  |
| barab-szabi-1        |     0.549353 |       0.405078 |   0.375074 |
| k-d_tree_polars      |     0.541943 |       0.386381 |   0.380374 |
| Bori_Aron_solution-1 |     0.537163 |       0.521817 |   0.505135 |
| k-d_tree_pandas      |     0.543843 |       0.367554 |   0.50958  |
| k-d_tree_sklearn     |    10.5873   |       1.0397   |   0.680702 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541009 |       0.38047  |   0.372813 |
| k-d_tree_polars      |     0.544253 |       0.395905 |   0.380686 |
| barab-szabi-1        |     0.540878 |       0.395963 |   0.386184 |
| Bori_Aron_solution-1 |     0.582739 |       0.511923 |   0.504412 |
| k-d_tree_pandas      |     0.542096 |       0.372236 |   0.520812 |
| k-d_tree_sklearn     |     0.547571 |       0.864808 |   0.706875 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544633 |       0.395336 |   0.386645 |
| k-d_tree_polars      |     0.543102 |       0.415843 |   0.408338 |
| barab-szabi-1        |     0.540805 |       0.415311 |   0.412637 |
| Bori_Aron_solution-1 |     0.541429 |       0.5519   |   0.507094 |
| k-d_tree_pandas      |     0.546276 |       0.390896 |   0.557971 |
| k-d_tree_sklearn     |     0.546715 |       0.907645 |   0.709835 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559797 |       0.457394 |   0.420016 |
| k-d_tree_polars      |     0.567016 |       0.526997 |   0.510926 |
| barab-szabi-1        |     0.548664 |       0.528105 |   0.516852 |
| Bori_Aron_solution-1 |     0.533317 |       0.729371 |   0.526198 |
| k-d_tree_pandas      |     0.542238 |       0.469405 |   0.696071 |
| k-d_tree_sklearn     |     0.550154 |       1.13811  |   0.771287 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546712 |       0.712852 |   0.457476 |
| Bori_Aron_solution-1 |     0.536158 |       1.36817  |   0.555751 |
| k-d_tree_polars      |     0.546122 |       0.83058  |   0.847078 |
| k-d_tree_sklearn     |     0.551619 |       1.93465  |   0.860413 |
| barab-szabi-1        |     0.543512 |       0.843627 |   0.890999 |
| k-d_tree_pandas      |     0.543358 |       0.732171 |   1.12626  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548806 |        4.95644 |   0.70578  |
| Bori_Aron_solution-1 |     0.535511 |       10.2653  |   0.827374 |
| k-d_tree_sklearn     |     0.552863 |       14.8975  |   0.962531 |
| k-d_tree_polars      |     0.549298 |        4.82257 |   6.11674  |
| barab-szabi-1        |     0.542463 |        4.82379 |   6.12021  |
| k-d_tree_pandas      |     0.546724 |        3.80522 |   6.53618  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.758703 |        68.5592 |    3.23453 |
| k-d_tree_sklearn     |     0.544138 |       219.132  |    3.83125 |
| Bori_Aron_solution-1 |     0.550801 |       143.647  |   18.1135  |