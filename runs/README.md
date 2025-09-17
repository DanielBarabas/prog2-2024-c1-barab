# 2025-09-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.8339   |       0.91134  |   0.434601 |
| k-d_tree_polars      |     0.537711 |       0.417694 |   0.438438 |
| barab-szabi-1        |     0.539372 |       0.415816 |   0.447796 |
| solution-1           |     7.573    |       1e-06    |   0.507556 |
| Bori_Aron_solution-1 |     0.52889  |       0.601942 |   0.563046 |
| k-d_tree_pandas      |     0.533867 |       0.39405  |   0.573915 |
| k-d_tree_sklearn     |     3.09287  |       1.19629  |   1.09935  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554089 |       0.435146 |   0.435317 |
| k-d_tree_polars      |     0.549402 |       0.416202 |   0.437597 |
| barab-szabi-1        |     0.549593 |       0.42019  |   0.442301 |
| Bori_Aron_solution-1 |     0.545849 |       0.569488 |   0.564985 |
| k-d_tree_pandas      |     0.548193 |       0.406066 |   0.56897  |
| k-d_tree_sklearn     |     0.54868  |       0.969474 |   1.05921  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539142 |       0.480841 |   0.452667 |
| k-d_tree_polars      |     0.537596 |       0.435527 |   0.454264 |
| barab-szabi-1        |     0.540962 |       0.434205 |   0.470988 |
| Bori_Aron_solution-1 |     0.535966 |       0.584913 |   0.54745  |
| k-d_tree_pandas      |     0.537931 |       0.401927 |   0.596198 |
| k-d_tree_sklearn     |     0.575559 |       1.04695  |   1.11509  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549026 |       0.506388 |   0.475627 |
| k-d_tree_polars      |     0.558442 |       0.559328 |   0.562344 |
| Bori_Aron_solution-1 |     0.544139 |       0.776546 |   0.574991 |
| barab-szabi-1        |     0.550102 |       0.558575 |   0.581399 |
| k-d_tree_pandas      |     0.550496 |       0.499667 |   0.747312 |
| k-d_tree_sklearn     |     0.552903 |       1.28047  |   1.18815  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552131 |       0.767878 |   0.517778 |
| Bori_Aron_solution-1 |     0.546798 |       1.45229  |   0.605942 |
| k-d_tree_polars      |     0.553751 |       0.90156  |   0.935158 |
| barab-szabi-1        |     0.550894 |       0.9138   |   0.975772 |
| k-d_tree_pandas      |     0.551005 |       0.767302 |   1.22377  |
| k-d_tree_sklearn     |     0.550711 |       2.17363  |   1.25947  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554464 |        5.49046 |   0.755603 |
| Bori_Aron_solution-1 |     0.56077  |       10.9539  |   0.858096 |
| k-d_tree_sklearn     |     0.557988 |       16.9617  |   1.36782  |
| k-d_tree_polars      |     0.554059 |        5.05299 |   6.74804  |
| barab-szabi-1        |     0.550306 |        5.03084 |   6.82792  |
| k-d_tree_pandas      |     0.558032 |        3.92636 |   7.2022   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560208 |        75.0774 |    2.83792 |
| k-d_tree_sklearn     |     1.19338  |       243.403  |    4.01368 |
| Bori_Aron_solution-1 |     0.545074 |       142.961  |   18.2751  |