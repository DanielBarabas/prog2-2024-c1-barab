# 2025-12-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.37284  |       1e-06    |   0.42184  |
| barab-szabi-2        |     0.520097 |       0.488898 |   0.427796 |
| barab-szabi-1        |     0.527754 |       0.415004 |   0.42996  |
| k-d_tree_polars      |     0.52693  |       0.405154 |   0.431722 |
| Bori_Aron_solution-1 |     0.520053 |       0.546623 |   0.543929 |
| k-d_tree_pandas      |     8.11003  |       0.407197 |   0.643153 |
| k-d_tree_sklearn     |     3.00935  |       1.05854  |   1.05625  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532936 |       0.436313 |   0.430537 |
| k-d_tree_polars      |     0.530614 |       0.4152   |   0.433425 |
| barab-szabi-1        |     0.534221 |       0.413016 |   0.435527 |
| Bori_Aron_solution-1 |     0.52152  |       0.556994 |   0.548725 |
| k-d_tree_pandas      |     0.530887 |       0.397894 |   0.55714  |
| k-d_tree_sklearn     |     0.532856 |       0.964477 |   1.06737  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533535 |       0.440039 |   0.44865  |
| k-d_tree_polars      |     0.53086  |       0.442101 |   0.459249 |
| barab-szabi-1        |     0.528267 |       0.437919 |   0.467269 |
| Bori_Aron_solution-1 |     0.527728 |       0.601672 |   0.549549 |
| k-d_tree_pandas      |     0.536    |       0.411122 |   0.612688 |
| k-d_tree_sklearn     |     0.536811 |       1.0143   |   1.10022  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53177  |       0.505054 |   0.472698 |
| k-d_tree_polars      |     0.531554 |       0.556272 |   0.556074 |
| Bori_Aron_solution-1 |     0.520967 |       0.782942 |   0.560383 |
| barab-szabi-1        |     0.524516 |       0.559893 |   0.565976 |
| k-d_tree_pandas      |     0.531577 |       0.503817 |   0.777825 |
| k-d_tree_sklearn     |     0.530228 |       1.26178  |   1.16385  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527568 |       0.754165 |   0.514808 |
| Bori_Aron_solution-1 |     0.523474 |       1.45698  |   0.591988 |
| k-d_tree_polars      |     0.527127 |       0.932002 |   0.912133 |
| barab-szabi-1        |     0.532514 |       0.930353 |   0.945472 |
| k-d_tree_pandas      |     0.531102 |       0.825936 |   1.16793  |
| k-d_tree_sklearn     |     0.536679 |       2.12362  |   1.22438  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529728 |        5.24181 |   0.790508 |
| Bori_Aron_solution-1 |     0.532229 |       10.985   |   0.850769 |
| k-d_tree_sklearn     |     0.536306 |       16.74    |   1.33971  |
| k-d_tree_polars      |     0.531668 |        5.34899 |   6.49158  |
| barab-szabi-1        |     0.533539 |        5.43541 |   6.59172  |
| k-d_tree_pandas      |     0.532535 |        4.39204 |   7.19607  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528762 |        80.7289 |    2.84134 |
| k-d_tree_sklearn     |     0.542504 |       239.9    |    4.19831 |
| Bori_Aron_solution-1 |     0.648451 |       151.122  |   17.7417  |