# 2025-01-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574619 |       0.494478 |   0.398603 |
| k-d_tree_polars      |     0.637378 |       0.400758 |   0.401152 |
| barab-szabi-1        |     0.577391 |       0.405196 |   0.41336  |
| Bori_Aron_solution-1 |     0.580765 |       0.530007 |   0.536099 |
| solution-1           |     7.54227  |       1e-06    |   0.565373 |
| k-d_tree_pandas      |     7.87841  |       0.44557  |   0.678179 |
| k-d_tree_sklearn     |     3.05732  |       1.1693   |   1.0233   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588344 |       0.404061 |   0.402166 |
| barab-szabi-1        |     0.583753 |       0.407039 |   0.403842 |
| k-d_tree_polars      |     0.583759 |       0.433691 |   0.410834 |
| Bori_Aron_solution-1 |     0.572744 |       0.538228 |   0.524271 |
| k-d_tree_pandas      |     0.584358 |       0.40227  |   0.553699 |
| k-d_tree_sklearn     |     0.590408 |       0.93597  |   1.03413  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583227 |       0.413393 |   0.422732 |
| k-d_tree_polars      |     0.584366 |       0.442815 |   0.431444 |
| barab-szabi-1        |     0.598581 |       0.428862 |   0.431996 |
| Bori_Aron_solution-1 |     0.583276 |       0.573702 |   0.533393 |
| k-d_tree_pandas      |     0.587683 |       0.401103 |   0.584337 |
| k-d_tree_sklearn     |     0.602301 |       0.992803 |   1.0339   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588524 |       0.471398 |   0.441058 |
| k-d_tree_polars      |     0.584716 |       0.534515 |   0.524929 |
| barab-szabi-1        |     0.582233 |       0.53965  |   0.53416  |
| Bori_Aron_solution-1 |     0.584627 |       0.737349 |   0.552358 |
| k-d_tree_pandas      |     0.581463 |       0.476152 |   0.73034  |
| k-d_tree_sklearn     |     0.590022 |       1.18791  |   1.10011  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580428 |       0.736573 |   0.479241 |
| Bori_Aron_solution-1 |     0.573485 |       1.376    |   0.570726 |
| k-d_tree_polars      |     0.607096 |       0.856914 |   0.877749 |
| barab-szabi-1        |     0.588099 |       0.850435 |   0.912856 |
| k-d_tree_pandas      |     0.580299 |       0.745484 |   1.15283  |
| k-d_tree_sklearn     |     0.592518 |       2.09057  |   1.23172  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.582839 |        5.28142 |   0.727461 |
| Bori_Aron_solution-1 |     0.57536  |       10.5112  |   0.865656 |
| k-d_tree_sklearn     |     0.590236 |       15.8507  |   1.32845  |
| k-d_tree_polars      |     0.591955 |        4.78446 |   6.52951  |
| barab-szabi-1        |     0.586163 |        4.81497 |   6.58037  |
| k-d_tree_pandas      |     0.585888 |        3.84029 |   6.97206  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584736 |         73.42  |    2.93592 |
| k-d_tree_sklearn     |     0.592181 |        223.807 |    4.40411 |
| Bori_Aron_solution-1 |     0.701023 |        143.437 |   18.7887  |