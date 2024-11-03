# 2024-11-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.675215 |       0.402092 |   0.389326 |
| barab-szabi-1        |     0.654375 |       0.416948 |   0.398669 |
| k-d_tree_polars      |     0.633396 |       0.432405 |   0.40564  |
| solution-1           |     7.76548  |       1e-06    |   0.493447 |
| Bori_Aron_solution-1 |     0.639314 |       0.567118 |   0.524261 |
| k-d_tree_pandas      |     0.643101 |       0.382522 |   0.535472 |
| k-d_tree_sklearn     |    10.6815   |       1.23667  |   1.04607  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621168 |       0.390275 |   0.391773 |
| k-d_tree_polars      |     0.62337  |       0.410428 |   0.392788 |
| barab-szabi-1        |     0.630192 |       0.406693 |   0.406584 |
| Bori_Aron_solution-1 |     0.624629 |       0.595374 |   0.543046 |
| k-d_tree_pandas      |     0.628585 |       0.401501 |   0.562176 |
| k-d_tree_sklearn     |     0.634531 |       0.888897 |   0.96802  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620346 |       0.402219 |   0.397922 |
| barab-szabi-1        |     0.619068 |       0.431332 |   0.423102 |
| k-d_tree_polars      |     0.624726 |       0.430318 |   0.42521  |
| Bori_Aron_solution-1 |     0.628527 |       0.57138  |   0.529042 |
| k-d_tree_pandas      |     0.618259 |       0.403989 |   0.591226 |
| k-d_tree_sklearn     |     0.621652 |       0.948563 |   1.01112  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622576 |       0.469496 |   0.430828 |
| k-d_tree_polars      |     0.636009 |       0.538046 |   0.513981 |
| barab-szabi-1        |     0.614448 |       0.531337 |   0.527322 |
| Bori_Aron_solution-1 |     0.615534 |       0.744983 |   0.535806 |
| k-d_tree_pandas      |     0.630173 |       0.538083 |   0.745703 |
| k-d_tree_sklearn     |     0.645044 |       1.17255  |   1.09154  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.646579 |       0.742352 |   0.528035 |
| Bori_Aron_solution-1 |     0.613191 |       1.45027  |   0.596775 |
| k-d_tree_polars      |     0.61626  |       0.874707 |   0.905733 |
| barab-szabi-1        |     0.624877 |       0.856718 |   0.910902 |
| k-d_tree_sklearn     |     0.664007 |       2.01461  |   1.13467  |
| k-d_tree_pandas      |     0.656815 |       0.766584 |   1.18894  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631217 |        5.40953 |   0.726484 |
| Bori_Aron_solution-1 |     0.619364 |       10.6702  |   0.845834 |
| k-d_tree_sklearn     |     0.636375 |       16.558   |   1.23879  |
| barab-szabi-1        |     0.624138 |        4.85066 |   6.5743   |
| k-d_tree_polars      |     0.619537 |        4.90244 |   6.73448  |
| k-d_tree_pandas      |     0.626817 |        3.86267 |   6.97709  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634892 |        71.9824 |    2.87035 |
| k-d_tree_sklearn     |     0.623425 |       224.932  |    4.26358 |
| Bori_Aron_solution-1 |     0.654151 |       155.779  |   15.5963  |