# 2024-10-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613379 |       0.386832 |   0.381449 |
| barab-szabi-1        |     0.618925 |       0.409345 |   0.385038 |
| k-d_tree_polars      |     0.619712 |       0.397665 |   0.403949 |
| solution-1           |     7.38019  |       1e-06    |   0.411178 |
| Bori_Aron_solution-1 |     0.606367 |       0.514806 |   0.517195 |
| k-d_tree_pandas      |     0.611027 |       0.376613 |   0.519758 |
| k-d_tree_sklearn     |    10.2055   |       1.05692  |   0.948225 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617566 |       0.390077 |   0.387496 |
| k-d_tree_polars      |     0.623016 |       0.401107 |   0.389118 |
| barab-szabi-1        |     0.615332 |       0.403223 |   0.391282 |
| Bori_Aron_solution-1 |     0.609224 |       0.527719 |   0.517862 |
| k-d_tree_pandas      |     0.61443  |       0.379362 |   0.522781 |
| k-d_tree_sklearn     |     0.616589 |       0.876403 |   1.01597  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61186  |       0.404403 |   0.39954  |
| k-d_tree_polars      |     0.614157 |       0.426216 |   0.418793 |
| barab-szabi-1        |     0.614638 |       0.423795 |   0.422233 |
| Bori_Aron_solution-1 |     0.605199 |       0.559916 |   0.519073 |
| k-d_tree_pandas      |     0.622578 |       0.399242 |   0.573161 |
| k-d_tree_sklearn     |     0.613603 |       0.923949 |   0.977149 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611768 |       0.473556 |   0.431286 |
| k-d_tree_polars      |     0.616074 |       0.533036 |   0.521427 |
| barab-szabi-1        |     0.616745 |       0.539558 |   0.532568 |
| Bori_Aron_solution-1 |     0.609658 |       0.74561  |   0.533789 |
| k-d_tree_pandas      |     0.619717 |       0.480525 |   0.724591 |
| k-d_tree_sklearn     |     0.616926 |       1.17831  |   1.03292  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615518 |       0.720232 |   0.460303 |
| Bori_Aron_solution-1 |     0.620509 |       1.38055  |   0.552821 |
| k-d_tree_polars      |     0.611963 |       0.86447  |   0.866873 |
| barab-szabi-1        |     0.609692 |       0.868668 |   0.926153 |
| k-d_tree_sklearn     |     0.64505  |       2.00792  |   1.12244  |
| k-d_tree_pandas      |     0.620042 |       0.751406 |   1.14553  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616579 |        5.51086 |   0.726152 |
| Bori_Aron_solution-1 |     0.612212 |       10.7788  |   0.812836 |
| k-d_tree_sklearn     |     0.61552  |       16.0891  |   1.24467  |
| k-d_tree_polars      |     0.612239 |        4.89072 |   6.68112  |
| barab-szabi-1        |     0.622754 |        4.86595 |   6.6867   |
| k-d_tree_pandas      |     0.60959  |        3.901   |   7.28823  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632651 |        71.3862 |    2.99559 |
| k-d_tree_sklearn     |     0.634597 |       223.424  |    4.18662 |
| Bori_Aron_solution-1 |     0.619669 |       151.552  |   18.3777  |