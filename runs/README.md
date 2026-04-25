# 2026-04-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.45331  |       0.42117  |   0.417628 |
| k-d_tree_polars      |     0.455079 |       0.400229 |   0.426344 |
| barab-szabi-1        |     0.452998 |       0.404423 |   0.426507 |
| solution-1           |     7.72242  |       1e-06    |   0.525607 |
| Bori_Aron_solution-1 |     0.450517 |       0.532591 |   0.531151 |
| k-d_tree_pandas      |     0.45358  |       0.402304 |   0.531714 |
| k-d_tree_sklearn     |    10.4709   |       1.23267  |   1.05968  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.453894 |       0.424127 |   0.420398 |
| k-d_tree_polars      |     0.476682 |       0.40615  |   0.42906  |
| barab-szabi-1        |     0.452366 |       0.4065   |   0.42989  |
| Bori_Aron_solution-1 |     0.446694 |       0.543589 |   0.543179 |
| k-d_tree_pandas      |     0.458654 |       0.384017 |   0.543622 |
| k-d_tree_sklearn     |     0.457597 |       0.945071 |   1.04479  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456313 |       0.460599 |   0.436442 |
| barab-szabi-1        |     0.455465 |       0.434768 |   0.45698  |
| k-d_tree_polars      |     0.467775 |       0.447266 |   0.460629 |
| Bori_Aron_solution-1 |     0.447826 |       0.589572 |   0.553585 |
| k-d_tree_pandas      |     0.454217 |       0.404382 |   0.583866 |
| k-d_tree_sklearn     |     0.457061 |       1.02191  |   1.06132  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.453195 |       0.50137  |   0.468901 |
| Bori_Aron_solution-1 |     0.445778 |       0.778048 |   0.54775  |
| k-d_tree_polars      |     0.451705 |       0.551573 |   0.549154 |
| barab-szabi-1        |     0.452608 |       0.560631 |   0.565155 |
| k-d_tree_pandas      |     0.458056 |       0.492805 |   0.705438 |
| k-d_tree_sklearn     |     0.460011 |       1.24083  |   1.08886  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.452034 |       0.748159 |   0.50406  |
| Bori_Aron_solution-1 |     0.447427 |       1.4789   |   0.573735 |
| k-d_tree_polars      |     0.452486 |       0.908694 |   0.951649 |
| barab-szabi-1        |     0.457079 |       0.908999 |   0.990831 |
| k-d_tree_sklearn     |     0.454734 |       2.13119  |   1.15016  |
| k-d_tree_pandas      |     0.455636 |       0.776494 |   1.17813  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.451465 |        5.35446 |   0.701595 |
| Bori_Aron_solution-1 |     0.444192 |       11.2358  |   0.792742 |
| k-d_tree_sklearn     |     0.454519 |       16.786   |   1.21312  |
| k-d_tree_polars      |     0.454182 |        5.23444 |   7.24722  |
| barab-szabi-1        |     0.459508 |        5.22806 |   7.2617   |
| k-d_tree_pandas      |     0.451702 |        4.19233 |   7.65941  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.681172 |         75.395 |    2.4295  |
| k-d_tree_sklearn     |     0.457553 |        256.766 |    3.21481 |
| Bori_Aron_solution-1 |     0.455371 |        155.74  |   17.8994  |