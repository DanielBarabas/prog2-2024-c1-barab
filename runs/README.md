# 2024-07-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.88281  |       1e-06    |   0.362406 |
| barab-szabi-2        |     0.556444 |       0.39223  |   0.381855 |
| barab-szabi-1        |     0.571509 |       0.397518 |   0.391471 |
| k-d_tree_polars      |     0.566084 |       0.458978 |   0.404487 |
| Bori_Aron_solution-1 |     0.54251  |       0.52641  |   0.524791 |
| k-d_tree_sklearn     |     3.12073  |       0.936904 |   0.723141 |
| k-d_tree_pandas      |     8.16869  |       0.393242 |   0.884383 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56585  |       0.386831 |   0.382312 |
| barab-szabi-1        |     0.58528  |       0.405859 |   0.394217 |
| k-d_tree_polars      |     0.564285 |       0.404823 |   0.401969 |
| Bori_Aron_solution-1 |     0.570652 |       0.532351 |   0.523115 |
| k-d_tree_pandas      |     0.556617 |       0.39407  |   0.537232 |
| k-d_tree_sklearn     |     0.571494 |       0.903467 |   0.707011 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567101 |       0.399566 |   0.399446 |
| k-d_tree_polars      |     0.557447 |       0.434736 |   0.421912 |
| barab-szabi-1        |     0.570286 |       0.428654 |   0.430949 |
| Bori_Aron_solution-1 |     0.582915 |       0.568404 |   0.52782  |
| k-d_tree_pandas      |     0.569134 |       0.406937 |   0.581508 |
| k-d_tree_sklearn     |     0.577589 |       0.949509 |   0.800093 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566603 |       0.465909 |   0.428583 |
| k-d_tree_polars      |     0.563272 |       0.539589 |   0.520932 |
| barab-szabi-1        |     0.563953 |       0.530874 |   0.528359 |
| Bori_Aron_solution-1 |     0.561142 |       0.751833 |   0.553052 |
| k-d_tree_pandas      |     0.566678 |       0.480414 |   0.71539  |
| k-d_tree_sklearn     |     0.570303 |       1.16573  |   0.802878 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567453 |       0.720999 |   0.486326 |
| Bori_Aron_solution-1 |     0.55897  |       1.40388  |   0.563162 |
| k-d_tree_polars      |     0.562928 |       0.845271 |   0.881377 |
| k-d_tree_sklearn     |     0.572775 |       2.00692  |   0.886354 |
| barab-szabi-1        |     0.560383 |       0.859763 |   0.924091 |
| k-d_tree_pandas      |     0.57246  |       0.735584 |   1.15364  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562356 |        5.62484 |   0.771232 |
| Bori_Aron_solution-1 |     0.558293 |       11.1105  |   0.880831 |
| k-d_tree_sklearn     |     0.564148 |       16.6575  |   1.0536   |
| barab-szabi-1        |     0.562588 |        4.83087 |   6.91032  |
| k-d_tree_polars      |     0.563806 |        4.91232 |   7.15889  |
| k-d_tree_pandas      |     0.567011 |        3.87459 |   7.38216  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.723632 |        74.3686 |    3.87107 |
| k-d_tree_sklearn     |     0.617543 |       235.846  |    4.23296 |
| Bori_Aron_solution-1 |     0.550019 |       158.375  |   14.9575  |