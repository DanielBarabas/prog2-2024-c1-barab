# 2025-08-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.92818  |       1e-06    |   0.35976  |
| barab-szabi-2        |     8.17749  |       0.511752 |   0.421164 |
| k-d_tree_polars      |     0.526359 |       0.400514 |   0.426802 |
| barab-szabi-1        |     0.531068 |       0.406124 |   0.430722 |
| Bori_Aron_solution-1 |     0.518763 |       0.541788 |   0.541446 |
| k-d_tree_pandas      |     0.528784 |       0.384634 |   0.545113 |
| k-d_tree_sklearn     |     3.03561  |       1.06144  |   1.06579  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539022 |       0.425957 |   0.429124 |
| barab-szabi-1        |     0.539636 |       0.406154 |   0.429245 |
| k-d_tree_polars      |     0.541921 |       0.41066  |   0.429472 |
| Bori_Aron_solution-1 |     0.534521 |       0.552603 |   0.55073  |
| k-d_tree_pandas      |     0.537509 |       0.384996 |   0.553546 |
| k-d_tree_sklearn     |     0.54504  |       0.968075 |   1.06137  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539736 |       0.435664 |   0.43943  |
| k-d_tree_polars      |     0.537075 |       0.431453 |   0.451493 |
| barab-szabi-1        |     0.534057 |       0.431969 |   0.456878 |
| Bori_Aron_solution-1 |     0.536098 |       0.587582 |   0.544987 |
| k-d_tree_pandas      |     0.537417 |       0.402817 |   0.616618 |
| k-d_tree_sklearn     |     0.543888 |       1.02484  |   1.07507  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537885 |       0.502157 |   0.466971 |
| barab-szabi-1        |     0.546361 |       0.544693 |   0.560567 |
| k-d_tree_polars      |     0.537667 |       0.547576 |   0.562118 |
| Bori_Aron_solution-1 |     0.537464 |       0.764474 |   0.5705   |
| k-d_tree_pandas      |     0.540298 |       0.487457 |   0.732125 |
| k-d_tree_sklearn     |     0.540868 |       1.23322  |   1.14133  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539967 |       0.743184 |   0.499831 |
| Bori_Aron_solution-1 |     0.531807 |       1.3898   |   0.58511  |
| k-d_tree_polars      |     0.538808 |       0.873045 |   0.9001   |
| barab-szabi-1        |     0.54166  |       0.893363 |   0.931776 |
| k-d_tree_pandas      |     0.542939 |       0.7639   |   1.1632   |
| k-d_tree_sklearn     |     0.545162 |       2.04028  |   1.22223  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544025 |        5.1227  |   0.74087  |
| Bori_Aron_solution-1 |     0.53684  |       10.5093  |   0.840188 |
| k-d_tree_sklearn     |     0.547143 |       15.6743  |   1.28503  |
| k-d_tree_polars      |     0.53819  |        4.95882 |   6.39358  |
| barab-szabi-1        |     0.537372 |        5.05027 |   6.52489  |
| k-d_tree_pandas      |     0.550533 |        3.91374 |   6.77164  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547266 |        69.7813 |    2.66525 |
| k-d_tree_sklearn     |     1.17058  |       230.81   |    4.2759  |
| Bori_Aron_solution-1 |     0.539134 |       142.693  |   17.8089  |