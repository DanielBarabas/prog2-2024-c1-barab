# 2024-08-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.74574  |       0.628092 |   0.393075 |
| k-d_tree_polars      |     0.609769 |       0.401832 |   0.398217 |
| barab-szabi-1        |     0.612602 |       0.414845 |   0.43551  |
| solution-1           |     7.43818  |       1e-06    |   0.446592 |
| Bori_Aron_solution-1 |     0.62063  |       0.5285   |   0.5187   |
| k-d_tree_pandas      |     0.597805 |       0.427759 |   0.529719 |
| k-d_tree_sklearn     |     2.92862  |       1.03478  |   0.694173 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617699 |       0.386497 |   0.381698 |
| k-d_tree_polars      |     0.60977  |       0.40515  |   0.390984 |
| barab-szabi-1        |     0.613045 |       0.401598 |   0.406842 |
| k-d_tree_pandas      |     0.611382 |       0.376748 |   0.529242 |
| Bori_Aron_solution-1 |     0.603294 |       0.53856  |   0.572062 |
| k-d_tree_sklearn     |     0.604687 |       0.87328  |   0.69243  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634101 |       0.406943 |   0.402665 |
| k-d_tree_polars      |     0.63713  |       0.420633 |   0.416331 |
| barab-szabi-1        |     0.630435 |       0.437735 |   0.431426 |
| Bori_Aron_solution-1 |     0.610265 |       0.567183 |   0.546692 |
| k-d_tree_pandas      |     0.62497  |       0.412259 |   0.599744 |
| k-d_tree_sklearn     |     0.625784 |       0.932043 |   0.723263 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615905 |       0.470774 |   0.43079  |
| k-d_tree_polars      |     0.60546  |       0.535775 |   0.517112 |
| barab-szabi-1        |     0.60633  |       0.530584 |   0.527984 |
| Bori_Aron_solution-1 |     0.608991 |       0.739317 |   0.530151 |
| k-d_tree_pandas      |     0.614502 |       0.488922 |   0.739932 |
| k-d_tree_sklearn     |     0.610332 |       1.15783  |   0.791151 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613948 |       0.708219 |   0.456325 |
| Bori_Aron_solution-1 |     0.598461 |       1.36772  |   0.561019 |
| k-d_tree_polars      |     0.604407 |       0.851946 |   0.857265 |
| k-d_tree_sklearn     |     0.608225 |       1.94648  |   0.864629 |
| barab-szabi-1        |     0.60766  |       0.848587 |   0.890201 |
| k-d_tree_pandas      |     0.609754 |       0.742873 |   1.13556  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.600391 |        5.2557  |   0.724947 |
| Bori_Aron_solution-1 |     0.595609 |       10.7808  |   0.815979 |
| k-d_tree_sklearn     |     0.606325 |       15.9743  |   0.981253 |
| k-d_tree_polars      |     0.606527 |        4.83225 |   6.43297  |
| barab-szabi-1        |     0.607399 |        4.90186 |   6.49649  |
| k-d_tree_pandas      |     0.603948 |        3.87516 |   6.86423  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60845  |         71.269 |    3.00628 |
| k-d_tree_sklearn     |     0.642941 |        228.254 |    3.96367 |
| Bori_Aron_solution-1 |     0.718825 |        151.371 |   17.1139  |