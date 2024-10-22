# 2024-10-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.48115  |       1e-06    |   0.358825 |
| k-d_tree_polars      |     0.614841 |       0.395279 |   0.38869  |
| barab-szabi-1        |     0.616745 |       0.404253 |   0.389472 |
| barab-szabi-2        |     0.621018 |       0.405892 |   0.394423 |
| k-d_tree_pandas      |     0.623057 |       0.391058 |   0.532709 |
| Bori_Aron_solution-1 |     0.617295 |       0.527578 |   0.553847 |
| k-d_tree_sklearn     |    10.3468   |       0.992594 |   0.959239 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620357 |       0.393487 |   0.386777 |
| barab-szabi-1        |     0.61561  |       0.409507 |   0.391731 |
| k-d_tree_polars      |     0.621157 |       0.414225 |   0.399426 |
| Bori_Aron_solution-1 |     0.64009  |       0.530885 |   0.537217 |
| k-d_tree_pandas      |     0.628937 |       0.394671 |   0.549563 |
| k-d_tree_sklearn     |     0.614148 |       0.887903 |   0.989532 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.624673 |       0.408102 |   0.403055 |
| k-d_tree_polars      |     0.614526 |       0.432857 |   0.423124 |
| barab-szabi-1        |     0.626876 |       0.437517 |   0.474331 |
| Bori_Aron_solution-1 |     0.619129 |       0.577781 |   0.533305 |
| k-d_tree_pandas      |     0.619723 |       0.40752  |   0.58766  |
| k-d_tree_sklearn     |     0.620976 |       0.96375  |   1.007    |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622045 |       0.469294 |   0.42806  |
| k-d_tree_polars      |     0.624589 |       0.54897  |   0.532632 |
| barab-szabi-1        |     0.620622 |       0.551105 |   0.536098 |
| Bori_Aron_solution-1 |     0.613533 |       0.747855 |   0.550806 |
| k-d_tree_pandas      |     0.625822 |       0.48703  |   0.723335 |
| k-d_tree_sklearn     |     0.625481 |       1.18806  |   1.07274  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616044 |       0.719056 |   0.459529 |
| Bori_Aron_solution-1 |     0.603339 |       1.38285  |   0.559254 |
| k-d_tree_polars      |     0.613418 |       0.856944 |   0.871525 |
| barab-szabi-1        |     0.6104   |       0.842663 |   0.90457  |
| k-d_tree_pandas      |     0.614454 |       0.747774 |   1.14587  |
| k-d_tree_sklearn     |     0.626557 |       1.9986   |   1.15857  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612205 |        5.2503  |   0.732802 |
| Bori_Aron_solution-1 |     0.607767 |       10.6483  |   0.806521 |
| k-d_tree_sklearn     |     0.616714 |       16.011   |   1.24646  |
| k-d_tree_polars      |     0.616181 |        4.86054 |   6.47378  |
| barab-szabi-1        |     0.608978 |        4.8616  |   6.48523  |
| k-d_tree_pandas      |     0.61035  |        3.91056 |   6.85026  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.638838 |        75.0171 |    2.96233 |
| k-d_tree_sklearn     |     0.61713  |       237.51   |    4.14679 |
| Bori_Aron_solution-1 |     0.641042 |       152.172  |   17.2965  |