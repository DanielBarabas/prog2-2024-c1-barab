# 2025-05-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.87032  |       1e-06    |   0.433546 |
| k-d_tree_polars      |     0.572124 |       0.426841 |   0.445441 |
| barab-szabi-2        |     0.601726 |       0.438025 |   0.447166 |
| barab-szabi-1        |     8.02968  |       0.484478 |   0.546883 |
| Bori_Aron_solution-1 |     0.565936 |       0.605981 |   0.598007 |
| k-d_tree_pandas      |     0.605741 |       0.420948 |   0.60394  |
| k-d_tree_sklearn     |     3.08133  |       1.11331  |   1.12859  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.600316 |       0.442801 |   0.458483 |
| k-d_tree_polars      |     0.607692 |       0.461335 |   0.461469 |
| barab-szabi-1        |     0.597604 |       0.492355 |   0.467798 |
| Bori_Aron_solution-1 |     0.592814 |       0.607065 |   0.60323  |
| k-d_tree_pandas      |     0.593989 |       0.419674 |   0.604316 |
| k-d_tree_sklearn     |     0.604198 |       1.09641  |   1.13814  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609717 |       0.458351 |   0.463717 |
| k-d_tree_polars      |     0.608245 |       0.484858 |   0.480309 |
| barab-szabi-1        |     0.596395 |       0.509032 |   0.488495 |
| Bori_Aron_solution-1 |     0.589442 |       0.638936 |   0.627372 |
| k-d_tree_pandas      |     0.618006 |       0.44647  |   0.666054 |
| k-d_tree_sklearn     |     0.595763 |       1.16545  |   1.21906  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613436 |       0.527492 |   0.50347  |
| k-d_tree_polars      |     0.604773 |       0.618211 |   0.602432 |
| barab-szabi-1        |     0.600676 |       0.602567 |   0.608565 |
| Bori_Aron_solution-1 |     0.596515 |       0.840551 |   0.633738 |
| k-d_tree_pandas      |     0.597302 |       0.53145  |   0.796082 |
| k-d_tree_sklearn     |     0.608805 |       1.37311  |   1.26995  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.59553  |       0.824933 |   0.629029 |
| Bori_Aron_solution-1 |     0.56994  |       1.49809  |   0.638742 |
| k-d_tree_polars      |     0.619998 |       0.926512 |   0.966392 |
| barab-szabi-1        |     0.617622 |       0.931421 |   1.04454  |
| k-d_tree_pandas      |     0.611392 |       0.797787 |   1.27301  |
| k-d_tree_sklearn     |     0.594642 |       2.33672  |   1.37318  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565559 |        6.22025 |   0.82588  |
| Bori_Aron_solution-1 |     0.601901 |       11.7556  |   0.945691 |
| k-d_tree_sklearn     |     0.610722 |       19.0658  |   1.5725   |
| k-d_tree_pandas      |     0.603405 |        3.99907 |   7.27589  |
| k-d_tree_polars      |     0.597223 |        5.06614 |   7.40914  |
| barab-szabi-1        |     0.594309 |        5.09425 |   7.44066  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632797 |        75.3493 |    2.87572 |
| k-d_tree_sklearn     |     0.842604 |       249.384  |    4.42699 |
| Bori_Aron_solution-1 |     0.629865 |       152.341  |   17.9575  |