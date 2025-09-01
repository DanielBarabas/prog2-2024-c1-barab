# 2025-09-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.12228  |       0.681609 |   0.421375 |
| barab-szabi-1        |     0.531517 |       0.401042 |   0.425538 |
| k-d_tree_polars      |     0.537091 |       0.399323 |   0.430731 |
| solution-1           |     7.59112  |       1e-06    |   0.45529  |
| k-d_tree_pandas      |     0.527664 |       0.382577 |   0.53941  |
| Bori_Aron_solution-1 |     0.777433 |       0.545278 |   0.544294 |
| k-d_tree_sklearn     |     2.91412  |       1.15344  |   1.093    |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534183 |       0.424062 |   0.425338 |
| barab-szabi-1        |     0.541401 |       0.404936 |   0.428308 |
| k-d_tree_polars      |     0.538558 |       0.421452 |   0.428867 |
| Bori_Aron_solution-1 |     0.529409 |       0.549728 |   0.539359 |
| k-d_tree_pandas      |     0.542498 |       0.388207 |   0.552254 |
| k-d_tree_sklearn     |     0.540543 |       0.956033 |   1.05705  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543193 |       0.437467 |   0.434015 |
| k-d_tree_polars      |     0.568156 |       0.431266 |   0.451622 |
| barab-szabi-1        |     0.538586 |       0.431711 |   0.455194 |
| Bori_Aron_solution-1 |     0.535105 |       0.585827 |   0.545873 |
| k-d_tree_pandas      |     0.534895 |       0.4073   |   0.597076 |
| k-d_tree_sklearn     |     0.539309 |       1.00787  |   1.09386  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537689 |       0.496207 |   0.46533  |
| k-d_tree_polars      |     0.537646 |       0.543596 |   0.550547 |
| Bori_Aron_solution-1 |     0.531822 |       0.766535 |   0.560909 |
| barab-szabi-1        |     0.541437 |       0.543449 |   0.566576 |
| k-d_tree_pandas      |     0.542864 |       0.488548 |   0.736188 |
| k-d_tree_sklearn     |     0.535446 |       1.23292  |   1.14157  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537348 |       0.737613 |   0.499486 |
| Bori_Aron_solution-1 |     0.528425 |       1.39459  |   0.583229 |
| k-d_tree_polars      |     0.536611 |       0.891478 |   0.906116 |
| barab-szabi-1        |     0.537284 |       0.879421 |   0.939607 |
| k-d_tree_pandas      |     0.535549 |       0.761946 |   1.16736  |
| k-d_tree_sklearn     |     0.549102 |       2.07936  |   1.22231  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54336  |        5.23809 |   0.764016 |
| Bori_Aron_solution-1 |     0.531122 |       10.5531  |   0.849835 |
| k-d_tree_sklearn     |     0.542279 |       15.9175  |   1.30664  |
| barab-szabi-1        |     0.551464 |        5.01666 |   6.56203  |
| k-d_tree_polars      |     0.538053 |        5.28041 |   6.67579  |
| k-d_tree_pandas      |     0.542777 |        3.93228 |   6.95234  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538402 |        74.4775 |    2.84294 |
| k-d_tree_sklearn     |     0.681924 |       234.997  |    4.01223 |
| Bori_Aron_solution-1 |     0.5529   |       141.833  |   17.9161  |