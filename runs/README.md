# 2024-03-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732281 |       0.36249  |   0.357964 |
| barab-szabi-1        |     0.733236 |       0.404787 |   0.361078 |
| k-d_tree_polars      |     8.25959  |       0.442149 |   0.412219 |
| solution-1           |     8.5072   |       1e-06    |   0.419986 |
| k-d_tree_pandas      |     0.730434 |       0.382512 |   0.503397 |
| Bori_Aron_solution-1 |     0.721487 |       0.499527 |   0.507424 |
| k-d_tree_sklearn     |     3.35615  |       0.900728 |   0.685329 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.73718  |       0.413353 |   0.368913 |
| barab-szabi-2        |     0.730651 |       0.414102 |   0.372469 |
| barab-szabi-1        |     0.733119 |       0.414916 |   0.38389  |
| Bori_Aron_solution-1 |     0.720407 |       0.513057 |   0.507791 |
| k-d_tree_pandas      |     0.73291  |       0.388573 |   0.556065 |
| k-d_tree_sklearn     |     0.737309 |       0.864056 |   0.712515 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.738451 |       0.382315 |   0.380631 |
| k-d_tree_polars      |     0.73785  |       0.437041 |   0.397193 |
| barab-szabi-1        |     0.737412 |       0.435416 |   0.403081 |
| Bori_Aron_solution-1 |     0.719695 |       0.54912  |   0.506109 |
| k-d_tree_pandas      |     0.748202 |       0.415825 |   0.554947 |
| k-d_tree_sklearn     |     0.738773 |       0.90951  |   0.765049 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.725343 |       0.442061 |   0.40055  |
| k-d_tree_polars      |     0.73574  |       0.552339 |   0.499413 |
| barab-szabi-1        |     0.732833 |       0.542942 |   0.507136 |
| Bori_Aron_solution-1 |     0.721772 |       0.737    |   0.516797 |
| k-d_tree_pandas      |     0.733962 |       0.488509 |   0.686174 |
| k-d_tree_sklearn     |     0.740324 |       1.12064  |   0.766869 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732065 |       0.687796 |   0.439143 |
| Bori_Aron_solution-1 |     0.712439 |       1.39754  |   0.538842 |
| k-d_tree_polars      |     0.742038 |       0.877891 |   0.848395 |
| k-d_tree_sklearn     |     0.742027 |       1.95964  |   0.86221  |
| barab-szabi-1        |     0.732171 |       0.86674  |   0.882808 |
| k-d_tree_pandas      |     0.728798 |       0.762276 |   1.14038  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.742053 |        5.24583 |   0.740217 |
| Bori_Aron_solution-1 |     0.724611 |       10.6545  |   0.804904 |
| k-d_tree_sklearn     |     0.737659 |       16.5882  |   1.07173  |
| k-d_tree_polars      |     0.740135 |        5.24305 |   6.46511  |
| barab-szabi-1        |     0.732472 |        4.95648 |   6.52421  |
| k-d_tree_pandas      |     0.729037 |        3.97397 |   6.82484  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.851518 |        71.8249 |    3.84638 |
| k-d_tree_sklearn     |     0.74293  |       232.148  |    5.49642 |
| Bori_Aron_solution-1 |     0.856497 |       147.351  |   14.1451  |