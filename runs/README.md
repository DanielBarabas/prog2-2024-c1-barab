# 2024-12-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.62027  |       1e-06    |   0.354365 |
| barab-szabi-2        |     0.617044 |       0.388508 |   0.380054 |
| barab-szabi-1        |     0.613332 |       0.393498 |   0.381584 |
| k-d_tree_polars      |     0.613585 |       0.39518  |   0.390922 |
| Bori_Aron_solution-1 |     0.608963 |       0.513145 |   0.512941 |
| k-d_tree_pandas      |     0.614666 |       0.37356  |   0.547401 |
| k-d_tree_sklearn     |    10.389    |       0.973388 |   0.953113 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605542 |       0.389676 |   0.387871 |
| barab-szabi-1        |     0.614517 |       0.409065 |   0.394119 |
| k-d_tree_polars      |     0.613854 |       0.402201 |   0.394278 |
| Bori_Aron_solution-1 |     0.679449 |       0.526039 |   0.516345 |
| k-d_tree_pandas      |     0.60797  |       0.388055 |   0.528469 |
| k-d_tree_sklearn     |     0.618945 |       0.921757 |   0.961224 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625254 |       0.399712 |   0.398798 |
| k-d_tree_polars      |     0.61288  |       0.423439 |   0.418316 |
| barab-szabi-1        |     0.619327 |       0.432815 |   0.425622 |
| Bori_Aron_solution-1 |     0.622266 |       0.556348 |   0.517833 |
| k-d_tree_pandas      |     0.607316 |       0.400458 |   0.56558  |
| k-d_tree_sklearn     |     0.617803 |       0.930499 |   0.98232  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.649895 |       0.465989 |   0.425004 |
| k-d_tree_polars      |     0.617202 |       0.538205 |   0.519614 |
| barab-szabi-1        |     0.609745 |       0.530073 |   0.527851 |
| Bori_Aron_solution-1 |     0.603972 |       0.743746 |   0.541875 |
| k-d_tree_pandas      |     0.610678 |       0.480384 |   0.708438 |
| k-d_tree_sklearn     |     0.615932 |       1.15291  |   1.05011  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608812 |       0.717397 |   0.464451 |
| Bori_Aron_solution-1 |     0.603712 |       1.39956  |   0.55806  |
| k-d_tree_polars      |     0.609426 |       0.860754 |   0.858191 |
| barab-szabi-1        |     0.613533 |       0.871632 |   0.903345 |
| k-d_tree_sklearn     |     0.616241 |       1.98606  |   1.13329  |
| k-d_tree_pandas      |     0.610101 |       0.750988 |   1.14038  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611336 |        5.41356 |   0.766964 |
| Bori_Aron_solution-1 |     0.603108 |       10.7424  |   0.816852 |
| k-d_tree_sklearn     |     0.616715 |       15.9056  |   1.24045  |
| k-d_tree_polars      |     0.611425 |        4.88472 |   6.45119  |
| barab-szabi-1        |     0.613053 |        4.85764 |   6.5243   |
| k-d_tree_pandas      |     0.611109 |        3.86575 |   7.20301  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626649 |        74.2121 |    3.09166 |
| k-d_tree_sklearn     |     0.632851 |       231.818  |    4.09401 |
| Bori_Aron_solution-1 |     0.618953 |       148.736  |   17.7932  |