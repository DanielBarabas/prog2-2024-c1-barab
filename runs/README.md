# 2026-09-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.19171  |       0        |   0.302201 |
| barab-szabi-2        |     0.361896 |       0.359668 |   0.351581 |
| k-d_tree_polars      |     0.364152 |       0.340756 |   0.363207 |
| barab-szabi-1        |     7.62659  |       0.365464 |   0.40597  |
| k-d_tree_pandas      |     0.362334 |       0.313507 |   0.445147 |
| Bori_Aron_solution-1 |     0.35665  |       0.447534 |   0.456948 |
| k-d_tree_sklearn     |     2.46186  |       0.857613 |   0.865805 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.367609 |       0.336865 |   0.362084 |
| barab-szabi-1        |     0.372838 |       0.345026 |   0.366456 |
| barab-szabi-2        |     0.368555 |       0.357726 |   0.379338 |
| Bori_Aron_solution-1 |     0.364723 |       0.450758 |   0.441249 |
| k-d_tree_pandas      |     0.368332 |       0.320684 |   0.449513 |
| k-d_tree_sklearn     |     0.40741  |       0.911178 |   0.871687 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.370709 |       0.373866 |   0.365485 |
| k-d_tree_polars      |     0.375535 |       0.38048  |   0.383153 |
| barab-szabi-1        |     0.368665 |       0.371032 |   0.385232 |
| Bori_Aron_solution-1 |     0.367802 |       0.481493 |   0.451845 |
| k-d_tree_pandas      |     0.375499 |       0.342106 |   0.482085 |
| k-d_tree_sklearn     |     0.375096 |       0.867929 |   0.904963 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.374969 |       0.41893  |   0.403615 |
| k-d_tree_polars      |     0.36987  |       0.473626 |   0.459334 |
| Bori_Aron_solution-1 |     0.374316 |       0.628684 |   0.46565  |
| barab-szabi-1        |     0.369215 |       0.483059 |   0.545281 |
| k-d_tree_pandas      |     0.375185 |       0.404986 |   0.582607 |
| k-d_tree_sklearn     |     0.374547 |       1.02967  |   0.936399 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.374898 |       0.620116 |   0.428424 |
| Bori_Aron_solution-1 |     0.368331 |       1.16768  |   0.478708 |
| k-d_tree_polars      |     0.372936 |       0.859236 |   0.763466 |
| barab-szabi-1        |     0.374099 |       0.826766 |   0.811872 |
| k-d_tree_pandas      |     0.373152 |       0.608804 |   0.934941 |
| k-d_tree_sklearn     |     0.376441 |       1.78441  |   0.954266 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.368659 |        4.55593 |   0.631552 |
| Bori_Aron_solution-1 |     0.378659 |        9.03903 |   0.655483 |
| k-d_tree_sklearn     |     0.372625 |       14.0959  |   0.99355  |
| k-d_tree_polars      |     0.370004 |        4.86314 |   6.04016  |
| barab-szabi-1        |     0.373111 |        4.66672 |   6.07387  |
| k-d_tree_pandas      |     0.369365 |        3.15705 |   6.3261   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.996217 |        73.1962 |    2.34713 |
| k-d_tree_sklearn     |     0.64283  |       219.805  |    2.81903 |
| Bori_Aron_solution-1 |     0.363473 |       150.095  |   26.0215  |