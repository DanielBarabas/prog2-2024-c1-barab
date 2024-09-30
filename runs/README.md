# 2024-09-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.59676  |       0.39406  |   0.382755 |
| barab-szabi-2        |     0.608927 |       0.389037 |   0.383559 |
| Bori_Aron_solution-1 |     4.71627  |       0.719128 |   0.448761 |
| k-d_tree_polars      |     0.596941 |       0.403338 |   0.466454 |
| k-d_tree_pandas      |     6.98208  |       0.450186 |   0.515689 |
| solution-1           |     8.65274  |       1e-06    |   0.557245 |
| k-d_tree_sklearn     |     4.13738  |       1.03485  |   0.952021 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619205 |       0.395166 |   0.383763 |
| k-d_tree_polars      |     0.613091 |       0.411931 |   0.391287 |
| barab-szabi-1        |     0.630114 |       0.402179 |   0.402057 |
| Bori_Aron_solution-1 |     0.606379 |       0.530048 |   0.523812 |
| k-d_tree_pandas      |     0.608626 |       0.382403 |   0.530541 |
| k-d_tree_sklearn     |     0.613149 |       0.9022   |   0.96772  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615637 |       0.408428 |   0.397536 |
| barab-szabi-1        |     0.612409 |       0.426076 |   0.418226 |
| k-d_tree_polars      |     0.611465 |       0.423472 |   0.435248 |
| Bori_Aron_solution-1 |     0.622164 |       0.563231 |   0.520977 |
| k-d_tree_pandas      |     0.61283  |       0.399899 |   0.568872 |
| k-d_tree_sklearn     |     0.622139 |       0.947564 |   0.986222 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61181  |       0.460503 |   0.425742 |
| k-d_tree_polars      |     0.610921 |       0.53353  |   0.515549 |
| barab-szabi-1        |     0.613821 |       0.529766 |   0.521282 |
| Bori_Aron_solution-1 |     0.615685 |       0.741815 |   0.548506 |
| k-d_tree_pandas      |     0.614535 |       0.47452  |   0.716446 |
| k-d_tree_sklearn     |     0.620254 |       1.16291  |   1.04064  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608449 |       0.702622 |   0.459104 |
| Bori_Aron_solution-1 |     0.606674 |       1.37079  |   0.563399 |
| k-d_tree_polars      |     0.614155 |       0.843756 |   0.867654 |
| barab-szabi-1        |     0.60959  |       0.850206 |   0.904149 |
| k-d_tree_sklearn     |     0.613475 |       1.96406  |   1.13843  |
| k-d_tree_pandas      |     0.610703 |       0.73592  |   1.15459  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613547 |        5.18608 |   0.726042 |
| Bori_Aron_solution-1 |     0.605549 |       10.567   |   0.824702 |
| k-d_tree_sklearn     |     0.640836 |       15.9999  |   1.24903  |
| k-d_tree_polars      |     0.616993 |        4.85466 |   6.90885  |
| k-d_tree_pandas      |     0.623083 |        3.84239 |   6.95447  |
| barab-szabi-1        |     0.64821  |        4.85998 |   6.9772   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.819761 |        71.3215 |    3.16671 |
| k-d_tree_sklearn     |     1.05474  |       226.767  |    5.05661 |
| Bori_Aron_solution-1 |     0.606229 |       158.35   |   17.7762  |