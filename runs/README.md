# 2024-12-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.63725  |       0.391308 |   0.387139 |
| k-d_tree_polars      |     0.625659 |       0.404796 |   0.388376 |
| barab-szabi-1        |     0.618483 |       0.398665 |   0.392823 |
| solution-1           |     7.71908  |       1e-06    |   0.50286  |
| Bori_Aron_solution-1 |     0.612161 |       0.524264 |   0.523015 |
| k-d_tree_pandas      |     0.615978 |       0.37999  |   0.532467 |
| k-d_tree_sklearn     |    10.6741   |       1.3521   |   0.988074 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618508 |       0.388695 |   0.396409 |
| k-d_tree_polars      |     0.616653 |       0.407296 |   0.397725 |
| barab-szabi-1        |     0.620801 |       0.417449 |   0.398182 |
| Bori_Aron_solution-1 |     0.617242 |       0.532124 |   0.527146 |
| k-d_tree_pandas      |     0.61056  |       0.388662 |   0.533788 |
| k-d_tree_sklearn     |     0.634795 |       0.896447 |   0.979591 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620858 |       0.41047  |   0.399127 |
| barab-szabi-1        |     0.613088 |       0.432097 |   0.423875 |
| k-d_tree_polars      |     0.616761 |       0.437841 |   0.424469 |
| Bori_Aron_solution-1 |     0.612205 |       0.574528 |   0.528157 |
| k-d_tree_pandas      |     0.617362 |       0.405007 |   0.576688 |
| k-d_tree_sklearn     |     0.612833 |       0.956894 |   1.00074  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618293 |       0.469194 |   0.431392 |
| k-d_tree_polars      |     0.618767 |       0.545379 |   0.519507 |
| barab-szabi-1        |     0.621086 |       0.535136 |   0.529757 |
| Bori_Aron_solution-1 |     0.617389 |       0.744471 |   0.534691 |
| k-d_tree_pandas      |     0.623433 |       0.481319 |   0.708468 |
| k-d_tree_sklearn     |     0.634992 |       1.17875  |   1.05147  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616259 |       0.719737 |   0.470745 |
| Bori_Aron_solution-1 |     0.628133 |       1.3812   |   0.563745 |
| k-d_tree_polars      |     0.616845 |       0.858084 |   0.868544 |
| barab-szabi-1        |     0.621323 |       0.863551 |   0.902564 |
| k-d_tree_sklearn     |     0.61571  |       1.99028  |   1.14766  |
| k-d_tree_pandas      |     0.620436 |       0.755628 |   1.14881  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611506 |        5.46847 |   0.743922 |
| Bori_Aron_solution-1 |     0.614785 |       10.8922  |   0.823559 |
| k-d_tree_sklearn     |     0.625313 |       16.3435  |   1.26649  |
| k-d_tree_polars      |     0.613687 |        4.90832 |   6.67406  |
| barab-szabi-1        |     0.615903 |        4.92978 |   6.74019  |
| k-d_tree_pandas      |     0.616301 |        3.94203 |   7.07782  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.651016 |        75.5164 |    3.04897 |
| k-d_tree_sklearn     |     0.628057 |       231.987  |    4.33106 |
| Bori_Aron_solution-1 |     0.634943 |       151.264  |   17.9641  |