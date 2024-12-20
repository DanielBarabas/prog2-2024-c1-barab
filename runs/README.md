# 2024-12-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.33126  |       1e-06    |   0.358193 |
| barab-szabi-2        |     0.619827 |       0.408027 |   0.398965 |
| barab-szabi-1        |     0.63072  |       0.411772 |   0.403551 |
| k-d_tree_polars      |     0.619714 |       0.40356  |   0.429852 |
| k-d_tree_pandas      |     0.63207  |       0.399461 |   0.554765 |
| Bori_Aron_solution-1 |     0.629996 |       0.541569 |   0.594391 |
| k-d_tree_sklearn     |    11.0444   |       1.17441  |   0.979216 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.641068 |       0.405387 |   0.400356 |
| k-d_tree_polars      |     0.640367 |       0.444996 |   0.409432 |
| barab-szabi-1        |     0.636284 |       0.429596 |   0.409502 |
| k-d_tree_pandas      |     0.643877 |       0.406811 |   0.5633   |
| Bori_Aron_solution-1 |     0.634526 |       0.562072 |   0.585383 |
| k-d_tree_sklearn     |     0.645959 |       0.928699 |   1.00411  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634011 |       0.42944  |   0.428166 |
| k-d_tree_polars      |     0.653636 |       0.457412 |   0.433387 |
| barab-szabi-1        |     0.653222 |       0.453032 |   0.448883 |
| Bori_Aron_solution-1 |     0.652369 |       0.603174 |   0.577148 |
| k-d_tree_pandas      |     0.663117 |       0.421578 |   0.602002 |
| k-d_tree_sklearn     |     0.644735 |       0.99985  |   1.05924  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.638765 |       0.484292 |   0.456877 |
| k-d_tree_polars      |     0.641781 |       0.568574 |   0.540128 |
| barab-szabi-1        |     0.673086 |       0.570118 |   0.549778 |
| Bori_Aron_solution-1 |     0.637473 |       0.78041  |   0.575672 |
| k-d_tree_pandas      |     0.638771 |       0.504734 |   0.738868 |
| k-d_tree_sklearn     |     0.645983 |       1.2317   |   1.12407  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.643317 |       0.747966 |   0.521    |
| Bori_Aron_solution-1 |     0.631202 |       1.42407  |   0.585648 |
| k-d_tree_polars      |     0.635165 |       0.886958 |   0.898245 |
| barab-szabi-1        |     0.640459 |       0.87639  |   0.913213 |
| k-d_tree_pandas      |     0.628995 |       0.767291 |   1.18062  |
| k-d_tree_sklearn     |     0.637465 |       2.11888  |   1.2263   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617695 |        5.54733 |    0.75864 |
| Bori_Aron_solution-1 |     0.622297 |       10.9206  |    0.82304 |
| k-d_tree_sklearn     |     0.636739 |       16.4855  |    1.27697 |
| k-d_tree_polars      |     0.622799 |        4.92432 |    6.66421 |
| barab-szabi-1        |     0.624943 |        5.11962 |    6.77215 |
| k-d_tree_pandas      |     0.62062  |        3.91339 |    7.16863 |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.641736 |        73.9719 |    3.05922 |
| k-d_tree_sklearn     |     0.647858 |       234.695  |    4.35867 |
| Bori_Aron_solution-1 |     0.648011 |       143.734  |   18.2838  |