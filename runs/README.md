# 2025-04-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.560332 |       0.414338 |   0.411819 |
| solution-1           |     7.12835  |       1e-06    |   0.41189  |
| barab-szabi-2        |     0.55935  |       0.418408 |   0.414975 |
| barab-szabi-1        |     0.554867 |       0.409704 |   0.420849 |
| Bori_Aron_solution-1 |     0.558368 |       0.561209 |   0.558599 |
| k-d_tree_pandas      |     7.64875  |       0.452211 |   0.606523 |
| k-d_tree_sklearn     |     2.97974  |       1.00655  |   1.04926  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.574686 |       0.413977 |   0.420087 |
| k-d_tree_polars      |     0.572431 |       0.417603 |   0.42064  |
| barab-szabi-2        |     0.57626  |       0.414347 |   0.436717 |
| Bori_Aron_solution-1 |     0.594215 |       0.563292 |   0.549461 |
| k-d_tree_pandas      |     0.579959 |       0.404592 |   0.572903 |
| k-d_tree_sklearn     |     0.567967 |       0.963409 |   1.03357  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565925 |       0.442316 |   0.435843 |
| k-d_tree_polars      |     0.567424 |       0.438389 |   0.441192 |
| barab-szabi-1        |     0.566622 |       0.436667 |   0.44617  |
| Bori_Aron_solution-1 |     0.566267 |       0.597656 |   0.546237 |
| k-d_tree_pandas      |     0.563517 |       0.409228 |   0.598863 |
| k-d_tree_sklearn     |     0.579249 |       1.01109  |   1.06567  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566598 |       0.482908 |   0.452327 |
| k-d_tree_polars      |     0.564778 |       0.543435 |   0.53855  |
| barab-szabi-1        |     0.565296 |       0.536491 |   0.546422 |
| Bori_Aron_solution-1 |     0.55638  |       0.757235 |   0.565463 |
| k-d_tree_pandas      |     0.569526 |       0.481159 |   0.735132 |
| k-d_tree_sklearn     |     0.562816 |       1.2463   |   1.13656  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564137 |       0.728229 |   0.482624 |
| Bori_Aron_solution-1 |     0.592055 |       1.42117  |   0.602887 |
| k-d_tree_polars      |     0.571877 |       0.884585 |   0.896422 |
| barab-szabi-1        |     0.566924 |       0.882887 |   0.932649 |
| k-d_tree_pandas      |     0.564782 |       0.759596 |   1.21338  |
| k-d_tree_sklearn     |     0.575202 |       2.14741  |   1.2395   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565302 |        5.57684 |   0.779328 |
| Bori_Aron_solution-1 |     0.561786 |       11.0666  |   0.894582 |
| k-d_tree_sklearn     |     0.575413 |       16.7733  |   1.33402  |
| barab-szabi-1        |     0.561483 |        5.07564 |   6.78194  |
| k-d_tree_polars      |     0.577803 |        5.0742  |   6.9303   |
| k-d_tree_pandas      |     0.573208 |        3.98886 |   7.27363  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.717914 |        76.1475 |    2.94527 |
| k-d_tree_sklearn     |     0.636689 |       232.355  |    4.18051 |
| Bori_Aron_solution-1 |     0.55661  |       161.261  |   14.202   |