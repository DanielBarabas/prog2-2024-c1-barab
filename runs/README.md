# 2026-02-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.430605 |       0.400851 |   0.39508  |
| k-d_tree_polars      |     0.429786 |       0.37293  |   0.397176 |
| solution-1           |     6.96718  |       1e-06    |   0.431792 |
| barab-szabi-1        |     8.04162  |       0.424037 |   0.453986 |
| k-d_tree_pandas      |     0.428625 |       0.355024 |   0.501438 |
| Bori_Aron_solution-1 |     0.417679 |       0.497402 |   0.504309 |
| k-d_tree_sklearn     |     2.71287  |       0.94075  |   0.963899 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.439512 |       0.405417 |   0.406119 |
| barab-szabi-1        |     0.441893 |       0.384024 |   0.406807 |
| k-d_tree_polars      |     0.444742 |       0.393087 |   0.415091 |
| Bori_Aron_solution-1 |     0.458098 |       0.537108 |   0.51788  |
| k-d_tree_pandas      |     0.43803  |       0.361793 |   0.518019 |
| k-d_tree_sklearn     |     0.443503 |       0.904952 |   0.978732 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.437687 |       0.416403 |   0.414747 |
| k-d_tree_polars      |     0.437721 |       0.403218 |   0.434283 |
| barab-szabi-1        |     0.444009 |       0.408262 |   0.434746 |
| Bori_Aron_solution-1 |     0.42772  |       0.544585 |   0.508016 |
| k-d_tree_pandas      |     0.448816 |       0.3815   |   0.553913 |
| k-d_tree_sklearn     |     0.446131 |       0.951942 |   0.986679 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.440915 |       0.467155 |   0.437292 |
| k-d_tree_polars      |     0.439532 |       0.537445 |   0.51551  |
| barab-szabi-1        |     0.440817 |       0.518178 |   0.520399 |
| Bori_Aron_solution-1 |     0.44044  |       0.706395 |   0.52525  |
| k-d_tree_pandas      |     0.443107 |       0.45471  |   0.664849 |
| k-d_tree_sklearn     |     0.446541 |       1.19624  |   1.04858  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.441094 |       0.694981 |   0.475547 |
| Bori_Aron_solution-1 |     0.435123 |       1.29364  |   0.548352 |
| k-d_tree_polars      |     0.436907 |       0.82122  |   0.82965  |
| barab-szabi-1        |     0.441321 |       0.837697 |   0.855395 |
| k-d_tree_pandas      |     0.445713 |       0.715376 |   1.05001  |
| k-d_tree_sklearn     |     0.444159 |       1.91672  |   1.10594  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.440707 |        4.80447 |   0.676736 |
| Bori_Aron_solution-1 |     0.430976 |        9.76404 |   0.849915 |
| k-d_tree_sklearn     |     0.450009 |       13.971   |   1.20988  |
| barab-szabi-1        |     0.443948 |        4.79516 |   6.01359  |
| k-d_tree_polars      |     0.442328 |        4.74691 |   6.01901  |
| k-d_tree_pandas      |     0.438947 |        3.75993 |   6.47914  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.441679 |        65.3055 |    2.51326 |
| k-d_tree_sklearn     |     0.63927  |       174.225  |    3.8842  |
| Bori_Aron_solution-1 |     0.440229 |       129.226  |   22.0059  |