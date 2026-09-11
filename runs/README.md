# 2026-09-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525416 |       0.495402 |   0.498937 |
| k-d_tree_polars      |     0.528141 |       0.484915 |   0.536534 |
| Bori_Aron_solution-1 |     0.522889 |       0.638356 |   0.637382 |
| k-d_tree_pandas      |     0.529479 |       0.474629 |   0.656168 |
| solution-1           |     8.65753  |       1e-06    |   0.664356 |
| barab-szabi-1        |     9.44256  |       0.605605 |   0.706631 |
| k-d_tree_sklearn     |     3.6934   |       1.62771  |   1.26492  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.526698 |       0.499267 |   0.500371 |
| barab-szabi-1        |     0.534579 |       0.486131 |   0.518964 |
| k-d_tree_polars      |     0.534037 |       0.503819 |   0.521399 |
| Bori_Aron_solution-1 |     0.520767 |       0.632967 |   0.651119 |
| k-d_tree_pandas      |     0.533574 |       0.444892 |   0.667503 |
| k-d_tree_sklearn     |     0.56508  |       1.17457  |   1.23177  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.519692 |       0.564936 |   0.52752  |
| barab-szabi-2        |     0.512139 |       0.487275 |   0.549563 |
| barab-szabi-1        |     0.533732 |       0.518293 |   0.572963 |
| Bori_Aron_solution-1 |     0.526168 |       0.655791 |   0.613693 |
| k-d_tree_pandas      |     0.550843 |       0.479163 |   0.689877 |
| k-d_tree_sklearn     |     0.52624  |       1.21341  |   1.21774  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.50804  |       0.543651 |   0.518125 |
| k-d_tree_polars      |     0.522499 |       0.625576 |   0.61424  |
| barab-szabi-1        |     0.546135 |       0.644274 |   0.632644 |
| Bori_Aron_solution-1 |     0.519981 |       0.873217 |   0.667948 |
| k-d_tree_pandas      |     0.531564 |       0.5727   |   0.84949  |
| k-d_tree_sklearn     |     0.512395 |       1.43691  |   1.27782  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.491809 |       1.45889  |   0.613279 |
| barab-szabi-2        |     0.48042  |       0.779142 |   0.67276  |
| k-d_tree_polars      |     0.491022 |       0.938097 |   0.920634 |
| barab-szabi-1        |     0.511001 |       0.961578 |   1.03092  |
| k-d_tree_sklearn     |     0.479296 |       2.14341  |   1.25941  |
| k-d_tree_pandas      |     0.499652 |       0.843936 |   1.25999  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.504934 |        5.27627 |   0.794266 |
| Bori_Aron_solution-1 |     0.461907 |       11.3831  |   0.819821 |
| k-d_tree_sklearn     |     0.514214 |       18.5826  |   1.4206   |
| barab-szabi-1        |     0.488751 |        5.44089 |   6.8917   |
| k-d_tree_polars      |     0.493536 |        5.41608 |   7.3143   |
| k-d_tree_pandas      |     0.497799 |        4.41395 |   7.38943  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.706516 |        72.3298 |    2.82234 |
| k-d_tree_sklearn     |     0.823128 |       248.216  |    4.16475 |
| Bori_Aron_solution-1 |     0.476769 |       156.707  |   24.6913  |