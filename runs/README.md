# 2024-04-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.754066 |       0.351591 |   0.352905 |
| barab-szabi-1        |     0.7587   |       0.425288 |   0.357419 |
| k-d_tree_polars      |     8.7987   |       0.456711 |   0.375351 |
| solution-1           |     8.97921  |       1e-06    |   0.376068 |
| k-d_tree_pandas      |     0.757932 |       0.414115 |   0.480727 |
| Bori_Aron_solution-1 |     0.743779 |       0.501565 |   0.51136  |
| k-d_tree_sklearn     |     3.69032  |       0.92727  |   0.677907 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.773569 |       0.431688 |   0.36237  |
| barab-szabi-1        |     0.766349 |       0.410947 |   0.36775  |
| barab-szabi-2        |     0.768306 |       0.36938  |   0.459196 |
| Bori_Aron_solution-1 |     0.76861  |       0.540263 |   0.521711 |
| k-d_tree_pandas      |     0.770667 |       0.425314 |   0.523704 |
| k-d_tree_sklearn     |     0.790593 |       0.923384 |   0.685642 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.761198 |       0.386527 |   0.368488 |
| barab-szabi-1        |     0.766884 |       0.440754 |   0.388689 |
| k-d_tree_polars      |     0.787719 |       0.45661  |   0.390754 |
| Bori_Aron_solution-1 |     0.747139 |       0.542321 |   0.50601  |
| k-d_tree_pandas      |     0.765296 |       0.430101 |   0.576057 |
| k-d_tree_sklearn     |     0.768467 |       0.995541 |   0.736142 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.753881 |       0.440032 |   0.39269  |
| k-d_tree_polars      |     0.744446 |       0.565225 |   0.483685 |
| Bori_Aron_solution-1 |     0.778165 |       0.722405 |   0.495378 |
| barab-szabi-1        |     0.771541 |       0.57658  |   0.501737 |
| k-d_tree_pandas      |     0.763411 |       0.503541 |   0.683787 |
| k-d_tree_sklearn     |     0.776459 |       1.12491  |   0.771551 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.763414 |       0.705891 |   0.421256 |
| Bori_Aron_solution-1 |     0.750999 |       1.40165  |   0.539324 |
| k-d_tree_polars      |     0.754161 |       0.863176 |   0.835556 |
| k-d_tree_sklearn     |     0.770549 |       2.02892  |   0.873441 |
| barab-szabi-1        |     0.749623 |       0.873108 |   0.901224 |
| k-d_tree_pandas      |     0.746844 |       0.766802 |   1.27551  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.745364 |        5.60894 |   0.75017  |
| Bori_Aron_solution-1 |     0.740804 |       10.98    |   0.791146 |
| k-d_tree_sklearn     |     0.759257 |       16.5277  |   1.0671   |
| barab-szabi-1        |     0.749163 |        4.79686 |   6.86356  |
| k-d_tree_polars      |     0.773    |        4.90444 |   7.07758  |
| k-d_tree_pandas      |     0.754536 |        3.89967 |   7.17102  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.906417 |        76.2133 |    3.96059 |
| k-d_tree_sklearn     |     0.74921  |       233.19   |    5.31436 |
| Bori_Aron_solution-1 |     0.803992 |       144.513  |   15.2518  |