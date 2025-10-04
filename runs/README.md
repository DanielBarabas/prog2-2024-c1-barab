# 2025-10-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539412 |       0.47995  |   0.440454 |
| k-d_tree_polars      |     0.567705 |       0.428128 |   0.446133 |
| barab-szabi-1        |     0.563306 |       0.421652 |   0.448583 |
| solution-1           |     7.78682  |       1e-06    |   0.469001 |
| Bori_Aron_solution-1 |     0.62512  |       0.566472 |   0.570122 |
| k-d_tree_pandas      |     7.97704  |       0.447583 |   0.650148 |
| k-d_tree_sklearn     |     3.08576  |       1.16183  |   1.10864  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.568474 |       0.43739  |   0.446267 |
| k-d_tree_polars      |     0.567631 |       0.431561 |   0.44662  |
| barab-szabi-1        |     0.577422 |       0.431084 |   0.459171 |
| Bori_Aron_solution-1 |     0.559305 |       0.577661 |   0.569153 |
| k-d_tree_pandas      |     0.557955 |       0.407037 |   0.581949 |
| k-d_tree_sklearn     |     0.571574 |       1.02216  |   1.11503  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559712 |       0.456584 |   0.454549 |
| k-d_tree_polars      |     0.561469 |       0.466457 |   0.474677 |
| barab-szabi-1        |     0.565455 |       0.458726 |   0.475855 |
| Bori_Aron_solution-1 |     0.555212 |       0.615795 |   0.569823 |
| k-d_tree_pandas      |     0.555351 |       0.421484 |   0.616635 |
| k-d_tree_sklearn     |     0.573299 |       1.06469  |   1.14344  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554378 |       0.531137 |   0.493996 |
| k-d_tree_polars      |     0.559249 |       0.578524 |   0.572993 |
| Bori_Aron_solution-1 |     0.558697 |       0.806247 |   0.582876 |
| barab-szabi-1        |     0.558727 |       0.582621 |   0.587119 |
| k-d_tree_pandas      |     0.576178 |       0.53675  |   0.772933 |
| k-d_tree_sklearn     |     0.569885 |       1.34389  |   1.21263  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569292 |       0.774167 |   0.529031 |
| Bori_Aron_solution-1 |     0.553538 |       1.50677  |   0.609393 |
| k-d_tree_polars      |     0.562193 |       0.966913 |   0.954672 |
| barab-szabi-1        |     0.57282  |       0.982451 |   0.990539 |
| k-d_tree_pandas      |     0.560155 |       0.837969 |   1.21943  |
| k-d_tree_sklearn     |     0.566096 |       2.23235  |   1.28083  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56575  |        5.64563 |   0.770653 |
| Bori_Aron_solution-1 |     0.551768 |       11.4905  |   0.863891 |
| k-d_tree_sklearn     |     0.574791 |       17.8533  |   1.38336  |
| k-d_tree_polars      |     0.563795 |        5.67194 |   6.91183  |
| barab-szabi-1        |     0.560424 |        5.74569 |   6.98354  |
| k-d_tree_pandas      |     0.5645   |        4.57218 |   7.39352  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558836 |        74.6086 |    2.80522 |
| k-d_tree_sklearn     |     0.576448 |       243.903  |    4.31351 |
| Bori_Aron_solution-1 |     0.682732 |       154.212  |   18.1883  |