# 2024-03-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.7436   |       0.359815 |   0.356227 |
| barab-szabi-1        |     0.734815 |       0.394593 |   0.360017 |
| k-d_tree_polars      |     9.03247  |       0.422992 |   0.407912 |
| solution-1           |     7.97808  |       1e-06    |   0.42017  |
| Bori_Aron_solution-1 |     0.716054 |       0.495889 |   0.49652  |
| k-d_tree_pandas      |     0.727796 |       0.375589 |   0.504615 |
| k-d_tree_sklearn     |     3.45039  |       0.896504 |   0.684764 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.731344 |       0.373449 |   0.353179 |
| barab-szabi-1        |     0.734852 |       0.404133 |   0.365599 |
| k-d_tree_polars      |     0.730247 |       0.405674 |   0.366624 |
| Bori_Aron_solution-1 |     0.718463 |       0.50522  |   0.491266 |
| k-d_tree_pandas      |     0.727235 |       0.387948 |   0.512968 |
| k-d_tree_sklearn     |     0.736673 |       0.845191 |   0.674465 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.749875 |       0.374994 |   0.36883  |
| k-d_tree_polars      |     0.729561 |       0.43325  |   0.391789 |
| barab-szabi-1        |     0.774349 |       0.429198 |   0.393447 |
| Bori_Aron_solution-1 |     0.72018  |       0.540391 |   0.496894 |
| k-d_tree_pandas      |     0.73962  |       0.400301 |   0.547616 |
| k-d_tree_sklearn     |     0.73756  |       0.897421 |   0.702742 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.724477 |       0.443158 |   0.400584 |
| k-d_tree_polars      |     0.727442 |       0.536967 |   0.491278 |
| barab-szabi-1        |     0.729935 |       0.538219 |   0.498318 |
| Bori_Aron_solution-1 |     0.715325 |       0.728682 |   0.506842 |
| k-d_tree_pandas      |     0.733209 |       0.487144 |   0.685897 |
| k-d_tree_sklearn     |     0.732924 |       1.12913  |   0.755304 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734286 |       0.69279  |   0.44215  |
| Bori_Aron_solution-1 |     0.717279 |       1.38017  |   0.535551 |
| k-d_tree_polars      |     0.725496 |       0.858372 |   0.836081 |
| k-d_tree_sklearn     |     0.737074 |       1.93445  |   0.855933 |
| barab-szabi-1        |     0.733616 |       0.865672 |   0.872658 |
| k-d_tree_pandas      |     0.732109 |       0.760129 |   1.10964  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.727796 |        5.27329 |   0.745191 |
| Bori_Aron_solution-1 |     0.723278 |       10.7535  |   0.790917 |
| k-d_tree_sklearn     |     0.750901 |       15.9384  |   1.06191  |
| k-d_tree_polars      |     0.733561 |        4.92889 |   6.48928  |
| barab-szabi-1        |     0.729175 |        5.02838 |   6.6995   |
| k-d_tree_pandas      |     0.74167  |        3.98718 |   6.89412  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.90881  |        72.2231 |    3.62229 |
| k-d_tree_sklearn     |     0.736361 |       231.579  |    5.27465 |
| Bori_Aron_solution-1 |     0.84505  |       145.178  |   16.4992  |