# 2024-06-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.70322  |       0.344523 |   0.33181  |
| k-d_tree_polars      |     0.799444 |       0.394074 |   0.340245 |
| barab-szabi-1        |     0.789497 |       0.417575 |   0.341321 |
| Bori_Aron_solution-1 |     5.32426  |       0.400173 |   0.397781 |
| k-d_tree_pandas      |     0.789953 |       0.372997 |   0.468956 |
| solution-1           |     7.99454  |       1e-06    |   0.562109 |
| k-d_tree_sklearn     |     4.05851  |       1.12184  |   0.66959  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.78205  |       0.341296 |   0.339511 |
| k-d_tree_polars      |     0.786406 |       0.401841 |   0.346176 |
| barab-szabi-1        |     0.783729 |       0.40601  |   0.346302 |
| Bori_Aron_solution-1 |     0.772262 |       0.474338 |   0.465058 |
| k-d_tree_pandas      |     0.789555 |       0.378088 |   0.475217 |
| k-d_tree_sklearn     |     0.800587 |       0.843778 |   0.673402 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.78712  |       0.354055 |   0.353023 |
| k-d_tree_polars      |     0.807932 |       0.425076 |   0.369489 |
| barab-szabi-1        |     0.793994 |       0.426949 |   0.373085 |
| Bori_Aron_solution-1 |     0.775316 |       0.519346 |   0.467438 |
| k-d_tree_pandas      |     0.792521 |       0.398535 |   0.518535 |
| k-d_tree_sklearn     |     0.791883 |       0.886854 |   0.69804  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.784236 |       0.420609 |   0.387877 |
| k-d_tree_polars      |     0.796423 |       0.53568  |   0.470289 |
| barab-szabi-1        |     0.814983 |       0.53651  |   0.481002 |
| Bori_Aron_solution-1 |     0.78866  |       0.69213  |   0.48157  |
| k-d_tree_pandas      |     0.790114 |       0.48118  |   0.652252 |
| k-d_tree_sklearn     |     0.788975 |       1.10316  |   0.755136 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.781256 |       0.664061 |   0.454029 |
| Bori_Aron_solution-1 |     0.775852 |       1.33346  |   0.507469 |
| k-d_tree_polars      |     0.784517 |       0.858311 |   0.816202 |
| barab-szabi-1        |     0.787145 |       0.860251 |   0.854496 |
| k-d_tree_sklearn     |     0.788062 |       1.92233  |   0.862911 |
| k-d_tree_pandas      |     0.784346 |       0.749369 |   1.07255  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.788832 |        5.16502 |   0.754889 |
| Bori_Aron_solution-1 |     0.775556 |       10.5578  |   0.766316 |
| k-d_tree_sklearn     |     0.790723 |       15.6057  |   1.02763  |
| barab-szabi-1        |     0.784667 |        4.98306 |   6.34279  |
| k-d_tree_polars      |     0.789765 |        4.96245 |   6.39338  |
| k-d_tree_pandas      |     0.779166 |        4.00298 |   6.69124  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.04508  |        77.4561 |    3.832   |
| k-d_tree_sklearn     |     1.22109  |       226.733  |    4.45461 |
| Bori_Aron_solution-1 |     0.775436 |       149.109  |   17.1126  |