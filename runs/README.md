# 2026-10-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.50699  |       1e-06    |   0.323849 |
| barab-szabi-2        |     0.352769 |       0.342528 |   0.343524 |
| k-d_tree_polars      |     0.355131 |       0.332185 |   0.344654 |
| k-d_tree_pandas      |     0.37459  |       0.316756 |   0.427909 |
| Bori_Aron_solution-1 |     0.349807 |       0.428668 |   0.431169 |
| barab-szabi-1        |     8.39002  |       0.471373 |   0.438244 |
| k-d_tree_sklearn     |     2.73534  |       0.922491 |   0.851464 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.377192 |       0.353284 |   0.347492 |
| barab-szabi-1        |     0.366609 |       0.35896  |   0.350694 |
| Bori_Aron_solution-1 |     0.364003 |       0.444315 |   0.439614 |
| k-d_tree_polars      |     0.382228 |       0.362817 |   0.440291 |
| k-d_tree_pandas      |     0.366964 |       0.32355  |   0.456246 |
| k-d_tree_sklearn     |     0.37968  |       0.830389 |   0.891336 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.380634 |       0.355135 |   0.349511 |
| k-d_tree_polars      |     0.383419 |       0.377981 |   0.37131  |
| barab-szabi-1        |     0.370939 |       0.369362 |   0.37675  |
| Bori_Aron_solution-1 |     0.375428 |       0.502209 |   0.454783 |
| k-d_tree_pandas      |     0.381319 |       0.335149 |   0.475088 |
| k-d_tree_sklearn     |     0.376532 |       0.833653 |   0.876157 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.391959 |       0.426467 |   0.378907 |
| Bori_Aron_solution-1 |     0.362486 |       0.622627 |   0.443154 |
| k-d_tree_polars      |     0.365665 |       0.471864 |   0.447893 |
| barab-szabi-1        |     0.364346 |       0.446549 |   0.452693 |
| k-d_tree_pandas      |     0.377472 |       0.390164 |   0.635823 |
| k-d_tree_sklearn     |     0.389044 |       1.0357   |   0.921896 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.377924 |       0.627825 |   0.443155 |
| Bori_Aron_solution-1 |     0.388311 |       1.16857  |   0.47697  |
| k-d_tree_polars      |     0.37071  |       0.70369  |   0.746551 |
| barab-szabi-1        |     0.374648 |       0.711652 |   0.778853 |
| k-d_tree_pandas      |     0.384504 |       0.615922 |   0.926751 |
| k-d_tree_sklearn     |     0.390992 |       1.74167  |   0.955774 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.35709  |        9.01538 |   0.654111 |
| barab-szabi-2        |     0.371666 |        4.61606 |   0.655586 |
| k-d_tree_sklearn     |     0.377379 |       14.7755  |   1.04332  |
| barab-szabi-1        |     0.371    |        4.83989 |   5.83199  |
| k-d_tree_polars      |     0.380222 |        4.73342 |   5.87951  |
| k-d_tree_pandas      |     0.378238 |        3.12693 |   6.06993  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.06781  |        70.1054 |    2.43052 |
| k-d_tree_sklearn     |     0.600472 |       229.92   |    2.95792 |
| Bori_Aron_solution-1 |     0.369153 |       149.456  |   32.3474  |