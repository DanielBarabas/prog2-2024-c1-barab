# 2024-07-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.559726 |       0.401794 |   0.386874 |
| k-d_tree_polars      |     0.556096 |       0.403333 |   0.388266 |
| barab-szabi-2        |     0.558037 |       0.388786 |   0.388282 |
| solution-1           |     7.79549  |       1e-06    |   0.398631 |
| k-d_tree_pandas      |     0.556111 |       0.37843  |   0.528625 |
| Bori_Aron_solution-1 |     0.563726 |       0.526711 |   0.529416 |
| k-d_tree_sklearn     |    10.5154   |       1.02037  |   0.711898 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555801 |       0.392667 |   0.386701 |
| barab-szabi-1        |     0.573629 |       0.407374 |   0.392172 |
| k-d_tree_polars      |     0.559771 |       0.401341 |   0.400525 |
| Bori_Aron_solution-1 |     0.576396 |       0.536381 |   0.530876 |
| k-d_tree_pandas      |     0.560409 |       0.384708 |   0.538466 |
| k-d_tree_sklearn     |     0.602586 |       0.907815 |   0.713013 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558599 |       0.399455 |   0.401508 |
| k-d_tree_polars      |     0.560693 |       0.429662 |   0.415235 |
| barab-szabi-1        |     0.580422 |       0.43     |   0.423399 |
| Bori_Aron_solution-1 |     0.55482  |       0.566374 |   0.534696 |
| k-d_tree_pandas      |     0.568324 |       0.399534 |   0.575507 |
| k-d_tree_sklearn     |     0.567159 |       0.939889 |   0.734607 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566556 |       0.466897 |   0.430738 |
| k-d_tree_polars      |     0.558531 |       0.537774 |   0.518756 |
| barab-szabi-1        |     0.556768 |       0.535393 |   0.525907 |
| Bori_Aron_solution-1 |     0.550976 |       0.746264 |   0.542693 |
| k-d_tree_pandas      |     0.554833 |       0.480577 |   0.717049 |
| k-d_tree_sklearn     |     0.59876  |       1.17023  |   0.788477 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.582283 |       0.722653 |   0.471236 |
| Bori_Aron_solution-1 |     0.553471 |       1.4088   |   0.56904  |
| k-d_tree_polars      |     0.555685 |       0.858519 |   0.870191 |
| k-d_tree_sklearn     |     0.564278 |       2.00978  |   0.876789 |
| barab-szabi-1        |     0.563772 |       0.857849 |   0.907406 |
| k-d_tree_pandas      |     0.56007  |       0.74927  |   1.15382  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555094 |        5.34856 |   0.721494 |
| Bori_Aron_solution-1 |     0.552682 |       10.7298  |   0.847135 |
| k-d_tree_sklearn     |     0.56224  |       16.1785  |   0.990324 |
| k-d_tree_polars      |     0.562156 |        4.8795  |   6.50061  |
| barab-szabi-1        |     0.564877 |        4.88381 |   6.51761  |
| k-d_tree_pandas      |     0.556559 |        3.88128 |   6.94745  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.804359 |        71.6114 |    3.14985 |
| k-d_tree_sklearn     |     0.560794 |       226.507  |    3.90253 |
| Bori_Aron_solution-1 |     0.551465 |       147.063  |   17.3117  |