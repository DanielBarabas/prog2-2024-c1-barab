# 2024-11-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.51887  |       1e-06    |   0.351201 |
| k-d_tree_polars      |     0.613564 |       0.395766 |   0.384763 |
| barab-szabi-2        |     0.613193 |       0.383399 |   0.385043 |
| barab-szabi-1        |     0.624669 |       0.392721 |   0.38571  |
| Bori_Aron_solution-1 |     0.612532 |       0.515617 |   0.517369 |
| k-d_tree_pandas      |     0.614967 |       0.375933 |   0.517684 |
| k-d_tree_sklearn     |    10.2253   |       0.963615 |   0.948539 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61133  |       0.447703 |   0.383042 |
| k-d_tree_polars      |     0.612052 |       0.40252  |   0.389399 |
| barab-szabi-1        |     0.622382 |       0.401396 |   0.393765 |
| Bori_Aron_solution-1 |     0.608142 |       0.524095 |   0.518068 |
| k-d_tree_pandas      |     0.61058  |       0.377636 |   0.538599 |
| k-d_tree_sklearn     |     0.614283 |       0.88578  |   0.967536 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631032 |       0.410986 |   0.397535 |
| k-d_tree_polars      |     0.612789 |       0.423417 |   0.412915 |
| barab-szabi-1        |     0.617194 |       0.423216 |   0.41824  |
| Bori_Aron_solution-1 |     0.605973 |       0.558385 |   0.521015 |
| k-d_tree_pandas      |     0.649725 |       0.3971   |   0.572333 |
| k-d_tree_sklearn     |     0.620349 |       0.935907 |   0.983083 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616792 |       0.463857 |   0.431239 |
| k-d_tree_polars      |     0.623957 |       0.539934 |   0.516795 |
| barab-szabi-1        |     0.617    |       0.541692 |   0.524216 |
| Bori_Aron_solution-1 |     0.607201 |       0.741607 |   0.544917 |
| k-d_tree_pandas      |     0.615292 |       0.482322 |   0.705394 |
| k-d_tree_sklearn     |     0.609598 |       1.15993  |   1.04482  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61032  |       0.715621 |   0.46615  |
| Bori_Aron_solution-1 |     0.602341 |       1.37749  |   0.562541 |
| k-d_tree_polars      |     0.614964 |       0.856739 |   0.854444 |
| barab-szabi-1        |     0.608442 |       0.862939 |   0.904594 |
| k-d_tree_sklearn     |     0.623172 |       2.01053  |   1.13705  |
| k-d_tree_pandas      |     0.611311 |       0.738467 |   1.13741  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605898 |        5.15797 |   0.7363   |
| Bori_Aron_solution-1 |     0.603602 |       10.5518  |   0.812158 |
| k-d_tree_sklearn     |     0.616308 |       15.6467  |   1.2502   |
| barab-szabi-1        |     0.609596 |        4.89047 |   6.33524  |
| k-d_tree_polars      |     0.61608  |        4.90826 |   6.37448  |
| k-d_tree_pandas      |     0.618614 |        3.91473 |   6.72405  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.637068 |        73.5335 |    3.055   |
| k-d_tree_sklearn     |     0.611839 |       227.533  |    4.16511 |
| Bori_Aron_solution-1 |     0.640464 |       146.123  |   17.7973  |