# 2026-02-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.95628  |       1e-06    |   0.364438 |
| barab-szabi-2        |     0.487634 |       0.431834 |   0.429145 |
| k-d_tree_polars      |     0.491288 |       0.411263 |   0.442477 |
| k-d_tree_pandas      |     0.484093 |       0.39212  |   0.546402 |
| barab-szabi-1        |     8.94233  |       0.427017 |   0.550892 |
| Bori_Aron_solution-1 |     0.476308 |       0.551532 |   0.556364 |
| k-d_tree_sklearn     |     3.44874  |       1.03318  |   1.07329  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495589 |       0.436321 |   0.433684 |
| barab-szabi-1        |     0.49858  |       0.420634 |   0.44198  |
| k-d_tree_polars      |     0.493748 |       0.415041 |   0.443497 |
| Bori_Aron_solution-1 |     0.486265 |       0.558068 |   0.550424 |
| k-d_tree_pandas      |     0.496754 |       0.395257 |   0.56797  |
| k-d_tree_sklearn     |     0.49473  |       0.980518 |   1.07733  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498505 |       0.451739 |   0.451294 |
| k-d_tree_polars      |     0.492032 |       0.438601 |   0.464631 |
| barab-szabi-1        |     0.496972 |       0.438382 |   0.471142 |
| Bori_Aron_solution-1 |     0.490291 |       0.598689 |   0.552084 |
| k-d_tree_pandas      |     0.492658 |       0.419224 |   0.601173 |
| k-d_tree_sklearn     |     0.499083 |       1.02175  |   1.09778  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.493841 |       0.517673 |   0.480328 |
| k-d_tree_polars      |     0.493845 |       0.559547 |   0.559963 |
| Bori_Aron_solution-1 |     0.490165 |       0.813566 |   0.561764 |
| barab-szabi-1        |     0.495703 |       0.566684 |   0.570576 |
| k-d_tree_pandas      |     0.493505 |       0.511711 |   0.749127 |
| k-d_tree_sklearn     |     0.506846 |       1.29492  |   1.15804  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.506939 |       0.736457 |   0.514472 |
| Bori_Aron_solution-1 |     0.48799  |       1.48314  |   0.591427 |
| k-d_tree_polars      |     0.494581 |       0.932597 |   0.908459 |
| barab-szabi-1        |     0.501687 |       0.970012 |   0.991262 |
| k-d_tree_pandas      |     0.491792 |       0.8239   |   1.18053  |
| k-d_tree_sklearn     |     0.497426 |       2.13354  |   1.222    |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.493601 |        5.06825 |   0.745932 |
| Bori_Aron_solution-1 |     0.495571 |       10.9925  |   0.821495 |
| k-d_tree_sklearn     |     0.501452 |       17.0678  |   1.34713  |
| barab-szabi-1        |     0.49973  |        5.54103 |   6.47124  |
| k-d_tree_polars      |     0.495107 |        5.49348 |   6.52628  |
| k-d_tree_pandas      |     0.492913 |        4.43965 |   6.88763  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.506563 |        69.1366 |    2.57652 |
| k-d_tree_sklearn     |     0.755055 |       238.056  |    4.19753 |
| Bori_Aron_solution-1 |     0.503726 |       145.714  |   17.5518  |