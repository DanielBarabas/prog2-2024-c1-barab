# 2024-03-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.717269 |       0.570964 |   0.362964 |
| barab-szabi-1        |     0.718057 |       0.438373 |   0.384123 |
| k-d_tree_polars      |     0.754518 |       0.427786 |   0.389324 |
| Bori_Aron_solution-1 |     0.692433 |       0.521741 |   0.517068 |
| k-d_tree_sklearn     |     3.39547  |       1.35816  |   0.717496 |
| solution-1           |     8.42534  |       2e-06    |   0.83827  |
| k-d_tree_pandas      |     9.41589  |       0.475932 |   1.09882  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734786 |       0.393515 |   0.379953 |
| k-d_tree_polars      |     0.736932 |       0.433085 |   0.38444  |
| barab-szabi-1        |     0.743514 |       0.435894 |   0.386703 |
| Bori_Aron_solution-1 |     0.719126 |       0.535378 |   0.520825 |
| k-d_tree_pandas      |     0.738004 |       0.408411 |   0.539328 |
| k-d_tree_sklearn     |     0.760491 |       0.907295 |   0.70525  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.733817 |       0.402467 |   0.385339 |
| k-d_tree_polars      |     0.734445 |       0.443167 |   0.409997 |
| barab-szabi-1        |     0.765115 |       0.468773 |   0.416503 |
| Bori_Aron_solution-1 |     0.714879 |       0.575318 |   0.524093 |
| k-d_tree_pandas      |     0.758006 |       0.41481  |   0.573489 |
| k-d_tree_sklearn     |     0.744663 |       0.970406 |   0.726173 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.731033 |       0.461846 |   0.418129 |
| k-d_tree_polars      |     0.730691 |       0.555995 |   0.504941 |
| barab-szabi-1        |     0.719956 |       0.545075 |   0.521919 |
| Bori_Aron_solution-1 |     0.71861  |       0.7587   |   0.540652 |
| k-d_tree_pandas      |     0.728352 |       0.497016 |   0.718701 |
| k-d_tree_sklearn     |     0.735002 |       1.16152  |   0.808869 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.725743 |       0.742465 |   0.471561 |
| Bori_Aron_solution-1 |     0.712772 |       1.4163   |   0.551795 |
| k-d_tree_polars      |     0.717792 |       0.851264 |   0.877136 |
| barab-szabi-1        |     0.71362  |       0.871637 |   0.894308 |
| k-d_tree_sklearn     |     0.72719  |       2.00082  |   0.911275 |
| k-d_tree_pandas      |     0.716915 |       0.755859 |   1.17659  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.71081  |        5.48767 |   0.758334 |
| Bori_Aron_solution-1 |     0.702502 |       10.8597  |   0.824472 |
| k-d_tree_sklearn     |     0.734888 |       17.0252  |   1.09364  |
| barab-szabi-1        |     0.723807 |        4.84997 |   6.76517  |
| k-d_tree_polars      |     0.722389 |        4.89083 |   6.86325  |
| k-d_tree_pandas      |     0.713617 |        3.91663 |   7.24004  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.704749 |        74.0419 |    3.51793 |
| k-d_tree_sklearn     |     0.839596 |       242.307  |    4.95143 |
| Bori_Aron_solution-1 |     0.799442 |       145.359  |   14.3009  |