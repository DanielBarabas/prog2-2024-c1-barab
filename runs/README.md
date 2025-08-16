# 2025-08-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.553616 |       0.4179   |   0.433751 |
| barab-szabi-2        |     0.962167 |       0.431411 |   0.435817 |
| solution-1           |     7.94289  |       1e-06    |   0.525235 |
| barab-szabi-1        |     0.988471 |       0.41758  |   0.537642 |
| Bori_Aron_solution-1 |     0.543048 |       0.559221 |   0.550852 |
| k-d_tree_pandas      |     8.41976  |       0.532174 |   0.77052  |
| k-d_tree_sklearn     |     3.21661  |       1.2729   |   1.07468  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.556792 |       0.432486 |   0.437831 |
| barab-szabi-2        |     0.556573 |       0.448073 |   0.441412 |
| barab-szabi-1        |     0.555685 |       0.433426 |   0.454256 |
| k-d_tree_pandas      |     0.548232 |       0.399668 |   0.565479 |
| Bori_Aron_solution-1 |     0.547551 |       0.578424 |   0.570786 |
| k-d_tree_sklearn     |     0.557443 |       0.995907 |   1.08689  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548693 |       0.449669 |   0.450318 |
| barab-szabi-1        |     0.547175 |       0.450856 |   0.470114 |
| k-d_tree_polars      |     0.552283 |       0.471393 |   0.474653 |
| Bori_Aron_solution-1 |     0.542353 |       0.597081 |   0.562927 |
| k-d_tree_pandas      |     0.553749 |       0.412776 |   0.614155 |
| k-d_tree_sklearn     |     0.557715 |       1.05179  |   1.13832  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555866 |       0.511252 |   0.47482  |
| k-d_tree_polars      |     0.555085 |       0.578516 |   0.566845 |
| Bori_Aron_solution-1 |     0.544732 |       0.782843 |   0.575929 |
| barab-szabi-1        |     0.691936 |       0.558312 |   0.579915 |
| k-d_tree_pandas      |     0.546633 |       0.497205 |   0.745469 |
| k-d_tree_sklearn     |     0.556323 |       1.28154  |   1.18583  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551097 |       0.75304  |   0.515963 |
| Bori_Aron_solution-1 |     0.552256 |       1.4428   |   0.607415 |
| k-d_tree_polars      |     0.556718 |       0.927045 |   0.927866 |
| barab-szabi-1        |     0.548546 |       0.905858 |   0.972831 |
| k-d_tree_pandas      |     0.552191 |       0.780143 |   1.21238  |
| k-d_tree_sklearn     |     0.570413 |       2.27134  |   1.29719  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554936 |        6.16467 |   0.888055 |
| Bori_Aron_solution-1 |     0.55206  |       11.647   |   0.890342 |
| k-d_tree_sklearn     |     0.559723 |       18.3881  |   1.41777  |
| k-d_tree_polars      |     0.570387 |        5.24436 |   7.28717  |
| barab-szabi-1        |     0.549748 |        5.23971 |   7.5444   |
| k-d_tree_pandas      |     0.565314 |        4.0658  |   7.85013  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550322 |        89.4582 |    3.66531 |
| k-d_tree_sklearn     |     0.582458 |       274.437  |    4.41565 |
| Bori_Aron_solution-1 |     0.611417 |       161.271  |   16.1277  |