# 2026-11-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.04672  |       0        |   0.27409  |
| barab-szabi-2        |     0.346805 |       0.340791 |   0.34681  |
| barab-szabi-1        |     0.341647 |       0.329711 |   0.350613 |
| k-d_tree_polars      |     7.90117  |       0.387921 |   0.378421 |
| Bori_Aron_solution-1 |     0.345066 |       0.438413 |   0.429706 |
| k-d_tree_pandas      |     0.344583 |       0.301485 |   0.440726 |
| k-d_tree_sklearn     |     2.89996  |       0.81082  |   0.831141 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.356092 |       0.345626 |   0.339402 |
| k-d_tree_polars      |     0.35096  |       0.332368 |   0.348504 |
| barab-szabi-1        |     0.355776 |       0.333032 |   0.357758 |
| k-d_tree_pandas      |     0.349722 |       0.304926 |   0.427143 |
| Bori_Aron_solution-1 |     0.35436  |       0.436072 |   0.435591 |
| k-d_tree_sklearn     |     0.354033 |       0.790534 |   0.838262 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.350796 |       0.352236 |   0.339512 |
| barab-szabi-1        |     0.3496   |       0.353855 |   0.368645 |
| k-d_tree_polars      |     0.348901 |       0.358723 |   0.4033   |
| Bori_Aron_solution-1 |     0.344844 |       0.461795 |   0.431312 |
| k-d_tree_pandas      |     0.358366 |       0.324193 |   0.46973  |
| k-d_tree_sklearn     |     0.355544 |       0.813968 |   0.851442 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.34479  |       0.417266 |   0.376539 |
| Bori_Aron_solution-1 |     0.351817 |       0.623436 |   0.443407 |
| k-d_tree_polars      |     0.353849 |       0.449699 |   0.450526 |
| barab-szabi-1        |     0.350283 |       0.441872 |   0.469835 |
| k-d_tree_pandas      |     0.350638 |       0.393678 |   0.678524 |
| k-d_tree_sklearn     |     0.350852 |       1.00004  |   0.879554 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.347479 |       0.655208 |   0.425564 |
| Bori_Aron_solution-1 |     0.344977 |       1.16955  |   0.479345 |
| k-d_tree_polars      |     0.349529 |       0.778632 |   0.779383 |
| barab-szabi-1        |     0.346691 |       0.728483 |   0.819715 |
| k-d_tree_sklearn     |     0.353971 |       1.74173  |   0.932144 |
| k-d_tree_pandas      |     0.348624 |       0.613028 |   0.939106 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.356887 |        4.70886 |   0.702144 |
| Bori_Aron_solution-1 |     0.340985 |        9.22125 |   0.878194 |
| k-d_tree_sklearn     |     0.352284 |       14.0892  |   1.03553  |
| k-d_tree_polars      |     0.350734 |        4.56174 |   6.07528  |
| barab-szabi-1        |     0.350318 |        4.52847 |   6.11862  |
| k-d_tree_pandas      |     0.348254 |        3.13044 |   6.33199  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.433324 |       215.701  |    3.0532  |
| barab-szabi-2        |     0.594574 |        70.7968 |    3.77813 |
| Bori_Aron_solution-1 |     0.343051 |       147.608  |   23.8826  |