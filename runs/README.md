# 2025-04-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.64259  |       1e-06    |   0.361631 |
| barab-szabi-2        |     0.557616 |       0.413814 |   0.414248 |
| k-d_tree_polars      |     0.568213 |       0.425518 |   0.427112 |
| barab-szabi-1        |     0.567059 |       0.441634 |   0.432997 |
| Bori_Aron_solution-1 |     0.552119 |       0.544171 |   0.546908 |
| k-d_tree_pandas      |     8.43412  |       0.399964 |   0.607065 |
| k-d_tree_sklearn     |     3.05547  |       1.02133  |   1.10502  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57483  |       0.417573 |   0.413816 |
| barab-szabi-1        |     0.605105 |       0.423431 |   0.43769  |
| k-d_tree_polars      |     0.583332 |       0.422531 |   0.440654 |
| Bori_Aron_solution-1 |     0.558595 |       0.563119 |   0.557764 |
| k-d_tree_pandas      |     0.575647 |       0.39323  |   0.560512 |
| k-d_tree_sklearn     |     0.568578 |       0.971371 |   1.07435  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591274 |       0.452527 |   0.445456 |
| barab-szabi-1        |     0.583258 |       0.485965 |   0.454289 |
| k-d_tree_polars      |     0.584618 |       0.462906 |   0.484182 |
| Bori_Aron_solution-1 |     0.568301 |       0.594749 |   0.569331 |
| k-d_tree_pandas      |     0.571162 |       0.408557 |   0.602161 |
| k-d_tree_sklearn     |     0.589094 |       1.07572  |   1.09614  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571772 |       0.494664 |   0.459228 |
| k-d_tree_polars      |     0.598758 |       0.552663 |   0.541809 |
| barab-szabi-1        |     0.573388 |       0.548414 |   0.548145 |
| Bori_Aron_solution-1 |     0.576049 |       0.779202 |   0.581679 |
| k-d_tree_pandas      |     0.585535 |       0.491546 |   0.755114 |
| k-d_tree_sklearn     |     0.576698 |       1.26087  |   1.15097  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567186 |       0.736303 |   0.493549 |
| Bori_Aron_solution-1 |     0.558926 |       1.42291  |   0.604437 |
| k-d_tree_polars      |     0.579432 |       0.883949 |   0.93343  |
| barab-szabi-1        |     0.5764   |       0.900259 |   0.977242 |
| k-d_tree_pandas      |     0.565921 |       0.755635 |   1.20991  |
| k-d_tree_sklearn     |     0.574245 |       2.1585   |   1.23194  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571431 |        5.41098 |   0.730765 |
| Bori_Aron_solution-1 |     0.575424 |       10.7938  |   0.905813 |
| k-d_tree_sklearn     |     0.577086 |       16.4599  |   1.35079  |
| k-d_tree_polars      |     0.573544 |        4.96631 |   6.71204  |
| barab-szabi-1        |     0.582684 |        4.99183 |   6.94691  |
| k-d_tree_pandas      |     0.568973 |        3.84308 |   7.19569  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.829556 |        74.0509 |    3.40587 |
| k-d_tree_sklearn     |     0.678957 |       235.375  |    4.36375 |
| Bori_Aron_solution-1 |     0.561918 |       151.645  |   16.0702  |