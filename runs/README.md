# 2025-03-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.604098 |       0.454988 |   0.454428 |
| barab-szabi-2        |     0.590567 |       0.452699 |   0.462356 |
| barab-szabi-1        |     0.611451 |       0.494734 |   0.505448 |
| solution-1           |     8.2578   |       1e-06    |   0.584125 |
| Bori_Aron_solution-1 |     0.598674 |       0.622894 |   0.630632 |
| k-d_tree_pandas      |     8.67149  |       0.488526 |   0.78364  |
| k-d_tree_sklearn     |     3.43731  |       1.31417  |   1.14445  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.637414 |       0.444231 |   0.460814 |
| barab-szabi-1        |     0.604809 |       0.462177 |   0.463326 |
| barab-szabi-2        |     0.607408 |       0.449169 |   0.463676 |
| k-d_tree_pandas      |     0.615619 |       0.426835 |   0.606072 |
| Bori_Aron_solution-1 |     0.598794 |       0.629857 |   0.612865 |
| k-d_tree_sklearn     |     0.622344 |       1.05643  |   1.16918  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612197 |       0.474965 |   0.458447 |
| k-d_tree_polars      |     0.61429  |       0.478689 |   0.481877 |
| barab-szabi-1        |     0.618248 |       0.510558 |   0.48436  |
| Bori_Aron_solution-1 |     0.614354 |       0.652183 |   0.619532 |
| k-d_tree_pandas      |     0.625912 |       0.450006 |   0.677865 |
| k-d_tree_sklearn     |     0.606532 |       1.15031  |   1.2043   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623081 |       0.53055  |   0.482904 |
| k-d_tree_polars      |     0.621376 |       0.599067 |   0.595182 |
| barab-szabi-1        |     0.619002 |       0.58917  |   0.608932 |
| Bori_Aron_solution-1 |     0.617745 |       0.817065 |   0.645185 |
| k-d_tree_pandas      |     0.627796 |       0.521393 |   0.803009 |
| k-d_tree_sklearn     |     0.621253 |       1.36711  |   1.28412  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.620343 |       1.52625  |   0.670488 |
| barab-szabi-2        |     0.630608 |       0.812455 |   0.682256 |
| k-d_tree_polars      |     0.641263 |       0.927038 |   0.990697 |
| barab-szabi-1        |     0.638856 |       0.943861 |   1.03666  |
| k-d_tree_pandas      |     0.616794 |       0.799496 |   1.29337  |
| k-d_tree_sklearn     |     0.62305  |       2.32408  |   1.33971  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618748 |        5.86013 |   0.768939 |
| Bori_Aron_solution-1 |     0.61113  |       11.377   |   0.941811 |
| k-d_tree_sklearn     |     0.614156 |       18.6477  |   1.48778  |
| barab-szabi-1        |     0.618704 |        5.02156 |   7.15988  |
| k-d_tree_polars      |     0.605688 |        5.01278 |   7.25668  |
| k-d_tree_pandas      |     0.623099 |        3.90437 |   7.65914  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.872232 |        72.7794 |    3.48768 |
| k-d_tree_sklearn     |     0.667173 |       226.478  |    4.25631 |
| Bori_Aron_solution-1 |     0.617844 |       159.162  |   15.4379  |