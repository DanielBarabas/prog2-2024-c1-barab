# 2024-08-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.69538  |       1e-06    |   0.367396 |
| barab-szabi-1        |     0.624703 |       0.399733 |   0.390732 |
| barab-szabi-2        |     0.618215 |       0.386992 |   0.392214 |
| k-d_tree_polars      |     0.615855 |       0.405761 |   0.398793 |
| Bori_Aron_solution-1 |     0.642553 |       0.528155 |   0.538128 |
| k-d_tree_pandas      |     7.94462  |       0.396508 |   0.665728 |
| k-d_tree_sklearn     |     2.98445  |       0.950804 |   0.722955 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623601 |       0.397629 |   0.391123 |
| k-d_tree_polars      |     0.618046 |       0.407797 |   0.397967 |
| barab-szabi-1        |     0.622034 |       0.40433  |   0.402413 |
| Bori_Aron_solution-1 |     0.607663 |       0.535103 |   0.536503 |
| k-d_tree_pandas      |     0.626116 |       0.392487 |   0.538549 |
| k-d_tree_sklearn     |     0.626145 |       0.950872 |   0.716749 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.64208  |       0.408209 |   0.408109 |
| barab-szabi-1        |     0.617982 |       0.431885 |   0.419256 |
| k-d_tree_polars      |     0.633524 |       0.427913 |   0.42167  |
| Bori_Aron_solution-1 |     0.610409 |       0.568097 |   0.536116 |
| k-d_tree_pandas      |     0.627867 |       0.403348 |   0.573015 |
| k-d_tree_sklearn     |     0.631287 |       0.964895 |   0.740796 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618454 |       0.465066 |   0.428749 |
| k-d_tree_polars      |     0.61298  |       0.547696 |   0.523701 |
| barab-szabi-1        |     0.619269 |       0.533475 |   0.532177 |
| Bori_Aron_solution-1 |     0.614041 |       0.754379 |   0.545867 |
| k-d_tree_pandas      |     0.6212   |       0.489568 |   0.708869 |
| k-d_tree_sklearn     |     0.627167 |       1.18096  |   0.796388 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62015  |       0.726987 |   0.468454 |
| Bori_Aron_solution-1 |     0.612426 |       1.39729  |   0.578969 |
| k-d_tree_polars      |     0.61871  |       0.863238 |   0.878997 |
| k-d_tree_sklearn     |     0.629821 |       2.03814  |   0.882902 |
| barab-szabi-1        |     0.624997 |       0.863955 |   0.915058 |
| k-d_tree_pandas      |     0.626631 |       0.751344 |   1.16152  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613597 |        5.6104  |   0.757404 |
| Bori_Aron_solution-1 |     0.611716 |       10.8868  |   0.8553   |
| k-d_tree_sklearn     |     0.618136 |       16.5784  |   0.991009 |
| k-d_tree_polars      |     0.618438 |        4.90672 |   6.7426   |
| barab-szabi-1        |     0.628172 |        4.87884 |   6.80482  |
| k-d_tree_pandas      |     0.621225 |        3.90388 |   7.19139  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.942331 |        74.8584 |    3.50735 |
| k-d_tree_sklearn     |     0.631864 |       232.503  |    3.92089 |
| Bori_Aron_solution-1 |     0.65232  |       155.457  |   16.8908  |