# 2024-10-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.57206  |       1e-06    |   0.3517   |
| barab-szabi-2        |     0.615385 |       0.382101 |   0.372911 |
| k-d_tree_polars      |     0.623624 |       0.397057 |   0.380413 |
| barab-szabi-1        |     0.614428 |       0.390256 |   0.381308 |
| Bori_Aron_solution-1 |     0.598237 |       0.522102 |   0.514927 |
| k-d_tree_pandas      |     0.609346 |       0.373887 |   0.515027 |
| k-d_tree_sklearn     |    10.3235   |       1.04617  |   0.971775 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610485 |       0.38139  |   0.378861 |
| k-d_tree_polars      |     0.611971 |       0.402718 |   0.385678 |
| barab-szabi-1        |     0.617232 |       0.406022 |   0.38994  |
| Bori_Aron_solution-1 |     0.621987 |       0.51816  |   0.516965 |
| k-d_tree_pandas      |     0.607515 |       0.378543 |   0.523057 |
| k-d_tree_sklearn     |     0.620482 |       0.883092 |   0.95472  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615547 |       0.405954 |   0.403409 |
| k-d_tree_polars      |     0.619769 |       0.426224 |   0.413744 |
| barab-szabi-1        |     0.6263   |       0.465372 |   0.425545 |
| Bori_Aron_solution-1 |     0.61451  |       0.56981  |   0.530252 |
| k-d_tree_pandas      |     0.618532 |       0.40839  |   0.579777 |
| k-d_tree_sklearn     |     0.620667 |       0.926729 |   0.995907 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608812 |       0.458604 |   0.416885 |
| k-d_tree_polars      |     0.612875 |       0.531497 |   0.510403 |
| barab-szabi-1        |     0.609838 |       0.539159 |   0.52318  |
| Bori_Aron_solution-1 |     0.606295 |       0.738218 |   0.531307 |
| k-d_tree_pandas      |     0.605708 |       0.47686  |   0.699533 |
| k-d_tree_sklearn     |     0.621144 |       1.1509   |   1.0235   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608815 |       0.700302 |   0.454525 |
| Bori_Aron_solution-1 |     0.605343 |       1.37593  |   0.55673  |
| k-d_tree_polars      |     0.608429 |       0.857383 |   0.856833 |
| barab-szabi-1        |     0.612275 |       0.848626 |   0.893602 |
| k-d_tree_sklearn     |     0.615974 |       1.95746  |   1.1196   |
| k-d_tree_pandas      |     0.608984 |       0.742744 |   1.13633  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.639964 |        5.41392 |   0.750008 |
| Bori_Aron_solution-1 |     0.611665 |       10.9758  |   0.826306 |
| k-d_tree_sklearn     |     0.613105 |       15.9504  |   1.24676  |
| barab-szabi-1        |     0.62966  |        4.8619  |   6.6878   |
| k-d_tree_polars      |     0.614064 |        4.90836 |   6.97052  |
| k-d_tree_pandas      |     0.631314 |        3.90778 |   7.14861  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.653811 |        73.5933 |    3.14153 |
| k-d_tree_sklearn     |     0.625393 |       239.889  |    4.27874 |
| Bori_Aron_solution-1 |     0.621445 |       157.578  |   16.3172  |