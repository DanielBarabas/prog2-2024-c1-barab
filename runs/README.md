# 2025-07-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.51132  |       0.714435 |   0.420152 |
| k-d_tree_polars      |     0.551309 |       0.401624 |   0.421299 |
| barab-szabi-1        |     0.553424 |       0.403069 |   0.427647 |
| Bori_Aron_solution-1 |     0.535283 |       0.54761  |   0.540665 |
| k-d_tree_pandas      |     0.5526   |       0.384014 |   0.546472 |
| solution-1           |     8.10924  |       1e-06    |   0.654552 |
| k-d_tree_sklearn     |     3.0113   |       1.14762  |   1.07255  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.550299 |       0.408584 |   0.42472  |
| barab-szabi-2        |     0.556151 |       0.422363 |   0.428746 |
| k-d_tree_polars      |     0.553312 |       0.409471 |   0.428902 |
| Bori_Aron_solution-1 |     0.54718  |       0.568216 |   0.546057 |
| k-d_tree_pandas      |     0.559883 |       0.389946 |   0.564003 |
| k-d_tree_sklearn     |     0.567203 |       0.977423 |   1.07714  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560114 |       0.441106 |   0.436678 |
| k-d_tree_polars      |     0.560621 |       0.437747 |   0.451805 |
| barab-szabi-1        |     0.550535 |       0.435838 |   0.459857 |
| Bori_Aron_solution-1 |     0.552579 |       0.594944 |   0.553918 |
| k-d_tree_pandas      |     0.55262  |       0.409976 |   0.638914 |
| k-d_tree_sklearn     |     0.596085 |       1.03225  |   1.0858   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559752 |       0.50286  |   0.465853 |
| k-d_tree_polars      |     0.55665  |       0.552454 |   0.551447 |
| barab-szabi-1        |     0.553993 |       0.552883 |   0.564033 |
| Bori_Aron_solution-1 |     0.547646 |       0.777242 |   0.567693 |
| k-d_tree_pandas      |     0.559746 |       0.490729 |   0.738738 |
| k-d_tree_sklearn     |     0.558285 |       1.24756  |   1.13966  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555142 |       0.757311 |   0.499065 |
| Bori_Aron_solution-1 |     0.55194  |       1.40226  |   0.610024 |
| k-d_tree_polars      |     0.555758 |       0.88192  |   0.906381 |
| barab-szabi-1        |     0.559168 |       0.886549 |   0.942813 |
| k-d_tree_pandas      |     0.550375 |       0.758113 |   1.17227  |
| k-d_tree_sklearn     |     0.561281 |       2.09634  |   1.21196  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554896 |        5.88715 |   0.758915 |
| Bori_Aron_solution-1 |     0.546331 |       10.7353  |   0.856926 |
| k-d_tree_sklearn     |     0.55812  |       16.3284  |   1.32028  |
| barab-szabi-1        |     0.560645 |        5.07919 |   6.64843  |
| k-d_tree_polars      |     0.55141  |        5.09741 |   6.82895  |
| k-d_tree_pandas      |     0.572426 |        3.99126 |   7.28185  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564461 |        77.2643 |    2.76848 |
| k-d_tree_sklearn     |     0.805374 |       239.471  |    3.95439 |
| Bori_Aron_solution-1 |     0.562818 |       144.521  |   17.7948  |