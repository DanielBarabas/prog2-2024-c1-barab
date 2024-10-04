# 2024-10-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606241 |       0.377878 |   0.372634 |
| barab-szabi-1        |     0.5956   |       0.388473 |   0.38495  |
| k-d_tree_polars      |     0.601307 |       0.423396 |   0.390665 |
| solution-1           |     7.52503  |       1e-06    |   0.411622 |
| Bori_Aron_solution-1 |     4.36573  |       0.551539 |   0.448546 |
| k-d_tree_pandas      |     4.10793  |       0.389296 |   0.516993 |
| k-d_tree_sklearn     |     2.98819  |       0.938171 |   0.937473 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.62478  |       0.398335 |   0.386596 |
| barab-szabi-2        |     0.611388 |       0.383851 |   0.39038  |
| k-d_tree_polars      |     0.602255 |       0.401371 |   0.391515 |
| Bori_Aron_solution-1 |     0.603661 |       0.527226 |   0.511894 |
| k-d_tree_pandas      |     0.616872 |       0.38079  |   0.523256 |
| k-d_tree_sklearn     |     0.608906 |       0.883518 |   0.967316 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610178 |       0.4407   |   0.392537 |
| barab-szabi-1        |     0.610601 |       0.43118  |   0.429158 |
| k-d_tree_polars      |     0.612692 |       0.433254 |   0.434406 |
| Bori_Aron_solution-1 |     0.628634 |       0.571703 |   0.535087 |
| k-d_tree_pandas      |     0.622252 |       0.40649  |   0.58988  |
| k-d_tree_sklearn     |     0.618837 |       0.944691 |   0.988357 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609892 |       0.455963 |   0.422104 |
| k-d_tree_polars      |     0.604455 |       0.525305 |   0.518288 |
| barab-szabi-1        |     0.60812  |       0.529402 |   0.525783 |
| Bori_Aron_solution-1 |     0.605658 |       0.728266 |   0.529775 |
| k-d_tree_pandas      |     0.606548 |       0.480664 |   0.709056 |
| k-d_tree_sklearn     |     0.611254 |       1.14382  |   1.03313  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606857 |       0.701213 |   0.462883 |
| Bori_Aron_solution-1 |     0.599411 |       1.35304  |   0.558653 |
| k-d_tree_polars      |     0.602311 |       0.844275 |   0.850458 |
| barab-szabi-1        |     0.609214 |       0.852952 |   0.895738 |
| k-d_tree_sklearn     |     0.610734 |       1.92315  |   1.12694  |
| k-d_tree_pandas      |     0.604609 |       0.738156 |   1.13085  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614089 |        5.44627 |   0.734293 |
| Bori_Aron_solution-1 |     0.605181 |       10.9138  |   0.821979 |
| k-d_tree_sklearn     |     0.619574 |       16.5088  |   1.25616  |
| k-d_tree_polars      |     0.608871 |        4.83967 |   6.75764  |
| barab-szabi-1        |     0.619689 |        4.81868 |   6.9108   |
| k-d_tree_pandas      |     0.608527 |        3.83441 |   7.11392  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.710687 |        74.9837 |    3.12499 |
| k-d_tree_sklearn     |     0.83151  |       231.813  |    4.29812 |
| Bori_Aron_solution-1 |     0.601358 |       146.323  |   16.5047  |