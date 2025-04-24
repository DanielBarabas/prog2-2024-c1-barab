# 2025-04-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545503 |       0.41134  |   0.402369 |
| barab-szabi-1        |     0.561321 |       0.402142 |   0.411101 |
| solution-1           |     7.28646  |       1e-06    |   0.484361 |
| k-d_tree_pandas      |     0.553699 |       0.392159 |   0.540617 |
| Bori_Aron_solution-1 |     0.54711  |       0.556623 |   0.546361 |
| k-d_tree_polars      |     7.43346  |       0.502849 |   0.644139 |
| k-d_tree_sklearn     |     3.03889  |       1.16208  |   1.09246  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.602367 |       0.405231 |   0.41196  |
| barab-szabi-1        |     0.575955 |       0.420569 |   0.428479 |
| k-d_tree_polars      |     0.576316 |       0.421935 |   0.429907 |
| k-d_tree_pandas      |     0.57026  |       0.387371 |   0.551021 |
| Bori_Aron_solution-1 |     0.567137 |       0.559954 |   0.554959 |
| k-d_tree_sklearn     |     0.568687 |       0.947472 |   1.02457  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554937 |       0.425627 |   0.436277 |
| barab-szabi-1        |     0.556038 |       0.426844 |   0.436935 |
| k-d_tree_polars      |     0.573933 |       0.431009 |   0.437423 |
| Bori_Aron_solution-1 |     0.550967 |       0.5796   |   0.537996 |
| k-d_tree_pandas      |     0.555391 |       0.401282 |   0.588572 |
| k-d_tree_sklearn     |     0.573169 |       1.03024  |   1.07709  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56469  |       0.493461 |   0.453902 |
| k-d_tree_polars      |     0.569035 |       0.548024 |   0.548027 |
| barab-szabi-1        |     0.572486 |       0.556383 |   0.558841 |
| Bori_Aron_solution-1 |     0.562687 |       0.781425 |   0.569225 |
| k-d_tree_pandas      |     0.567236 |       0.489958 |   0.753156 |
| k-d_tree_sklearn     |     0.583568 |       1.29168  |   1.16162  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579032 |       0.758761 |   0.547757 |
| Bori_Aron_solution-1 |     0.574927 |       1.44487  |   0.610663 |
| k-d_tree_polars      |     0.572501 |       0.888847 |   0.931077 |
| barab-szabi-1        |     0.591231 |       0.891004 |   0.954488 |
| k-d_tree_pandas      |     0.578146 |       0.7802   |   1.20375  |
| k-d_tree_sklearn     |     0.579338 |       2.11989  |   1.2513   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.573191 |        5.49542 |   0.718348 |
| Bori_Aron_solution-1 |     0.569756 |       11.1097  |   0.894865 |
| k-d_tree_sklearn     |     0.60253  |       18.4406  |   1.46165  |
| barab-szabi-1        |     0.582955 |        5.06863 |   6.79668  |
| k-d_tree_polars      |     0.579963 |        5.06402 |   6.87356  |
| k-d_tree_pandas      |     0.569383 |        4.00163 |   7.18803  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611543 |         74.566 |    2.71896 |
| k-d_tree_sklearn     |     0.8843   |        225.589 |    4.40909 |
| Bori_Aron_solution-1 |     0.590634 |        143.13  |   18.7719  |