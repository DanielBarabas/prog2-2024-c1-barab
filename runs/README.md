# 2024-12-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.4952   |       1e-06    |   0.364056 |
| barab-szabi-1        |     0.616385 |       0.403248 |   0.389684 |
| barab-szabi-2        |     0.609123 |       0.430726 |   0.390905 |
| k-d_tree_polars      |     0.620808 |       0.395597 |   0.403337 |
| k-d_tree_pandas      |     0.671653 |       0.377181 |   0.525356 |
| Bori_Aron_solution-1 |     0.609986 |       0.514619 |   0.525632 |
| k-d_tree_sklearn     |    10.5062   |       1.10804  |   0.967356 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.617377 |       0.410272 |   0.393502 |
| barab-szabi-2        |     0.652724 |       0.390628 |   0.395478 |
| barab-szabi-1        |     0.632914 |       0.41083  |   0.402658 |
| Bori_Aron_solution-1 |     0.60833  |       0.530574 |   0.530658 |
| k-d_tree_pandas      |     0.630765 |       0.39353  |   0.532782 |
| k-d_tree_sklearn     |     0.618261 |       0.889989 |   0.963644 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620448 |       0.403676 |   0.407589 |
| k-d_tree_polars      |     0.620229 |       0.43119  |   0.427596 |
| barab-szabi-1        |     0.623363 |       0.430698 |   0.428375 |
| k-d_tree_pandas      |     0.620364 |       0.400641 |   0.569727 |
| Bori_Aron_solution-1 |     0.61764  |       0.558964 |   0.592585 |
| k-d_tree_sklearn     |     0.623104 |       0.933406 |   0.994437 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615663 |       0.465482 |   0.426571 |
| k-d_tree_polars      |     0.612777 |       0.542037 |   0.526784 |
| barab-szabi-1        |     0.618219 |       0.535869 |   0.528397 |
| Bori_Aron_solution-1 |     0.60958  |       0.74269  |   0.535936 |
| k-d_tree_pandas      |     0.61612  |       0.477876 |   0.708838 |
| k-d_tree_sklearn     |     0.617998 |       1.1719   |   1.04703  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617084 |       0.718495 |   0.462502 |
| Bori_Aron_solution-1 |     0.612696 |       1.38761  |   0.560717 |
| k-d_tree_polars      |     0.614502 |       0.858935 |   0.873762 |
| barab-szabi-1        |     0.620452 |       0.863976 |   0.917527 |
| k-d_tree_sklearn     |     0.619923 |       1.99562  |   1.14501  |
| k-d_tree_pandas      |     0.619126 |       0.752335 |   1.14656  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620897 |        5.4672  |   0.732071 |
| Bori_Aron_solution-1 |     0.609849 |       10.8067  |   0.822704 |
| k-d_tree_sklearn     |     0.61606  |       16.3402  |   1.24357  |
| barab-szabi-1        |     0.618372 |        4.84324 |   6.65912  |
| k-d_tree_polars      |     0.615398 |        4.88883 |   6.67628  |
| k-d_tree_pandas      |     0.611598 |        3.87446 |   7.0768   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.640185 |        72.2338 |    2.8587  |
| k-d_tree_sklearn     |     0.628038 |       226.863  |    4.31424 |
| Bori_Aron_solution-1 |     0.653169 |       150.393  |   18.686   |