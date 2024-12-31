# 2024-12-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.65449  |       1e-06    |   0.361729 |
| barab-szabi-2        |     0.609249 |       0.394087 |   0.382675 |
| k-d_tree_polars      |     0.610038 |       0.402514 |   0.383    |
| barab-szabi-1        |     0.610157 |       0.393154 |   0.386964 |
| Bori_Aron_solution-1 |     0.610628 |       0.524106 |   0.51735  |
| k-d_tree_pandas      |     0.613131 |       0.38136  |   0.523574 |
| k-d_tree_sklearn     |    10.4529   |       1.08821  |   0.981907 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610213 |       0.399855 |   0.387913 |
| k-d_tree_polars      |     0.623084 |       0.408402 |   0.390695 |
| barab-szabi-1        |     0.615473 |       0.402368 |   0.395342 |
| Bori_Aron_solution-1 |     0.606651 |       0.523342 |   0.520662 |
| k-d_tree_pandas      |     0.609815 |       0.400933 |   0.561532 |
| k-d_tree_sklearn     |     0.623695 |       0.890864 |   0.985099 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619202 |       0.405628 |   0.396854 |
| k-d_tree_polars      |     0.622461 |       0.429612 |   0.418606 |
| barab-szabi-1        |     0.614349 |       0.426724 |   0.427644 |
| Bori_Aron_solution-1 |     0.611793 |       0.563333 |   0.526233 |
| k-d_tree_pandas      |     0.627041 |       0.398196 |   0.570972 |
| k-d_tree_sklearn     |     0.628416 |       0.966792 |   1.02584  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607934 |       0.466645 |   0.427434 |
| k-d_tree_polars      |     0.606063 |       0.532182 |   0.520142 |
| barab-szabi-1        |     0.611867 |       0.538443 |   0.532621 |
| Bori_Aron_solution-1 |     0.617918 |       0.742969 |   0.534414 |
| k-d_tree_pandas      |     0.622985 |       0.484226 |   0.706134 |
| k-d_tree_sklearn     |     0.61794  |       1.15909  |   1.0345   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.628704 |       0.741542 |   0.492337 |
| Bori_Aron_solution-1 |     0.603083 |       1.4105   |   0.563135 |
| barab-szabi-1        |     0.618448 |       0.867152 |   0.900168 |
| k-d_tree_polars      |     0.626364 |       0.854192 |   0.90226  |
| k-d_tree_sklearn     |     0.630024 |       1.96831  |   1.11688  |
| k-d_tree_pandas      |     0.617778 |       0.746202 |   1.13858  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.624352 |        5.29713 |   0.733959 |
| Bori_Aron_solution-1 |     0.611416 |       10.4922  |   0.817023 |
| k-d_tree_sklearn     |     0.613593 |       16.6171  |   1.29059  |
| k-d_tree_polars      |     0.645113 |        4.89462 |   6.59025  |
| barab-szabi-1        |     0.621265 |        4.89236 |   6.67111  |
| k-d_tree_pandas      |     0.615799 |        3.926   |   7.0923   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.652832 |        70.7904 |    2.94789 |
| k-d_tree_sklearn     |     0.636472 |       227.637  |    4.13673 |
| Bori_Aron_solution-1 |     0.629641 |       146.994  |   18.6826  |