# 2024-08-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.83397  |       0.697266 |   0.385579 |
| k-d_tree_polars      |     0.593241 |       0.392618 |   0.385585 |
| barab-szabi-1        |     0.594756 |       0.392862 |   0.386153 |
| solution-1           |     7.62534  |       1e-06    |   0.452969 |
| k-d_tree_pandas      |     0.603167 |       0.409501 |   0.535245 |
| Bori_Aron_solution-1 |     0.598526 |       0.513703 |   0.547657 |
| k-d_tree_sklearn     |     2.99496  |       0.962946 |   0.693415 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610472 |       0.387958 |   0.388581 |
| k-d_tree_polars      |     0.607656 |       0.399774 |   0.389441 |
| barab-szabi-1        |     0.630399 |       0.396857 |   0.389557 |
| Bori_Aron_solution-1 |     0.59901  |       0.522167 |   0.520588 |
| k-d_tree_pandas      |     0.605169 |       0.376553 |   0.529204 |
| k-d_tree_sklearn     |     0.612953 |       0.882622 |   0.696297 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621051 |       0.403182 |   0.396722 |
| barab-szabi-1        |     0.620414 |       0.42635  |   0.418737 |
| k-d_tree_polars      |     0.607639 |       0.424971 |   0.419048 |
| Bori_Aron_solution-1 |     0.60694  |       0.581686 |   0.554047 |
| k-d_tree_pandas      |     0.605213 |       0.402667 |   0.569853 |
| k-d_tree_sklearn     |     0.611406 |       0.93044  |   0.721632 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616847 |       0.462614 |   0.425701 |
| k-d_tree_polars      |     0.611614 |       0.532714 |   0.515208 |
| barab-szabi-1        |     0.604756 |       0.53106  |   0.527412 |
| Bori_Aron_solution-1 |     0.598413 |       0.738101 |   0.537601 |
| k-d_tree_pandas      |     0.6013   |       0.474536 |   0.702465 |
| k-d_tree_sklearn     |     0.609453 |       1.14846  |   0.780446 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609663 |       0.703512 |   0.459995 |
| Bori_Aron_solution-1 |     0.600112 |       1.37487  |   0.561678 |
| k-d_tree_polars      |     0.60873  |       0.854061 |   0.863404 |
| k-d_tree_sklearn     |     0.610379 |       1.96487  |   0.871487 |
| barab-szabi-1        |     0.615496 |       0.844537 |   0.895545 |
| k-d_tree_pandas      |     0.604248 |       0.742049 |   1.1397   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.602349 |        5.36236 |   0.735645 |
| Bori_Aron_solution-1 |     0.602876 |       10.8374  |   0.820098 |
| k-d_tree_sklearn     |     0.620674 |       16.3818  |   0.986708 |
| k-d_tree_polars      |     0.614724 |        4.87251 |   6.66095  |
| barab-szabi-1        |     0.60296  |        4.84041 |   6.68188  |
| k-d_tree_pandas      |     0.600657 |        3.8726  |   7.01712  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612096 |        72.6569 |    3.07837 |
| k-d_tree_sklearn     |     0.625348 |       238.256  |    4.00429 |
| Bori_Aron_solution-1 |     0.696535 |       144.163  |   18.7936  |