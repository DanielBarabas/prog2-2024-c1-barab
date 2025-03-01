# 2025-03-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.583336 |       0.412321 |   0.412072 |
| barab-szabi-2        |     0.583926 |       0.426176 |   0.413409 |
| solution-1           |     7.50207  |       1e-06    |   0.414626 |
| barab-szabi-1        |     0.578279 |       0.406604 |   0.420431 |
| Bori_Aron_solution-1 |     0.573034 |       0.549576 |   0.546515 |
| k-d_tree_pandas      |     7.95856  |       0.419238 |   0.620483 |
| k-d_tree_sklearn     |     3.12752  |       1.0658   |   1.05149  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.60529  |       0.424587 |   0.432344 |
| k-d_tree_polars      |     0.60833  |       0.436017 |   0.43588  |
| barab-szabi-2        |     0.620136 |       0.423006 |   0.516474 |
| Bori_Aron_solution-1 |     0.6108   |       0.622746 |   0.5691   |
| k-d_tree_pandas      |     0.594294 |       0.393619 |   0.590511 |
| k-d_tree_sklearn     |     0.618749 |       1.03228  |   1.13395  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.642243 |       0.45775  |   0.459183 |
| barab-szabi-1        |     0.625417 |       0.468381 |   0.467699 |
| k-d_tree_polars      |     0.646271 |       0.475558 |   0.470991 |
| Bori_Aron_solution-1 |     0.639528 |       0.64937  |   0.594233 |
| k-d_tree_pandas      |     0.622273 |       0.438623 |   0.642465 |
| k-d_tree_sklearn     |     0.64548  |       1.13827  |   1.19353  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629376 |       0.527249 |   0.485066 |
| k-d_tree_polars      |     0.632847 |       0.592148 |   0.576818 |
| barab-szabi-1        |     0.637124 |       0.583847 |   0.584372 |
| Bori_Aron_solution-1 |     0.634665 |       0.838151 |   0.623955 |
| k-d_tree_pandas      |     0.655521 |       0.520594 |   0.807512 |
| k-d_tree_sklearn     |     0.623994 |       1.28081  |   1.19385  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607347 |       0.746319 |   0.520072 |
| Bori_Aron_solution-1 |     0.617116 |       1.45562  |   0.640542 |
| k-d_tree_polars      |     0.638357 |       0.886421 |   0.924452 |
| barab-szabi-1        |     0.624339 |       0.894679 |   0.992168 |
| k-d_tree_pandas      |     0.621405 |       0.771754 |   1.23201  |
| k-d_tree_sklearn     |     0.609726 |       2.13633  |   1.25569  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58286  |        5.2736  |   0.736866 |
| Bori_Aron_solution-1 |     0.61487  |       10.5466  |   0.879524 |
| k-d_tree_sklearn     |     0.60691  |       15.7932  |   1.3583   |
| k-d_tree_polars      |     0.587761 |        4.97345 |   6.3604   |
| barab-szabi-1        |     0.593986 |        4.97588 |   6.37     |
| k-d_tree_pandas      |     0.604675 |        3.86952 |   7.36012  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.87787  |        69.7096 |    2.99039 |
| k-d_tree_sklearn     |     0.691123 |       226.022  |    4.13435 |
| Bori_Aron_solution-1 |     0.596749 |       154.005  |   16.6663  |