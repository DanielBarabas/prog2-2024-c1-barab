# 2025-06-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.60295  |       1e-06    |   0.419319 |
| barab-szabi-1        |     0.544731 |       0.412807 |   0.430057 |
| k-d_tree_polars      |     0.540942 |       0.411155 |   0.433032 |
| barab-szabi-2        |     0.546097 |       0.425001 |   0.43593  |
| Bori_Aron_solution-1 |     0.548666 |       0.575768 |   0.56153  |
| k-d_tree_pandas      |     8.15104  |       0.419892 |   0.785302 |
| k-d_tree_sklearn     |     3.36592  |       1.14543  |   1.10043  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.562801 |       0.415582 |   0.429908 |
| barab-szabi-2        |     0.556073 |       0.423614 |   0.431379 |
| barab-szabi-1        |     0.570454 |       0.422535 |   0.440136 |
| k-d_tree_pandas      |     0.566688 |       0.409385 |   0.567228 |
| Bori_Aron_solution-1 |     0.557714 |       0.577904 |   0.568233 |
| k-d_tree_sklearn     |     0.581737 |       0.992091 |   1.0745   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581211 |       0.450502 |   0.445935 |
| k-d_tree_polars      |     0.573249 |       0.452506 |   0.471107 |
| barab-szabi-1        |     0.566278 |       0.448387 |   0.47813  |
| Bori_Aron_solution-1 |     0.552224 |       0.607088 |   0.563843 |
| k-d_tree_pandas      |     0.557022 |       0.419303 |   0.609672 |
| k-d_tree_sklearn     |     0.569573 |       1.09025  |   1.13778  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566771 |       0.521442 |   0.469195 |
| k-d_tree_polars      |     0.559504 |       0.552606 |   0.564686 |
| barab-szabi-1        |     0.572961 |       0.560448 |   0.571678 |
| Bori_Aron_solution-1 |     0.554224 |       0.778432 |   0.571865 |
| k-d_tree_pandas      |     0.560821 |       0.493977 |   0.74521  |
| k-d_tree_sklearn     |     0.559074 |       1.29952  |   1.16867  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558739 |       0.771329 |   0.521009 |
| Bori_Aron_solution-1 |     0.569074 |       1.43354  |   0.599191 |
| k-d_tree_polars      |     0.569645 |       0.886657 |   0.93071  |
| barab-szabi-1        |     0.562854 |       0.885092 |   0.963534 |
| k-d_tree_sklearn     |     0.566314 |       2.11955  |   1.23221  |
| k-d_tree_pandas      |     0.558586 |       0.760871 |   1.23232  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557839 |        5.4134  |   0.759752 |
| Bori_Aron_solution-1 |     0.574203 |       10.7858  |   0.87224  |
| k-d_tree_sklearn     |     0.56456  |       16.7095  |   1.32709  |
| k-d_tree_polars      |     0.56296  |        5.01733 |   6.71194  |
| barab-szabi-1        |     0.56405  |        5.00907 |   6.77833  |
| k-d_tree_pandas      |     0.559582 |        3.88866 |   7.0744   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.775964 |        76.0442 |    2.89617 |
| k-d_tree_sklearn     |     0.668981 |       239.498  |    3.89347 |
| Bori_Aron_solution-1 |     0.554372 |       146.431  |   16.9354  |