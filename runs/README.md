# 2025-05-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.33948  |       1e-06    |   0.405554 |
| barab-szabi-2        |     0.556049 |       0.413228 |   0.417815 |
| k-d_tree_polars      |     0.536495 |       0.399666 |   0.418644 |
| barab-szabi-1        |     7.55367  |       0.428973 |   0.490454 |
| k-d_tree_pandas      |     0.556489 |       0.38222  |   0.539072 |
| Bori_Aron_solution-1 |     0.530014 |       0.54458  |   0.543519 |
| k-d_tree_sklearn     |     2.83135  |       1.07732  |   1.04226  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561708 |       0.418729 |   0.419094 |
| k-d_tree_polars      |     0.551132 |       0.413306 |   0.424414 |
| barab-szabi-1        |     0.554801 |       0.411608 |   0.43002  |
| Bori_Aron_solution-1 |     0.54265  |       0.552001 |   0.539607 |
| k-d_tree_pandas      |     0.555181 |       0.395264 |   0.552372 |
| k-d_tree_sklearn     |     0.556752 |       0.961265 |   1.04812  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570704 |       0.444672 |   0.440386 |
| k-d_tree_polars      |     0.54864  |       0.432433 |   0.445499 |
| barab-szabi-1        |     0.554507 |       0.441716 |   0.450281 |
| Bori_Aron_solution-1 |     0.548946 |       0.585678 |   0.55225  |
| k-d_tree_pandas      |     0.54968  |       0.426822 |   0.626111 |
| k-d_tree_sklearn     |     0.555584 |       1.0149   |   1.07308  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552927 |       0.495289 |   0.466492 |
| Bori_Aron_solution-1 |     0.546142 |       0.762469 |   0.556274 |
| k-d_tree_polars      |     0.559918 |       0.541587 |   0.556805 |
| barab-szabi-1        |     0.553546 |       0.546374 |   0.557487 |
| k-d_tree_pandas      |     0.550564 |       0.483897 |   0.730886 |
| k-d_tree_sklearn     |     0.553477 |       1.22758  |   1.12959  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547505 |       0.741586 |   0.492785 |
| Bori_Aron_solution-1 |     0.545719 |       1.41044  |   0.583752 |
| k-d_tree_polars      |     0.550907 |       0.878312 |   0.899196 |
| barab-szabi-1        |     0.550812 |       0.887858 |   0.93451  |
| k-d_tree_pandas      |     0.550876 |       0.757331 |   1.17829  |
| k-d_tree_sklearn     |     0.5504   |       2.04915  |   1.22763  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550988 |        5.12729 |   0.741097 |
| Bori_Aron_solution-1 |     0.543509 |       10.5977  |   0.872929 |
| k-d_tree_sklearn     |     0.5579   |       15.6463  |   1.32225  |
| barab-szabi-1        |     0.545765 |        4.99821 |   6.49438  |
| k-d_tree_polars      |     0.548419 |        5.0099  |   6.62544  |
| k-d_tree_pandas      |     0.551367 |        3.98218 |   6.93231  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609715 |        76.1069 |    2.89762 |
| k-d_tree_sklearn     |     0.702883 |       231.845  |    4.14056 |
| Bori_Aron_solution-1 |     0.545958 |       141.148  |   17.3629  |