# 2025-07-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.791244 |       0.4331   |   0.446731 |
| barab-szabi-1        |     1.03286  |       0.43598  |   0.450344 |
| barab-szabi-2        |     8.50637  |       0.773464 |   0.453067 |
| solution-1           |     8.16082  |       1e-06    |   0.569956 |
| k-d_tree_pandas      |     0.576955 |       0.415334 |   0.599866 |
| Bori_Aron_solution-1 |     1.03144  |       0.607482 |   0.600753 |
| k-d_tree_sklearn     |     3.64091  |       1.25065  |   1.11835  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.58285  |       0.44693  |   0.446295 |
| barab-szabi-2        |     0.581355 |       0.447599 |   0.44733  |
| k-d_tree_polars      |     0.581758 |       0.441396 |   0.449062 |
| Bori_Aron_solution-1 |     0.579057 |       0.580965 |   0.568012 |
| k-d_tree_pandas      |     0.584893 |       0.419097 |   0.594334 |
| k-d_tree_sklearn     |     0.588427 |       1.0329   |   1.10645  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.573966 |       0.454849 |   0.455399 |
| k-d_tree_polars      |     0.57076  |       0.450981 |   0.464378 |
| barab-szabi-1        |     0.581338 |       0.474306 |   0.475407 |
| Bori_Aron_solution-1 |     0.571628 |       0.621133 |   0.582302 |
| k-d_tree_pandas      |     0.567827 |       0.418139 |   0.631809 |
| k-d_tree_sklearn     |     0.582919 |       1.14165  |   1.13498  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603576 |       0.5135   |   0.478692 |
| k-d_tree_polars      |     0.586161 |       0.589116 |   0.577734 |
| Bori_Aron_solution-1 |     0.574741 |       0.786513 |   0.582895 |
| barab-szabi-1        |     0.571393 |       0.566143 |   0.584061 |
| k-d_tree_pandas      |     0.577245 |       0.52072  |   0.784571 |
| k-d_tree_sklearn     |     0.575151 |       1.29057  |   1.23259  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586168 |       0.780984 |   0.526062 |
| Bori_Aron_solution-1 |     0.574074 |       1.47601  |   0.621658 |
| k-d_tree_polars      |     0.565016 |       0.90009  |   0.931912 |
| barab-szabi-1        |     0.575326 |       0.927641 |   0.97685  |
| k-d_tree_pandas      |     0.574218 |       0.769485 |   1.19787  |
| k-d_tree_sklearn     |     0.578649 |       2.15368  |   1.25013  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566905 |        5.45808 |   0.764876 |
| Bori_Aron_solution-1 |     0.557085 |       10.8753  |   0.85782  |
| k-d_tree_sklearn     |     0.568537 |       16.0507  |   1.35799  |
| barab-szabi-1        |     0.579832 |        5.05544 |   6.48956  |
| k-d_tree_polars      |     0.565459 |        5.11768 |   7.05483  |
| k-d_tree_pandas      |     0.595575 |        4.01221 |   7.3092   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.582271 |         85.588 |    2.94732 |
| k-d_tree_sklearn     |     0.82005  |        234.471 |    4.0037  |
| Bori_Aron_solution-1 |     0.621647 |        144.696 |   18.2039  |