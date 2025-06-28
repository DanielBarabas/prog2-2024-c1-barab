# 2025-06-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.51913  |       1e-06    |   0.36251  |
| barab-szabi-2        |     0.55822  |       0.42612  |   0.42345  |
| barab-szabi-1        |     0.561943 |       0.406888 |   0.426037 |
| k-d_tree_polars      |     0.559515 |       0.409247 |   0.43056  |
| Bori_Aron_solution-1 |     0.552563 |       0.546815 |   0.548859 |
| k-d_tree_pandas      |     0.596121 |       0.386969 |   0.564946 |
| k-d_tree_sklearn     |    10.1068   |       1.14554  |   1.05344  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.554552 |       0.409877 |   0.425018 |
| barab-szabi-2        |     0.559732 |       0.425378 |   0.426567 |
| barab-szabi-1        |     0.553744 |       0.415499 |   0.431843 |
| Bori_Aron_solution-1 |     0.552321 |       0.55316  |   0.553827 |
| k-d_tree_pandas      |     0.558736 |       0.388727 |   0.563326 |
| k-d_tree_sklearn     |     0.559347 |       0.967508 |   1.058    |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544703 |       0.426681 |   0.42637  |
| k-d_tree_polars      |     0.550218 |       0.428032 |   0.449028 |
| barab-szabi-1        |     0.555671 |       0.429464 |   0.453559 |
| Bori_Aron_solution-1 |     0.547293 |       0.595065 |   0.543159 |
| k-d_tree_pandas      |     0.54718  |       0.40482  |   0.590343 |
| k-d_tree_sklearn     |     0.551247 |       1.01271  |   1.08057  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547918 |       0.49642  |   0.460461 |
| k-d_tree_polars      |     0.549399 |       0.538576 |   0.545047 |
| barab-szabi-1        |     0.555453 |       0.543208 |   0.558833 |
| Bori_Aron_solution-1 |     0.556874 |       0.76031  |   0.562218 |
| k-d_tree_pandas      |     0.563147 |       0.487117 |   0.750099 |
| k-d_tree_sklearn     |     0.552593 |       1.23495  |   1.15113  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548192 |       0.732927 |   0.500732 |
| Bori_Aron_solution-1 |     0.542248 |       1.3943   |   0.57795  |
| k-d_tree_polars      |     0.549621 |       0.873685 |   0.896663 |
| barab-szabi-1        |     0.547088 |       0.876618 |   0.942528 |
| k-d_tree_pandas      |     0.552609 |       0.753003 |   1.17248  |
| k-d_tree_sklearn     |     0.552395 |       2.05766  |   1.19973  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549834 |        5.22177 |   0.723917 |
| Bori_Aron_solution-1 |     0.543989 |       10.5242  |   0.835765 |
| k-d_tree_sklearn     |     0.558005 |       15.8595  |   1.29566  |
| k-d_tree_polars      |     0.556995 |        4.98271 |   6.4728   |
| barab-szabi-1        |     0.552912 |        4.99451 |   6.65503  |
| k-d_tree_pandas      |     0.550897 |        3.92069 |   6.96311  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553567 |        68.1638 |    2.55349 |
| k-d_tree_sklearn     |     0.566738 |       222.205  |    3.89401 |
| Bori_Aron_solution-1 |     0.544267 |       144.847  |   16.2945  |