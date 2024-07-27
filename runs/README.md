# 2024-07-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.97351  |       1e-06    |   0.36886  |
| barab-szabi-2        |     0.553101 |       0.392089 |   0.389889 |
| k-d_tree_polars      |     0.569264 |       0.407245 |   0.393674 |
| barab-szabi-1        |     8.37204  |       0.422118 |   0.459512 |
| Bori_Aron_solution-1 |     0.557623 |       0.522519 |   0.538476 |
| k-d_tree_pandas      |     0.571396 |       0.387966 |   0.540671 |
| k-d_tree_sklearn     |     3.15091  |       0.956276 |   0.713748 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577454 |       0.390735 |   0.385182 |
| barab-szabi-1        |     0.571825 |       0.414758 |   0.397019 |
| k-d_tree_polars      |     0.575838 |       0.414501 |   0.39767  |
| Bori_Aron_solution-1 |     0.568682 |       0.538072 |   0.530453 |
| k-d_tree_pandas      |     0.568093 |       0.389769 |   0.54793  |
| k-d_tree_sklearn     |     0.565008 |       0.908907 |   0.721335 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574919 |       0.409227 |   0.403372 |
| barab-szabi-1        |     0.56559  |       0.43474  |   0.42592  |
| k-d_tree_polars      |     0.570336 |       0.439692 |   0.456405 |
| Bori_Aron_solution-1 |     0.579062 |       0.583957 |   0.539028 |
| k-d_tree_pandas      |     0.570027 |       0.406911 |   0.582581 |
| k-d_tree_sklearn     |     0.567332 |       0.965724 |   0.746543 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566769 |       0.472955 |   0.431044 |
| k-d_tree_polars      |     0.565855 |       0.551171 |   0.518107 |
| barab-szabi-1        |     0.571476 |       0.545408 |   0.533651 |
| Bori_Aron_solution-1 |     0.562491 |       0.744699 |   0.549113 |
| k-d_tree_pandas      |     0.563055 |       0.496425 |   0.725151 |
| k-d_tree_sklearn     |     0.565518 |       1.17356  |   0.798286 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563738 |       0.723484 |   0.470854 |
| Bori_Aron_solution-1 |     0.553295 |       1.39653  |   0.568771 |
| k-d_tree_polars      |     0.564662 |       0.861835 |   0.877301 |
| k-d_tree_sklearn     |     0.566253 |       2.04171  |   0.888279 |
| barab-szabi-1        |     0.564021 |       0.857451 |   0.923337 |
| k-d_tree_pandas      |     0.565399 |       0.755246 |   1.17846  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559528 |        5.27345 |   0.7309   |
| Bori_Aron_solution-1 |     0.551711 |       10.6115  |   0.842542 |
| k-d_tree_sklearn     |     0.55791  |       15.9206  |   0.991886 |
| barab-szabi-1        |     0.569686 |        4.83677 |   6.41689  |
| k-d_tree_polars      |     0.556154 |        4.79857 |   6.45362  |
| k-d_tree_pandas      |     0.557656 |        3.88829 |   6.93184  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553755 |        71.1275 |    2.96529 |
| k-d_tree_sklearn     |     0.583627 |       228.746  |    3.9107  |
| Bori_Aron_solution-1 |     0.619598 |       144.811  |   18.84    |