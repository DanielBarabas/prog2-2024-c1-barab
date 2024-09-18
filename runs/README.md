# 2024-09-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629373 |       0.39604  |   0.393826 |
| barab-szabi-1        |     0.612006 |       0.416616 |   0.403017 |
| k-d_tree_polars      |     0.636271 |       0.413508 |   0.406963 |
| solution-1           |     7.56681  |       1e-06    |   0.43128  |
| Bori_Aron_solution-1 |     4.5051   |       0.518983 |   0.465145 |
| k-d_tree_pandas      |     4.10986  |       0.410749 |   0.544376 |
| k-d_tree_sklearn     |     3.07426  |       0.938595 |   1.00071  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.625344 |       0.410955 |   0.396794 |
| barab-szabi-2        |     0.631306 |       0.398258 |   0.399355 |
| barab-szabi-1        |     0.627282 |       0.413781 |   0.41712  |
| Bori_Aron_solution-1 |     0.642098 |       0.550501 |   0.53919  |
| k-d_tree_pandas      |     0.612599 |       0.381583 |   0.550326 |
| k-d_tree_sklearn     |     0.621306 |       0.914672 |   0.988715 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618716 |       0.415508 |   0.416317 |
| k-d_tree_polars      |     0.623364 |       0.433153 |   0.418583 |
| barab-szabi-1        |     0.620084 |       0.43142  |   0.429502 |
| Bori_Aron_solution-1 |     0.615581 |       0.592658 |   0.54284  |
| k-d_tree_pandas      |     0.623626 |       0.406194 |   0.577129 |
| k-d_tree_sklearn     |     0.626612 |       0.969952 |   1.00482  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.63241  |       0.47399  |   0.444633 |
| k-d_tree_polars      |     0.641399 |       0.545848 |   0.541006 |
| barab-szabi-1        |     0.628125 |       0.543628 |   0.544018 |
| Bori_Aron_solution-1 |     0.648198 |       0.776067 |   0.565715 |
| k-d_tree_pandas      |     0.627572 |       0.501272 |   0.740683 |
| k-d_tree_sklearn     |     0.644772 |       1.19084  |   1.09384  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603448 |       0.706689 |   0.460855 |
| Bori_Aron_solution-1 |     0.624001 |       1.4326   |   0.577592 |
| k-d_tree_polars      |     0.6328   |       0.847845 |   0.862711 |
| barab-szabi-1        |     0.603278 |       0.851505 |   0.909648 |
| k-d_tree_sklearn     |     0.608896 |       1.96653  |   1.12582  |
| k-d_tree_pandas      |     0.620437 |       0.743356 |   1.17787  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607138 |        5.17777 |   0.735747 |
| Bori_Aron_solution-1 |     0.600375 |       10.471   |   0.827369 |
| k-d_tree_sklearn     |     0.617758 |       15.6747  |   1.23657  |
| k-d_tree_polars      |     0.607972 |        4.82888 |   6.52153  |
| barab-szabi-1        |     0.616147 |        4.84297 |   6.57442  |
| k-d_tree_pandas      |     0.600472 |        3.83441 |   6.86683  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.703657 |        73.4056 |    3.09772 |
| k-d_tree_sklearn     |     0.870665 |       235.063  |    4.2353  |
| Bori_Aron_solution-1 |     0.600717 |       146.049  |   16.9222  |