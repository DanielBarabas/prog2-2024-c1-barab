# 2025-02-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.14026  |       1e-06    |   0.356058 |
| barab-szabi-2        |     3.75133  |       0.424924 |   0.401069 |
| k-d_tree_polars      |     0.598974 |       0.403503 |   0.406725 |
| barab-szabi-1        |     0.581088 |       0.405702 |   0.409228 |
| Bori_Aron_solution-1 |     4.37054  |       0.564184 |   0.483283 |
| k-d_tree_pandas      |     0.584179 |       0.378608 |   0.543913 |
| k-d_tree_sklearn     |     2.9706   |       0.976859 |   1.06642  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.596231 |       0.411234 |   0.40687  |
| barab-szabi-2        |     0.58915  |       0.411507 |   0.410095 |
| barab-szabi-1        |     0.587161 |       0.411669 |   0.414994 |
| Bori_Aron_solution-1 |     0.577221 |       0.597714 |   0.549219 |
| k-d_tree_pandas      |     0.589081 |       0.396328 |   0.560826 |
| k-d_tree_sklearn     |     0.588859 |       0.954953 |   1.06287  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58814  |       0.421274 |   0.414886 |
| barab-szabi-1        |     0.584333 |       0.438099 |   0.43776  |
| k-d_tree_polars      |     0.585685 |       0.449572 |   0.439763 |
| Bori_Aron_solution-1 |     0.583298 |       0.593218 |   0.588071 |
| k-d_tree_pandas      |     0.584896 |       0.403339 |   0.596539 |
| k-d_tree_sklearn     |     0.593576 |       1.01011  |   1.06728  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579772 |       0.485586 |   0.452752 |
| k-d_tree_polars      |     0.58613  |       0.541268 |   0.541046 |
| barab-szabi-1        |     0.58389  |       0.537576 |   0.542602 |
| Bori_Aron_solution-1 |     0.579916 |       0.757725 |   0.56428  |
| k-d_tree_pandas      |     0.61024  |       0.48989  |   0.741514 |
| k-d_tree_sklearn     |     0.591364 |       1.22425  |   1.10452  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.596337 |       0.734481 |   0.483209 |
| Bori_Aron_solution-1 |     0.578166 |       1.39027  |   0.59881  |
| k-d_tree_polars      |     0.613723 |       0.873034 |   0.886531 |
| barab-szabi-1        |     0.585523 |       0.867603 |   0.93524  |
| k-d_tree_pandas      |     0.588698 |       0.746893 |   1.17786  |
| k-d_tree_sklearn     |     0.594626 |       2.14488  |   1.23953  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584297 |        5.32797 |   0.734195 |
| Bori_Aron_solution-1 |     0.5892   |       10.6286  |   0.873425 |
| k-d_tree_sklearn     |     0.591438 |       17.0036  |   1.3582   |
| barab-szabi-1        |     0.596449 |        4.95236 |   6.60046  |
| k-d_tree_polars      |     0.615225 |        4.95459 |   6.77293  |
| k-d_tree_pandas      |     0.593823 |        3.80948 |   7.09037  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.84772  |        76.5117 |    3.50238 |
| k-d_tree_sklearn     |     0.729111 |       236.693  |    4.21558 |
| Bori_Aron_solution-1 |     0.584042 |       161.354  |   15.7013  |