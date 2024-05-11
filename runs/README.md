# 2024-05-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.722402 |       0.350489 |   0.338732 |
| barab-szabi-1        |     8.70939  |       0.422701 |   0.347034 |
| k-d_tree_polars      |     0.713871 |       0.406012 |   0.354276 |
| solution-1           |     8.09462  |       1e-06    |   0.36115  |
| Bori_Aron_solution-1 |     0.696176 |       0.473132 |   0.470392 |
| k-d_tree_pandas      |     0.70547  |       0.383053 |   0.478657 |
| k-d_tree_sklearn     |     3.24161  |       0.877534 |   0.657208 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.736015 |       0.40679  |   0.351066 |
| barab-szabi-1        |     0.737201 |       0.413568 |   0.353562 |
| barab-szabi-2        |     0.744996 |       0.3516   |   0.36021  |
| Bori_Aron_solution-1 |     0.726546 |       0.483401 |   0.484754 |
| k-d_tree_pandas      |     0.745834 |       0.388621 |   0.492424 |
| k-d_tree_sklearn     |     0.752916 |       0.859075 |   0.675756 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.75344  |       0.365036 |   0.358744 |
| k-d_tree_polars      |     0.747447 |       0.431396 |   0.376451 |
| barab-szabi-1        |     0.743166 |       0.436521 |   0.382189 |
| Bori_Aron_solution-1 |     0.737276 |       0.523795 |   0.489382 |
| k-d_tree_pandas      |     0.739374 |       0.402273 |   0.528077 |
| k-d_tree_sklearn     |     0.746345 |       0.891584 |   0.70359  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.743702 |       0.432777 |   0.398445 |
| k-d_tree_polars      |     0.734583 |       0.53852  |   0.479061 |
| Bori_Aron_solution-1 |     0.728532 |       0.713366 |   0.488311 |
| barab-szabi-1        |     0.739419 |       0.540872 |   0.489607 |
| k-d_tree_pandas      |     0.74281  |       0.478293 |   0.661214 |
| k-d_tree_sklearn     |     0.748026 |       1.10792  |   0.760908 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.740524 |       0.673338 |   0.423579 |
| Bori_Aron_solution-1 |     0.726864 |       1.3285   |   0.514303 |
| k-d_tree_polars      |     0.734121 |       0.847641 |   0.82219  |
| k-d_tree_sklearn     |     0.743652 |       1.90195  |   0.855411 |
| barab-szabi-1        |     0.735566 |       0.858624 |   0.89054  |
| k-d_tree_pandas      |     0.730953 |       0.743656 |   1.07848  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.743326 |        5.26881 |   0.734347 |
| Bori_Aron_solution-1 |     0.728616 |       10.5397  |   0.770551 |
| k-d_tree_sklearn     |     0.74898  |       15.7579  |   1.05473  |
| barab-szabi-1        |     0.739547 |        4.8366  |   6.49051  |
| k-d_tree_polars      |     0.740902 |        4.88815 |   6.51451  |
| k-d_tree_pandas      |     0.736454 |        3.86471 |   6.79816  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.12475  |        75.3032 |    4.09466 |
| k-d_tree_sklearn     |     0.891155 |       231.609  |    4.85319 |
| Bori_Aron_solution-1 |     0.721373 |       149.81   |   16.3722  |