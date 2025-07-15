# 2025-07-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.66727  |       0.543701 |   0.421152 |
| k-d_tree_polars      |     0.555457 |       0.402425 |   0.424282 |
| barab-szabi-1        |     0.540383 |       0.409333 |   0.431773 |
| solution-1           |     7.7467   |       1e-06    |   0.432096 |
| Bori_Aron_solution-1 |     0.538864 |       0.549168 |   0.540937 |
| k-d_tree_pandas      |     0.547515 |       0.39486  |   0.544019 |
| k-d_tree_sklearn     |     3.05025  |       1.14097  |   1.06359  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556385 |       0.426358 |   0.424747 |
| barab-szabi-1        |     0.58111  |       0.413491 |   0.426892 |
| k-d_tree_polars      |     0.559116 |       0.422781 |   0.440602 |
| Bori_Aron_solution-1 |     0.544028 |       0.554163 |   0.540911 |
| k-d_tree_pandas      |     0.553648 |       0.402095 |   0.586268 |
| k-d_tree_sklearn     |     0.566505 |       0.970302 |   1.07804  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556914 |       0.433695 |   0.43727  |
| barab-szabi-1        |     0.559338 |       0.43412  |   0.45595  |
| k-d_tree_polars      |     0.558757 |       0.432338 |   0.458843 |
| Bori_Aron_solution-1 |     0.551172 |       0.606889 |   0.546916 |
| k-d_tree_pandas      |     0.565087 |       0.408342 |   0.606297 |
| k-d_tree_sklearn     |     0.556406 |       1.03764  |   1.08672  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554871 |       0.50089  |   0.463493 |
| k-d_tree_polars      |     0.556074 |       0.547399 |   0.551063 |
| barab-szabi-1        |     0.567689 |       0.553611 |   0.576284 |
| Bori_Aron_solution-1 |     0.551619 |       0.770896 |   0.582814 |
| k-d_tree_pandas      |     0.554017 |       0.495395 |   0.742222 |
| k-d_tree_sklearn     |     0.561887 |       1.23048  |   1.13476  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557594 |       0.740765 |   0.494327 |
| Bori_Aron_solution-1 |     0.549958 |       1.41861  |   0.594723 |
| k-d_tree_polars      |     0.560946 |       0.895576 |   0.924597 |
| barab-szabi-1        |     0.563284 |       0.890069 |   0.944149 |
| k-d_tree_pandas      |     0.565658 |       0.765979 |   1.18312  |
| k-d_tree_sklearn     |     0.56579  |       2.09494  |   1.21178  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565166 |        5.26186 |   0.740155 |
| Bori_Aron_solution-1 |     0.552892 |       10.7013  |   0.83748  |
| k-d_tree_sklearn     |     0.556173 |       16.1252  |   1.29365  |
| barab-szabi-1        |     0.556822 |        4.99093 |   6.5361   |
| k-d_tree_polars      |     0.556137 |        5.0331  |   6.61495  |
| k-d_tree_pandas      |     0.555566 |        3.97339 |   7.00833  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555049 |         73.638 |    2.72638 |
| k-d_tree_sklearn     |     0.685014 |        233.112 |    3.91589 |
| Bori_Aron_solution-1 |     0.563362 |        142.162 |   17.7689  |