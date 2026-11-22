# 2026-11-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.7287   |       1e-06    |   0.351779 |
| barab-szabi-2        |     0.457332 |       0.437794 |   0.419966 |
| k-d_tree_polars      |     0.485304 |       0.433454 |   0.435184 |
| barab-szabi-1        |     0.454221 |       0.418441 |   0.438174 |
| Bori_Aron_solution-1 |     4.5385   |       0.526831 |   0.486587 |
| k-d_tree_pandas      |     0.452494 |       0.38811  |   0.598667 |
| k-d_tree_sklearn     |     7.79874  |       1.01958  |   1.0801   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465065 |       0.44634  |   0.430662 |
| k-d_tree_polars      |     0.458712 |       0.431317 |   0.437779 |
| barab-szabi-1        |     0.456565 |       0.422386 |   0.454912 |
| Bori_Aron_solution-1 |     0.449028 |       0.547503 |   0.548297 |
| k-d_tree_pandas      |     0.460352 |       0.392982 |   0.555582 |
| k-d_tree_sklearn     |     0.461456 |       1.00035  |   1.12011  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.450188 |       0.453977 |   0.435578 |
| k-d_tree_polars      |     0.455543 |       0.450207 |   0.468242 |
| barab-szabi-1        |     0.453612 |       0.452374 |   0.469596 |
| Bori_Aron_solution-1 |     0.448826 |       0.593089 |   0.557448 |
| k-d_tree_pandas      |     0.453779 |       0.410218 |   0.602025 |
| k-d_tree_sklearn     |     0.463958 |       1.0347   |   1.10957  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.454073 |       0.52131  |   0.47326  |
| k-d_tree_polars      |     0.452545 |       0.567769 |   0.566069 |
| barab-szabi-1        |     0.457645 |       0.577267 |   0.577962 |
| Bori_Aron_solution-1 |     0.44516  |       0.776886 |   0.591578 |
| k-d_tree_pandas      |     0.456483 |       0.502594 |   0.733334 |
| k-d_tree_sklearn     |     0.465448 |       1.27592  |   1.14818  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.452725 |       0.774247 |   0.530859 |
| Bori_Aron_solution-1 |     0.450034 |       1.48617  |   0.609329 |
| k-d_tree_polars      |     0.479623 |       0.927749 |   0.93844  |
| barab-szabi-1        |     0.461111 |       0.913573 |   0.985899 |
| k-d_tree_pandas      |     0.452998 |       0.811282 |   1.20399  |
| k-d_tree_sklearn     |     0.455712 |       2.12246  |   1.24712  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.44925  |        5.433   |   0.909685 |
| Bori_Aron_solution-1 |     0.44977  |       11.3809  |   1.13041  |
| k-d_tree_sklearn     |     0.454005 |       16.7263  |   1.37828  |
| barab-szabi-1        |     0.460208 |        5.28262 |   7.08038  |
| k-d_tree_polars      |     0.452104 |        5.29196 |   7.13807  |
| k-d_tree_pandas      |     0.448064 |        4.35256 |   7.24754  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529574 |        74.2821 |    4.35057 |
| k-d_tree_sklearn     |     0.708973 |       237.45   |    4.47595 |
| Bori_Aron_solution-1 |     0.455872 |       152.188  |   21.7373  |