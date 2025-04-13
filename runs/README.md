# 2025-04-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.36475  |       1e-06    |   0.362844 |
| barab-szabi-2        |     0.562381 |       0.420696 |   0.406921 |
| k-d_tree_polars      |     0.553703 |       0.403832 |   0.407273 |
| barab-szabi-1        |     0.560417 |       0.410749 |   0.42321  |
| Bori_Aron_solution-1 |     0.546892 |       0.548796 |   0.54544  |
| k-d_tree_pandas      |     7.61395  |       0.397393 |   0.587631 |
| k-d_tree_sklearn     |     2.90759  |       0.99181  |   1.02837  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.569686 |       0.418207 |   0.418762 |
| barab-szabi-1        |     0.577103 |       0.415092 |   0.422131 |
| barab-szabi-2        |     0.569684 |       0.416544 |   0.455409 |
| Bori_Aron_solution-1 |     0.593366 |       0.563496 |   0.551409 |
| k-d_tree_pandas      |     0.564973 |       0.398376 |   0.558334 |
| k-d_tree_sklearn     |     0.576583 |       0.969485 |   1.05711  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.569826 |       0.446844 |   0.440951 |
| barab-szabi-2        |     0.567346 |       0.426619 |   0.44468  |
| barab-szabi-1        |     0.571876 |       0.43716  |   0.447487 |
| Bori_Aron_solution-1 |     0.559308 |       0.611503 |   0.55971  |
| k-d_tree_pandas      |     0.56806  |       0.405274 |   0.601515 |
| k-d_tree_sklearn     |     0.577168 |       1.0152   |   1.06221  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569516 |       0.486975 |   0.451317 |
| k-d_tree_polars      |     0.569118 |       0.540577 |   0.537995 |
| barab-szabi-1        |     0.571908 |       0.541904 |   0.559126 |
| Bori_Aron_solution-1 |     0.567265 |       0.759823 |   0.567703 |
| k-d_tree_pandas      |     0.570025 |       0.480607 |   0.730033 |
| k-d_tree_sklearn     |     0.569374 |       1.22477  |   1.14454  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571529 |       0.736342 |   0.484468 |
| Bori_Aron_solution-1 |     0.571219 |       1.38713  |   0.592605 |
| k-d_tree_polars      |     0.56833  |       0.860185 |   0.896601 |
| barab-szabi-1        |     0.575541 |       0.883273 |   0.933949 |
| k-d_tree_pandas      |     0.573872 |       0.745996 |   1.17645  |
| k-d_tree_sklearn     |     0.570393 |       2.06135  |   1.20515  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.59237  |        5.23681 |   0.721244 |
| Bori_Aron_solution-1 |     0.567346 |       10.5565  |   0.88027  |
| k-d_tree_sklearn     |     0.587067 |       16.1319  |   1.32441  |
| barab-szabi-1        |     0.569813 |        4.92425 |   6.55653  |
| k-d_tree_polars      |     0.565606 |        4.94641 |   6.55955  |
| k-d_tree_pandas      |     0.57046  |        3.83338 |   6.939    |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.784851 |        71.3794 |    3.00244 |
| k-d_tree_sklearn     |     0.655994 |       227.417  |    4.11883 |
| Bori_Aron_solution-1 |     0.562383 |       155.42   |   12.6435  |