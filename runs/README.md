# 2025-07-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.577249 |       0.418038 |   0.443564 |
| barab-szabi-2        |     8.01419  |       0.885975 |   0.449972 |
| barab-szabi-1        |     0.565158 |       0.432726 |   0.45839  |
| Bori_Aron_solution-1 |     0.548836 |       0.567489 |   0.570307 |
| k-d_tree_pandas      |     0.579255 |       0.392934 |   0.594611 |
| solution-1           |     7.53761  |       1e-06    |   0.654035 |
| k-d_tree_sklearn     |     3.04192  |       1.24915  |   1.07998  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.599783 |       0.449409 |   0.45456  |
| barab-szabi-2        |     0.593945 |       0.459627 |   0.463178 |
| barab-szabi-1        |     0.612186 |       0.434356 |   0.463551 |
| Bori_Aron_solution-1 |     0.603167 |       0.616764 |   0.586452 |
| k-d_tree_pandas      |     0.580722 |       0.413039 |   0.592127 |
| k-d_tree_sklearn     |     0.569625 |       1.06207  |   1.17292  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.567522 |       0.448902 |   0.462889 |
| k-d_tree_polars      |     0.578007 |       0.451776 |   0.46321  |
| barab-szabi-2        |     0.57933  |       0.440642 |   0.482531 |
| Bori_Aron_solution-1 |     0.552937 |       0.608607 |   0.590673 |
| k-d_tree_pandas      |     0.569866 |       0.41888  |   0.639913 |
| k-d_tree_sklearn     |     0.58674  |       1.11752  |   1.14432  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581676 |       0.520564 |   0.490025 |
| k-d_tree_polars      |     0.556336 |       0.556634 |   0.554803 |
| barab-szabi-1        |     0.573112 |       0.574563 |   0.581989 |
| Bori_Aron_solution-1 |     0.572324 |       0.847698 |   0.635875 |
| k-d_tree_pandas      |     0.577586 |       0.487133 |   0.73411  |
| k-d_tree_sklearn     |     0.612347 |       1.26724  |   1.18344  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559501 |       0.754613 |   0.506248 |
| Bori_Aron_solution-1 |     0.557246 |       1.43193  |   0.582876 |
| k-d_tree_polars      |     0.561164 |       0.888447 |   0.942774 |
| barab-szabi-1        |     0.561711 |       0.883644 |   0.979314 |
| k-d_tree_pandas      |     0.555562 |       0.779997 |   1.22724  |
| k-d_tree_sklearn     |     0.564882 |       2.13281  |   1.23648  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559438 |        5.40207 |   0.739401 |
| Bori_Aron_solution-1 |     0.551377 |       10.5747  |   0.871284 |
| k-d_tree_sklearn     |     0.575689 |       16.3589  |   1.34925  |
| k-d_tree_polars      |     0.595    |        5.00313 |   6.64237  |
| barab-szabi-1        |     0.552232 |        5.0173  |   6.68925  |
| k-d_tree_pandas      |     0.556607 |        3.97274 |   7.00105  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56031  |        73.9731 |    2.70348 |
| k-d_tree_sklearn     |     0.778955 |       235.946  |    4.00995 |
| Bori_Aron_solution-1 |     0.563067 |       144.676  |   17.8862  |