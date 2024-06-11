# 2024-06-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.58137  |       0.356496 |   0.347756 |
| barab-szabi-1        |     0.79067  |       0.402055 |   0.349376 |
| k-d_tree_polars      |     0.824032 |       0.409922 |   0.352237 |
| Bori_Aron_solution-1 |     4.69838  |       0.421792 |   0.421305 |
| solution-1           |     8.2109   |       1e-06    |   0.432994 |
| k-d_tree_pandas      |     0.809261 |       0.398479 |   0.491469 |
| k-d_tree_sklearn     |     3.30823  |       1.03056  |   0.669955 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.809326 |       0.419013 |   0.351467 |
| barab-szabi-2        |     0.810906 |       0.354543 |   0.354087 |
| barab-szabi-1        |     0.805655 |       0.424032 |   0.358863 |
| Bori_Aron_solution-1 |     0.791535 |       0.489339 |   0.484818 |
| k-d_tree_pandas      |     0.809125 |       0.402682 |   0.496101 |
| k-d_tree_sklearn     |     0.822693 |       0.88874  |   0.701887 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.811406 |       0.433379 |   0.379068 |
| k-d_tree_polars      |     0.799806 |       0.44598  |   0.385389 |
| barab-szabi-2        |     0.796689 |       0.367954 |   0.385501 |
| Bori_Aron_solution-1 |     0.792687 |       0.528464 |   0.475944 |
| k-d_tree_pandas      |     0.806981 |       0.413163 |   0.53956  |
| k-d_tree_sklearn     |     0.820377 |       0.954013 |   0.727535 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.794649 |       0.428363 |   0.394194 |
| k-d_tree_polars      |     0.824427 |       0.556553 |   0.485139 |
| barab-szabi-1        |     0.806958 |       0.559062 |   0.493733 |
| Bori_Aron_solution-1 |     0.802727 |       0.713762 |   0.498321 |
| k-d_tree_pandas      |     0.808482 |       0.509991 |   0.686043 |
| k-d_tree_sklearn     |     0.815053 |       1.15485  |   0.781193 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.80425  |       0.689618 |   0.446082 |
| Bori_Aron_solution-1 |     0.806227 |       1.3886   |   0.526063 |
| k-d_tree_polars      |     0.802761 |       0.878621 |   0.843994 |
| barab-szabi-1        |     0.802475 |       0.879648 |   0.874466 |
| k-d_tree_sklearn     |     0.819671 |       1.9714   |   0.886471 |
| k-d_tree_pandas      |     0.801537 |       0.767914 |   1.10722  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.785146 |       10.7446  |   0.780953 |
| barab-szabi-2        |     0.805739 |        5.13331 |   0.789579 |
| k-d_tree_sklearn     |     0.804441 |       15.891   |   1.05802  |
| barab-szabi-1        |     0.795902 |        4.95679 |   6.51485  |
| k-d_tree_polars      |     0.793975 |        4.98402 |   6.56516  |
| k-d_tree_pandas      |     0.810137 |        4.01462 |   6.87457  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.00267  |        72.3651 |    3.86907 |
| k-d_tree_sklearn     |     0.885722 |       227.242  |    4.53495 |
| Bori_Aron_solution-1 |     0.788349 |       145.623  |   18.0864  |