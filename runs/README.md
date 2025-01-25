# 2025-01-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.45495  |       1e-06    |   0.370074 |
| barab-szabi-1        |     0.590904 |       0.400211 |   0.404578 |
| k-d_tree_polars      |     0.579555 |       0.414423 |   0.406955 |
| barab-szabi-2        |     7.83079  |       0.469409 |   0.407179 |
| Bori_Aron_solution-1 |     0.579272 |       0.541164 |   0.530595 |
| k-d_tree_pandas      |     0.585145 |       0.384575 |   0.535175 |
| k-d_tree_sklearn     |     2.98011  |       0.980106 |   1.03598  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.582631 |       0.405016 |   0.401603 |
| barab-szabi-1        |     0.614612 |       0.407612 |   0.405846 |
| k-d_tree_polars      |     0.600562 |       0.408535 |   0.406246 |
| Bori_Aron_solution-1 |     0.580081 |       0.540221 |   0.533977 |
| k-d_tree_pandas      |     0.580589 |       0.387785 |   0.544389 |
| k-d_tree_sklearn     |     0.585423 |       0.956588 |   1.01458  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58071  |       0.415249 |   0.414571 |
| k-d_tree_polars      |     0.584435 |       0.444263 |   0.436372 |
| barab-szabi-1        |     0.592418 |       0.435012 |   0.437561 |
| Bori_Aron_solution-1 |     0.610652 |       0.584765 |   0.545069 |
| k-d_tree_pandas      |     0.580735 |       0.432407 |   0.591453 |
| k-d_tree_sklearn     |     0.588826 |       0.988718 |   1.05191  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580296 |       0.478011 |   0.442814 |
| k-d_tree_polars      |     0.589478 |       0.539722 |   0.527314 |
| barab-szabi-1        |     0.587215 |       0.528733 |   0.532523 |
| Bori_Aron_solution-1 |     0.572622 |       0.74347  |   0.551745 |
| k-d_tree_pandas      |     0.586199 |       0.47809  |   0.710038 |
| k-d_tree_sklearn     |     0.582668 |       1.20899  |   1.12113  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.578517 |       0.730445 |   0.476742 |
| Bori_Aron_solution-1 |     0.579861 |       1.38665  |   0.577601 |
| k-d_tree_polars      |     0.583035 |       0.869211 |   0.910336 |
| barab-szabi-1        |     0.587422 |       0.86623  |   0.930744 |
| k-d_tree_pandas      |     0.583384 |       0.74454  |   1.17365  |
| k-d_tree_sklearn     |     0.591683 |       2.04626  |   1.19058  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587986 |        5.22222 |   0.732943 |
| Bori_Aron_solution-1 |     0.589085 |       10.5865  |   0.874081 |
| k-d_tree_sklearn     |     0.632178 |       16.2522  |   1.33759  |
| k-d_tree_polars      |     0.582687 |        4.90709 |   6.66256  |
| barab-szabi-1        |     0.592142 |        4.89575 |   6.67484  |
| k-d_tree_pandas      |     0.600513 |        3.84096 |   7.01277  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591649 |        75.8617 |    3.19924 |
| k-d_tree_sklearn     |     0.602099 |       226.248  |    4.84801 |
| Bori_Aron_solution-1 |     0.75834  |       157.047  |   17.2598  |