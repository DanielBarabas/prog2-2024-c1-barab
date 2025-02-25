# 2025-02-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.584015 |       0.406985 |   0.401046 |
| barab-szabi-2        |     3.79328  |       0.419136 |   0.403279 |
| k-d_tree_polars      |     0.58333  |       0.400576 |   0.40482  |
| solution-1           |     7.15803  |       1e-06    |   0.406191 |
| Bori_Aron_solution-1 |     4.34193  |       0.526619 |   0.482365 |
| k-d_tree_pandas      |     0.579957 |       0.376558 |   0.537033 |
| k-d_tree_sklearn     |     2.96188  |       0.965627 |   0.997173 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58871  |       0.403218 |   0.401132 |
| barab-szabi-1        |     0.580868 |       0.402444 |   0.40535  |
| k-d_tree_polars      |     0.582244 |       0.401014 |   0.410722 |
| Bori_Aron_solution-1 |     0.574145 |       0.540898 |   0.542254 |
| k-d_tree_pandas      |     0.606775 |       0.385902 |   0.550864 |
| k-d_tree_sklearn     |     0.589051 |       0.958408 |   1.05014  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581853 |       0.436475 |   0.414141 |
| k-d_tree_polars      |     0.578454 |       0.426749 |   0.432874 |
| barab-szabi-1        |     0.582237 |       0.428463 |   0.435653 |
| Bori_Aron_solution-1 |     0.573282 |       0.583612 |   0.535936 |
| k-d_tree_pandas      |     0.581892 |       0.400785 |   0.586849 |
| k-d_tree_sklearn     |     0.585166 |       0.985559 |   1.04113  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57698  |       0.477709 |   0.442384 |
| k-d_tree_polars      |     0.578772 |       0.531017 |   0.522809 |
| barab-szabi-1        |     0.58111  |       0.546484 |   0.537362 |
| Bori_Aron_solution-1 |     0.572618 |       0.750249 |   0.567661 |
| k-d_tree_pandas      |     0.579394 |       0.479706 |   0.722576 |
| k-d_tree_sklearn     |     0.578097 |       1.21023  |   1.11201  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575473 |       0.726962 |   0.475213 |
| Bori_Aron_solution-1 |     0.572235 |       1.37405  |   0.583106 |
| k-d_tree_polars      |     0.578557 |       0.866346 |   0.87593  |
| barab-szabi-1        |     0.578115 |       0.860893 |   0.920719 |
| k-d_tree_pandas      |     0.592237 |       0.74005  |   1.16615  |
| k-d_tree_sklearn     |     0.583775 |       2.02025  |   1.18413  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584128 |        5.20907 |   0.734319 |
| Bori_Aron_solution-1 |     0.573859 |       10.5694  |   0.870991 |
| k-d_tree_sklearn     |     0.585251 |       16.3056  |   1.31896  |
| barab-szabi-1        |     0.584286 |        4.95372 |   6.5005   |
| k-d_tree_polars      |     0.594368 |        4.87861 |   6.61758  |
| k-d_tree_pandas      |     0.586187 |        3.80573 |   6.92509  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.820452 |        70.4907 |    3.58167 |
| k-d_tree_sklearn     |     0.642538 |       228.144  |    4.29176 |
| Bori_Aron_solution-1 |     0.575579 |       149.028  |   16.147   |