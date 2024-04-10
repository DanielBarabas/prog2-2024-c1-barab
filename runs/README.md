# 2024-04-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.743416 |       0.413862 |   0.347326 |
| barab-szabi-2        |     0.741712 |       0.35005  |   0.355327 |
| k-d_tree_polars      |     9.55452  |       0.456224 |   0.356468 |
| solution-1           |     8.37108  |       1e-06    |   0.391772 |
| Bori_Aron_solution-1 |     0.734767 |       0.479131 |   0.487601 |
| k-d_tree_pandas      |     0.718791 |       0.389105 |   0.494905 |
| k-d_tree_sklearn     |     4.49064  |       0.913468 |   0.665923 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.751185 |       0.420569 |   0.349571 |
| k-d_tree_polars      |     0.761797 |       0.418235 |   0.352156 |
| barab-szabi-2        |     0.754171 |       0.354137 |   0.35678  |
| Bori_Aron_solution-1 |     0.742637 |       0.49571  |   0.481598 |
| k-d_tree_pandas      |     0.737752 |       0.391456 |   0.504382 |
| k-d_tree_sklearn     |     0.752874 |       0.876149 |   0.685059 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.755317 |       0.368693 |   0.361287 |
| barab-szabi-1        |     0.748595 |       0.443187 |   0.377705 |
| k-d_tree_polars      |     0.740228 |       0.445139 |   0.385445 |
| Bori_Aron_solution-1 |     0.733172 |       0.525463 |   0.486006 |
| k-d_tree_pandas      |     0.760024 |       0.414309 |   0.530551 |
| k-d_tree_sklearn     |     0.769916 |       0.926989 |   0.753011 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.7449   |       0.431055 |   0.393903 |
| k-d_tree_polars      |     0.743915 |       0.548216 |   0.485143 |
| barab-szabi-1        |     0.743869 |       0.551572 |   0.489709 |
| Bori_Aron_solution-1 |     0.737924 |       0.714362 |   0.498903 |
| k-d_tree_pandas      |     0.745587 |       0.49591  |   0.675347 |
| k-d_tree_sklearn     |     0.746859 |       1.1374   |   0.768852 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.74778  |       0.698555 |   0.451964 |
| Bori_Aron_solution-1 |     0.736956 |       1.36309  |   0.527115 |
| k-d_tree_polars      |     0.739569 |       0.859324 |   0.845421 |
| k-d_tree_sklearn     |     0.747239 |       1.98225  |   0.871184 |
| barab-szabi-1        |     0.738589 |       0.855687 |   0.901332 |
| k-d_tree_pandas      |     0.756003 |       0.760878 |   1.13316  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.766484 |        5.44163 |   0.74223  |
| Bori_Aron_solution-1 |     0.742762 |       10.7288  |   0.776327 |
| k-d_tree_sklearn     |     0.756692 |       16.3956  |   1.09157  |
| barab-szabi-1        |     0.759513 |        4.84655 |   6.66597  |
| k-d_tree_polars      |     0.744975 |        4.80599 |   6.74686  |
| k-d_tree_pandas      |     0.747478 |        3.94379 |   7.00988  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.82351  |        72.9815 |    3.68294 |
| k-d_tree_sklearn     |     0.748263 |       233.582  |    5.05839 |
| Bori_Aron_solution-1 |     0.818136 |       145.781  |   13.8686  |