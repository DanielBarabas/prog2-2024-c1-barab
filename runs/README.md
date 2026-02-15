# 2026-02-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485709 |       0.439419 |   0.437141 |
| solution-1           |     7.51196  |       1e-06    |   0.442217 |
| k-d_tree_polars      |     0.487898 |       0.414478 |   0.483969 |
| barab-szabi-1        |     9.83255  |       0.443858 |   0.561157 |
| k-d_tree_pandas      |     0.492839 |       0.394634 |   0.564889 |
| Bori_Aron_solution-1 |     0.481055 |       0.560741 |   0.572474 |
| k-d_tree_sklearn     |     2.97798  |       1.23767  |   1.06705  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498797 |       0.434681 |   0.43724  |
| k-d_tree_polars      |     0.498497 |       0.419013 |   0.445001 |
| barab-szabi-1        |     0.497832 |       0.421762 |   0.44922  |
| Bori_Aron_solution-1 |     0.492333 |       0.568475 |   0.552176 |
| k-d_tree_pandas      |     0.4961   |       0.39474  |   0.565693 |
| k-d_tree_sklearn     |     0.499287 |       0.991752 |   1.09495  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.497707 |       0.450925 |   0.452469 |
| k-d_tree_polars      |     0.499968 |       0.442642 |   0.469371 |
| barab-szabi-1        |     0.515297 |       0.444022 |   0.472786 |
| Bori_Aron_solution-1 |     0.490806 |       0.609118 |   0.561765 |
| k-d_tree_pandas      |     0.492609 |       0.413646 |   0.5995   |
| k-d_tree_sklearn     |     0.499702 |       1.03569  |   1.10245  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49649  |       0.512567 |   0.477545 |
| k-d_tree_polars      |     0.509129 |       0.565427 |   0.55666  |
| Bori_Aron_solution-1 |     0.490742 |       0.789707 |   0.574804 |
| barab-szabi-1        |     0.497494 |       0.563073 |   0.622542 |
| k-d_tree_pandas      |     0.494707 |       0.504888 |   0.743045 |
| k-d_tree_sklearn     |     0.496609 |       1.26481  |   1.13926  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.499126 |       0.734299 |   0.510275 |
| Bori_Aron_solution-1 |     0.487991 |       1.46989  |   0.592441 |
| k-d_tree_polars      |     0.497775 |       0.942914 |   0.915392 |
| barab-szabi-1        |     0.497542 |       0.933755 |   0.949501 |
| k-d_tree_pandas      |     0.494095 |       0.818545 |   1.18895  |
| k-d_tree_sklearn     |     0.497728 |       2.14367  |   1.22465  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49248  |        5.06583 |   0.732083 |
| Bori_Aron_solution-1 |     0.48652  |       11.0298  |   0.827691 |
| k-d_tree_sklearn     |     0.501484 |       16.9856  |   1.31483  |
| k-d_tree_polars      |     0.497109 |        5.46179 |   6.57795  |
| barab-szabi-1        |     0.496711 |        5.49753 |   6.59021  |
| k-d_tree_pandas      |     0.497528 |        4.43894 |   6.97877  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.504621 |        70.3513 |    2.59277 |
| k-d_tree_sklearn     |     0.816006 |       229.952  |    3.853   |
| Bori_Aron_solution-1 |     0.49606  |       148.854  |   14.416   |