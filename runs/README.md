# 2025-10-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553741 |       0.423604 |   0.423902 |
| k-d_tree_polars      |     0.553766 |       0.400045 |   0.432096 |
| solution-1           |     8.59431  |       1e-06    |   0.49122  |
| Bori_Aron_solution-1 |     0.978581 |       0.548342 |   0.551823 |
| barab-szabi-1        |     0.538974 |       0.422629 |   0.596131 |
| k-d_tree_pandas      |     8.43244  |       0.432069 |   1.03702  |
| k-d_tree_sklearn     |     3.192    |       1.35027  |   1.06729  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551014 |       0.424824 |   0.427888 |
| barab-szabi-1        |     0.548979 |       0.408409 |   0.429169 |
| k-d_tree_polars      |     0.557698 |       0.409501 |   0.432817 |
| Bori_Aron_solution-1 |     0.54433  |       0.552591 |   0.546241 |
| k-d_tree_pandas      |     0.551095 |       0.391908 |   0.561201 |
| k-d_tree_sklearn     |     0.55624  |       0.965751 |   1.06557  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550302 |       0.44756  |   0.439433 |
| k-d_tree_polars      |     0.549947 |       0.438863 |   0.454408 |
| barab-szabi-1        |     0.555495 |       0.443183 |   0.458452 |
| Bori_Aron_solution-1 |     0.542921 |       0.598141 |   0.550362 |
| k-d_tree_pandas      |     0.551768 |       0.442787 |   0.594012 |
| k-d_tree_sklearn     |     0.554046 |       1.02338  |   1.12365  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554295 |       0.499382 |   0.467448 |
| k-d_tree_polars      |     0.550708 |       0.563793 |   0.552579 |
| Bori_Aron_solution-1 |     0.546134 |       0.790157 |   0.562128 |
| barab-szabi-1        |     0.556859 |       0.565236 |   0.568923 |
| k-d_tree_pandas      |     0.558937 |       0.507875 |   0.736269 |
| k-d_tree_sklearn     |     0.552864 |       1.26241  |   1.12203  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55216  |       0.752133 |   0.496771 |
| Bori_Aron_solution-1 |     0.545933 |       1.44985  |   0.584043 |
| k-d_tree_polars      |     0.548617 |       0.939204 |   0.901771 |
| barab-szabi-1        |     0.549656 |       0.934803 |   0.947033 |
| k-d_tree_pandas      |     0.554425 |       0.814245 |   1.19175  |
| k-d_tree_sklearn     |     0.562171 |       2.11076  |   1.20683  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552747 |        4.9562  |   0.725389 |
| Bori_Aron_solution-1 |     0.545525 |       10.6057  |   0.817971 |
| k-d_tree_sklearn     |     0.557475 |       16.2273  |   1.30333  |
| k-d_tree_polars      |     0.556784 |        5.50599 |   6.31762  |
| barab-szabi-1        |     0.559221 |        5.49479 |   6.32748  |
| k-d_tree_pandas      |     0.54935  |        4.38841 |   6.632    |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.749872 |        71.2349 |    2.5556  |
| k-d_tree_sklearn     |     1.14265  |       236.409  |    4.02142 |
| Bori_Aron_solution-1 |     0.545982 |       152.005  |   13.6156  |