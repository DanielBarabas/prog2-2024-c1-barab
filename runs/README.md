# 2024-07-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.548119 |       0.390181 |   0.377737 |
| barab-szabi-2        |     0.997868 |       0.382675 |   0.394454 |
| k-d_tree_pandas      |     0.549334 |       0.371399 |   0.512313 |
| Bori_Aron_solution-1 |     0.539509 |       0.509305 |   0.540342 |
| barab-szabi-1        |     8.4785   |       0.496181 |   0.587082 |
| solution-1           |     8.05019  |       1e-06    |   0.660516 |
| k-d_tree_sklearn     |     3.14257  |       1.25145  |   0.686321 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54431  |       0.386863 |   0.375777 |
| k-d_tree_polars      |     0.547741 |       0.394999 |   0.389348 |
| barab-szabi-1        |     0.548836 |       0.397627 |   0.390269 |
| Bori_Aron_solution-1 |     0.538605 |       0.518375 |   0.50584  |
| k-d_tree_pandas      |     0.552216 |       0.390819 |   0.523465 |
| k-d_tree_sklearn     |     0.547526 |       0.879358 |   0.689809 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546214 |       0.399537 |   0.391513 |
| k-d_tree_polars      |     0.548454 |       0.420106 |   0.412447 |
| barab-szabi-1        |     0.547801 |       0.418613 |   0.418111 |
| Bori_Aron_solution-1 |     0.539933 |       0.55298  |   0.514875 |
| k-d_tree_pandas      |     0.573735 |       0.398874 |   0.571401 |
| k-d_tree_sklearn     |     0.554616 |       0.93089  |   0.719829 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547906 |       0.461774 |   0.4205   |
| k-d_tree_polars      |     0.548656 |       0.528872 |   0.508502 |
| Bori_Aron_solution-1 |     0.537623 |       0.733983 |   0.521894 |
| barab-szabi-1        |     0.545867 |       0.529841 |   0.522506 |
| k-d_tree_pandas      |     0.547313 |       0.47035  |   0.699291 |
| k-d_tree_sklearn     |     0.552945 |       1.14519  |   0.775055 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554775 |       0.704206 |   0.452749 |
| Bori_Aron_solution-1 |     0.544565 |       1.36639  |   0.552975 |
| k-d_tree_polars      |     0.547937 |       0.840947 |   0.844023 |
| k-d_tree_sklearn     |     0.546947 |       1.93987  |   0.85687  |
| barab-szabi-1        |     0.545834 |       0.846696 |   0.882485 |
| k-d_tree_pandas      |     0.542508 |       0.741106 |   1.12314  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546916 |        5.32816 |   0.722777 |
| Bori_Aron_solution-1 |     0.54939  |       10.5625  |   0.831015 |
| k-d_tree_sklearn     |     0.552634 |       15.9138  |   0.972947 |
| k-d_tree_polars      |     0.549259 |        4.82308 |   6.45095  |
| barab-szabi-1        |     0.54723  |        4.83588 |   6.52243  |
| k-d_tree_pandas      |     0.544698 |        3.85981 |   6.922    |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547391 |        71.4803 |    2.91624 |
| k-d_tree_sklearn     |     0.581254 |       225.858  |    3.88833 |
| Bori_Aron_solution-1 |     0.612452 |       147.178  |   17.9262  |