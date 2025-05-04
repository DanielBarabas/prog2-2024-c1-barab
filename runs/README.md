# 2025-05-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.504043 |       0.408616 |   0.401457 |
| barab-szabi-1        |     0.515172 |       0.398674 |   0.415331 |
| Bori_Aron_solution-1 |     0.490823 |       0.530476 |   0.533249 |
| k-d_tree_pandas      |     0.516965 |       0.37992  |   0.544708 |
| solution-1           |     7.79552  |       1e-06    |   0.569043 |
| k-d_tree_polars      |     7.91845  |       0.47338  |   0.672559 |
| k-d_tree_sklearn     |     3.00325  |       1.14535  |   1.08998  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.516246 |       0.404641 |   0.409133 |
| k-d_tree_polars      |     0.517353 |       0.401978 |   0.412335 |
| barab-szabi-1        |     0.519639 |       0.404739 |   0.414836 |
| Bori_Aron_solution-1 |     0.510804 |       0.550886 |   0.531241 |
| k-d_tree_pandas      |     0.517124 |       0.380596 |   0.547929 |
| k-d_tree_sklearn     |     0.52314  |       0.949461 |   1.01218  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.516058 |       0.417877 |   0.419542 |
| k-d_tree_polars      |     0.54639  |       0.42653  |   0.434593 |
| barab-szabi-1        |     0.51533  |       0.425822 |   0.441751 |
| Bori_Aron_solution-1 |     0.510617 |       0.581943 |   0.537737 |
| k-d_tree_pandas      |     0.517922 |       0.402833 |   0.587052 |
| k-d_tree_sklearn     |     0.519992 |       0.990805 |   1.0537   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.514923 |       0.481265 |   0.446758 |
| k-d_tree_polars      |     0.520298 |       0.540987 |   0.533685 |
| barab-szabi-1        |     0.517115 |       0.538661 |   0.542866 |
| Bori_Aron_solution-1 |     0.520775 |       0.75544  |   0.552881 |
| k-d_tree_pandas      |     0.515331 |       0.481867 |   0.721237 |
| k-d_tree_sklearn     |     0.520746 |       1.21336  |   1.10932  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.516124 |       0.72227  |   0.48074  |
| Bori_Aron_solution-1 |     0.508046 |       1.38826  |   0.583859 |
| k-d_tree_polars      |     0.515967 |       0.873405 |   0.881455 |
| barab-szabi-1        |     0.51598  |       0.878    |   0.964774 |
| k-d_tree_pandas      |     0.514044 |       0.751513 |   1.15981  |
| k-d_tree_sklearn     |     0.519497 |       2.02326  |   1.19819  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.515171 |        5.15577 |   0.70876  |
| Bori_Aron_solution-1 |     0.51109  |       10.6005  |   0.870106 |
| k-d_tree_sklearn     |     0.523237 |       15.8568  |   1.30162  |
| k-d_tree_polars      |     0.51472  |        4.96199 |   6.464    |
| barab-szabi-1        |     0.512708 |        5.00943 |   6.51612  |
| k-d_tree_pandas      |     0.527832 |        3.94887 |   6.91664  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.51754  |        73.8347 |    2.58044 |
| k-d_tree_sklearn     |     0.701415 |       225.128  |    4.16062 |
| Bori_Aron_solution-1 |     0.514966 |       139.715  |   19.0339  |