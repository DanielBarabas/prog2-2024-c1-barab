# 2024-10-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.51711  |       1e-06    |   0.347369 |
| k-d_tree_polars      |     0.609148 |       0.391333 |   0.378433 |
| barab-szabi-1        |     0.620731 |       0.391641 |   0.380312 |
| barab-szabi-2        |     0.606473 |       0.37857  |   0.424948 |
| k-d_tree_pandas      |     0.607972 |       0.371719 |   0.513147 |
| Bori_Aron_solution-1 |     0.61247  |       0.510514 |   0.514786 |
| k-d_tree_sklearn     |    10.1543   |       1.00173  |   0.938328 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61241  |       0.37828  |   0.377516 |
| barab-szabi-1        |     0.616651 |       0.398135 |   0.382605 |
| k-d_tree_polars      |     0.641021 |       0.404507 |   0.384006 |
| Bori_Aron_solution-1 |     0.604626 |       0.526182 |   0.516358 |
| k-d_tree_pandas      |     0.613536 |       0.378461 |   0.527105 |
| k-d_tree_sklearn     |     0.615474 |       0.877568 |   0.989763 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604717 |       0.395766 |   0.390475 |
| k-d_tree_polars      |     0.615561 |       0.425345 |   0.409596 |
| barab-szabi-1        |     0.610947 |       0.422108 |   0.415912 |
| Bori_Aron_solution-1 |     0.60685  |       0.563496 |   0.524706 |
| k-d_tree_pandas      |     0.616066 |       0.402173 |   0.568829 |
| k-d_tree_sklearn     |     0.613769 |       0.919327 |   0.978178 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611216 |       0.459769 |   0.421726 |
| k-d_tree_polars      |     0.604073 |       0.533169 |   0.508083 |
| barab-szabi-1        |     0.615969 |       0.530151 |   0.5216   |
| Bori_Aron_solution-1 |     0.604477 |       0.736285 |   0.524207 |
| k-d_tree_pandas      |     0.604955 |       0.479501 |   0.697581 |
| k-d_tree_sklearn     |     0.621615 |       1.15094  |   1.02879  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606005 |       0.707635 |   0.458756 |
| Bori_Aron_solution-1 |     0.597912 |       1.37854  |   0.552874 |
| k-d_tree_polars      |     0.61274  |       0.848801 |   0.855836 |
| barab-szabi-1        |     0.608071 |       0.852639 |   0.892547 |
| k-d_tree_sklearn     |     0.63018  |       1.97065  |   1.11985  |
| k-d_tree_pandas      |     0.610885 |       0.7398   |   1.13693  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610516 |        5.02974 |   0.716393 |
| Bori_Aron_solution-1 |     0.601894 |       10.4736  |   0.803527 |
| k-d_tree_sklearn     |     0.6112   |       15.6496  |   1.21913  |
| k-d_tree_polars      |     0.607739 |        4.84602 |   6.23284  |
| barab-szabi-1        |     0.610342 |        4.82618 |   6.34253  |
| k-d_tree_pandas      |     0.61638  |        3.92439 |   6.74139  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.647589 |        71.5399 |    2.8906  |
| k-d_tree_sklearn     |     0.610172 |       233.092  |    4.14182 |
| Bori_Aron_solution-1 |     0.615484 |       147.957  |   18.1442  |