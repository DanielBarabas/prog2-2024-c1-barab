# 2024-11-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614418 |       0.38425  |   0.377706 |
| barab-szabi-1        |     0.612791 |       0.399502 |   0.387972 |
| k-d_tree_polars      |     0.632605 |       0.394529 |   0.389561 |
| solution-1           |     7.48146  |       1e-06    |   0.435217 |
| Bori_Aron_solution-1 |     0.612261 |       0.516157 |   0.509925 |
| k-d_tree_pandas      |     0.614315 |       0.376283 |   0.528482 |
| k-d_tree_sklearn     |    10.2499   |       1.05705  |   0.949765 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.645866 |       0.389195 |   0.385959 |
| barab-szabi-1        |     0.622057 |       0.409335 |   0.393845 |
| k-d_tree_polars      |     0.619308 |       0.404678 |   0.396824 |
| Bori_Aron_solution-1 |     0.611032 |       0.53346  |   0.518797 |
| k-d_tree_pandas      |     0.624353 |       0.399247 |   0.531449 |
| k-d_tree_sklearn     |     0.630459 |       0.871119 |   0.965344 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61796  |       0.403883 |   0.397077 |
| barab-szabi-1        |     0.613508 |       0.427285 |   0.423454 |
| k-d_tree_polars      |     0.612503 |       0.429008 |   0.440073 |
| Bori_Aron_solution-1 |     0.611574 |       0.563937 |   0.52055  |
| k-d_tree_pandas      |     0.637233 |       0.402024 |   0.578147 |
| k-d_tree_sklearn     |     0.618834 |       0.935554 |   0.985964 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616291 |       0.469376 |   0.426974 |
| k-d_tree_polars      |     0.617765 |       0.537023 |   0.514652 |
| barab-szabi-1        |     0.615725 |       0.54033  |   0.527582 |
| Bori_Aron_solution-1 |     0.603801 |       0.747905 |   0.538795 |
| k-d_tree_pandas      |     0.61398  |       0.482993 |   0.711262 |
| k-d_tree_sklearn     |     0.614964 |       1.17214  |   1.04795  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621068 |       0.714795 |   0.471146 |
| Bori_Aron_solution-1 |     0.610921 |       1.39043  |   0.561064 |
| k-d_tree_polars      |     0.618949 |       0.863954 |   0.872093 |
| barab-szabi-1        |     0.62074  |       0.859331 |   0.917696 |
| k-d_tree_sklearn     |     0.622957 |       1.98504  |   1.12592  |
| k-d_tree_pandas      |     0.618576 |       0.75804  |   1.14148  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62309  |        5.46853 |   0.745557 |
| Bori_Aron_solution-1 |     0.608885 |       10.9235  |   0.820783 |
| k-d_tree_sklearn     |     0.620483 |       16.4877  |   1.26121  |
| k-d_tree_polars      |     0.616656 |        4.90984 |   6.73324  |
| barab-szabi-1        |     0.615405 |        4.90254 |   6.77866  |
| k-d_tree_pandas      |     0.613806 |        3.90601 |   7.18591  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.637507 |        72.9619 |    3.00378 |
| k-d_tree_sklearn     |     0.620317 |       230.629  |    4.28726 |
| Bori_Aron_solution-1 |     0.635889 |       159.481  |   16.6735  |