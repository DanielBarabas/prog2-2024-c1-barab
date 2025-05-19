# 2025-05-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.544994 |       0.418528 |   0.418574 |
| barab-szabi-2        |     0.558687 |       0.411524 |   0.422162 |
| Bori_Aron_solution-1 |     0.531239 |       0.544731 |   0.549815 |
| k-d_tree_pandas      |     0.55762  |       0.472925 |   0.577315 |
| barab-szabi-1        |     8.27598  |       0.556388 |   0.669541 |
| solution-1           |     7.9257   |       1e-06    |   0.792503 |
| k-d_tree_sklearn     |     3.29281  |       1.30475  |   1.0545   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561716 |       0.414022 |   0.422521 |
| k-d_tree_polars      |     0.562965 |       0.423707 |   0.426791 |
| barab-szabi-1        |     0.563425 |       0.428928 |   0.431166 |
| k-d_tree_pandas      |     0.554684 |       0.403346 |   0.562927 |
| Bori_Aron_solution-1 |     0.554417 |       0.572759 |   0.567015 |
| k-d_tree_sklearn     |     0.565534 |       0.969041 |   1.05685  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553965 |       0.432201 |   0.425789 |
| k-d_tree_polars      |     0.561064 |       0.446996 |   0.452887 |
| barab-szabi-1        |     0.578203 |       0.462594 |   0.464896 |
| Bori_Aron_solution-1 |     0.55866  |       0.593392 |   0.561125 |
| k-d_tree_pandas      |     0.55979  |       0.409623 |   0.602948 |
| k-d_tree_sklearn     |     0.567441 |       1.00502  |   1.07423  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553163 |       0.487487 |   0.457226 |
| k-d_tree_polars      |     0.556294 |       0.544181 |   0.545211 |
| barab-szabi-1        |     0.561914 |       0.555377 |   0.560308 |
| Bori_Aron_solution-1 |     0.549151 |       0.780526 |   0.563918 |
| k-d_tree_pandas      |     0.550578 |       0.490731 |   0.740308 |
| k-d_tree_sklearn     |     0.562175 |       1.23578  |   1.12621  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54989  |       0.727818 |   0.491493 |
| Bori_Aron_solution-1 |     0.547092 |       1.41015  |   0.593257 |
| k-d_tree_polars      |     0.557847 |       0.878953 |   0.899303 |
| barab-szabi-1        |     0.551005 |       0.878421 |   0.954027 |
| k-d_tree_pandas      |     0.553629 |       0.768509 |   1.1698   |
| k-d_tree_sklearn     |     0.554559 |       2.06245  |   1.22028  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553871 |        5.21876 |   0.718166 |
| Bori_Aron_solution-1 |     0.551601 |       10.6175  |   0.909988 |
| k-d_tree_sklearn     |     0.556447 |       16.0152  |   1.31056  |
| k-d_tree_polars      |     0.55161  |        5.01281 |   6.50693  |
| barab-szabi-1        |     0.551068 |        5.02121 |   6.54223  |
| k-d_tree_pandas      |     0.548877 |        4.00319 |   7.11168  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.67204  |        73.6344 |    2.95567 |
| k-d_tree_sklearn     |     0.772016 |       230.704  |    4.40109 |
| Bori_Aron_solution-1 |     0.544414 |       152.29   |   17.6305  |