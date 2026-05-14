# 2026-05-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470552 |       0.442416 |   0.444277 |
| k-d_tree_polars      |     0.4865   |       0.445739 |   0.46028  |
| Bori_Aron_solution-1 |     0.466946 |       0.559419 |   0.552393 |
| solution-1           |     8.24071  |       1e-06    |   0.557907 |
| k-d_tree_pandas      |     0.47037  |       0.395902 |   0.563998 |
| barab-szabi-1        |     8.92015  |       0.561829 |   0.658038 |
| k-d_tree_sklearn     |     3.15383  |       1.21636  |   1.11448  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.471959 |       0.423849 |   0.43663  |
| barab-szabi-2        |     0.484202 |       0.431542 |   0.438889 |
| barab-szabi-1        |     0.477766 |       0.41559  |   0.443806 |
| Bori_Aron_solution-1 |     0.46454  |       0.560806 |   0.568234 |
| k-d_tree_pandas      |     0.472398 |       0.401389 |   0.573495 |
| k-d_tree_sklearn     |     0.489573 |       1.01987  |   1.11658  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.477874 |       0.446888 |   0.454707 |
| barab-szabi-2        |     0.468837 |       0.45328  |   0.461974 |
| k-d_tree_polars      |     0.477033 |       0.441514 |   0.476334 |
| Bori_Aron_solution-1 |     0.491473 |       0.596262 |   0.560446 |
| k-d_tree_pandas      |     0.481638 |       0.417157 |   0.597234 |
| k-d_tree_sklearn     |     0.498523 |       1.06309  |   1.11598  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485914 |       0.510762 |   0.476152 |
| k-d_tree_polars      |     0.480519 |       0.574981 |   0.568354 |
| barab-szabi-1        |     0.471164 |       0.563582 |   0.57579  |
| Bori_Aron_solution-1 |     0.475538 |       0.796301 |   0.584272 |
| k-d_tree_pandas      |     0.47259  |       0.507668 |   0.732858 |
| k-d_tree_sklearn     |     0.48104  |       1.30552  |   1.16314  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479177 |       0.766889 |   0.525193 |
| Bori_Aron_solution-1 |     0.467681 |       1.48445  |   0.591101 |
| k-d_tree_polars      |     0.478558 |       0.909208 |   0.963773 |
| barab-szabi-1        |     0.482065 |       0.91048  |   1.00028  |
| k-d_tree_sklearn     |     0.480553 |       2.19277  |   1.18623  |
| k-d_tree_pandas      |     0.479118 |       0.795583 |   1.20169  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472112 |        5.66999 |   0.728999 |
| Bori_Aron_solution-1 |     0.458689 |       11.5947  |   0.806488 |
| k-d_tree_sklearn     |     0.476245 |       17.489   |   1.25549  |
| k-d_tree_polars      |     0.476164 |        5.2229  |   7.52101  |
| barab-szabi-1        |     0.472897 |        5.31301 |   7.61293  |
| k-d_tree_pandas      |     0.475162 |        4.20366 |   7.86772  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480011 |        78.6434 |    2.44411 |
| k-d_tree_sklearn     |     0.491219 |       265.641  |    3.26573 |
| Bori_Aron_solution-1 |     0.500623 |       156.425  |   24.125   |