# 2025-05-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.546159 |       0.448659 |   0.42448  |
| barab-szabi-2        |     0.533337 |       0.45308  |   0.446728 |
| solution-1           |     8.13759  |       1e-06    |   0.533098 |
| k-d_tree_pandas      |     0.555359 |       0.424906 |   0.59505  |
| Bori_Aron_solution-1 |     0.534074 |       0.610745 |   0.605354 |
| k-d_tree_polars      |     8.1808   |       0.534464 |   0.681594 |
| k-d_tree_sklearn     |     3.19807  |       1.35717  |   1.17813  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.558863 |       0.441908 |   0.442977 |
| barab-szabi-2        |     0.541065 |       0.471406 |   0.460253 |
| k-d_tree_polars      |     0.556889 |       0.434366 |   0.460991 |
| Bori_Aron_solution-1 |     0.591675 |       0.579023 |   0.563048 |
| k-d_tree_pandas      |     0.528336 |       0.391432 |   0.568979 |
| k-d_tree_sklearn     |     0.536881 |       0.9633   |   1.05458  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546411 |       0.43013  |   0.441702 |
| k-d_tree_polars      |     0.525804 |       0.440102 |   0.452173 |
| barab-szabi-1        |     0.578455 |       0.44945  |   0.471796 |
| Bori_Aron_solution-1 |     0.525066 |       0.632748 |   0.549845 |
| k-d_tree_pandas      |     0.523486 |       0.408641 |   0.606655 |
| k-d_tree_sklearn     |     0.538837 |       1.04079  |   1.16547  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534543 |       0.498331 |   0.461247 |
| k-d_tree_polars      |     0.531145 |       0.545726 |   0.547466 |
| barab-szabi-1        |     0.534244 |       0.559686 |   0.562181 |
| Bori_Aron_solution-1 |     0.522441 |       0.779185 |   0.569975 |
| k-d_tree_pandas      |     0.525478 |       0.498749 |   0.752917 |
| k-d_tree_sklearn     |     0.533533 |       1.24608  |   1.13148  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565805 |       0.791501 |   0.622886 |
| Bori_Aron_solution-1 |     0.529844 |       1.43098  |   0.672891 |
| k-d_tree_polars      |     0.528855 |       0.906253 |   0.958771 |
| barab-szabi-1        |     0.538065 |       0.93696  |   0.967295 |
| k-d_tree_pandas      |     0.554736 |       0.77731  |   1.19439  |
| k-d_tree_sklearn     |     0.531288 |       2.26101  |   1.30473  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541251 |        5.61835 |   0.772079 |
| Bori_Aron_solution-1 |     0.565937 |       11.1507  |   0.942163 |
| k-d_tree_sklearn     |     0.564407 |       16.9007  |   1.31859  |
| k-d_tree_polars      |     0.555909 |        5.08841 |   6.69771  |
| barab-szabi-1        |     0.526333 |        4.95703 |   6.84048  |
| k-d_tree_pandas      |     0.569617 |        4.00577 |   7.25087  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532182 |        81.7234 |    2.84368 |
| k-d_tree_sklearn     |     0.662622 |       236.901  |    4.23688 |
| Bori_Aron_solution-1 |     0.559709 |       161.4    |   17.0023  |