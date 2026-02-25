# 2026-02-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48386  |       0.44663  |   0.438174 |
| k-d_tree_polars      |     0.487763 |       0.410069 |   0.445604 |
| Bori_Aron_solution-1 |     0.488813 |       0.555449 |   0.557739 |
| k-d_tree_pandas      |     0.491385 |       0.391938 |   0.56637  |
| solution-1           |     7.38356  |       1e-06    |   0.606482 |
| barab-szabi-1        |     8.61289  |       0.482598 |   0.626882 |
| k-d_tree_sklearn     |     2.92483  |       1.13772  |   1.09581  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.500522 |       0.441554 |   0.442559 |
| barab-szabi-1        |     0.49822  |       0.417673 |   0.447718 |
| k-d_tree_polars      |     0.496881 |       0.417415 |   0.447965 |
| Bori_Aron_solution-1 |     0.489144 |       0.567664 |   0.555609 |
| k-d_tree_pandas      |     0.50277  |       0.40343  |   0.561363 |
| k-d_tree_sklearn     |     0.504193 |       1.01202  |   1.15628  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.499398 |       0.447649 |   0.471656 |
| barab-szabi-2        |     0.520196 |       0.459329 |   0.472026 |
| barab-szabi-1        |     0.520564 |       0.478745 |   0.495572 |
| Bori_Aron_solution-1 |     0.494432 |       0.605796 |   0.563373 |
| k-d_tree_pandas      |     0.514079 |       0.417892 |   0.607275 |
| k-d_tree_sklearn     |     0.498238 |       1.04262  |   1.10519  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498234 |       0.508833 |   0.478667 |
| Bori_Aron_solution-1 |     0.488388 |       0.789559 |   0.574517 |
| k-d_tree_polars      |     0.493263 |       0.565953 |   0.576402 |
| barab-szabi-1        |     0.500114 |       0.57232  |   0.585313 |
| k-d_tree_pandas      |     0.499471 |       0.508222 |   0.748753 |
| k-d_tree_sklearn     |     0.499855 |       1.28651  |   1.16087  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498502 |       0.741335 |   0.513781 |
| Bori_Aron_solution-1 |     0.494511 |       1.50287  |   0.618822 |
| k-d_tree_polars      |     0.512092 |       0.944736 |   0.926856 |
| barab-szabi-1        |     0.49775  |       0.938026 |   0.964456 |
| k-d_tree_pandas      |     0.498605 |       0.827332 |   1.20697  |
| k-d_tree_sklearn     |     0.503415 |       2.19857  |   1.25137  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49403  |        5.61253 |   0.824433 |
| Bori_Aron_solution-1 |     0.512027 |       11.3912  |   0.881377 |
| k-d_tree_sklearn     |     0.507632 |       17.1828  |   1.35671  |
| k-d_tree_polars      |     0.524679 |        5.52258 |   6.70317  |
| barab-szabi-1        |     0.502929 |        5.67103 |   6.71313  |
| k-d_tree_pandas      |     0.511189 |        4.47432 |   7.11854  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529172 |        76.8691 |    2.92172 |
| k-d_tree_sklearn     |     0.771651 |       254.308  |    4.19505 |
| Bori_Aron_solution-1 |     0.534168 |       152.948  |   21.0623  |