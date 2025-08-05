# 2025-08-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.556113 |       0.403579 |   0.425652 |
| barab-szabi-1        |     0.579272 |       0.436257 |   0.441065 |
| barab-szabi-2        |     8.1639   |       0.877847 |   0.449775 |
| k-d_tree_pandas      |     0.553588 |       0.382188 |   0.549439 |
| Bori_Aron_solution-1 |     0.554761 |       0.560631 |   0.555007 |
| solution-1           |     7.64987  |       1e-06    |   0.566377 |
| k-d_tree_sklearn     |     3.11649  |       1.11394  |   1.05308  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.558383 |       0.414974 |   0.430302 |
| k-d_tree_polars      |     0.554256 |       0.416864 |   0.434102 |
| barab-szabi-2        |     0.550175 |       0.433571 |   0.44833  |
| Bori_Aron_solution-1 |     0.547943 |       0.568262 |   0.544537 |
| k-d_tree_pandas      |     0.558428 |       0.392606 |   0.567757 |
| k-d_tree_sklearn     |     0.557657 |       1.00349  |   1.05669  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556901 |       0.436197 |   0.442049 |
| k-d_tree_polars      |     0.553664 |       0.437353 |   0.454106 |
| barab-szabi-1        |     0.590857 |       0.44829  |   0.480757 |
| Bori_Aron_solution-1 |     0.56115  |       0.598781 |   0.549586 |
| k-d_tree_pandas      |     0.554572 |       0.403255 |   0.600101 |
| k-d_tree_sklearn     |     0.558315 |       1.02079  |   1.08369  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553934 |       0.497109 |   0.470229 |
| k-d_tree_polars      |     0.554517 |       0.545033 |   0.554403 |
| barab-szabi-1        |     0.571678 |       0.556556 |   0.56892  |
| Bori_Aron_solution-1 |     0.552923 |       0.762566 |   0.573269 |
| k-d_tree_pandas      |     0.557214 |       0.488682 |   0.743826 |
| k-d_tree_sklearn     |     0.563855 |       1.26344  |   1.14691  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554504 |       0.744197 |   0.496854 |
| Bori_Aron_solution-1 |     0.548172 |       1.39451  |   0.586377 |
| k-d_tree_polars      |     0.551905 |       0.889675 |   0.902115 |
| barab-szabi-1        |     0.553532 |       0.896751 |   0.94481  |
| k-d_tree_pandas      |     0.552759 |       0.752546 |   1.18509  |
| k-d_tree_sklearn     |     0.553722 |       2.05491  |   1.20875  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553813 |        5.13802 |   0.752881 |
| Bori_Aron_solution-1 |     0.549079 |       10.5292  |   0.858704 |
| k-d_tree_sklearn     |     0.561553 |       15.8828  |   1.31166  |
| barab-szabi-1        |     0.558889 |        5.05462 |   6.45654  |
| k-d_tree_polars      |     0.549902 |        5.01133 |   6.50389  |
| k-d_tree_pandas      |     0.558082 |        3.92805 |   6.87144  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554585 |        72.0632 |    2.79256 |
| k-d_tree_sklearn     |     0.713414 |       231.607  |    4.02626 |
| Bori_Aron_solution-1 |     0.566774 |       148.82   |   17.6755  |