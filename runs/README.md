# 2026-10-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.304984 |       0.322659 |   0.308311 |
| k-d_tree_polars      |     0.320416 |       0.324017 |   0.335051 |
| solution-1           |     5.77177  |       1e-06    |   0.363185 |
| Bori_Aron_solution-1 |     0.318172 |       0.435434 |   0.41033  |
| k-d_tree_pandas      |     0.320105 |       0.285821 |   0.422457 |
| barab-szabi-1        |     7.40177  |       0.481692 |   0.570317 |
| k-d_tree_sklearn     |     2.3518   |       1.12058  |   0.833966 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.312242 |       0.341031 |   0.333045 |
| barab-szabi-2        |     0.32919  |       0.343229 |   0.336893 |
| barab-szabi-1        |     0.322046 |       0.319832 |   0.350418 |
| k-d_tree_pandas      |     0.326544 |       0.294215 |   0.41595  |
| Bori_Aron_solution-1 |     0.321641 |       0.424259 |   0.419141 |
| k-d_tree_sklearn     |     0.359563 |       0.732924 |   0.885709 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.334435 |       0.334655 |   0.318    |
| k-d_tree_polars      |     0.311354 |       0.316548 |   0.338579 |
| barab-szabi-1        |     0.318946 |       0.33637  |   0.352834 |
| Bori_Aron_solution-1 |     0.303911 |       0.416778 |   0.403177 |
| k-d_tree_pandas      |     0.341437 |       0.328828 |   0.414141 |
| k-d_tree_sklearn     |     0.315321 |       0.776164 |   0.826084 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.347879 |       0.3925   |   0.353001 |
| barab-szabi-1        |     0.316606 |       0.393893 |   0.400012 |
| Bori_Aron_solution-1 |     0.303672 |       0.550847 |   0.426108 |
| k-d_tree_polars      |     0.322643 |       0.422772 |   0.433761 |
| k-d_tree_pandas      |     0.320758 |       0.351208 |   0.500286 |
| k-d_tree_sklearn     |     0.320927 |       0.952161 |   0.889517 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.299749 |       0.524671 |   0.364118 |
| Bori_Aron_solution-1 |     0.30894  |       0.964562 |   0.427249 |
| k-d_tree_polars      |     0.338187 |       0.637402 |   0.613665 |
| barab-szabi-1        |     0.320616 |       0.619676 |   0.696228 |
| k-d_tree_pandas      |     0.314813 |       0.518223 |   0.773641 |
| k-d_tree_sklearn     |     0.296488 |       1.35018  |   0.782056 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.294844 |        6.88113 |   0.527735 |
| barab-szabi-2        |     0.28912  |        3.52254 |   0.56525  |
| k-d_tree_sklearn     |     0.323987 |       11.6157  |   0.95111  |
| barab-szabi-1        |     0.307357 |        3.64185 |   4.77341  |
| k-d_tree_polars      |     0.283805 |        3.61164 |   4.82076  |
| k-d_tree_pandas      |     0.290847 |        2.36672 |   4.88858  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566141 |        58.8335 |    2.31016 |
| k-d_tree_sklearn     |     0.458657 |       171.926  |    2.34073 |
| Bori_Aron_solution-1 |     0.323982 |       123.507  |   22.7915  |