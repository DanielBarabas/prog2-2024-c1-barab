# 2025-05-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.501638 |       0.398289 |   0.409048 |
| barab-szabi-2        |     0.500982 |       0.408156 |   0.411454 |
| Bori_Aron_solution-1 |     0.495879 |       0.539119 |   0.537436 |
| k-d_tree_pandas      |     0.503976 |       0.381833 |   0.544351 |
| solution-1           |     7.50327  |       1e-06    |   0.640078 |
| k-d_tree_polars      |     7.76691  |       0.490372 |   0.711291 |
| k-d_tree_sklearn     |     3.03494  |       1.1298   |   1.01445  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.517122 |       0.405486 |   0.413154 |
| barab-szabi-2        |     0.513015 |       0.411128 |   0.413992 |
| barab-szabi-1        |     0.516912 |       0.403118 |   0.414687 |
| Bori_Aron_solution-1 |     0.508973 |       0.546835 |   0.540359 |
| k-d_tree_pandas      |     0.539136 |       0.385604 |   0.551009 |
| k-d_tree_sklearn     |     0.519575 |       0.943189 |   1.02114  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.515927 |       0.416673 |   0.426977 |
| barab-szabi-1        |     0.516484 |       0.428426 |   0.446524 |
| k-d_tree_polars      |     0.516319 |       0.429061 |   0.450954 |
| k-d_tree_pandas      |     0.521737 |       0.399863 |   0.594188 |
| Bori_Aron_solution-1 |     0.513235 |       0.577703 |   0.651823 |
| k-d_tree_sklearn     |     0.520689 |       0.985516 |   1.06006  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52046  |       0.480993 |   0.449435 |
| k-d_tree_polars      |     0.518862 |       0.536181 |   0.540749 |
| barab-szabi-1        |     0.515942 |       0.539701 |   0.549928 |
| Bori_Aron_solution-1 |     0.515505 |       0.756143 |   0.557287 |
| k-d_tree_pandas      |     0.516091 |       0.480757 |   0.72573  |
| k-d_tree_sklearn     |     0.518681 |       1.20901  |   1.11144  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.514627 |       0.720613 |   0.481821 |
| Bori_Aron_solution-1 |     0.509646 |       1.3912   |   0.578368 |
| k-d_tree_polars      |     0.518027 |       0.882858 |   0.888379 |
| barab-szabi-1        |     0.526691 |       0.877409 |   0.924481 |
| k-d_tree_pandas      |     0.519397 |       0.7535   |   1.16407  |
| k-d_tree_sklearn     |     0.519184 |       2.02309  |   1.19933  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.516585 |        4.9997  |   0.709711 |
| Bori_Aron_solution-1 |     0.512598 |       10.3549  |   0.878313 |
| k-d_tree_sklearn     |     0.525447 |       15.5019  |   1.37177  |
| k-d_tree_polars      |     0.51864  |        5.04158 |   6.27629  |
| barab-szabi-1        |     0.516787 |        5.06545 |   6.32574  |
| k-d_tree_pandas      |     0.519212 |        3.9853  |   6.77501  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.521464 |        73.2327 |    2.6056  |
| k-d_tree_sklearn     |     0.810881 |       230.268  |    4.28766 |
| Bori_Aron_solution-1 |     0.525615 |       141.117  |   17.9551  |