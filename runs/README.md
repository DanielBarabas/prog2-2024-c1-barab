# 2024-06-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.7637   |       0.388146 |   0.380983 |
| barab-szabi-1        |     0.805206 |       0.39167  |   0.387685 |
| k-d_tree_polars      |     0.803477 |       0.395627 |   0.387925 |
| solution-1           |     8.58827  |       1e-06    |   0.423031 |
| Bori_Aron_solution-1 |     5.03148  |       0.530365 |   0.467184 |
| k-d_tree_pandas      |     0.801313 |       0.377393 |   0.539685 |
| k-d_tree_sklearn     |     3.48541  |       1.1957   |   0.717888 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.81093  |       0.387255 |   0.387847 |
| k-d_tree_polars      |     0.80774  |       0.408164 |   0.398993 |
| barab-szabi-1        |     0.810074 |       0.40791  |   0.400681 |
| Bori_Aron_solution-1 |     0.800908 |       0.528358 |   0.517989 |
| k-d_tree_pandas      |     0.812707 |       0.38648  |   0.536104 |
| k-d_tree_sklearn     |     0.818471 |       0.914041 |   0.732846 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.826671 |       0.409347 |   0.400051 |
| k-d_tree_polars      |     0.817615 |       0.428403 |   0.418131 |
| barab-szabi-1        |     0.813867 |       0.423978 |   0.425664 |
| Bori_Aron_solution-1 |     0.790802 |       0.56529  |   0.524005 |
| k-d_tree_pandas      |     0.802084 |       0.40282  |   0.573484 |
| k-d_tree_sklearn     |     0.815063 |       0.967702 |   0.761414 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.795253 |       0.465112 |   0.450768 |
| k-d_tree_polars      |     0.796624 |       0.542716 |   0.518654 |
| Bori_Aron_solution-1 |     0.797861 |       0.745862 |   0.531651 |
| barab-szabi-1        |     0.799145 |       0.537786 |   0.532173 |
| k-d_tree_pandas      |     0.807465 |       0.478883 |   0.70363  |
| k-d_tree_sklearn     |     0.808754 |       1.1909   |   0.813353 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.795772 |       0.713832 |   0.467999 |
| Bori_Aron_solution-1 |     0.794255 |       1.40297  |   0.556542 |
| k-d_tree_polars      |     0.798742 |       0.863416 |   0.878386 |
| barab-szabi-1        |     0.802721 |       0.859565 |   0.91345  |
| k-d_tree_sklearn     |     0.812227 |       2.01383  |   0.915611 |
| k-d_tree_pandas      |     0.805502 |       0.760421 |   1.15227  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.802772 |        5.4065  |   0.756823 |
| Bori_Aron_solution-1 |     0.786571 |       10.885   |   0.848724 |
| k-d_tree_sklearn     |     0.806706 |       16.524   |   1.08372  |
| barab-szabi-1        |     0.800557 |        4.98823 |   6.67593  |
| k-d_tree_polars      |     0.802626 |        5.02036 |   6.79709  |
| k-d_tree_pandas      |     0.796956 |        4.00039 |   7.0022   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.00227  |        70.5384 |    4.07522 |
| k-d_tree_sklearn     |     0.901803 |       223.908  |    4.47358 |
| Bori_Aron_solution-1 |     0.793739 |       147.769  |   17.3527  |