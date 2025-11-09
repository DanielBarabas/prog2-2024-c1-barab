# 2025-11-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.24283  |       1e-06    |   0.413657 |
| k-d_tree_polars      |     0.546874 |       0.414551 |   0.430515 |
| barab-szabi-2        |     0.510891 |       0.447619 |   0.43326  |
| barab-szabi-1        |     0.528474 |       0.402135 |   0.510267 |
| Bori_Aron_solution-1 |     0.520218 |       0.543933 |   0.550864 |
| k-d_tree_pandas      |     8.1403   |       0.404053 |   0.651267 |
| k-d_tree_sklearn     |     2.96149  |       1.05991  |   1.06199  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.529063 |       0.407119 |   0.430881 |
| barab-szabi-2        |     0.526185 |       0.428192 |   0.432184 |
| barab-szabi-1        |     0.525237 |       0.411209 |   0.432186 |
| Bori_Aron_solution-1 |     0.519217 |       0.551468 |   0.548241 |
| k-d_tree_pandas      |     0.526539 |       0.390877 |   0.558864 |
| k-d_tree_sklearn     |     0.528376 |       0.974984 |   1.05351  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525757 |       0.43603  |   0.439148 |
| k-d_tree_polars      |     0.533864 |       0.435693 |   0.45488  |
| barab-szabi-1        |     0.534384 |       0.433584 |   0.463431 |
| Bori_Aron_solution-1 |     0.520608 |       0.596296 |   0.543333 |
| k-d_tree_pandas      |     0.530228 |       0.410387 |   0.598289 |
| k-d_tree_sklearn     |     0.532305 |       1.00555  |   1.09671  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537605 |       0.505112 |   0.481576 |
| k-d_tree_polars      |     0.530181 |       0.557817 |   0.553318 |
| Bori_Aron_solution-1 |     0.568577 |       0.774588 |   0.560805 |
| barab-szabi-1        |     0.527345 |       0.56567  |   0.569965 |
| k-d_tree_pandas      |     0.527847 |       0.503674 |   0.750558 |
| k-d_tree_sklearn     |     0.529863 |       1.24801  |   1.15248  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528385 |       0.743453 |   0.499782 |
| Bori_Aron_solution-1 |     0.517716 |       1.44124  |   0.581675 |
| k-d_tree_polars      |     0.524814 |       0.917145 |   0.900095 |
| barab-szabi-1        |     0.526399 |       0.924661 |   0.935863 |
| k-d_tree_pandas      |     0.529183 |       0.812827 |   1.16224  |
| k-d_tree_sklearn     |     0.530222 |       2.0934   |   1.21157  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.524821 |        5.23185 |   0.749685 |
| Bori_Aron_solution-1 |     0.519536 |       11.1371  |   0.842527 |
| k-d_tree_sklearn     |     0.530589 |       16.4258  |   1.31075  |
| k-d_tree_polars      |     0.530075 |        5.38627 |   6.57412  |
| barab-szabi-1        |     0.5278   |        5.38035 |   6.57486  |
| k-d_tree_pandas      |     0.526165 |        4.46225 |   6.91109  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529479 |        72.0118 |    2.74566 |
| k-d_tree_sklearn     |     0.537735 |       234.443  |    4.0872  |
| Bori_Aron_solution-1 |     0.723238 |       146.666  |   18.0398  |