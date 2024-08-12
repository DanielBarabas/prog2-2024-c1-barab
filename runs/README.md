# 2024-08-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.75617  |       1e-06    |   0.353602 |
| k-d_tree_polars      |     0.604689 |       0.402329 |   0.38953  |
| barab-szabi-2        |     7.93331  |       0.480507 |   0.391662 |
| barab-szabi-1        |     0.606332 |       0.406542 |   0.392127 |
| Bori_Aron_solution-1 |     0.616521 |       0.538603 |   0.529414 |
| k-d_tree_pandas      |     0.610553 |       0.403849 |   0.545546 |
| k-d_tree_sklearn     |     3.05023  |       0.940162 |   0.702327 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634519 |       0.393536 |   0.398796 |
| k-d_tree_polars      |     0.618717 |       0.404788 |   0.40267  |
| barab-szabi-1        |     0.630023 |       0.424994 |   0.404309 |
| Bori_Aron_solution-1 |     0.612377 |       0.53797  |   0.529487 |
| k-d_tree_pandas      |     0.623215 |       0.388226 |   0.616627 |
| k-d_tree_sklearn     |     0.623432 |       0.946269 |   0.723202 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623621 |       0.41158  |   0.406291 |
| k-d_tree_polars      |     0.636559 |       0.440316 |   0.424281 |
| barab-szabi-1        |     0.615156 |       0.435859 |   0.425266 |
| Bori_Aron_solution-1 |     0.610702 |       0.590559 |   0.541383 |
| k-d_tree_pandas      |     0.622878 |       0.411483 |   0.585952 |
| k-d_tree_sklearn     |     0.624579 |       0.9908   |   0.751369 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617159 |       0.480947 |   0.431106 |
| k-d_tree_polars      |     0.625067 |       0.545563 |   0.517976 |
| barab-szabi-1        |     0.618573 |       0.539331 |   0.536087 |
| Bori_Aron_solution-1 |     0.614618 |       0.766426 |   0.548809 |
| k-d_tree_pandas      |     0.620971 |       0.487188 |   0.71268  |
| k-d_tree_sklearn     |     0.61398  |       1.18518  |   0.797787 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616543 |       0.740046 |   0.507199 |
| Bori_Aron_solution-1 |     0.616631 |       1.41184  |   0.584818 |
| k-d_tree_polars      |     0.628404 |       0.862787 |   0.876028 |
| k-d_tree_sklearn     |     0.629709 |       2.04116  |   0.88435  |
| barab-szabi-1        |     0.626539 |       0.872025 |   0.925982 |
| k-d_tree_pandas      |     0.640253 |       0.757596 |   1.1581   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626773 |        5.70734 |   0.780113 |
| Bori_Aron_solution-1 |     0.608604 |       11.1486  |   0.869572 |
| k-d_tree_sklearn     |     0.625296 |       17.0621  |   1.0115   |
| k-d_tree_polars      |     0.620933 |        4.88737 |   6.90143  |
| barab-szabi-1        |     0.615846 |        4.89592 |   6.90728  |
| k-d_tree_pandas      |     0.623108 |        3.91789 |   7.25761  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626041 |        75.2872 |    3.25105 |
| k-d_tree_sklearn     |     0.645949 |       240.676  |    4.00623 |
| Bori_Aron_solution-1 |     0.693269 |       149.504  |   18.1772  |