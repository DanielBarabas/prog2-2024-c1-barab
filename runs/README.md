# 2026-07-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.10719  |       1e-06    |   0.323887 |
| barab-szabi-2        |     0.353532 |       0.34462  |   0.344732 |
| k-d_tree_polars      |     0.363386 |       0.333472 |   0.360666 |
| Bori_Aron_solution-1 |     0.352565 |       0.428015 |   0.427283 |
| k-d_tree_pandas      |     0.372827 |       0.304629 |   0.435373 |
| barab-szabi-1        |     9.08441  |       0.398216 |   0.508703 |
| k-d_tree_sklearn     |     3.27806  |       0.937397 |   0.847344 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.361873 |       0.352207 |   0.357537 |
| barab-szabi-1        |     0.371946 |       0.337761 |   0.357925 |
| k-d_tree_polars      |     0.373487 |       0.343225 |   0.36734  |
| k-d_tree_pandas      |     0.36428  |       0.306666 |   0.435759 |
| Bori_Aron_solution-1 |     0.365141 |       0.449251 |   0.435898 |
| k-d_tree_sklearn     |     0.370755 |       0.794498 |   0.843954 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.369601 |       0.367562 |   0.366418 |
| k-d_tree_polars      |     0.363789 |       0.36651  |   0.375918 |
| barab-szabi-1        |     0.380193 |       0.363027 |   0.385988 |
| Bori_Aron_solution-1 |     0.363688 |       0.47409  |   0.435765 |
| k-d_tree_pandas      |     0.367929 |       0.326009 |   0.468805 |
| k-d_tree_sklearn     |     0.371547 |       0.84259  |   0.878313 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.367158 |       0.41034  |   0.428446 |
| k-d_tree_polars      |     0.369527 |       0.458744 |   0.447415 |
| Bori_Aron_solution-1 |     0.369743 |       0.629309 |   0.450559 |
| barab-szabi-1        |     0.362778 |       0.454744 |   0.460123 |
| k-d_tree_pandas      |     0.368977 |       0.407917 |   0.576151 |
| k-d_tree_sklearn     |     0.365141 |       1.03817  |   0.926206 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.364322 |       0.617187 |   0.424799 |
| Bori_Aron_solution-1 |     0.3624   |       1.15724  |   0.475969 |
| k-d_tree_polars      |     0.371745 |       0.73368  |   0.753458 |
| barab-szabi-1        |     0.365439 |       0.706408 |   0.799364 |
| k-d_tree_sklearn     |     0.374303 |       1.69927  |   0.927582 |
| k-d_tree_pandas      |     0.367509 |       0.608847 |   0.929672 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.364591 |        4.69121 |   0.632856 |
| Bori_Aron_solution-1 |     0.364465 |        9.12507 |   0.662404 |
| k-d_tree_sklearn     |     0.368693 |       15.0203  |   0.997936 |
| k-d_tree_polars      |     0.364618 |        4.58827 |   6.15006  |
| barab-szabi-1        |     0.362681 |        4.61484 |   6.18938  |
| k-d_tree_pandas      |     0.370533 |        3.1877  |   6.43783  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.366518 |        71.4491 |    2.53841 |
| k-d_tree_sklearn     |     1.02371  |       226.018  |    3.32914 |
| Bori_Aron_solution-1 |     0.363683 |       147.775  |   26.5423  |