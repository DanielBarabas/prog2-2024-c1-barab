# 2024-07-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.63411  |       1e-06    |   0.348039 |
| barab-szabi-2        |     0.549055 |       0.390135 |   0.376942 |
| barab-szabi-1        |     0.553548 |       0.393966 |   0.385698 |
| k-d_tree_polars      |     0.555077 |       0.394597 |   0.393219 |
| k-d_tree_pandas      |     0.554239 |       0.372199 |   0.514513 |
| Bori_Aron_solution-1 |     0.548507 |       0.509405 |   0.522325 |
| k-d_tree_sklearn     |    10.4738   |       1.07402  |   0.689139 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551888 |       0.388061 |   0.38235  |
| k-d_tree_polars      |     0.549938 |       0.396095 |   0.385355 |
| barab-szabi-1        |     0.551325 |       0.407047 |   0.396228 |
| Bori_Aron_solution-1 |     0.544972 |       0.523816 |   0.50904  |
| k-d_tree_pandas      |     0.55034  |       0.377652 |   0.527156 |
| k-d_tree_sklearn     |     0.556552 |       0.876024 |   0.689791 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551668 |       0.394389 |   0.395272 |
| k-d_tree_polars      |     0.548456 |       0.425615 |   0.412123 |
| barab-szabi-1        |     0.551581 |       0.423038 |   0.417925 |
| Bori_Aron_solution-1 |     0.560304 |       0.556753 |   0.51555  |
| k-d_tree_pandas      |     0.548151 |       0.395111 |   0.584553 |
| k-d_tree_sklearn     |     0.554777 |       0.918869 |   0.7224   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551869 |       0.458905 |   0.423274 |
| k-d_tree_polars      |     0.550658 |       0.529831 |   0.50911  |
| barab-szabi-1        |     0.552671 |       0.529805 |   0.520893 |
| Bori_Aron_solution-1 |     0.547861 |       0.741634 |   0.528506 |
| k-d_tree_pandas      |     0.554303 |       0.478039 |   0.699906 |
| k-d_tree_sklearn     |     0.54874  |       1.15626  |   0.778487 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551642 |       0.710916 |   0.458733 |
| Bori_Aron_solution-1 |     0.549743 |       1.39203  |   0.560458 |
| k-d_tree_polars      |     0.550632 |       0.85258  |   0.859894 |
| k-d_tree_sklearn     |     0.552522 |       2.08071  |   0.866036 |
| barab-szabi-1        |     0.54944  |       0.847495 |   0.895307 |
| k-d_tree_pandas      |     0.549063 |       0.744071 |   1.13684  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556511 |        5.5404  |   0.726773 |
| Bori_Aron_solution-1 |     0.543755 |       10.7428  |   0.855728 |
| k-d_tree_sklearn     |     0.554904 |       15.9525  |   0.974527 |
| k-d_tree_polars      |     0.558519 |        4.8795  |   6.73952  |
| barab-szabi-1        |     0.556281 |        4.91012 |   6.79257  |
| k-d_tree_pandas      |     0.563665 |        3.90455 |   7.18597  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.894447 |        72.6127 |    3.43919 |
| k-d_tree_sklearn     |     0.578697 |       233.392  |    3.94011 |
| Bori_Aron_solution-1 |     0.554801 |       149.561  |   17.5948  |