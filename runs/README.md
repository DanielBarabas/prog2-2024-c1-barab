# 2025-09-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.71465  |       1.32237  |   0.434645 |
| k-d_tree_polars      |     0.535273 |       0.417513 |   0.438936 |
| barab-szabi-1        |     0.555979 |       0.415326 |   0.446676 |
| k-d_tree_pandas      |     0.53855  |       0.397314 |   0.556958 |
| Bori_Aron_solution-1 |     0.589244 |       0.554831 |   0.559497 |
| solution-1           |     7.81763  |       1e-06    |   0.928677 |
| k-d_tree_sklearn     |     3.22238  |       1.53608  |   1.09668  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547498 |       0.436821 |   0.436659 |
| k-d_tree_polars      |     0.572976 |       0.423057 |   0.451095 |
| barab-szabi-1        |     0.561999 |       0.428654 |   0.457315 |
| Bori_Aron_solution-1 |     0.547239 |       0.567225 |   0.565549 |
| k-d_tree_pandas      |     0.554284 |       0.409092 |   0.587919 |
| k-d_tree_sklearn     |     0.563713 |       1.03401  |   1.1464   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5619   |       0.451609 |   0.456458 |
| barab-szabi-1        |     0.564399 |       0.454847 |   0.476771 |
| k-d_tree_polars      |     0.569309 |       0.463157 |   0.477983 |
| Bori_Aron_solution-1 |     0.5553   |       0.61165  |   0.572921 |
| k-d_tree_pandas      |     0.552541 |       0.4248   |   0.632599 |
| k-d_tree_sklearn     |     0.566711 |       1.07939  |   1.12851  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556796 |       0.518987 |   0.478501 |
| k-d_tree_polars      |     0.556065 |       0.57152  |   0.575905 |
| Bori_Aron_solution-1 |     0.55179  |       0.786448 |   0.578088 |
| barab-szabi-1        |     0.558626 |       0.569764 |   0.584146 |
| k-d_tree_pandas      |     0.552738 |       0.491997 |   0.759491 |
| k-d_tree_sklearn     |     0.561955 |       1.27254  |   1.1518   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550118 |       0.7813   |   0.508804 |
| Bori_Aron_solution-1 |     0.537425 |       1.39501  |   0.578214 |
| k-d_tree_polars      |     0.546522 |       0.890819 |   0.911849 |
| barab-szabi-1        |     0.54038  |       0.887597 |   0.943106 |
| k-d_tree_pandas      |     0.542539 |       0.762104 |   1.18759  |
| k-d_tree_sklearn     |     0.540476 |       2.09291  |   1.24683  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549797 |        5.54161 |   0.7662   |
| Bori_Aron_solution-1 |     0.552896 |       10.9629  |   0.858127 |
| k-d_tree_sklearn     |     0.574232 |       17.889   |   1.40834  |
| k-d_tree_polars      |     0.542742 |        5.05805 |   6.94318  |
| barab-szabi-1        |     0.572192 |        5.09393 |   7.18276  |
| k-d_tree_pandas      |     0.562014 |        3.90291 |   7.22928  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570173 |        73.2657 |    2.72959 |
| k-d_tree_sklearn     |     1.10873  |       238.633  |    4.04714 |
| Bori_Aron_solution-1 |     0.540001 |       147.932  |   15.6803  |