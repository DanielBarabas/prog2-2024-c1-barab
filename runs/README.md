# 2026-04-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.466722 |       0.409429 |   0.433489 |
| barab-szabi-1        |     0.470036 |       0.416241 |   0.444348 |
| barab-szabi-2        |     0.468547 |       0.457549 |   0.454232 |
| solution-1           |     7.68331  |       1e-06    |   0.47523  |
| k-d_tree_pandas      |     0.477431 |       0.395459 |   0.55657  |
| Bori_Aron_solution-1 |     0.459249 |       0.552246 |   0.557379 |
| k-d_tree_sklearn     |    10.3443   |       1.33237  |   1.10907  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.477941 |       0.433229 |   0.453026 |
| barab-szabi-2        |     0.48137  |       0.462591 |   0.457371 |
| barab-szabi-1        |     0.491276 |       0.445825 |   0.464539 |
| Bori_Aron_solution-1 |     0.472249 |       0.575928 |   0.57193  |
| k-d_tree_pandas      |     0.479032 |       0.428135 |   0.595643 |
| k-d_tree_sklearn     |     0.480835 |       1.04947  |   1.16232  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477253 |       0.469793 |   0.455316 |
| barab-szabi-1        |     0.478565 |       0.456292 |   0.475294 |
| k-d_tree_polars      |     0.483959 |       0.455952 |   0.475365 |
| Bori_Aron_solution-1 |     0.475533 |       0.615071 |   0.58801  |
| k-d_tree_pandas      |     0.476617 |       0.429049 |   0.606559 |
| k-d_tree_sklearn     |     0.491732 |       1.11652  |   1.18237  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479655 |       0.525572 |   0.492154 |
| k-d_tree_polars      |     0.473568 |       0.564956 |   0.574291 |
| barab-szabi-1        |     0.476581 |       0.574202 |   0.590609 |
| Bori_Aron_solution-1 |     0.481798 |       0.796061 |   0.5913   |
| k-d_tree_pandas      |     0.476896 |       0.519158 |   0.750245 |
| k-d_tree_sklearn     |     0.483349 |       1.32997  |   1.16226  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472779 |       0.771747 |   0.589537 |
| Bori_Aron_solution-1 |     0.463025 |       1.5184   |   0.630329 |
| k-d_tree_polars      |     0.484565 |       0.937469 |   0.987827 |
| barab-szabi-1        |     0.472706 |       0.936    |   1.04418  |
| k-d_tree_pandas      |     0.475714 |       0.823002 |   1.21932  |
| k-d_tree_sklearn     |     0.470403 |       2.25017  |   1.22751  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467346 |        5.74987 |   0.737505 |
| Bori_Aron_solution-1 |     0.458762 |       11.6206  |   0.816049 |
| k-d_tree_sklearn     |     0.488184 |       18.0083  |   1.29527  |
| k-d_tree_polars      |     0.480157 |        5.38677 |   7.57818  |
| barab-szabi-1        |     0.473768 |        5.31854 |   7.69629  |
| k-d_tree_pandas      |     0.479136 |        4.2262  |   7.99769  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.67192  |        78.8297 |     2.4805 |
| k-d_tree_sklearn     |     0.482969 |       266.121  |     3.3615 |
| Bori_Aron_solution-1 |     0.465807 |       160.055  |    18.368  |