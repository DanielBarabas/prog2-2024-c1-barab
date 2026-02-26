# 2026-02-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48018  |       0.430072 |   0.430423 |
| k-d_tree_polars      |     0.56941  |       0.457533 |   0.43784  |
| solution-1           |    11.8206   |       1e-06    |   0.53662  |
| Bori_Aron_solution-1 |     0.475297 |       0.547625 |   0.54857  |
| k-d_tree_pandas      |     0.482275 |       0.389832 |   0.549917 |
| barab-szabi-1        |     8.04422  |       0.525406 |   0.685453 |
| k-d_tree_sklearn     |     3.33239  |       1.26189  |   1.07209  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492021 |       0.44188  |   0.440041 |
| k-d_tree_polars      |     0.49256  |       0.416485 |   0.441544 |
| barab-szabi-1        |     0.492022 |       0.411949 |   0.446781 |
| Bori_Aron_solution-1 |     0.489067 |       0.567613 |   0.555548 |
| k-d_tree_pandas      |     0.502091 |       0.395891 |   0.575709 |
| k-d_tree_sklearn     |     0.511614 |       0.991278 |   1.08096  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49204  |       0.463003 |   0.444619 |
| k-d_tree_polars      |     0.49139  |       0.438119 |   0.471581 |
| barab-szabi-1        |     0.502203 |       0.44327  |   0.472756 |
| Bori_Aron_solution-1 |     0.486613 |       0.601352 |   0.550747 |
| k-d_tree_pandas      |     0.495159 |       0.433471 |   0.612452 |
| k-d_tree_sklearn     |     0.49976  |       1.05044  |   1.13395  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.499826 |       0.511177 |   0.483758 |
| k-d_tree_polars      |     0.503642 |       0.57249  |   0.574189 |
| Bori_Aron_solution-1 |     0.489698 |       0.805486 |   0.576796 |
| barab-szabi-1        |     0.514693 |       0.567495 |   0.578154 |
| k-d_tree_pandas      |     0.504226 |       0.506518 |   0.756045 |
| k-d_tree_sklearn     |     0.506836 |       1.31671  |   1.18582  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.500695 |       0.746688 |   0.518845 |
| Bori_Aron_solution-1 |     0.496973 |       1.47744  |   0.601213 |
| k-d_tree_polars      |     0.502113 |       0.952253 |   0.938515 |
| barab-szabi-1        |     0.497772 |       0.931605 |   0.973409 |
| k-d_tree_pandas      |     0.497818 |       0.830799 |   1.21594  |
| k-d_tree_sklearn     |     0.507398 |       2.20019  |   1.27602  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495783 |        5.31829 |   0.773664 |
| Bori_Aron_solution-1 |     0.502922 |       11.2263  |   0.83649  |
| k-d_tree_sklearn     |     0.501241 |       17.027   |   1.30454  |
| k-d_tree_polars      |     0.492343 |        5.50611 |   6.84848  |
| barab-szabi-1        |     0.511124 |        5.43942 |   6.89925  |
| k-d_tree_pandas      |     0.500157 |        4.48093 |   7.15759  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.490091 |        73.9054 |    2.7807  |
| k-d_tree_sklearn     |     0.903348 |       243.15   |    4.06954 |
| Bori_Aron_solution-1 |     0.51641  |       148.472  |   21.757   |