# 2026-01-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.522757 |       0.461041 |   0.433334 |
| k-d_tree_polars      |     0.53035  |       0.401219 |   0.43542  |
| barab-szabi-1        |     0.536927 |       0.401842 |   0.435976 |
| solution-1           |     7.53232  |       1e-06    |   0.449681 |
| Bori_Aron_solution-1 |     0.532591 |       0.540429 |   0.544634 |
| k-d_tree_pandas      |     8.54854  |       0.413461 |   0.671733 |
| k-d_tree_sklearn     |     3.002    |       1.09923  |   1.07104  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529955 |       0.439481 |   0.439108 |
| barab-szabi-1        |     0.536839 |       0.422641 |   0.443153 |
| k-d_tree_polars      |     0.528124 |       0.409649 |   0.466565 |
| k-d_tree_pandas      |     0.60486  |       0.384832 |   0.552653 |
| Bori_Aron_solution-1 |     0.52872  |       0.547492 |   0.559917 |
| k-d_tree_sklearn     |     0.537197 |       0.972803 |   1.0727   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53061  |       0.445313 |   0.454655 |
| k-d_tree_polars      |     0.536663 |       0.436681 |   0.462721 |
| barab-szabi-1        |     0.539783 |       0.434737 |   0.470993 |
| Bori_Aron_solution-1 |     0.525476 |       0.593386 |   0.543638 |
| k-d_tree_pandas      |     0.542606 |       0.409147 |   0.595017 |
| k-d_tree_sklearn     |     0.532107 |       1.01496  |   1.08928  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531944 |       0.508533 |   0.478997 |
| k-d_tree_polars      |     0.530655 |       0.56187  |   0.560377 |
| Bori_Aron_solution-1 |     0.523343 |       0.776577 |   0.5624   |
| barab-szabi-1        |     0.52633  |       0.562349 |   0.567605 |
| k-d_tree_pandas      |     0.534391 |       0.500213 |   0.741126 |
| k-d_tree_sklearn     |     0.536016 |       1.25918  |   1.15202  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527755 |       0.732626 |   0.504928 |
| Bori_Aron_solution-1 |     0.5235   |       1.462    |   0.589496 |
| k-d_tree_polars      |     0.535088 |       0.930976 |   0.919834 |
| barab-szabi-1        |     0.534213 |       0.923837 |   0.969146 |
| k-d_tree_pandas      |     0.531002 |       0.806362 |   1.17251  |
| k-d_tree_sklearn     |     0.53951  |       2.12748  |   1.21365  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530432 |        5.29877 |   0.749564 |
| Bori_Aron_solution-1 |     0.522838 |       11.3404  |   0.849783 |
| k-d_tree_sklearn     |     0.540736 |       17.2059  |   1.33093  |
| k-d_tree_polars      |     0.531604 |        5.44063 |   6.75542  |
| barab-szabi-1        |     0.531437 |        5.58597 |   6.79836  |
| k-d_tree_pandas      |     0.528013 |        4.47092 |   7.19027  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532836 |        78.5576 |    2.87086 |
| k-d_tree_sklearn     |     0.542995 |       246.848  |    4.16204 |
| Bori_Aron_solution-1 |     0.687052 |       156.601  |   16.7679  |