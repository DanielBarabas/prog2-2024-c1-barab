# 2025-08-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.16245  |       0.773685 |   0.418845 |
| barab-szabi-1        |     0.542648 |       0.410012 |   0.422253 |
| k-d_tree_polars      |     0.556439 |       0.409896 |   0.452627 |
| Bori_Aron_solution-1 |     0.541011 |       0.558223 |   0.550028 |
| k-d_tree_pandas      |     0.562191 |       0.385142 |   0.559605 |
| solution-1           |     7.49174  |       1e-06    |   0.593998 |
| k-d_tree_sklearn     |     3.0271   |       1.13087  |   1.06595  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.560661 |       0.416177 |   0.432168 |
| barab-szabi-2        |     0.557767 |       0.450579 |   0.443177 |
| barab-szabi-1        |     0.573194 |       0.422231 |   0.447714 |
| k-d_tree_pandas      |     0.570176 |       0.393003 |   0.553488 |
| Bori_Aron_solution-1 |     0.557436 |       0.567075 |   0.55823  |
| k-d_tree_sklearn     |     0.557742 |       0.982226 |   1.05337  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565256 |       0.43411  |   0.441538 |
| k-d_tree_polars      |     0.558651 |       0.449619 |   0.454602 |
| barab-szabi-1        |     0.554569 |       0.436311 |   0.471528 |
| Bori_Aron_solution-1 |     0.557588 |       0.598935 |   0.555271 |
| k-d_tree_pandas      |     0.558177 |       0.4091   |   0.604142 |
| k-d_tree_sklearn     |     0.56079  |       1.03758  |   1.08383  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558854 |       0.504266 |   0.475189 |
| k-d_tree_polars      |     0.559844 |       0.558082 |   0.563285 |
| barab-szabi-1        |     0.563105 |       0.563798 |   0.563636 |
| Bori_Aron_solution-1 |     0.554748 |       0.772834 |   0.572567 |
| k-d_tree_pandas      |     0.565539 |       0.493374 |   0.752785 |
| k-d_tree_sklearn     |     0.575346 |       1.26328  |   1.13989  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55951  |       0.758007 |   0.504873 |
| Bori_Aron_solution-1 |     0.552706 |       1.40625  |   0.592818 |
| k-d_tree_polars      |     0.555267 |       0.899765 |   0.918378 |
| barab-szabi-1        |     0.558925 |       0.931113 |   0.97132  |
| k-d_tree_pandas      |     0.554564 |       0.771589 |   1.18747  |
| k-d_tree_sklearn     |     0.5605   |       2.11093  |   1.23295  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562768 |        5.3717  |   0.75323  |
| Bori_Aron_solution-1 |     0.548104 |       10.7434  |   0.853322 |
| k-d_tree_sklearn     |     0.565294 |       16.3535  |   1.306    |
| k-d_tree_polars      |     0.570491 |        5.00518 |   6.71793  |
| barab-szabi-1        |     0.557436 |        5.01536 |   6.79735  |
| k-d_tree_pandas      |     0.55544  |        3.96904 |   7.08593  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556528 |        76.5286 |    2.79366 |
| k-d_tree_sklearn     |     0.765235 |       237.616  |    4.1357  |
| Bori_Aron_solution-1 |     0.56935  |       143.271  |   18.1149  |