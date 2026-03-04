# 2026-03-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.503898 |       0.402853 |   0.434129 |
| barab-szabi-2        |     0.487701 |       0.44037  |   0.450644 |
| solution-1           |     8.61319  |       1e-06    |   0.460511 |
| k-d_tree_pandas      |     0.500726 |       0.390547 |   0.557086 |
| Bori_Aron_solution-1 |     0.48303  |       0.564034 |   0.558589 |
| barab-szabi-1        |    25.641    |       0.462071 |   0.611427 |
| k-d_tree_sklearn     |     2.9925   |       1.16364  |   1.09552  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.502679 |       0.43556  |   0.44727  |
| barab-szabi-1        |     0.506633 |       0.421631 |   0.453241 |
| k-d_tree_polars      |     0.501806 |       0.412658 |   0.457844 |
| Bori_Aron_solution-1 |     0.504498 |       0.574987 |   0.558837 |
| k-d_tree_pandas      |     0.511929 |       0.413156 |   0.566437 |
| k-d_tree_sklearn     |     0.514182 |       1.02875  |   1.12445  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.508675 |       0.458363 |   0.461403 |
| barab-szabi-1        |     0.515937 |       0.453178 |   0.481228 |
| k-d_tree_polars      |     0.502604 |       0.449872 |   0.481246 |
| Bori_Aron_solution-1 |     0.513328 |       0.607379 |   0.573639 |
| k-d_tree_pandas      |     0.503493 |       0.449939 |   0.629634 |
| k-d_tree_sklearn     |     0.506412 |       1.06448  |   1.14918  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.499231 |       0.536428 |   0.488225 |
| k-d_tree_polars      |     0.504371 |       0.568997 |   0.570129 |
| Bori_Aron_solution-1 |     0.507457 |       0.807528 |   0.586098 |
| barab-szabi-1        |     0.512756 |       0.568352 |   0.596199 |
| k-d_tree_pandas      |     0.493517 |       0.506618 |   0.74731  |
| k-d_tree_sklearn     |     0.509402 |       1.26885  |   1.14413  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496997 |       0.74137  |   0.507898 |
| Bori_Aron_solution-1 |     0.487251 |       1.45809  |   0.597533 |
| k-d_tree_polars      |     0.499034 |       0.934914 |   0.930037 |
| barab-szabi-1        |     0.512996 |       0.973261 |   0.971307 |
| k-d_tree_pandas      |     0.500715 |       0.839503 |   1.20581  |
| k-d_tree_sklearn     |     0.538948 |       2.14984  |   1.23215  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495354 |        5.18175 |   0.777542 |
| Bori_Aron_solution-1 |     0.496553 |       11.5392  |   0.839565 |
| k-d_tree_sklearn     |     0.531576 |       18.2121  |   1.35264  |
| barab-szabi-1        |     0.491987 |        5.45335 |   6.70585  |
| k-d_tree_polars      |     0.521266 |        5.72694 |   6.88486  |
| k-d_tree_pandas      |     0.502421 |        4.53033 |   7.43685  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.499204 |        73.5829 |    2.77946 |
| k-d_tree_sklearn     |     0.848282 |       234.979  |    3.91998 |
| Bori_Aron_solution-1 |     0.514413 |       151.321  |   18.1778  |