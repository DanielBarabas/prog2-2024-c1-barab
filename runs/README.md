# 2026-04-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.463694 |       0.40215  |   0.43464  |
| barab-szabi-2        |     9.08972  |       0.938432 |   0.440655 |
| barab-szabi-1        |     0.452192 |       0.402338 |   0.446091 |
| k-d_tree_pandas      |     0.460734 |       0.382627 |   0.550475 |
| Bori_Aron_solution-1 |     0.454909 |       0.552279 |   0.568321 |
| solution-1           |     8.35977  |       1e-06    |   0.720765 |
| k-d_tree_sklearn     |     3.00819  |       1.35034  |   1.0825   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.457732 |       0.441863 |   0.433201 |
| barab-szabi-1        |     0.46535  |       0.419007 |   0.443547 |
| k-d_tree_polars      |     0.498194 |       0.428553 |   0.469527 |
| Bori_Aron_solution-1 |     0.48448  |       0.585313 |   0.590183 |
| k-d_tree_pandas      |     0.490265 |       0.402085 |   0.597796 |
| k-d_tree_sklearn     |     0.466974 |       0.995469 |   1.12403  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.494034 |       0.473538 |   0.46436  |
| k-d_tree_polars      |     0.467078 |       0.449671 |   0.46519  |
| barab-szabi-1        |     0.477198 |       0.446314 |   0.480986 |
| Bori_Aron_solution-1 |     0.474471 |       0.600346 |   0.554601 |
| k-d_tree_pandas      |     0.466882 |       0.414873 |   0.614407 |
| k-d_tree_sklearn     |     0.469393 |       1.05078  |   1.20128  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464977 |       0.52545  |   0.481162 |
| barab-szabi-1        |     0.464911 |       0.568383 |   0.580092 |
| k-d_tree_polars      |     0.477347 |       0.585348 |   0.588077 |
| Bori_Aron_solution-1 |     0.468375 |       0.823673 |   0.596256 |
| k-d_tree_pandas      |     0.477265 |       0.52304  |   0.756663 |
| k-d_tree_sklearn     |     0.468885 |       1.29145  |   1.18176  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475039 |       0.750382 |   0.523706 |
| Bori_Aron_solution-1 |     0.47162  |       1.51376  |   0.603061 |
| k-d_tree_polars      |     0.468958 |       0.94808  |   0.940372 |
| barab-szabi-1        |     0.481182 |       0.932892 |   0.966294 |
| k-d_tree_pandas      |     0.462023 |       0.828821 |   1.22126  |
| k-d_tree_sklearn     |     0.466619 |       2.24737  |   1.31337  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.457758 |        5.60479 |   0.81301  |
| Bori_Aron_solution-1 |     0.470448 |       11.8504  |   0.840905 |
| k-d_tree_sklearn     |     0.473234 |       19.4864  |   1.36328  |
| k-d_tree_polars      |     0.462659 |        5.54204 |   6.80848  |
| k-d_tree_pandas      |     0.465828 |        4.42758 |   7.13818  |
| barab-szabi-1        |     0.474991 |        5.63718 |   7.25974  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.45576  |        75.9315 |    2.84136 |
| k-d_tree_sklearn     |     0.466454 |       247.236  |    3.85533 |
| Bori_Aron_solution-1 |     0.45694  |       154.471  |   23.493   |