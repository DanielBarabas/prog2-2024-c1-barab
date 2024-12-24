# 2024-12-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.623038 |       0.406082 |   0.391411 |
| barab-szabi-1        |     0.644384 |       0.411487 |   0.400906 |
| barab-szabi-2        |     0.630345 |       0.408871 |   0.411862 |
| solution-1           |     7.874    |       1e-06    |   0.426778 |
| Bori_Aron_solution-1 |     0.616905 |       0.519377 |   0.518698 |
| k-d_tree_pandas      |     0.620855 |       0.381455 |   0.524878 |
| k-d_tree_sklearn     |    10.548    |       1.17479  |   0.988998 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.6132   |       0.402801 |   0.393211 |
| barab-szabi-2        |     0.614476 |       0.396899 |   0.39489  |
| barab-szabi-1        |     0.613312 |       0.412626 |   0.416338 |
| k-d_tree_pandas      |     0.619858 |       0.383879 |   0.533747 |
| Bori_Aron_solution-1 |     0.610547 |       0.532626 |   0.535405 |
| k-d_tree_sklearn     |     0.618012 |       0.907699 |   0.98269  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610765 |       0.407734 |   0.408078 |
| k-d_tree_polars      |     0.615623 |       0.429068 |   0.417763 |
| barab-szabi-1        |     0.614825 |       0.467395 |   0.429418 |
| Bori_Aron_solution-1 |     0.607795 |       0.567583 |   0.544966 |
| k-d_tree_pandas      |     0.62151  |       0.408598 |   0.580237 |
| k-d_tree_sklearn     |     0.613492 |       0.939502 |   0.995816 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613127 |       0.467541 |   0.434644 |
| k-d_tree_polars      |     0.660883 |       0.535908 |   0.517133 |
| barab-szabi-1        |     0.615158 |       0.541652 |   0.527046 |
| Bori_Aron_solution-1 |     0.607718 |       0.744906 |   0.535828 |
| k-d_tree_pandas      |     0.621609 |       0.482642 |   0.705459 |
| k-d_tree_sklearn     |     0.621434 |       1.18007  |   1.06275  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613197 |       0.714662 |   0.46785  |
| Bori_Aron_solution-1 |     0.607876 |       1.39875  |   0.560632 |
| k-d_tree_polars      |     0.612533 |       0.864961 |   0.85985  |
| barab-szabi-1        |     0.614836 |       0.870203 |   0.902879 |
| k-d_tree_pandas      |     0.613508 |       0.753292 |   1.13453  |
| k-d_tree_sklearn     |     0.614329 |       1.98966  |   1.14615  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612204 |        5.20191 |   0.71575  |
| Bori_Aron_solution-1 |     0.606471 |       10.4323  |   0.816443 |
| k-d_tree_sklearn     |     0.617442 |       15.4419  |   1.24552  |
| k-d_tree_polars      |     0.616758 |        4.91442 |   6.25603  |
| barab-szabi-1        |     0.614224 |        4.91546 |   6.34377  |
| k-d_tree_pandas      |     0.610589 |        3.90876 |   6.62948  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632085 |        71.1831 |    2.85812 |
| k-d_tree_sklearn     |     0.61916  |       226.71   |    4.18624 |
| Bori_Aron_solution-1 |     0.639761 |       149.217  |   18.7046  |