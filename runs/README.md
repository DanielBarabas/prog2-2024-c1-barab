# 2024-10-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.871972 |       0.381294 |   0.378545 |
| k-d_tree_polars      |     1.07964  |       0.39598  |   0.38204  |
| barab-szabi-1        |     0.608369 |       0.411571 |   0.387517 |
| k-d_tree_pandas      |     0.616093 |       0.379991 |   0.519026 |
| Bori_Aron_solution-1 |     0.610509 |       0.522609 |   0.521809 |
| solution-1           |     8.23973  |       1e-06    |   0.546105 |
| k-d_tree_sklearn     |    11.038    |       1.30181  |   0.95895  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615413 |       0.38679  |   0.379175 |
| k-d_tree_polars      |     0.613838 |       0.40283  |   0.39     |
| barab-szabi-1        |     0.621061 |       0.413005 |   0.402974 |
| Bori_Aron_solution-1 |     0.61841  |       0.53568  |   0.522593 |
| k-d_tree_pandas      |     0.61629  |       0.381472 |   0.531689 |
| k-d_tree_sklearn     |     0.613235 |       0.897376 |   0.950264 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615476 |       0.39808  |   0.392693 |
| k-d_tree_polars      |     0.614685 |       0.425775 |   0.412457 |
| barab-szabi-1        |     0.619502 |       0.444658 |   0.421009 |
| Bori_Aron_solution-1 |     0.604944 |       0.575335 |   0.521211 |
| k-d_tree_pandas      |     0.611938 |       0.398659 |   0.571573 |
| k-d_tree_sklearn     |     0.620092 |       0.931816 |   0.979562 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613117 |       0.464369 |   0.421017 |
| k-d_tree_polars      |     0.61445  |       0.535778 |   0.513931 |
| barab-szabi-1        |     0.6129   |       0.537144 |   0.52626  |
| Bori_Aron_solution-1 |     0.612411 |       0.746366 |   0.538539 |
| k-d_tree_pandas      |     0.61271  |       0.480391 |   0.706451 |
| k-d_tree_sklearn     |     0.61773  |       1.17809  |   1.03442  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614389 |       0.707027 |   0.467817 |
| Bori_Aron_solution-1 |     0.608711 |       1.40559  |   0.56754  |
| k-d_tree_polars      |     0.611225 |       0.887588 |   0.858725 |
| barab-szabi-1        |     0.611336 |       0.84842  |   0.905104 |
| k-d_tree_sklearn     |     0.625786 |       1.99161  |   1.11672  |
| k-d_tree_pandas      |     0.621133 |       0.752014 |   1.17122  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61289  |        5.2369  |   0.729597 |
| Bori_Aron_solution-1 |     0.606426 |       10.6088  |   0.815808 |
| k-d_tree_sklearn     |     0.635274 |       16.1604  |   1.24314  |
| k-d_tree_polars      |     0.618238 |        4.88712 |   6.41697  |
| barab-szabi-1        |     0.622754 |        4.89014 |   6.53457  |
| k-d_tree_pandas      |     0.619337 |        3.84742 |   6.83753  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.66032  |        70.4253 |     2.9697 |
| k-d_tree_sklearn     |     0.623565 |       226.754  |     4.2223 |
| Bori_Aron_solution-1 |     0.649101 |       140.88   |    18.9785 |