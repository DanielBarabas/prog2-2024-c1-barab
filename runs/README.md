# 2026-03-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460257 |       0.437544 |   0.428591 |
| k-d_tree_polars      |     0.46674  |       0.408149 |   0.442354 |
| k-d_tree_pandas      |     0.470724 |       0.382072 |   0.553125 |
| Bori_Aron_solution-1 |     0.465673 |       0.557929 |   0.554275 |
| solution-1           |     9.11073  |       1e-06    |   0.558643 |
| barab-szabi-1        |     8.44502  |       0.596378 |   0.701828 |
| k-d_tree_sklearn     |     3.18835  |       1.6961   |   1.08527  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467032 |       0.451413 |   0.431655 |
| k-d_tree_polars      |     0.483025 |       0.424825 |   0.447731 |
| barab-szabi-1        |     0.472252 |       0.40962  |   0.452559 |
| k-d_tree_pandas      |     0.465938 |       0.392409 |   0.562114 |
| Bori_Aron_solution-1 |     0.457141 |       0.58059  |   0.568678 |
| k-d_tree_sklearn     |     0.488257 |       1.04637  |   1.09919  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463276 |       0.449435 |   0.447393 |
| k-d_tree_polars      |     0.463745 |       0.44389  |   0.470561 |
| barab-szabi-1        |     0.464798 |       0.434382 |   0.479672 |
| Bori_Aron_solution-1 |     0.456604 |       0.604609 |   0.558305 |
| k-d_tree_pandas      |     0.464626 |       0.422225 |   0.617448 |
| k-d_tree_sklearn     |     0.466801 |       1.06858  |   1.10575  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466207 |       0.52036  |   0.490203 |
| k-d_tree_polars      |     0.463928 |       0.56461  |   0.571893 |
| Bori_Aron_solution-1 |     0.459456 |       0.783814 |   0.576469 |
| barab-szabi-1        |     0.470598 |       0.568343 |   0.576873 |
| k-d_tree_pandas      |     0.470037 |       0.500503 |   0.733464 |
| k-d_tree_sklearn     |     0.46413  |       1.28283  |   1.13915  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468517 |       0.754575 |   0.547001 |
| Bori_Aron_solution-1 |     0.463126 |       1.48663  |   0.604379 |
| k-d_tree_polars      |     0.467976 |       0.93267  |   0.950794 |
| barab-szabi-1        |     0.461817 |       0.954869 |   0.985628 |
| k-d_tree_pandas      |     0.492575 |       0.815349 |   1.20223  |
| k-d_tree_sklearn     |     0.477055 |       2.20522  |   1.24211  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471853 |        5.25736 |   0.746978 |
| Bori_Aron_solution-1 |     0.457134 |       11.2368  |   0.809163 |
| k-d_tree_sklearn     |     0.469642 |       17.4928  |   1.31387  |
| k-d_tree_polars      |     0.466467 |        5.60301 |   6.84481  |
| barab-szabi-1        |     0.463047 |        5.55798 |   6.87586  |
| k-d_tree_pandas      |     0.467959 |        4.53048 |   7.23714  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.784436 |         71.638 |    2.71225 |
| k-d_tree_sklearn     |     0.468772 |        237.826 |    3.98311 |
| Bori_Aron_solution-1 |     0.465274 |        157.361 |   16.2599  |