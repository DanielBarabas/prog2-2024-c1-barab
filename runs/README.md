# 2024-10-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.630753 |       0.401616 |   0.392845 |
| barab-szabi-2        |     0.63486  |       0.401786 |   0.401162 |
| barab-szabi-1        |     0.638707 |       0.417354 |   0.40209  |
| Bori_Aron_solution-1 |     0.61926  |       0.538512 |   0.530065 |
| k-d_tree_pandas      |     0.630112 |       0.396852 |   0.53179  |
| solution-1           |     7.94595  |       1e-06    |   0.68119  |
| k-d_tree_sklearn     |    10.8183   |       1.34385  |   0.999714 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.637647 |       0.417369 |   0.401847 |
| barab-szabi-2        |     0.641564 |       0.399852 |   0.412142 |
| k-d_tree_polars      |     0.632246 |       0.41891  |   0.415791 |
| Bori_Aron_solution-1 |     0.628619 |       0.554255 |   0.544251 |
| k-d_tree_pandas      |     0.63127  |       0.395935 |   0.550676 |
| k-d_tree_sklearn     |     0.632275 |       0.909214 |   0.990282 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.635118 |       0.411866 |   0.404297 |
| barab-szabi-1        |     0.628057 |       0.445395 |   0.431915 |
| k-d_tree_polars      |     0.638123 |       0.445891 |   0.432598 |
| Bori_Aron_solution-1 |     0.618814 |       0.64366  |   0.533911 |
| k-d_tree_pandas      |     0.633744 |       0.419577 |   0.603398 |
| k-d_tree_sklearn     |     0.646079 |       0.986374 |   1.04691  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634448 |       0.4705   |   0.431967 |
| barab-szabi-1        |     0.624633 |       0.555439 |   0.52875  |
| k-d_tree_polars      |     0.638873 |       0.558665 |   0.53139  |
| Bori_Aron_solution-1 |     0.622565 |       0.760198 |   0.571416 |
| k-d_tree_pandas      |     0.636658 |       0.494354 |   0.728801 |
| k-d_tree_sklearn     |     0.643011 |       1.17892  |   1.05159  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.646441 |       0.721341 |   0.470346 |
| Bori_Aron_solution-1 |     0.639196 |       1.40589  |   0.573633 |
| k-d_tree_polars      |     0.635582 |       0.869607 |   0.893713 |
| barab-szabi-1        |     0.62522  |       0.865492 |   0.93193  |
| k-d_tree_sklearn     |     0.636002 |       2.04152  |   1.1691   |
| k-d_tree_pandas      |     0.636198 |       0.754317 |   1.17455  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.641125 |        5.54465 |   0.758176 |
| Bori_Aron_solution-1 |     0.632075 |       10.8984  |   0.824283 |
| k-d_tree_sklearn     |     0.639553 |       17.7894  |   1.33911  |
| barab-szabi-1        |     0.634477 |        4.89632 |   6.76049  |
| k-d_tree_polars      |     0.651832 |        4.87744 |   6.78918  |
| k-d_tree_pandas      |     0.628888 |        3.93042 |   7.1775   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.64548  |         76.44  |     3.0745 |
| k-d_tree_sklearn     |     0.648302 |        242.297 |     4.358  |
| Bori_Aron_solution-1 |     0.623891 |        149.207 |    16.4911 |