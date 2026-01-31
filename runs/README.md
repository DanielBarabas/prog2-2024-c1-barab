# 2026-01-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.514092 |       0.487509 |   0.430115 |
| barab-szabi-1        |     0.525047 |       0.454571 |   0.437843 |
| k-d_tree_polars      |     0.533657 |       0.417259 |   0.441765 |
| solution-1           |     8.00367  |       1e-06    |   0.446959 |
| Bori_Aron_solution-1 |     0.515329 |       0.602829 |   0.562837 |
| k-d_tree_pandas      |     8.92342  |       0.412539 |   0.674833 |
| k-d_tree_sklearn     |     3.16162  |       1.08975  |   1.07527  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527529 |       0.457391 |   0.449503 |
| barab-szabi-1        |     0.530576 |       0.426366 |   0.453188 |
| k-d_tree_polars      |     0.536936 |       0.434738 |   0.46359  |
| k-d_tree_pandas      |     0.534503 |       0.404509 |   0.568771 |
| Bori_Aron_solution-1 |     0.543395 |       0.599612 |   0.576089 |
| k-d_tree_sklearn     |     0.535043 |       0.976653 |   1.09933  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537532 |       0.4655   |   0.462623 |
| barab-szabi-1        |     0.535442 |       0.435653 |   0.467102 |
| k-d_tree_polars      |     0.530002 |       0.438406 |   0.478749 |
| Bori_Aron_solution-1 |     0.516014 |       0.595302 |   0.544496 |
| k-d_tree_pandas      |     0.534861 |       0.426678 |   0.614228 |
| k-d_tree_sklearn     |     0.539813 |       1.08968  |   1.09717  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.526787 |       0.51356  |   0.480306 |
| k-d_tree_polars      |     0.521597 |       0.56589  |   0.5719   |
| barab-szabi-1        |     0.532375 |       0.55727  |   0.577406 |
| Bori_Aron_solution-1 |     0.528638 |       0.800991 |   0.588045 |
| k-d_tree_pandas      |     0.522529 |       0.500484 |   0.737251 |
| k-d_tree_sklearn     |     0.535228 |       1.27703  |   1.1479   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531373 |       0.743484 |   0.516365 |
| Bori_Aron_solution-1 |     0.519582 |       1.46561  |   0.589419 |
| k-d_tree_polars      |     0.534593 |       0.926757 |   0.927071 |
| barab-szabi-1        |     0.525568 |       0.938678 |   0.982105 |
| k-d_tree_pandas      |     0.540234 |       0.835129 |   1.20222  |
| k-d_tree_sklearn     |     0.529888 |       2.16005  |   1.24373  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534873 |        5.12364 |   0.742738 |
| Bori_Aron_solution-1 |     0.529135 |       11.0717  |   0.844821 |
| k-d_tree_sklearn     |     0.526797 |       17.0081  |   1.33251  |
| barab-szabi-1        |     0.535222 |        5.40507 |   6.56656  |
| k-d_tree_polars      |     0.525871 |        5.59723 |   6.68959  |
| k-d_tree_pandas      |     0.543    |        4.44944 |   7.1103   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536882 |        69.5283 |    2.64378 |
| k-d_tree_sklearn     |     0.537672 |       230.252  |    4.01987 |
| Bori_Aron_solution-1 |     0.6683   |       146.16   |   17.8687  |