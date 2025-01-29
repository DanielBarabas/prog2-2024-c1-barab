# 2025-01-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.30137  |       1e-06    |   0.35717  |
| barab-szabi-2        |     7.75788  |       0.499348 |   0.394996 |
| k-d_tree_polars      |     0.574211 |       0.399628 |   0.40147  |
| barab-szabi-1        |     0.580425 |       0.395728 |   0.401697 |
| Bori_Aron_solution-1 |     0.572672 |       0.534758 |   0.524514 |
| k-d_tree_pandas      |     0.580089 |       0.386753 |   0.525385 |
| k-d_tree_sklearn     |     3.10909  |       1.03337  |   1.00545  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.576805 |       0.403236 |   0.398053 |
| k-d_tree_polars      |     0.579022 |       0.413363 |   0.401382 |
| barab-szabi-1        |     0.579778 |       0.406243 |   0.402991 |
| Bori_Aron_solution-1 |     0.57107  |       0.532891 |   0.525658 |
| k-d_tree_pandas      |     0.583174 |       0.38217  |   0.543629 |
| k-d_tree_sklearn     |     0.588677 |       1.00546  |   1.01134  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584855 |       0.417798 |   0.408387 |
| k-d_tree_polars      |     0.579741 |       0.429133 |   0.429818 |
| barab-szabi-1        |     0.578212 |       0.4275   |   0.442375 |
| Bori_Aron_solution-1 |     0.59876  |       0.568405 |   0.530279 |
| k-d_tree_pandas      |     0.590448 |       0.408124 |   0.588398 |
| k-d_tree_sklearn     |     0.582397 |       0.981284 |   1.03175  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591211 |       0.486148 |   0.443263 |
| k-d_tree_polars      |     0.583019 |       0.538856 |   0.528791 |
| barab-szabi-1        |     0.580919 |       0.530121 |   0.538107 |
| Bori_Aron_solution-1 |     0.5741   |       0.734043 |   0.540537 |
| k-d_tree_pandas      |     0.578905 |       0.475607 |   0.713328 |
| k-d_tree_sklearn     |     0.589275 |       1.24878  |   1.08606  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579061 |       0.722905 |   0.475192 |
| Bori_Aron_solution-1 |     0.574046 |       1.35393  |   0.565608 |
| k-d_tree_polars      |     0.579961 |       0.87026  |   0.876339 |
| barab-szabi-1        |     0.588032 |       0.859541 |   0.912305 |
| k-d_tree_pandas      |     0.577428 |       0.739012 |   1.14417  |
| k-d_tree_sklearn     |     0.586258 |       2.03065  |   1.18796  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586854 |        5.35661 |   0.725482 |
| Bori_Aron_solution-1 |     0.591639 |       10.3947  |   0.854828 |
| k-d_tree_sklearn     |     0.586299 |       16.2903  |   1.30754  |
| k-d_tree_polars      |     0.579834 |        4.85175 |   6.57122  |
| barab-szabi-1        |     0.580698 |        4.84164 |   6.57292  |
| k-d_tree_pandas      |     0.577631 |        3.75978 |   7.0933   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.592475 |        77.7512 |    3.10506 |
| k-d_tree_sklearn     |     0.616444 |       233.614  |    4.50457 |
| Bori_Aron_solution-1 |     0.681395 |       144.959  |   18.3983  |