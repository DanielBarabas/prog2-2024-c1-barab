# 2024-10-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.644298 |       0.398373 |   0.385472 |
| barab-szabi-1        |     0.635338 |       0.407812 |   0.392496 |
| barab-szabi-2        |     0.625686 |       0.413252 |   0.397089 |
| solution-1           |     7.68168  |       1e-06    |   0.437999 |
| k-d_tree_pandas      |     0.619631 |       0.37883  |   0.51976  |
| Bori_Aron_solution-1 |     0.636955 |       0.523126 |   0.523052 |
| k-d_tree_sklearn     |    10.2395   |       1.07764  |   0.960494 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61613  |       0.385829 |   0.377812 |
| barab-szabi-1        |     0.616855 |       0.409192 |   0.39112  |
| k-d_tree_polars      |     0.617087 |       0.404727 |   0.403934 |
| Bori_Aron_solution-1 |     0.611057 |       0.526609 |   0.515609 |
| k-d_tree_pandas      |     0.639903 |       0.384163 |   0.527292 |
| k-d_tree_sklearn     |     0.61557  |       0.874021 |   0.975077 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608336 |       0.398043 |   0.394676 |
| barab-szabi-1        |     0.605221 |       0.424836 |   0.413196 |
| k-d_tree_polars      |     0.609875 |       0.425492 |   0.425839 |
| k-d_tree_pandas      |     0.620221 |       0.402785 |   0.576126 |
| Bori_Aron_solution-1 |     0.604026 |       0.563237 |   0.579588 |
| k-d_tree_sklearn     |     0.616219 |       0.913546 |   0.969932 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620083 |       0.467864 |   0.423059 |
| k-d_tree_polars      |     0.630191 |       0.541671 |   0.518254 |
| Bori_Aron_solution-1 |     0.600174 |       0.738554 |   0.52898  |
| barab-szabi-1        |     0.61176  |       0.541022 |   0.531889 |
| k-d_tree_pandas      |     0.613645 |       0.476762 |   0.701066 |
| k-d_tree_sklearn     |     0.624093 |       1.17203  |   1.05521  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609996 |       0.707185 |   0.458792 |
| Bori_Aron_solution-1 |     0.604715 |       1.39048  |   0.561589 |
| k-d_tree_polars      |     0.609707 |       0.855349 |   0.86095  |
| barab-szabi-1        |     0.618521 |       0.855228 |   0.900703 |
| k-d_tree_sklearn     |     0.613726 |       1.96784  |   1.11767  |
| k-d_tree_pandas      |     0.613119 |       0.74469  |   1.14245  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617371 |        5.26024 |   0.710526 |
| Bori_Aron_solution-1 |     0.605801 |       10.6483  |   0.798833 |
| k-d_tree_sklearn     |     0.613963 |       16.3393  |   1.23486  |
| barab-szabi-1        |     0.616363 |        4.84831 |   6.51655  |
| k-d_tree_polars      |     0.607396 |        4.87645 |   6.62896  |
| k-d_tree_pandas      |     0.609405 |        3.87988 |   7.05199  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.682088 |        72.8603 |    2.91551 |
| k-d_tree_sklearn     |     0.638658 |       234.227  |    4.33305 |
| Bori_Aron_solution-1 |     0.645031 |       145.126  |   18.3619  |