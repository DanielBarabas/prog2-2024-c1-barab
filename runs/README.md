# 2026-03-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.54856  |       1e-06    |   0.386142 |
| barab-szabi-2        |     0.489778 |       0.451038 |   0.449088 |
| k-d_tree_polars      |     0.490546 |       0.438467 |   0.455439 |
| barab-szabi-1        |     8.03652  |       0.43021  |   0.48937  |
| Bori_Aron_solution-1 |     0.488972 |       0.567451 |   0.565137 |
| k-d_tree_pandas      |     0.499174 |       0.405482 |   0.596284 |
| k-d_tree_sklearn     |     2.98435  |       1.09233  |   1.10874  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.508891 |       0.463584 |   0.445423 |
| barab-szabi-1        |     0.554418 |       0.418528 |   0.46112  |
| k-d_tree_polars      |     0.507817 |       0.449293 |   0.500486 |
| Bori_Aron_solution-1 |     0.4954   |       0.570008 |   0.56459  |
| k-d_tree_pandas      |     0.507631 |       0.402625 |   0.571986 |
| k-d_tree_sklearn     |     0.516069 |       1.00006  |   1.12981  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.512613 |       0.462093 |   0.475936 |
| barab-szabi-2        |     0.514002 |       0.464554 |   0.480919 |
| k-d_tree_polars      |     0.513638 |       0.529799 |   0.486982 |
| Bori_Aron_solution-1 |     0.503008 |       0.66188  |   0.56822  |
| k-d_tree_pandas      |     0.506979 |       0.424095 |   0.613861 |
| k-d_tree_sklearn     |     0.507952 |       1.05758  |   1.14869  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.508047 |       0.5251   |   0.495647 |
| Bori_Aron_solution-1 |     0.512375 |       0.795227 |   0.574764 |
| k-d_tree_polars      |     0.502015 |       0.599595 |   0.583774 |
| barab-szabi-1        |     0.513891 |       0.580488 |   0.602642 |
| k-d_tree_pandas      |     0.507269 |       0.517475 |   0.754628 |
| k-d_tree_sklearn     |     0.511692 |       1.29543  |   1.19292  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5054   |       0.775623 |   0.535063 |
| Bori_Aron_solution-1 |     0.518329 |       1.48848  |   0.602792 |
| k-d_tree_polars      |     0.516593 |       0.930268 |   0.96759  |
| barab-szabi-1        |     0.503172 |       0.951169 |   0.996979 |
| k-d_tree_pandas      |     0.502774 |       0.840964 |   1.21297  |
| k-d_tree_sklearn     |     0.514892 |       2.25464  |   1.27837  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.515659 |        5.43706 |   0.787069 |
| Bori_Aron_solution-1 |     0.508254 |       11.5657  |   0.887546 |
| k-d_tree_sklearn     |     0.50561  |       17.7269  |   1.35572  |
| barab-szabi-1        |     0.497053 |        5.53271 |   6.89989  |
| k-d_tree_polars      |     0.51296  |        5.52256 |   6.95706  |
| k-d_tree_pandas      |     0.508035 |        4.60202 |   7.28314  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.506473 |        73.3137 |    2.85023 |
| k-d_tree_sklearn     |     0.759539 |       243.881  |    3.9776  |
| Bori_Aron_solution-1 |     0.516555 |       155.583  |   13.2975  |