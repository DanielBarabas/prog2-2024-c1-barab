# 2025-07-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563357 |       0.446699 |   0.432274 |
| k-d_tree_polars      |     0.5747   |       0.414914 |   0.44147  |
| solution-1           |     7.65011  |       1e-06    |   0.451684 |
| barab-szabi-1        |     0.569359 |       0.424731 |   0.47104  |
| Bori_Aron_solution-1 |     0.555511 |       0.548861 |   0.553209 |
| k-d_tree_pandas      |     0.574991 |       0.398549 |   0.573071 |
| k-d_tree_sklearn     |    10.478    |       1.47504  |   1.13099  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.565951 |       0.437015 |   0.435011 |
| barab-szabi-1        |     0.563946 |       0.421664 |   0.444495 |
| barab-szabi-2        |     0.551736 |       0.420525 |   0.464558 |
| Bori_Aron_solution-1 |     0.549715 |       0.563903 |   0.5465   |
| k-d_tree_pandas      |     0.560408 |       0.394079 |   0.558239 |
| k-d_tree_sklearn     |     0.565725 |       0.978787 |   1.07533  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580446 |       0.44905  |   0.449928 |
| k-d_tree_polars      |     0.581414 |       0.449908 |   0.467963 |
| barab-szabi-1        |     0.589089 |       0.454942 |   0.492604 |
| Bori_Aron_solution-1 |     0.57798  |       0.614223 |   0.575288 |
| k-d_tree_pandas      |     0.572303 |       0.42282  |   0.617415 |
| k-d_tree_sklearn     |     0.564515 |       1.07286  |   1.1467   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566373 |       0.520543 |   0.486807 |
| k-d_tree_polars      |     0.567086 |       0.562711 |   0.570301 |
| Bori_Aron_solution-1 |     0.570636 |       0.790494 |   0.577846 |
| barab-szabi-1        |     0.575005 |       0.553334 |   0.579374 |
| k-d_tree_pandas      |     0.574334 |       0.508128 |   0.768668 |
| k-d_tree_sklearn     |     0.581171 |       1.27801  |   1.20433  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.576938 |       0.772829 |   0.58091  |
| Bori_Aron_solution-1 |     0.583195 |       1.45749  |   0.627409 |
| k-d_tree_polars      |     0.568211 |       0.90331  |   0.926863 |
| barab-szabi-1        |     0.576762 |       0.893361 |   0.967669 |
| k-d_tree_pandas      |     0.569097 |       0.784528 |   1.21051  |
| k-d_tree_sklearn     |     0.57299  |       2.13166  |   1.22998  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577203 |        5.53955 |   0.74915  |
| Bori_Aron_solution-1 |     0.574391 |       11.4365  |   0.889886 |
| k-d_tree_sklearn     |     0.589482 |       16.8211  |   1.37882  |
| barab-szabi-1        |     0.567069 |        5.06304 |   6.76184  |
| k-d_tree_polars      |     0.565212 |        5.01122 |   7.1051   |
| k-d_tree_pandas      |     0.584062 |        4.01842 |   7.3503   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.576042 |        73.2489 |    2.67237 |
| k-d_tree_sklearn     |     0.595915 |       242.641  |    4.01604 |
| Bori_Aron_solution-1 |     0.561913 |       152.048  |   17.3955  |