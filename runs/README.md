# 2025-11-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.529823 |       0.407703 |   0.436756 |
| barab-szabi-2        |     0.518143 |       0.592837 |   0.438221 |
| k-d_tree_polars      |     0.538273 |       0.410244 |   0.439928 |
| solution-1           |     7.49307  |       1e-06    |   0.499119 |
| Bori_Aron_solution-1 |     0.519031 |       0.559585 |   0.566122 |
| k-d_tree_pandas      |     8.09145  |       0.414044 |   0.706522 |
| k-d_tree_sklearn     |     3.31137  |       1.1367   |   1.07159  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528906 |       0.431094 |   0.430881 |
| k-d_tree_polars      |     0.541123 |       0.427381 |   0.449216 |
| barab-szabi-1        |     0.541023 |       0.423845 |   0.449291 |
| Bori_Aron_solution-1 |     0.533364 |       0.567454 |   0.557271 |
| k-d_tree_pandas      |     0.526746 |       0.39792  |   0.560302 |
| k-d_tree_sklearn     |     0.5436   |       0.976496 |   1.08322  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.526867 |       0.4462   |   0.445014 |
| k-d_tree_polars      |     0.526458 |       0.447805 |   0.465416 |
| barab-szabi-1        |     0.541947 |       0.441565 |   0.467684 |
| Bori_Aron_solution-1 |     0.522997 |       0.603614 |   0.561031 |
| k-d_tree_pandas      |     0.530286 |       0.414996 |   0.605312 |
| k-d_tree_sklearn     |     0.532494 |       1.03341  |   1.10004  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.526875 |       0.504558 |   0.477332 |
| k-d_tree_polars      |     0.532309 |       0.5678   |   0.563924 |
| Bori_Aron_solution-1 |     0.523958 |       0.78579  |   0.571629 |
| barab-szabi-1        |     0.525465 |       0.571199 |   0.57505  |
| k-d_tree_pandas      |     0.53284  |       0.512881 |   0.740139 |
| k-d_tree_sklearn     |     0.534346 |       1.27057  |   1.16354  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525792 |       0.747337 |   0.508249 |
| Bori_Aron_solution-1 |     0.520961 |       1.49107  |   0.611769 |
| k-d_tree_polars      |     0.525005 |       0.926617 |   0.909374 |
| barab-szabi-1        |     0.558602 |       0.930761 |   0.952512 |
| k-d_tree_pandas      |     0.530154 |       0.792609 |   1.17869  |
| k-d_tree_sklearn     |     0.53643  |       2.13161  |   1.23     |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533588 |        5.72646 |   0.790356 |
| Bori_Aron_solution-1 |     0.526732 |       11.1809  |   0.84251  |
| k-d_tree_sklearn     |     0.537756 |       17.8907  |   1.38084  |
| k-d_tree_polars      |     0.53135  |        5.3911  |   6.70825  |
| barab-szabi-1        |     0.545034 |        5.48582 |   6.83044  |
| k-d_tree_pandas      |     0.540755 |        4.50003 |   7.13197  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530351 |        74.6947 |    2.77538 |
| k-d_tree_sklearn     |     0.555864 |       243.676  |    4.26946 |
| Bori_Aron_solution-1 |     0.707148 |       153.626  |   16.7744  |