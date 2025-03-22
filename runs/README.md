# 2025-03-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     1.01532  |       0.40022  |   0.405549 |
| barab-szabi-2        |     0.551867 |       0.403951 |   0.408524 |
| barab-szabi-1        |     1.04619  |       0.427264 |   0.488012 |
| Bori_Aron_solution-1 |     1.04232  |       0.546605 |   0.547208 |
| solution-1           |     7.60445  |       1e-06    |   0.674805 |
| k-d_tree_pandas      |     8.03285  |       0.532461 |   0.758102 |
| k-d_tree_sklearn     |     2.93469  |       1.17831  |   1.01803  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565204 |       0.408956 |   0.408037 |
| barab-szabi-1        |     0.56608  |       0.408941 |   0.410906 |
| k-d_tree_polars      |     0.577142 |       0.408078 |   0.412388 |
| Bori_Aron_solution-1 |     0.555176 |       0.554042 |   0.539842 |
| k-d_tree_pandas      |     0.567516 |       0.394608 |   0.55056  |
| k-d_tree_sklearn     |     0.588458 |       0.948143 |   1.01387  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564768 |       0.422678 |   0.422141 |
| k-d_tree_polars      |     0.579217 |       0.434706 |   0.43395  |
| barab-szabi-1        |     0.566469 |       0.43406  |   0.441198 |
| Bori_Aron_solution-1 |     0.559228 |       0.58238  |   0.546284 |
| k-d_tree_pandas      |     0.564844 |       0.404879 |   0.601136 |
| k-d_tree_sklearn     |     0.5677   |       0.99011  |   1.04286  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563074 |       0.479176 |   0.451302 |
| k-d_tree_polars      |     0.565572 |       0.539204 |   0.533327 |
| barab-szabi-1        |     0.566967 |       0.534118 |   0.548588 |
| Bori_Aron_solution-1 |     0.556247 |       0.750057 |   0.558882 |
| k-d_tree_pandas      |     0.56035  |       0.479453 |   0.725347 |
| k-d_tree_sklearn     |     0.571504 |       1.21444  |   1.09828  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564846 |       0.723108 |   0.489013 |
| Bori_Aron_solution-1 |     0.554797 |       1.38543  |   0.589554 |
| k-d_tree_polars      |     0.561853 |       0.863658 |   0.884031 |
| barab-szabi-1        |     0.569853 |       0.868289 |   0.924556 |
| k-d_tree_pandas      |     0.565601 |       0.747575 |   1.17886  |
| k-d_tree_sklearn     |     0.572729 |       2.03289  |   1.18475  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580301 |        5.25233 |   0.758739 |
| Bori_Aron_solution-1 |     0.559331 |       10.4067  |   0.866209 |
| k-d_tree_sklearn     |     0.572537 |       15.6344  |   1.31263  |
| barab-szabi-1        |     0.564969 |        4.88901 |   6.39429  |
| k-d_tree_polars      |     0.561174 |        4.9186  |   6.6205   |
| k-d_tree_pandas      |     0.564182 |        3.81534 |   6.83312  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.804579 |        71.4256 |    2.98877 |
| k-d_tree_sklearn     |     0.697347 |       224.792  |    4.27951 |
| Bori_Aron_solution-1 |     0.562321 |       152.098  |   16.969   |