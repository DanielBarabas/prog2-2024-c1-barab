# 2024-08-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.49676  |       1e-06    |   0.361196 |
| barab-szabi-2        |     0.606923 |       0.378097 |   0.37913  |
| barab-szabi-1        |     0.602265 |       0.389396 |   0.380079 |
| k-d_tree_polars      |     0.604932 |       0.385826 |   0.386715 |
| Bori_Aron_solution-1 |     0.593551 |       0.510952 |   0.513995 |
| k-d_tree_pandas      |     7.7831   |       0.405449 |   0.659631 |
| k-d_tree_sklearn     |     2.95914  |       1.00082  |   0.688626 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598646 |       0.419676 |   0.375921 |
| barab-szabi-1        |     0.596491 |       0.395471 |   0.387569 |
| k-d_tree_polars      |     0.600414 |       0.393867 |   0.39186  |
| Bori_Aron_solution-1 |     0.597507 |       0.577523 |   0.513541 |
| k-d_tree_pandas      |     0.601381 |       0.374843 |   0.525524 |
| k-d_tree_sklearn     |     0.603066 |       0.878678 |   0.698524 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60382  |       0.394326 |   0.393939 |
| k-d_tree_polars      |     0.599657 |       0.418215 |   0.414689 |
| barab-szabi-1        |     0.600967 |       0.450103 |   0.417711 |
| Bori_Aron_solution-1 |     0.59355  |       0.572043 |   0.513169 |
| k-d_tree_pandas      |     0.615515 |       0.391373 |   0.564981 |
| k-d_tree_sklearn     |     0.608156 |       0.922633 |   0.713712 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.600486 |       0.454818 |   0.418662 |
| k-d_tree_polars      |     0.615381 |       0.527818 |   0.505099 |
| barab-szabi-1        |     0.601675 |       0.525542 |   0.520992 |
| Bori_Aron_solution-1 |     0.597508 |       0.737283 |   0.530783 |
| k-d_tree_pandas      |     0.600252 |       0.472163 |   0.697218 |
| k-d_tree_sklearn     |     0.607392 |       1.15211  |   0.772063 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.597551 |       0.701161 |   0.453742 |
| Bori_Aron_solution-1 |     0.595485 |       1.36226  |   0.552941 |
| k-d_tree_polars      |     0.602525 |       0.836427 |   0.84502  |
| k-d_tree_sklearn     |     0.606614 |       1.95656  |   0.867294 |
| barab-szabi-1        |     0.60102  |       0.84228  |   0.876944 |
| k-d_tree_pandas      |     0.601982 |       0.737724 |   1.12025  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605144 |        5.27995 |   0.706588 |
| Bori_Aron_solution-1 |     0.595271 |       10.6283  |   0.836072 |
| k-d_tree_sklearn     |     0.617763 |       15.7533  |   0.967261 |
| k-d_tree_polars      |     0.602018 |        4.84746 |   6.46511  |
| barab-szabi-1        |     0.603435 |        4.80581 |   6.48563  |
| k-d_tree_pandas      |     0.601658 |        3.85695 |   6.91999  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.795982 |        69.7781 |    3.09091 |
| k-d_tree_sklearn     |     0.602258 |       220.155  |    3.75482 |
| Bori_Aron_solution-1 |     0.606932 |       141.384  |   17.427   |