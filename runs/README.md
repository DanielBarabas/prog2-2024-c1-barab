# 2025-12-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     9.28451  |       1e-06    |   0.430007 |
| barab-szabi-2        |     0.527018 |       0.474244 |   0.441094 |
| k-d_tree_polars      |     0.548177 |       0.415341 |   0.441718 |
| barab-szabi-1        |     0.545794 |       0.415424 |   0.468645 |
| Bori_Aron_solution-1 |     0.538529 |       0.570574 |   0.567718 |
| k-d_tree_pandas      |     9.34926  |       0.441839 |   0.682931 |
| k-d_tree_sklearn     |     3.42445  |       1.14714  |   1.10571  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543296 |       0.458606 |   0.441713 |
| k-d_tree_polars      |     0.544476 |       0.419565 |   0.447217 |
| barab-szabi-1        |     0.545394 |       0.421144 |   0.452299 |
| Bori_Aron_solution-1 |     0.542287 |       0.57608  |   0.569651 |
| k-d_tree_pandas      |     0.546154 |       0.401584 |   0.573667 |
| k-d_tree_sklearn     |     0.549563 |       1.00483  |   1.11447  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544041 |       0.45736  |   0.459409 |
| barab-szabi-1        |     0.542278 |       0.443689 |   0.475366 |
| k-d_tree_polars      |     0.541005 |       0.447741 |   0.478448 |
| Bori_Aron_solution-1 |     0.531515 |       0.617709 |   0.566845 |
| k-d_tree_pandas      |     0.540495 |       0.418308 |   0.618934 |
| k-d_tree_sklearn     |     0.557217 |       1.02776  |   1.12402  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54819  |       0.514269 |   0.472777 |
| k-d_tree_polars      |     0.532547 |       0.555231 |   0.558717 |
| Bori_Aron_solution-1 |     0.531087 |       0.78013  |   0.561869 |
| barab-szabi-1        |     0.53532  |       0.572282 |   0.567786 |
| k-d_tree_pandas      |     0.542799 |       0.512028 |   0.751127 |
| k-d_tree_sklearn     |     0.532163 |       1.26472  |   1.13698  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528585 |       0.73242  |   0.507558 |
| Bori_Aron_solution-1 |     0.521883 |       1.43813  |   0.58149  |
| k-d_tree_polars      |     0.533095 |       0.922921 |   0.910753 |
| barab-szabi-1        |     0.527497 |       0.926973 |   0.949464 |
| k-d_tree_pandas      |     0.526216 |       0.820159 |   1.16913  |
| k-d_tree_sklearn     |     0.539066 |       2.09917  |   1.20758  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541162 |        4.95482 |   0.738603 |
| Bori_Aron_solution-1 |     0.519989 |       11.1771  |   0.857453 |
| k-d_tree_sklearn     |     0.531131 |       16.3403  |   1.3072   |
| k-d_tree_polars      |     0.536986 |        5.37633 |   6.46107  |
| barab-szabi-1        |     0.541595 |        5.37168 |   6.55587  |
| k-d_tree_pandas      |     0.527803 |        4.48277 |   7.15907  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538834 |        77.9744 |    2.63236 |
| k-d_tree_sklearn     |     0.542928 |       236.637  |    4.15149 |
| Bori_Aron_solution-1 |     0.657939 |       154.188  |   18.0029  |