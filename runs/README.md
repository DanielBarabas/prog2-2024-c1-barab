# 2024-04-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.743866 |       0.400136 |   0.333615 |
| barab-szabi-1        |     0.739304 |       0.411102 |   0.345937 |
| k-d_tree_polars      |     8.33585  |       0.451932 |   0.35559  |
| solution-1           |     7.8215   |       1e-06    |   0.405499 |
| k-d_tree_pandas      |     0.709125 |       0.381429 |   0.472275 |
| Bori_Aron_solution-1 |     0.73185  |       0.481317 |   0.487266 |
| k-d_tree_sklearn     |     3.20948  |       0.903214 |   0.665459 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732016 |       0.344611 |   0.342999 |
| k-d_tree_polars      |     0.749839 |       0.420607 |   0.347021 |
| barab-szabi-1        |     0.734736 |       0.409071 |   0.349552 |
| Bori_Aron_solution-1 |     0.723413 |       0.480431 |   0.466831 |
| k-d_tree_pandas      |     0.743833 |       0.393193 |   0.499942 |
| k-d_tree_sklearn     |     0.754806 |       0.850096 |   0.696453 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.748971 |       0.364251 |   0.35737  |
| k-d_tree_polars      |     0.743687 |       0.435055 |   0.375775 |
| barab-szabi-1        |     0.735762 |       0.431099 |   0.37877  |
| Bori_Aron_solution-1 |     0.726593 |       0.520511 |   0.484076 |
| k-d_tree_pandas      |     0.732415 |       0.40503  |   0.527645 |
| k-d_tree_sklearn     |     0.746245 |       0.897076 |   0.686635 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.766035 |       0.430462 |   0.388571 |
| k-d_tree_polars      |     0.741408 |       0.541887 |   0.477197 |
| barab-szabi-1        |     0.733221 |       0.54129  |   0.488886 |
| Bori_Aron_solution-1 |     0.725906 |       0.70055  |   0.50136  |
| k-d_tree_pandas      |     0.747404 |       0.4879   |   0.672294 |
| k-d_tree_sklearn     |     0.74752  |       1.11703  |   0.760559 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.743248 |       0.680258 |   0.435299 |
| Bori_Aron_solution-1 |     0.718981 |       1.36133  |   0.517724 |
| k-d_tree_polars      |     0.737666 |       0.856246 |   0.825208 |
| barab-szabi-1        |     0.729053 |       0.848665 |   0.875447 |
| k-d_tree_sklearn     |     0.746418 |       1.96679  |   0.884834 |
| k-d_tree_pandas      |     0.730971 |       0.746578 |   1.11301  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.746014 |        5.46069 |   0.742712 |
| Bori_Aron_solution-1 |     0.730792 |       10.6516  |   0.779309 |
| k-d_tree_sklearn     |     0.764005 |       16.3045  |   1.06403  |
| barab-szabi-1        |     0.740654 |        4.84044 |   6.57261  |
| k-d_tree_polars      |     0.740447 |        4.85888 |   6.70279  |
| k-d_tree_pandas      |     0.739174 |        3.92365 |   7.0234   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.897975 |        73.6562 |    3.80091 |
| k-d_tree_sklearn     |     0.764907 |       228.249  |    5.19112 |
| Bori_Aron_solution-1 |     0.87996  |       146.936  |   16.6245  |