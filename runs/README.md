# 2025-03-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.36611  |       1e-06    |   0.360597 |
| barab-szabi-2        |     0.545308 |       0.407443 |   0.401332 |
| k-d_tree_polars      |     0.553761 |       0.406259 |   0.408898 |
| barab-szabi-1        |     0.550814 |       0.411701 |   0.41683  |
| Bori_Aron_solution-1 |     0.556493 |       0.546242 |   0.54145  |
| k-d_tree_pandas      |     7.8771   |       0.400229 |   0.595937 |
| k-d_tree_sklearn     |     2.93618  |       0.976737 |   1.05037  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569126 |       0.415359 |   0.412765 |
| k-d_tree_polars      |     0.567122 |       0.41158  |   0.414046 |
| barab-szabi-1        |     0.568686 |       0.412558 |   0.41963  |
| Bori_Aron_solution-1 |     0.556423 |       0.55698  |   0.550237 |
| k-d_tree_pandas      |     0.647883 |       0.387451 |   0.556269 |
| k-d_tree_sklearn     |     0.564497 |       0.952606 |   1.0334   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567951 |       0.421291 |   0.419756 |
| barab-szabi-1        |     0.560655 |       0.430894 |   0.43859  |
| k-d_tree_polars      |     0.581795 |       0.434129 |   0.441553 |
| Bori_Aron_solution-1 |     0.556091 |       0.583336 |   0.540317 |
| k-d_tree_pandas      |     0.582361 |       0.40519  |   0.602765 |
| k-d_tree_sklearn     |     0.569814 |       1.00821  |   1.05819  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565032 |       0.487494 |   0.450841 |
| k-d_tree_polars      |     0.563604 |       0.537434 |   0.538608 |
| barab-szabi-1        |     0.571569 |       0.553577 |   0.556416 |
| Bori_Aron_solution-1 |     0.556708 |       0.757143 |   0.567654 |
| k-d_tree_pandas      |     0.565747 |       0.480309 |   0.728718 |
| k-d_tree_sklearn     |     0.571974 |       1.21494  |   1.10629  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.576562 |       0.735772 |   0.484664 |
| Bori_Aron_solution-1 |     0.558053 |       1.39569  |   0.588814 |
| k-d_tree_polars      |     0.576998 |       0.861316 |   0.891332 |
| barab-szabi-1        |     0.563118 |       0.857403 |   0.923242 |
| k-d_tree_pandas      |     0.570303 |       0.749128 |   1.184    |
| k-d_tree_sklearn     |     0.567578 |       2.06136  |   1.19896  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558932 |        5.14961 |   0.728526 |
| Bori_Aron_solution-1 |     0.561616 |       10.3811  |   0.885373 |
| k-d_tree_sklearn     |     0.581462 |       15.4727  |   1.3023   |
| barab-szabi-1        |     0.566599 |        4.9285  |   6.37732  |
| k-d_tree_polars      |     0.569169 |        4.92219 |   6.43129  |
| k-d_tree_pandas      |     0.56267  |        3.86143 |   6.884    |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.741749 |        70.6076 |    2.84877 |
| k-d_tree_sklearn     |     0.640225 |       222.855  |    4.23561 |
| Bori_Aron_solution-1 |     0.560586 |       151.344  |   15.3588  |