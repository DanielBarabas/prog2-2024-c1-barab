# 2025-08-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545161 |       0.425783 |   0.428044 |
| solution-1           |     8.05051  |       1e-06    |   0.443668 |
| k-d_tree_polars      |     0.554085 |       0.414485 |   0.448332 |
| barab-szabi-1        |     0.549139 |       0.42388  |   0.456722 |
| Bori_Aron_solution-1 |     0.551138 |       0.562548 |   0.58189  |
| k-d_tree_pandas      |     8.13472  |       0.42633  |   0.739657 |
| k-d_tree_sklearn     |     3.07112  |       1.15492  |   1.07974  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.550934 |       0.4242   |   0.439124 |
| barab-szabi-2        |     0.549987 |       0.433243 |   0.442322 |
| barab-szabi-1        |     0.564942 |       0.422442 |   0.446088 |
| Bori_Aron_solution-1 |     0.555946 |       0.575901 |   0.570154 |
| k-d_tree_pandas      |     0.567839 |       0.415236 |   0.591195 |
| k-d_tree_sklearn     |     0.550999 |       1.01466  |   1.10649  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549866 |       0.451424 |   0.447344 |
| k-d_tree_polars      |     0.586198 |       0.467323 |   0.479451 |
| barab-szabi-1        |     0.556652 |       0.447784 |   0.480904 |
| Bori_Aron_solution-1 |     0.541396 |       0.614977 |   0.567338 |
| k-d_tree_pandas      |     0.556436 |       0.427401 |   0.632546 |
| k-d_tree_sklearn     |     0.549319 |       1.07762  |   1.18117  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554561 |       0.520758 |   0.483689 |
| k-d_tree_polars      |     0.556369 |       0.565419 |   0.567792 |
| Bori_Aron_solution-1 |     0.542246 |       0.783251 |   0.573815 |
| barab-szabi-1        |     0.54805  |       0.560875 |   0.575104 |
| k-d_tree_pandas      |     0.547281 |       0.512018 |   0.746938 |
| k-d_tree_sklearn     |     0.554735 |       1.26651  |   1.18405  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554802 |       0.758975 |   0.526726 |
| Bori_Aron_solution-1 |     0.552316 |       1.4563   |   0.622497 |
| k-d_tree_polars      |     0.553167 |       0.893836 |   0.932819 |
| barab-szabi-1        |     0.55754  |       0.915485 |   0.983142 |
| k-d_tree_pandas      |     0.553822 |       0.778105 |   1.2158   |
| k-d_tree_sklearn     |     0.55326  |       2.17166  |   1.28081  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569052 |        5.4299  |   0.764911 |
| Bori_Aron_solution-1 |     0.554098 |       10.8283  |   0.856146 |
| k-d_tree_sklearn     |     0.553985 |       17.3783  |   1.34635  |
| barab-szabi-1        |     0.548498 |        5.0756  |   6.85952  |
| k-d_tree_polars      |     0.552546 |        5.14173 |   7.03744  |
| k-d_tree_pandas      |     0.576867 |        3.98137 |   7.2955   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547259 |        74.6704 |    2.91532 |
| k-d_tree_sklearn     |     0.576649 |       240.197  |    4.50557 |
| Bori_Aron_solution-1 |     0.606549 |       148.472  |   18.3772  |