# 2025-11-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.526434 |       0.403839 |   0.428961 |
| barab-szabi-2        |     0.513186 |       0.530345 |   0.432405 |
| barab-szabi-1        |     0.529149 |       0.406949 |   0.434673 |
| solution-1           |     7.56256  |       1e-06    |   0.542397 |
| Bori_Aron_solution-1 |     0.523486 |       0.550928 |   0.550168 |
| k-d_tree_pandas      |     8.64049  |       0.457636 |   0.814526 |
| k-d_tree_sklearn     |     3.0492   |       1.33377  |   1.07097  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528513 |       0.42738  |   0.427299 |
| barab-szabi-1        |     0.534786 |       0.408693 |   0.436358 |
| k-d_tree_polars      |     0.530022 |       0.410599 |   0.440834 |
| Bori_Aron_solution-1 |     0.522605 |       0.56166  |   0.54397  |
| k-d_tree_pandas      |     0.534486 |       0.392339 |   0.556093 |
| k-d_tree_sklearn     |     0.536665 |       0.970249 |   1.07579  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527449 |       0.445488 |   0.441414 |
| k-d_tree_polars      |     0.530581 |       0.439121 |   0.459533 |
| barab-szabi-1        |     0.535222 |       0.439741 |   0.465921 |
| Bori_Aron_solution-1 |     0.523051 |       0.601672 |   0.553304 |
| k-d_tree_pandas      |     0.532804 |       0.416094 |   0.599096 |
| k-d_tree_sklearn     |     0.540919 |       1.03481  |   1.10027  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535836 |       0.50184  |   0.468566 |
| k-d_tree_polars      |     0.530808 |       0.561163 |   0.560354 |
| barab-szabi-1        |     0.527794 |       0.558489 |   0.56318  |
| Bori_Aron_solution-1 |     0.522558 |       0.781783 |   0.564879 |
| k-d_tree_pandas      |     0.53132  |       0.504721 |   0.740252 |
| k-d_tree_sklearn     |     0.532812 |       1.25158  |   1.13736  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.526524 |       0.738543 |   0.500427 |
| Bori_Aron_solution-1 |     0.525055 |       1.44536  |   0.582448 |
| k-d_tree_polars      |     0.527534 |       0.924272 |   0.902072 |
| barab-szabi-1        |     0.528696 |       0.931745 |   0.941252 |
| k-d_tree_pandas      |     0.529498 |       0.815363 |   1.17481  |
| k-d_tree_sklearn     |     0.535365 |       2.12105  |   1.21581  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529491 |        5.30744 |   0.733992 |
| Bori_Aron_solution-1 |     0.525779 |       11.2958  |   0.846855 |
| k-d_tree_sklearn     |     0.530128 |       16.9487  |   1.31794  |
| k-d_tree_polars      |     0.530189 |        5.45094 |   6.64252  |
| barab-szabi-1        |     0.527014 |        5.35547 |   6.68825  |
| k-d_tree_pandas      |     0.530872 |        4.4966  |   7.04995  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534114 |        74.6157 |    2.6696  |
| k-d_tree_sklearn     |     0.545953 |       232.626  |    4.53093 |
| Bori_Aron_solution-1 |     0.704066 |       155.449  |   18.543   |