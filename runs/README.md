# 2024-12-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.636575 |       0.394406 |   0.394781 |
| barab-szabi-1        |     0.626647 |       0.408676 |   0.401137 |
| k-d_tree_polars      |     0.627787 |       0.457683 |   0.409087 |
| solution-1           |     7.76189  |       1e-06    |   0.518575 |
| k-d_tree_pandas      |     0.640485 |       0.39617  |   0.536653 |
| Bori_Aron_solution-1 |     0.636405 |       0.553008 |   0.540039 |
| k-d_tree_sklearn     |    10.6702   |       1.32627  |   1.00529  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.638337 |       0.406369 |   0.408005 |
| barab-szabi-1        |     0.641094 |       0.422786 |   0.411201 |
| k-d_tree_polars      |     0.634669 |       0.426389 |   0.419564 |
| k-d_tree_pandas      |     0.689581 |       0.396929 |   0.549492 |
| Bori_Aron_solution-1 |     0.637822 |       0.550384 |   0.552069 |
| k-d_tree_sklearn     |     0.629366 |       0.94411  |   1.01567  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632929 |       0.40823  |   0.426643 |
| barab-szabi-1        |     0.627659 |       0.441832 |   0.433097 |
| k-d_tree_polars      |     0.634175 |       0.462061 |   0.434965 |
| Bori_Aron_solution-1 |     0.628284 |       0.604716 |   0.560367 |
| k-d_tree_pandas      |     0.63293  |       0.434197 |   0.613944 |
| k-d_tree_sklearn     |     0.632822 |       0.979502 |   1.05224  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620896 |       0.474027 |   0.436406 |
| k-d_tree_polars      |     0.622557 |       0.552563 |   0.523437 |
| barab-szabi-1        |     0.625791 |       0.556016 |   0.539504 |
| Bori_Aron_solution-1 |     0.626629 |       0.765445 |   0.569946 |
| k-d_tree_pandas      |     0.65168  |       0.502726 |   0.733043 |
| k-d_tree_sklearn     |     0.640268 |       1.22263  |   1.06815  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634388 |       0.743932 |   0.470866 |
| Bori_Aron_solution-1 |     0.621779 |       1.45261  |   0.6052   |
| k-d_tree_polars      |     0.627021 |       0.885275 |   0.882215 |
| barab-szabi-1        |     0.626969 |       0.878598 |   0.920714 |
| k-d_tree_pandas      |     0.663189 |       0.756947 |   1.14207  |
| k-d_tree_sklearn     |     0.647884 |       2.11131  |   1.19368  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631078 |        5.60012 |   0.751736 |
| Bori_Aron_solution-1 |     0.644439 |       11.1549  |   0.842853 |
| k-d_tree_sklearn     |     0.619552 |       16.9633  |   1.32016  |
| k-d_tree_polars      |     0.635996 |        4.96611 |   6.84815  |
| barab-szabi-1        |     0.640188 |        4.87657 |   6.91618  |
| k-d_tree_pandas      |     0.661969 |        3.94308 |   7.40421  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.651173 |        79.3097 |    3.09747 |
| k-d_tree_sklearn     |     0.655059 |       239.711  |    4.23956 |
| Bori_Aron_solution-1 |     0.651745 |       152.525  |   17.0441  |