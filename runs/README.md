# 2024-04-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.807583 |       0.440619 |   0.360437 |
| barab-szabi-2        |     0.746172 |       0.37274  |   0.370517 |
| k-d_tree_polars      |     0.842532 |       0.496867 |   0.376289 |
| solution-1           |     8.54444  |       1e-06    |   0.393415 |
| Bori_Aron_solution-1 |     0.77559  |       0.537118 |   0.532307 |
| k-d_tree_pandas      |    10.549    |       0.437501 |   0.53353  |
| k-d_tree_sklearn     |     3.69436  |       1.41087  |   0.804779 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.77601  |       0.431106 |   0.357298 |
| barab-szabi-2        |     0.786731 |       0.361911 |   0.363387 |
| barab-szabi-1        |     0.770293 |       0.433885 |   0.396743 |
| Bori_Aron_solution-1 |     0.767543 |       0.505583 |   0.505213 |
| k-d_tree_pandas      |     0.802313 |       0.459296 |   0.535501 |
| k-d_tree_sklearn     |     0.775509 |       0.906298 |   0.69505  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.767787 |       0.374732 |   0.364145 |
| k-d_tree_polars      |     0.826242 |       0.457696 |   0.390353 |
| barab-szabi-1        |     0.780512 |       0.454092 |   0.403609 |
| Bori_Aron_solution-1 |     0.763033 |       0.563294 |   0.522647 |
| k-d_tree_pandas      |     0.813037 |       0.442083 |   0.552897 |
| k-d_tree_sklearn     |     0.786486 |       0.953918 |   0.737507 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.796431 |       0.454143 |   0.410585 |
| k-d_tree_polars      |     0.800103 |       0.599644 |   0.498251 |
| Bori_Aron_solution-1 |     0.786094 |       0.751492 |   0.519712 |
| barab-szabi-1        |     0.782826 |       0.593503 |   0.525378 |
| k-d_tree_pandas      |     0.769464 |       0.512668 |   0.726407 |
| k-d_tree_sklearn     |     0.784689 |       1.23023  |   0.811943 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.765879 |       0.699627 |   0.431026 |
| Bori_Aron_solution-1 |     0.784284 |       1.44825  |   0.570998 |
| k-d_tree_polars      |     0.797166 |       0.899503 |   0.855046 |
| barab-szabi-1        |     0.776228 |       0.907658 |   0.881133 |
| k-d_tree_sklearn     |     0.793688 |       2.02434  |   0.888164 |
| k-d_tree_pandas      |     0.780582 |       0.782267 |   1.13988  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.778866 |       11.5788  |   0.856304 |
| barab-szabi-2        |     0.76192  |        6.11244 |   0.906082 |
| k-d_tree_sklearn     |     0.782494 |       18.5278  |   1.17692  |
| barab-szabi-1        |     0.790977 |        5.05614 |   7.42296  |
| k-d_tree_pandas      |     0.766341 |        4.0393  |   7.65423  |
| k-d_tree_polars      |     0.777207 |        5.13053 |   7.78821  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.772001 |        83.1419 |    4.33067 |
| k-d_tree_sklearn     |     1.02174  |       267.194  |    5.31473 |
| Bori_Aron_solution-1 |     0.862459 |       160.063  |   16.8301  |