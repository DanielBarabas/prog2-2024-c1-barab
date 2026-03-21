# 2026-03-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47812  |       0.430258 |   0.431446 |
| k-d_tree_polars      |     0.480467 |       0.400003 |   0.436679 |
| Bori_Aron_solution-1 |     0.474794 |       0.542096 |   0.549649 |
| k-d_tree_pandas      |     0.479212 |       0.381582 |   0.551954 |
| solution-1           |     8.31681  |       1e-06    |   0.61244  |
| barab-szabi-1        |     9.15371  |       0.464302 |   0.809635 |
| k-d_tree_sklearn     |     3.38348  |       1.13687  |   1.08111  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486135 |       0.432804 |   0.431749 |
| barab-szabi-1        |     0.519665 |       0.426733 |   0.435725 |
| k-d_tree_polars      |     0.488416 |       0.412059 |   0.438787 |
| Bori_Aron_solution-1 |     0.482536 |       0.550315 |   0.544052 |
| k-d_tree_pandas      |     0.489454 |       0.386963 |   0.554049 |
| k-d_tree_sklearn     |     0.491533 |       0.962047 |   1.05402  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.489898 |       0.449769 |   0.445807 |
| k-d_tree_polars      |     0.488846 |       0.437285 |   0.467412 |
| barab-szabi-1        |     0.487523 |       0.436221 |   0.472904 |
| Bori_Aron_solution-1 |     0.481097 |       0.594729 |   0.545872 |
| k-d_tree_pandas      |     0.491553 |       0.410774 |   0.596576 |
| k-d_tree_sklearn     |     0.492353 |       1.01437  |   1.07855  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.490996 |       0.505842 |   0.474274 |
| Bori_Aron_solution-1 |     0.486926 |       0.787632 |   0.561028 |
| barab-szabi-1        |     0.489038 |       0.562824 |   0.57898  |
| k-d_tree_polars      |     0.487968 |       0.561833 |   0.607132 |
| k-d_tree_pandas      |     0.488368 |       0.505511 |   0.732083 |
| k-d_tree_sklearn     |     0.493918 |       1.26625  |   1.1316   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488324 |       0.732752 |   0.505548 |
| Bori_Aron_solution-1 |     0.47816  |       1.46176  |   0.586059 |
| k-d_tree_polars      |     0.488045 |       0.938014 |   0.906424 |
| barab-szabi-1        |     0.489943 |       0.941193 |   0.954422 |
| k-d_tree_pandas      |     0.489781 |       0.821838 |   1.16755  |
| k-d_tree_sklearn     |     0.491657 |       2.12253  |   1.20861  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491417 |        4.98001 |   0.739983 |
| Bori_Aron_solution-1 |     0.481074 |       11.1054  |   0.83686  |
| k-d_tree_sklearn     |     0.489445 |       17.146   |   1.32382  |
| barab-szabi-1        |     0.488432 |        5.4432  |   6.47589  |
| k-d_tree_polars      |     0.490433 |        5.57862 |   6.48284  |
| k-d_tree_pandas      |     0.520382 |        4.49516 |   6.8131   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492452 |        73.3926 |    2.62778 |
| k-d_tree_sklearn     |     0.82581  |       241.23   |    4.08854 |
| Bori_Aron_solution-1 |     0.498486 |       156.46   |   15.3519  |