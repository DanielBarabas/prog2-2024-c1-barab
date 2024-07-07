# 2024-07-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.611743 |       0.443844 |   0.430299 |
| barab-szabi-2        |     0.639473 |       0.446233 |   0.434797 |
| solution-1           |     9.86771  |       1e-06    |   0.498225 |
| barab-szabi-1        |     0.69502  |       0.50761  |   0.516043 |
| Bori_Aron_solution-1 |     0.618851 |       0.611612 |   0.586519 |
| k-d_tree_pandas      |     9.10777  |       0.474142 |   0.693906 |
| k-d_tree_sklearn     |     3.39796  |       1.07255  |   0.78046  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.72459  |       0.542429 |   0.508737 |
| k-d_tree_polars      |     0.732622 |       0.548484 |   0.509665 |
| barab-szabi-2        |     0.718831 |       0.50325  |   0.512516 |
| k-d_tree_pandas      |     0.724594 |       0.51259  |   0.694094 |
| Bori_Aron_solution-1 |     0.707583 |       0.700341 |   0.706477 |
| k-d_tree_sklearn     |     0.735133 |       1.18867  |   0.93637  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.752869 |       0.529474 |   0.532092 |
| barab-szabi-1        |     0.726716 |       0.574906 |   0.542377 |
| k-d_tree_polars      |     0.721006 |       0.578096 |   0.557214 |
| Bori_Aron_solution-1 |     0.721484 |       0.793304 |   0.703247 |
| k-d_tree_pandas      |     0.738256 |       0.539668 |   0.754205 |
| k-d_tree_sklearn     |     0.736104 |       1.26507  |   0.971954 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60176  |       0.5134   |   0.475371 |
| k-d_tree_polars      |     0.654361 |       0.607951 |   0.555208 |
| barab-szabi-1        |     0.61906  |       0.584169 |   0.577491 |
| Bori_Aron_solution-1 |     0.606566 |       0.80294  |   0.615208 |
| k-d_tree_pandas      |     0.66868  |       0.531469 |   0.781804 |
| k-d_tree_sklearn     |     0.619471 |       1.27677  |   0.892064 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.72558  |       0.783181 |   0.556196 |
| Bori_Aron_solution-1 |     0.718616 |       1.6513   |   0.749115 |
| k-d_tree_sklearn     |     0.646868 |       2.21335  |   0.979806 |
| barab-szabi-1        |     0.623686 |       0.89356  |   0.994524 |
| k-d_tree_polars      |     0.719313 |       1.00096  |   1.09213  |
| k-d_tree_pandas      |     0.61212  |       0.880625 |   1.41207  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555532 |        5.36084 |   0.7754   |
| Bori_Aron_solution-1 |     0.55325  |       10.6766  |   0.857763 |
| k-d_tree_sklearn     |     0.56955  |       15.9477  |   1.05326  |
| barab-szabi-1        |     0.554957 |        4.83608 |   6.46253  |
| k-d_tree_polars      |     0.559034 |        4.82553 |   6.49827  |
| k-d_tree_pandas      |     0.620057 |        3.87528 |   6.91844  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.742245 |        73.6096 |    3.77642 |
| k-d_tree_sklearn     |     0.628035 |       229.139  |    4.32005 |
| Bori_Aron_solution-1 |     0.550193 |       147.819  |   17.2781  |