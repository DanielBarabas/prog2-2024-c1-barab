# 2026-02-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.64638  |       1e-06    |   0.370712 |
| barab-szabi-2        |     0.484583 |       0.459085 |   0.434076 |
| k-d_tree_polars      |     0.504096 |       0.421044 |   0.443264 |
| barab-szabi-1        |     0.505008 |       0.418578 |   0.450373 |
| Bori_Aron_solution-1 |     0.493174 |       0.57     |   0.563079 |
| k-d_tree_pandas      |     8.11059  |       0.467195 |   0.623633 |
| k-d_tree_sklearn     |     3.23583  |       1.14866  |   1.09858  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.50376  |       0.452891 |   0.443248 |
| k-d_tree_polars      |     0.500098 |       0.417    |   0.444007 |
| barab-szabi-1        |     0.491844 |       0.418727 |   0.452118 |
| Bori_Aron_solution-1 |     0.491747 |       0.560934 |   0.549582 |
| k-d_tree_pandas      |     0.510737 |       0.400141 |   0.579815 |
| k-d_tree_sklearn     |     0.530472 |       1.13407  |   1.08809  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.497607 |       0.461437 |   0.451418 |
| k-d_tree_polars      |     0.494145 |       0.443758 |   0.470568 |
| barab-szabi-1        |     0.496415 |       0.44293  |   0.472361 |
| Bori_Aron_solution-1 |     0.495417 |       0.605057 |   0.564972 |
| k-d_tree_pandas      |     0.504302 |       0.411475 |   0.610863 |
| k-d_tree_sklearn     |     0.500076 |       1.04175  |   1.09858  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.494596 |       0.51483  |   0.481953 |
| barab-szabi-1        |     0.498625 |       0.580881 |   0.57813  |
| k-d_tree_polars      |     0.493924 |       0.563923 |   0.58475  |
| Bori_Aron_solution-1 |     0.518291 |       0.899775 |   0.585733 |
| k-d_tree_pandas      |     0.506232 |       0.500876 |   0.787385 |
| k-d_tree_sklearn     |     0.501134 |       1.27628  |   1.19498  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.505398 |       0.759241 |   0.522909 |
| Bori_Aron_solution-1 |     0.493743 |       1.48107  |   0.607658 |
| k-d_tree_polars      |     0.501344 |       0.94807  |   0.92269  |
| barab-szabi-1        |     0.490845 |       0.938688 |   0.962519 |
| k-d_tree_pandas      |     0.503111 |       0.825718 |   1.19297  |
| k-d_tree_sklearn     |     0.512344 |       2.14126  |   1.22884  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496294 |        5.52443 |   0.769717 |
| Bori_Aron_solution-1 |     0.493238 |       11.4401  |   0.884006 |
| k-d_tree_sklearn     |     0.500824 |       17.8163  |   1.34159  |
| k-d_tree_polars      |     0.499582 |        5.56158 |   6.89046  |
| barab-szabi-1        |     0.501887 |        5.40623 |   6.93508  |
| k-d_tree_pandas      |     0.50371  |        4.4816  |   7.44657  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.497626 |        80.9475 |    2.80944 |
| k-d_tree_sklearn     |     0.521135 |       244.912  |    4.13809 |
| Bori_Aron_solution-1 |     0.630131 |       154.174  |   15.9226  |