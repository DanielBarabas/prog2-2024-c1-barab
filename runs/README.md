# 2024-12-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61632  |       0.397969 |   0.381018 |
| k-d_tree_polars      |     0.615221 |       0.39734  |   0.385359 |
| barab-szabi-1        |     0.616178 |       0.392727 |   0.386056 |
| solution-1           |     7.72146  |       1e-06    |   0.419665 |
| Bori_Aron_solution-1 |     0.611969 |       0.522574 |   0.527867 |
| k-d_tree_pandas      |     0.61956  |       0.384405 |   0.546904 |
| k-d_tree_sklearn     |    10.5024   |       1.06713  |   0.96086  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614156 |       0.415778 |   0.392554 |
| k-d_tree_polars      |     0.61685  |       0.405482 |   0.395456 |
| barab-szabi-1        |     0.624807 |       0.40997  |   0.407221 |
| Bori_Aron_solution-1 |     0.614331 |       0.536345 |   0.530397 |
| k-d_tree_pandas      |     0.62531  |       0.392237 |   0.551982 |
| k-d_tree_sklearn     |     0.625195 |       0.910969 |   1.00118  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.641281 |       0.412987 |   0.40406  |
| k-d_tree_polars      |     0.623345 |       0.436841 |   0.423687 |
| barab-szabi-1        |     0.627416 |       0.453956 |   0.432405 |
| Bori_Aron_solution-1 |     0.624632 |       0.573382 |   0.542608 |
| k-d_tree_pandas      |     0.639543 |       0.411068 |   0.587465 |
| k-d_tree_sklearn     |     0.632557 |       0.956555 |   1.0178   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626557 |       0.480908 |   0.436424 |
| k-d_tree_polars      |     0.632186 |       0.560563 |   0.525071 |
| barab-szabi-1        |     0.634322 |       0.546566 |   0.531966 |
| Bori_Aron_solution-1 |     0.623719 |       0.7596   |   0.552755 |
| k-d_tree_pandas      |     0.631278 |       0.484283 |   0.720663 |
| k-d_tree_sklearn     |     0.630622 |       1.17784  |   1.06476  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.64103  |       0.749219 |   0.550739 |
| Bori_Aron_solution-1 |     0.623006 |       1.43919  |   0.57702  |
| k-d_tree_polars      |     0.633946 |       0.880088 |   0.890609 |
| barab-szabi-1        |     0.634654 |       0.87123  |   0.923544 |
| k-d_tree_pandas      |     0.627944 |       0.754957 |   1.17288  |
| k-d_tree_sklearn     |     0.634658 |       2.03787  |   1.18169  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608416 |        5.24173 |   0.732617 |
| Bori_Aron_solution-1 |     0.613886 |       10.591   |   0.809765 |
| k-d_tree_sklearn     |     0.633032 |       16.0231  |   1.24243  |
| k-d_tree_polars      |     0.613802 |        4.85148 |   6.46075  |
| barab-szabi-1        |     0.616264 |        4.85545 |   6.4935   |
| k-d_tree_pandas      |     0.614149 |        3.85366 |   6.81672  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.646013 |         73.395 |    2.86852 |
| k-d_tree_sklearn     |     0.618244 |        227.588 |    4.14778 |
| Bori_Aron_solution-1 |     0.638332 |        156.274 |   15.6947  |