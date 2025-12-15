# 2025-12-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.540779 |       0.42175  |   0.442971 |
| barab-szabi-2        |     0.534594 |       0.528435 |   0.443567 |
| k-d_tree_polars      |     0.541385 |       0.43388  |   0.454171 |
| solution-1           |     7.84686  |       1e-06    |   0.479843 |
| Bori_Aron_solution-1 |     0.538976 |       0.612399 |   0.58026  |
| k-d_tree_pandas      |     8.53263  |       0.424854 |   0.679009 |
| k-d_tree_sklearn     |     3.22832  |       1.13943  |   1.10126  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550095 |       0.449383 |   0.444216 |
| k-d_tree_polars      |     0.53696  |       0.422168 |   0.448785 |
| barab-szabi-1        |     0.537772 |       0.422122 |   0.451611 |
| Bori_Aron_solution-1 |     0.527357 |       0.56823  |   0.550511 |
| k-d_tree_pandas      |     0.558193 |       0.407239 |   0.601364 |
| k-d_tree_sklearn     |     0.546247 |       1.02458  |   1.1197   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534025 |       0.464482 |   0.463012 |
| k-d_tree_polars      |     0.545941 |       0.446654 |   0.47708  |
| barab-szabi-1        |     0.543704 |       0.448205 |   0.491725 |
| Bori_Aron_solution-1 |     0.539052 |       0.604309 |   0.573059 |
| k-d_tree_pandas      |     0.543566 |       0.420358 |   0.607464 |
| k-d_tree_sklearn     |     0.541064 |       1.05207  |   1.14228  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54254  |       0.521972 |   0.495955 |
| barab-szabi-1        |     0.557117 |       0.568111 |   0.578855 |
| k-d_tree_polars      |     0.551352 |       0.576383 |   0.584661 |
| Bori_Aron_solution-1 |     0.544407 |       0.803706 |   0.600201 |
| k-d_tree_pandas      |     0.532509 |       0.513695 |   0.750087 |
| k-d_tree_sklearn     |     0.539401 |       1.32535  |   1.216    |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560332 |       0.766617 |   0.543109 |
| Bori_Aron_solution-1 |     0.536515 |       1.50537  |   0.621413 |
| barab-szabi-1        |     0.541443 |       0.958753 |   0.97343  |
| k-d_tree_polars      |     0.562072 |       0.947994 |   1.0018   |
| k-d_tree_sklearn     |     0.567024 |       2.1928   |   1.2382   |
| k-d_tree_pandas      |     0.540818 |       0.835864 |   1.24223  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554969 |        5.35083 |   0.764944 |
| Bori_Aron_solution-1 |     0.538588 |       11.385   |   0.847293 |
| k-d_tree_sklearn     |     0.551622 |       17.5275  |   1.36004  |
| k-d_tree_polars      |     0.551455 |        5.50067 |   6.90801  |
| barab-szabi-1        |     0.543566 |        5.45903 |   6.96835  |
| k-d_tree_pandas      |     0.541538 |        4.43528 |   7.36887  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540192 |        78.6573 |    2.68126 |
| k-d_tree_sklearn     |     0.554748 |       239.633  |    4.29924 |
| Bori_Aron_solution-1 |     0.708186 |       157.759  |   16.2852  |