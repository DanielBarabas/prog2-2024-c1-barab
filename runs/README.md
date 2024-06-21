# 2024-06-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.753746 |       0.384374 |   0.373427 |
| barab-szabi-1        |     0.795309 |       0.383452 |   0.379876 |
| k-d_tree_polars      |     0.759348 |       0.396593 |   0.38398  |
| solution-1           |     7.92652  |       1e-06    |   0.428179 |
| Bori_Aron_solution-1 |     0.750129 |       0.509769 |   0.50547  |
| k-d_tree_pandas      |     8.34963  |       0.395746 |   0.551008 |
| k-d_tree_sklearn     |     3.34306  |       0.93506  |   0.713244 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.792426 |       0.386026 |   0.376633 |
| barab-szabi-1        |     0.790687 |       0.395858 |   0.38242  |
| k-d_tree_polars      |     0.795913 |       0.392575 |   0.389817 |
| Bori_Aron_solution-1 |     0.790568 |       0.516945 |   0.501212 |
| k-d_tree_pandas      |     0.792078 |       0.37282  |   0.519887 |
| k-d_tree_sklearn     |     0.797886 |       0.889735 |   0.74172  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.796679 |       0.396612 |   0.388575 |
| k-d_tree_polars      |     0.792927 |       0.422256 |   0.414267 |
| barab-szabi-1        |     0.797129 |       0.415831 |   0.419574 |
| Bori_Aron_solution-1 |     0.787178 |       0.552807 |   0.508838 |
| k-d_tree_pandas      |     0.787428 |       0.38723  |   0.558736 |
| k-d_tree_sklearn     |     0.821704 |       0.944787 |   0.748734 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.791193 |       0.460802 |   0.423357 |
| k-d_tree_polars      |     0.800591 |       0.528561 |   0.512722 |
| barab-szabi-1        |     0.789486 |       0.526361 |   0.52405  |
| Bori_Aron_solution-1 |     0.793773 |       0.732414 |   0.524065 |
| k-d_tree_pandas      |     0.793714 |       0.47524  |   0.693634 |
| k-d_tree_sklearn     |     0.797468 |       1.15662  |   0.79847  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.790709 |       0.712825 |   0.464633 |
| Bori_Aron_solution-1 |     0.78385  |       1.3842   |   0.54419  |
| k-d_tree_polars      |     0.793682 |       0.865193 |   0.858671 |
| barab-szabi-1        |     0.794608 |       0.853227 |   0.901841 |
| k-d_tree_sklearn     |     0.798745 |       1.96953  |   0.902973 |
| k-d_tree_pandas      |     0.794811 |       0.744815 |   1.11316  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.794828 |        5.38466 |   0.765929 |
| Bori_Aron_solution-1 |     0.779096 |       10.8056  |   0.838397 |
| k-d_tree_sklearn     |     0.80971  |       15.9513  |   1.07897  |
| k-d_tree_polars      |     0.791601 |        4.93316 |   6.54561  |
| barab-szabi-1        |     0.792215 |        4.91855 |   6.61696  |
| k-d_tree_pandas      |     0.796844 |        3.97926 |   6.85861  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.950947 |        72.8454 |    3.62176 |
| k-d_tree_sklearn     |     0.876043 |       228.593  |    4.52718 |
| Bori_Aron_solution-1 |     0.778471 |       149.073  |   17.1731  |