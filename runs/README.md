# 2026-08-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.5169   |       1e-06    |   0.373366 |
| barab-szabi-2        |     4.26672  |       0.472296 |   0.414776 |
| barab-szabi-1        |     0.417133 |       0.388833 |   0.426714 |
| k-d_tree_polars      |     0.421396 |       0.397573 |   0.436478 |
| Bori_Aron_solution-1 |     4.2967   |       0.550956 |   0.487089 |
| k-d_tree_pandas      |     0.414506 |       0.35853  |   0.506943 |
| k-d_tree_sklearn     |     2.56298  |       1.00773  |   0.986243 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.430054 |       0.422946 |   0.420941 |
| barab-szabi-1        |     0.429117 |       0.403642 |   0.430192 |
| k-d_tree_polars      |     0.43274  |       0.394851 |   0.433764 |
| Bori_Aron_solution-1 |     0.416774 |       0.528922 |   0.5165   |
| k-d_tree_pandas      |     0.428966 |       0.367663 |   0.532329 |
| k-d_tree_sklearn     |     0.436001 |       0.950726 |   1.01802  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.43069  |       0.441644 |   0.431531 |
| k-d_tree_polars      |     0.432473 |       0.427671 |   0.455439 |
| barab-szabi-1        |     0.427699 |       0.416485 |   0.457605 |
| Bori_Aron_solution-1 |     0.423915 |       0.5603   |   0.533345 |
| k-d_tree_pandas      |     0.422512 |       0.389428 |   0.559604 |
| k-d_tree_sklearn     |     0.430782 |       0.984113 |   1.0376   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.42314  |       0.489663 |   0.453053 |
| Bori_Aron_solution-1 |     0.424521 |       0.707757 |   0.519995 |
| k-d_tree_polars      |     0.430079 |       0.546228 |   0.532418 |
| barab-szabi-1        |     0.43184  |       0.533696 |   0.544475 |
| k-d_tree_pandas      |     0.435809 |       0.464702 |   0.669797 |
| k-d_tree_sklearn     |     0.426524 |       1.189    |   1.063    |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.431159 |       0.700928 |   0.52385  |
| Bori_Aron_solution-1 |     0.417754 |       1.30044  |   0.557292 |
| k-d_tree_polars      |     0.423728 |       0.845281 |   0.844636 |
| barab-szabi-1        |     0.437432 |       0.843759 |   0.883545 |
| k-d_tree_pandas      |     0.422543 |       0.719129 |   1.06614  |
| k-d_tree_sklearn     |     0.424895 |       1.92335  |   1.10794  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.430127 |        4.86008 |   0.702517 |
| Bori_Aron_solution-1 |     0.428316 |        9.79798 |   0.871263 |
| k-d_tree_sklearn     |     0.427157 |       14.1368  |   1.21426  |
| barab-szabi-1        |     0.418158 |        4.75254 |   6.05108  |
| k-d_tree_polars      |     0.418685 |        4.70744 |   6.10511  |
| k-d_tree_pandas      |     0.434885 |        3.73246 |   6.48079  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579249 |        68.5419 |    2.68345 |
| k-d_tree_sklearn     |     0.526145 |       179.183  |    3.95298 |
| Bori_Aron_solution-1 |     0.413676 |       139.248  |   17.0645  |