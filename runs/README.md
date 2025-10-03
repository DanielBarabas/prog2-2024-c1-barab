# 2025-10-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.556152 |       0.416379 |   0.433953 |
| k-d_tree_polars      |     0.541893 |       0.403864 |   0.437028 |
| barab-szabi-2        |     0.869897 |       0.608931 |   0.43796  |
| solution-1           |     9.01467  |       1e-06    |   0.50931  |
| Bori_Aron_solution-1 |     0.546781 |       0.553727 |   0.55734  |
| k-d_tree_pandas      |     8.80648  |       0.414517 |   0.753278 |
| k-d_tree_sklearn     |     3.0115   |       1.22714  |   1.07974  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551842 |       0.439421 |   0.436641 |
| k-d_tree_polars      |     0.550867 |       0.42632  |   0.44448  |
| barab-szabi-1        |     0.549434 |       0.419629 |   0.445219 |
| Bori_Aron_solution-1 |     0.549797 |       0.566817 |   0.556027 |
| k-d_tree_pandas      |     0.549668 |       0.410662 |   0.575186 |
| k-d_tree_sklearn     |     0.556012 |       0.988759 |   1.09252  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552325 |       0.446753 |   0.452326 |
| k-d_tree_polars      |     0.552368 |       0.454907 |   0.469043 |
| barab-szabi-1        |     0.556744 |       0.456845 |   0.476004 |
| Bori_Aron_solution-1 |     0.555985 |       0.621061 |   0.565874 |
| k-d_tree_pandas      |     0.558244 |       0.419065 |   0.605754 |
| k-d_tree_sklearn     |     0.583659 |       1.05405  |   1.12398  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556242 |       0.517712 |   0.482286 |
| k-d_tree_polars      |     0.558893 |       0.579602 |   0.56762  |
| Bori_Aron_solution-1 |     0.550423 |       0.797028 |   0.577195 |
| barab-szabi-1        |     0.559363 |       0.574243 |   0.581503 |
| k-d_tree_pandas      |     0.565523 |       0.524217 |   0.761799 |
| k-d_tree_sklearn     |     0.571503 |       1.29958  |   1.17312  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543504 |       0.760379 |   0.517545 |
| Bori_Aron_solution-1 |     0.566186 |       1.52918  |   0.652723 |
| k-d_tree_polars      |     0.562706 |       0.991829 |   0.963775 |
| barab-szabi-1        |     0.553138 |       0.959279 |   0.976837 |
| k-d_tree_pandas      |     0.561586 |       0.83375  |   1.17403  |
| k-d_tree_sklearn     |     0.55742  |       2.1802   |   1.24897  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569271 |        5.48998 |   0.754976 |
| Bori_Aron_solution-1 |     0.545802 |       11.7599  |   0.874456 |
| k-d_tree_sklearn     |     0.565162 |       17.4598  |   1.3257   |
| k-d_tree_polars      |     0.557803 |        5.65462 |   6.72835  |
| barab-szabi-1        |     0.56279  |        5.60696 |   6.79903  |
| k-d_tree_pandas      |     0.609714 |        4.62885 |   7.43001  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570328 |        72.9436 |    2.68437 |
| k-d_tree_sklearn     |     0.567797 |       239.189  |    4.32882 |
| Bori_Aron_solution-1 |     0.805256 |       152.643  |   18.6555  |