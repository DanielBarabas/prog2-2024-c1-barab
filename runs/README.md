# 2025-09-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.56089  |       0.626951 |   0.419679 |
| barab-szabi-1        |     0.537612 |       0.402853 |   0.424874 |
| k-d_tree_polars      |     0.533388 |       0.410438 |   0.432459 |
| solution-1           |     8.01758  |       1e-06    |   0.447395 |
| k-d_tree_pandas      |     0.540731 |       0.413534 |   0.54784  |
| Bori_Aron_solution-1 |     0.680144 |       0.551592 |   0.568744 |
| k-d_tree_sklearn     |     3.06319  |       1.15973  |   1.08243  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.557503 |       0.410581 |   0.436146 |
| k-d_tree_polars      |     0.565594 |       0.419696 |   0.441691 |
| barab-szabi-2        |     0.551369 |       0.447559 |   0.452889 |
| Bori_Aron_solution-1 |     0.540926 |       0.558465 |   0.556106 |
| k-d_tree_pandas      |     0.552466 |       0.400155 |   0.595459 |
| k-d_tree_sklearn     |     0.555838 |       0.989277 |   1.06016  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537623 |       0.440788 |   0.441879 |
| k-d_tree_polars      |     0.552169 |       0.468681 |   0.461911 |
| barab-szabi-1        |     0.546904 |       0.439139 |   0.46664  |
| Bori_Aron_solution-1 |     0.551993 |       0.592857 |   0.564201 |
| k-d_tree_pandas      |     0.541194 |       0.412639 |   0.603545 |
| k-d_tree_sklearn     |     0.554084 |       1.04191  |   1.11521  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550844 |       0.504421 |   0.471197 |
| k-d_tree_polars      |     0.543462 |       0.557982 |   0.555059 |
| barab-szabi-1        |     0.54604  |       0.549774 |   0.562121 |
| Bori_Aron_solution-1 |     0.54339  |       0.775923 |   0.579689 |
| k-d_tree_pandas      |     0.550415 |       0.498371 |   0.739084 |
| k-d_tree_sklearn     |     0.548627 |       1.24644  |   1.12528  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546273 |       0.75393  |   0.56253  |
| Bori_Aron_solution-1 |     0.554366 |       1.4505   |   0.61717  |
| k-d_tree_polars      |     0.543733 |       0.903592 |   0.919884 |
| barab-szabi-1        |     0.546252 |       0.884812 |   0.952747 |
| k-d_tree_pandas      |     0.554488 |       0.773347 |   1.22124  |
| k-d_tree_sklearn     |     0.548696 |       2.10146  |   1.24296  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543976 |        5.43305 |   0.736661 |
| Bori_Aron_solution-1 |     0.549736 |       10.802   |   0.854167 |
| k-d_tree_sklearn     |     0.553787 |       16.537   |   1.35655  |
| barab-szabi-1        |     0.547119 |        5.05065 |   6.69327  |
| k-d_tree_polars      |     0.542487 |        5.02097 |   6.71183  |
| k-d_tree_pandas      |     0.549329 |        3.943   |   7.08667  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54829  |        79.7028 |    2.66726 |
| k-d_tree_sklearn     |     0.720598 |       231.056  |    4.01328 |
| Bori_Aron_solution-1 |     0.553005 |       144.247  |   17.9606  |