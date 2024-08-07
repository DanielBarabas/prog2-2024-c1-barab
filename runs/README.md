# 2024-08-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.609636 |       0.398374 |   0.383948 |
| barab-szabi-2        |     7.80553  |       0.652608 |   0.385578 |
| barab-szabi-1        |     0.604648 |       0.395139 |   0.38809  |
| Bori_Aron_solution-1 |     0.602615 |       0.523564 |   0.515032 |
| k-d_tree_pandas      |     0.600898 |       0.441217 |   0.51758  |
| solution-1           |     7.73847  |       1e-06    |   0.543473 |
| k-d_tree_sklearn     |     2.97112  |       1.1001   |   0.724388 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614849 |       0.388773 |   0.387746 |
| barab-szabi-1        |     0.611538 |       0.401246 |   0.392426 |
| k-d_tree_polars      |     0.619581 |       0.407809 |   0.393933 |
| Bori_Aron_solution-1 |     0.606747 |       0.526101 |   0.512988 |
| k-d_tree_pandas      |     0.619753 |       0.38108  |   0.533364 |
| k-d_tree_sklearn     |     0.617849 |       0.914219 |   0.757722 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613901 |       0.403841 |   0.403872 |
| barab-szabi-1        |     0.610469 |       0.429685 |   0.423035 |
| k-d_tree_polars      |     0.618605 |       0.431723 |   0.426016 |
| Bori_Aron_solution-1 |     0.6003   |       0.556297 |   0.53384  |
| k-d_tree_pandas      |     0.614532 |       0.400644 |   0.581869 |
| k-d_tree_sklearn     |     0.61669  |       0.952457 |   0.741511 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616652 |       0.464035 |   0.427393 |
| k-d_tree_polars      |     0.615975 |       0.53425  |   0.520163 |
| barab-szabi-1        |     0.614642 |       0.532853 |   0.521759 |
| Bori_Aron_solution-1 |     0.620817 |       0.738405 |   0.543613 |
| k-d_tree_pandas      |     0.6185   |       0.479218 |   0.715039 |
| k-d_tree_sklearn     |     0.61534  |       1.16034  |   0.803148 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615785 |       0.71138  |   0.479194 |
| Bori_Aron_solution-1 |     0.606514 |       1.40553  |   0.566128 |
| k-d_tree_sklearn     |     0.637949 |       2.01834  |   0.881704 |
| k-d_tree_polars      |     0.623154 |       0.87474  |   0.895767 |
| barab-szabi-1        |     0.631514 |       0.867484 |   0.940173 |
| k-d_tree_pandas      |     0.611862 |       0.74234  |   1.14349  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607406 |        5.43348 |   0.735108 |
| Bori_Aron_solution-1 |     0.61589  |       10.7543  |   0.856008 |
| k-d_tree_sklearn     |     0.622626 |       16.3442  |   0.976515 |
| k-d_tree_polars      |     0.623905 |        4.89893 |   6.5446   |
| barab-szabi-1        |     0.612387 |        4.86503 |   6.66073  |
| k-d_tree_pandas      |     0.614362 |        3.91422 |   6.97086  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614039 |        73.5928 |    3.08609 |
| k-d_tree_sklearn     |     0.668442 |       233.597  |    3.9405  |
| Bori_Aron_solution-1 |     0.692603 |       147.394  |   17.6665  |