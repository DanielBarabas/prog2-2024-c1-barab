# 2025-01-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.41449  |       0.546112 |   0.390656 |
| k-d_tree_polars      |     0.569306 |       0.393863 |   0.395886 |
| barab-szabi-1        |     0.584375 |       0.393517 |   0.396647 |
| solution-1           |     7.05674  |       1e-06    |   0.4004   |
| Bori_Aron_solution-1 |     0.578335 |       0.518539 |   0.522511 |
| k-d_tree_pandas      |     0.577045 |       0.39234  |   0.524502 |
| k-d_tree_sklearn     |     2.83781  |       0.977048 |   1.00892  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575679 |       0.398342 |   0.39554  |
| barab-szabi-1        |     0.578599 |       0.402705 |   0.401198 |
| k-d_tree_polars      |     0.58187  |       0.401598 |   0.404967 |
| Bori_Aron_solution-1 |     0.573829 |       0.526631 |   0.521956 |
| k-d_tree_pandas      |     0.582146 |       0.381501 |   0.54668  |
| k-d_tree_sklearn     |     0.583462 |       0.944407 |   1.00342  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577478 |       0.412621 |   0.40601  |
| k-d_tree_polars      |     0.583373 |       0.426779 |   0.427801 |
| barab-szabi-1        |     0.578534 |       0.424998 |   0.436072 |
| Bori_Aron_solution-1 |     0.573251 |       0.588901 |   0.527454 |
| k-d_tree_pandas      |     0.588293 |       0.398222 |   0.600852 |
| k-d_tree_sklearn     |     0.585709 |       0.97755  |   1.03369  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58299  |       0.475733 |   0.438362 |
| k-d_tree_polars      |     0.579744 |       0.534662 |   0.530214 |
| Bori_Aron_solution-1 |     0.574982 |       0.740061 |   0.545085 |
| barab-szabi-1        |     0.58401  |       0.532308 |   0.549732 |
| k-d_tree_pandas      |     0.582468 |       0.477288 |   0.723267 |
| k-d_tree_sklearn     |     0.587517 |       1.19963  |   1.09586  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.602203 |       0.725091 |   0.479586 |
| Bori_Aron_solution-1 |     0.578662 |       1.3785   |   0.574058 |
| k-d_tree_polars      |     0.578864 |       0.858578 |   0.877641 |
| barab-szabi-1        |     0.580854 |       0.869029 |   0.914536 |
| k-d_tree_pandas      |     0.576215 |       0.740684 |   1.16867  |
| k-d_tree_sklearn     |     0.581826 |       2.02627  |   1.19435  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57934  |        5.30697 |   0.744333 |
| Bori_Aron_solution-1 |     0.572098 |       10.6909  |   0.87844  |
| k-d_tree_sklearn     |     0.588136 |       15.9322  |   1.28706  |
| k-d_tree_polars      |     0.580958 |        4.91609 |   6.69106  |
| barab-szabi-1        |     0.582802 |        4.92857 |   6.73183  |
| k-d_tree_pandas      |     0.579795 |        3.85971 |   7.06434  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574965 |        75.5741 |    3.06425 |
| k-d_tree_sklearn     |     0.58578  |       233.809  |    4.4103  |
| Bori_Aron_solution-1 |     0.639547 |       148.844  |   18.3923  |