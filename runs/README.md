# 2024-07-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534795 |       0.382675 |   0.381235 |
| k-d_tree_polars      |     0.569525 |       0.390233 |   0.386992 |
| barab-szabi-1        |     8.22218  |       0.520707 |   0.506947 |
| Bori_Aron_solution-1 |     0.546996 |       0.519354 |   0.512863 |
| k-d_tree_pandas      |     0.553628 |       0.373728 |   0.538037 |
| solution-1           |     7.77695  |       1e-06    |   0.544213 |
| k-d_tree_sklearn     |     3.04581  |       1.13448  |   0.693797 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55015  |       0.386518 |   0.384674 |
| k-d_tree_polars      |     0.552631 |       0.400153 |   0.393169 |
| barab-szabi-1        |     0.548797 |       0.401639 |   0.394459 |
| Bori_Aron_solution-1 |     0.545581 |       0.522194 |   0.526753 |
| k-d_tree_pandas      |     0.559358 |       0.386008 |   0.529579 |
| k-d_tree_sklearn     |     0.56224  |       0.880497 |   0.718502 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559912 |       0.405091 |   0.401728 |
| barab-szabi-1        |     0.574932 |       0.430384 |   0.418146 |
| k-d_tree_polars      |     0.551557 |       0.422697 |   0.420897 |
| Bori_Aron_solution-1 |     0.550114 |       0.560076 |   0.518374 |
| k-d_tree_pandas      |     0.549593 |       0.398979 |   0.586427 |
| k-d_tree_sklearn     |     0.570544 |       0.936905 |   0.743441 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560705 |       0.462459 |   0.443565 |
| k-d_tree_polars      |     0.547004 |       0.528417 |   0.516103 |
| barab-szabi-1        |     0.551798 |       0.531992 |   0.524165 |
| Bori_Aron_solution-1 |     0.545537 |       0.736678 |   0.53791  |
| k-d_tree_pandas      |     0.554731 |       0.473825 |   0.705571 |
| k-d_tree_sklearn     |     0.580512 |       1.1518   |   0.77622  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557914 |       0.713965 |   0.456049 |
| Bori_Aron_solution-1 |     0.545165 |       1.3966   |   0.564981 |
| k-d_tree_polars      |     0.553348 |       0.851874 |   0.860092 |
| k-d_tree_sklearn     |     0.554983 |       1.98208  |   0.872605 |
| barab-szabi-1        |     0.554736 |       0.855142 |   0.899977 |
| k-d_tree_pandas      |     0.559242 |       0.745084 |   1.14078  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552952 |        5.38936 |   0.724065 |
| Bori_Aron_solution-1 |     0.551476 |       10.8256  |   0.83913  |
| k-d_tree_sklearn     |     0.55589  |       15.8627  |   0.975086 |
| k-d_tree_polars      |     0.549515 |        4.76738 |   6.56856  |
| barab-szabi-1        |     0.555357 |        4.83866 |   6.58147  |
| k-d_tree_pandas      |     0.552712 |        3.89092 |   6.96583  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5528   |        70.6149 |    2.91271 |
| k-d_tree_sklearn     |     0.569296 |       226.403  |    3.91811 |
| Bori_Aron_solution-1 |     0.616255 |       145.441  |   18.575   |