# 2024-08-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.89393  |       0.583323 |   0.388669 |
| k-d_tree_polars      |     0.609381 |       0.399275 |   0.390278 |
| barab-szabi-1        |     0.607043 |       0.419623 |   0.399154 |
| solution-1           |     7.69798  |       1e-06    |   0.511865 |
| Bori_Aron_solution-1 |     0.624885 |       0.532204 |   0.524668 |
| k-d_tree_pandas      |     0.606989 |       0.432178 |   0.532014 |
| k-d_tree_sklearn     |     2.9446   |       1.03393  |   0.709754 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615696 |       0.391521 |   0.391769 |
| k-d_tree_polars      |     0.626491 |       0.426576 |   0.395116 |
| barab-szabi-1        |     0.615541 |       0.406452 |   0.397577 |
| Bori_Aron_solution-1 |     0.609738 |       0.581176 |   0.526149 |
| k-d_tree_pandas      |     0.62229  |       0.38712  |   0.548189 |
| k-d_tree_sklearn     |     0.623954 |       0.910606 |   0.707998 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616545 |       0.405071 |   0.40185  |
| k-d_tree_polars      |     0.622736 |       0.439012 |   0.419567 |
| barab-szabi-1        |     0.62055  |       0.445405 |   0.419919 |
| Bori_Aron_solution-1 |     0.626916 |       0.571223 |   0.53042  |
| k-d_tree_pandas      |     0.617224 |       0.404904 |   0.578707 |
| k-d_tree_sklearn     |     0.626793 |       0.975663 |   0.744001 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616918 |       0.472125 |   0.428645 |
| k-d_tree_polars      |     0.618091 |       0.537914 |   0.513884 |
| barab-szabi-1        |     0.620705 |       0.546503 |   0.528956 |
| Bori_Aron_solution-1 |     0.605606 |       0.755461 |   0.556413 |
| k-d_tree_pandas      |     0.617575 |       0.48381  |   0.713548 |
| k-d_tree_sklearn     |     0.623009 |       1.16861  |   0.797316 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616091 |       0.726793 |   0.472906 |
| Bori_Aron_solution-1 |     0.615526 |       1.42152  |   0.574127 |
| k-d_tree_polars      |     0.621023 |       0.857997 |   0.87673  |
| k-d_tree_sklearn     |     0.62782  |       2.04577  |   0.890684 |
| barab-szabi-1        |     0.618586 |       0.854319 |   0.913632 |
| k-d_tree_pandas      |     0.624029 |       0.750678 |   1.16172  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625886 |        5.30495 |   0.72181  |
| Bori_Aron_solution-1 |     0.61061  |       10.564   |   0.834424 |
| k-d_tree_sklearn     |     0.624008 |       15.9222  |   0.981867 |
| k-d_tree_polars      |     0.631915 |        4.88474 |   6.44159  |
| barab-szabi-1        |     0.618939 |        4.88617 |   6.52028  |
| k-d_tree_pandas      |     0.61898  |        3.89964 |   6.91485  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613662 |        70.6683 |    2.94405 |
| k-d_tree_sklearn     |     0.661518 |       229.441  |    3.94997 |
| Bori_Aron_solution-1 |     0.684806 |       152.265  |   18.9654  |