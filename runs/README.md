# 2026-03-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.457537 |       0.439399 |   0.42684  |
| k-d_tree_polars      |     0.463064 |       0.39556  |   0.433571 |
| Bori_Aron_solution-1 |     0.458629 |       0.546921 |   0.545212 |
| k-d_tree_pandas      |     0.463929 |       0.387104 |   0.549612 |
| solution-1           |     7.65561  |       1e-06    |   0.54965  |
| barab-szabi-1        |     8.17055  |       0.484759 |   0.586724 |
| k-d_tree_sklearn     |     3.19036  |       1.08605  |   1.06008  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471253 |       0.437983 |   0.426798 |
| barab-szabi-1        |     0.464806 |       0.405738 |   0.435127 |
| k-d_tree_polars      |     0.468697 |       0.409407 |   0.449235 |
| Bori_Aron_solution-1 |     0.454362 |       0.555319 |   0.552334 |
| k-d_tree_pandas      |     0.466522 |       0.415405 |   0.569235 |
| k-d_tree_sklearn     |     0.465512 |       0.991594 |   1.10395  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.455633 |       0.45332  |   0.449728 |
| k-d_tree_polars      |     0.465852 |       0.446493 |   0.474479 |
| barab-szabi-1        |     0.476046 |       0.441959 |   0.487797 |
| Bori_Aron_solution-1 |     0.458905 |       0.599107 |   0.562862 |
| k-d_tree_pandas      |     0.461355 |       0.411443 |   0.623005 |
| k-d_tree_sklearn     |     0.467563 |       1.0697   |   1.08684  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463585 |       0.509466 |   0.475326 |
| Bori_Aron_solution-1 |     0.452638 |       0.772399 |   0.560293 |
| k-d_tree_polars      |     0.462874 |       0.571625 |   0.577442 |
| barab-szabi-1        |     0.465214 |       0.580755 |   0.582876 |
| k-d_tree_pandas      |     0.464673 |       0.500725 |   0.734354 |
| k-d_tree_sklearn     |     0.468279 |       1.27062  |   1.13618  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460823 |       0.72546  |   0.51653  |
| Bori_Aron_solution-1 |     0.45411  |       1.46889  |   0.585994 |
| k-d_tree_polars      |     0.463859 |       0.932594 |   0.916947 |
| barab-szabi-1        |     0.458564 |       0.936762 |   0.956084 |
| k-d_tree_pandas      |     0.464634 |       0.814729 |   1.18969  |
| k-d_tree_sklearn     |     0.469987 |       2.15244  |   1.21513  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469704 |        5.39821 |   0.797972 |
| Bori_Aron_solution-1 |     0.465187 |       11.3612  |   0.8253   |
| k-d_tree_sklearn     |     0.47469  |       17.7637  |   1.31997  |
| barab-szabi-1        |     0.458834 |        5.7262  |   6.90794  |
| k-d_tree_polars      |     0.470547 |        5.68493 |   7.00388  |
| k-d_tree_pandas      |     0.471153 |        4.51673 |   7.31297  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.708899 |         75.895 |    2.89128 |
| k-d_tree_sklearn     |     0.469312 |        244.907 |    3.90063 |
| Bori_Aron_solution-1 |     0.464001 |        155.761 |   17.0774  |