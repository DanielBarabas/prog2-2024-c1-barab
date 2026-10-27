# 2026-10-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.53385  |       1e-06    |   0.277791 |
| barab-szabi-2        |     0.351924 |       0.343979 |   0.328987 |
| k-d_tree_polars      |     0.362952 |       0.338995 |   0.362136 |
| barab-szabi-1        |     7.70309  |       0.339569 |   0.367883 |
| k-d_tree_pandas      |     0.350038 |       0.307699 |   0.430938 |
| Bori_Aron_solution-1 |     0.3626   |       0.424914 |   0.431555 |
| k-d_tree_sklearn     |     2.87613  |       0.827276 |   0.839072 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.368807 |       0.364251 |   0.334384 |
| k-d_tree_polars      |     0.363891 |       0.343451 |   0.34521  |
| barab-szabi-1        |     0.369919 |       0.375987 |   0.356318 |
| Bori_Aron_solution-1 |     0.35866  |       0.442503 |   0.433038 |
| k-d_tree_pandas      |     0.372046 |       0.319372 |   0.459654 |
| k-d_tree_sklearn     |     0.368334 |       0.83129  |   0.858292 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.366483 |       0.356497 |   0.346035 |
| k-d_tree_polars      |     0.361526 |       0.359333 |   0.363374 |
| barab-szabi-1        |     0.35893  |       0.348275 |   0.368299 |
| Bori_Aron_solution-1 |     0.352917 |       0.471551 |   0.435617 |
| k-d_tree_pandas      |     0.36112  |       0.326749 |   0.463212 |
| k-d_tree_sklearn     |     0.365126 |       0.829059 |   0.854895 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.359254 |       0.416699 |   0.370712 |
| barab-szabi-1        |     0.361757 |       0.455111 |   0.451956 |
| k-d_tree_polars      |     0.358181 |       0.474247 |   0.453043 |
| Bori_Aron_solution-1 |     0.356672 |       0.636759 |   0.454498 |
| k-d_tree_pandas      |     0.359191 |       0.396394 |   0.565817 |
| k-d_tree_sklearn     |     0.364408 |       1.02469  |   0.881525 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.360376 |       0.641127 |   0.428903 |
| Bori_Aron_solution-1 |     0.353803 |       1.18113  |   0.489905 |
| k-d_tree_polars      |     0.360499 |       0.771965 |   0.772176 |
| barab-szabi-1        |     0.362228 |       0.776052 |   0.801457 |
| k-d_tree_sklearn     |     0.360122 |       1.78094  |   0.938952 |
| k-d_tree_pandas      |     0.367476 |       0.616565 |   0.944087 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.366938 |        4.89193 |   0.71716  |
| Bori_Aron_solution-1 |     0.354234 |        9.54188 |   0.904309 |
| k-d_tree_sklearn     |     0.362022 |       14.6361  |   1.04095  |
| barab-szabi-1        |     0.359517 |        4.58068 |   6.2809   |
| k-d_tree_polars      |     0.371764 |        4.71469 |   6.29989  |
| k-d_tree_pandas      |     0.355983 |        3.18003 |   6.62793  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.376218 |       217.192  |     2.9451 |
| barab-szabi-2        |     0.359732 |        71.1718 |     3.5258 |
| Bori_Aron_solution-1 |     0.360611 |       140.996  |    24.7217 |