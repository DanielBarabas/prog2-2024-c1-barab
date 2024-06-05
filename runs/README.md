# 2024-06-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.802281 |       0.408783 |   0.351362 |
| barab-szabi-2        |     4.7492   |       0.358909 |   0.354007 |
| k-d_tree_polars      |     0.812022 |       0.419227 |   0.355145 |
| solution-1           |     8.65359  |       1e-06    |   0.371915 |
| Bori_Aron_solution-1 |     4.72291  |       0.425727 |   0.428009 |
| k-d_tree_pandas      |     0.816762 |       0.391639 |   0.507326 |
| k-d_tree_sklearn     |     3.46878  |       0.957885 |   0.69575  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.813075 |       0.422392 |   0.355505 |
| k-d_tree_polars      |     0.808593 |       0.422635 |   0.358399 |
| barab-szabi-2        |     0.827849 |       0.35752  |   0.382126 |
| Bori_Aron_solution-1 |     0.796735 |       0.510339 |   0.49421  |
| k-d_tree_pandas      |     0.801503 |       0.405976 |   0.500216 |
| k-d_tree_sklearn     |     0.81298  |       0.871732 |   0.708216 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.831738 |       0.367054 |   0.366257 |
| k-d_tree_polars      |     0.827331 |       0.448184 |   0.383717 |
| barab-szabi-1        |     0.8052   |       0.461147 |   0.393464 |
| Bori_Aron_solution-1 |     0.795421 |       0.531691 |   0.49932  |
| k-d_tree_pandas      |     0.804084 |       0.413213 |   0.537519 |
| k-d_tree_sklearn     |     0.813364 |       0.941502 |   0.734984 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.804795 |       0.435546 |   0.405423 |
| k-d_tree_polars      |     0.81028  |       0.553856 |   0.485219 |
| barab-szabi-1        |     0.805441 |       0.552191 |   0.493047 |
| Bori_Aron_solution-1 |     0.802974 |       0.715441 |   0.506446 |
| k-d_tree_pandas      |     0.807648 |       0.498445 |   0.673558 |
| k-d_tree_sklearn     |     0.814656 |       1.15545  |   0.790518 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.799495 |       0.692841 |   0.450313 |
| Bori_Aron_solution-1 |     0.793378 |       1.38764  |   0.52543  |
| k-d_tree_polars      |     0.818193 |       0.895789 |   0.866002 |
| k-d_tree_sklearn     |     0.80799  |       2.05184  |   0.909376 |
| barab-szabi-1        |     0.801532 |       0.874222 |   0.916519 |
| k-d_tree_pandas      |     0.817715 |       0.769588 |   1.13801  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.817009 |        5.54586 |   0.737471 |
| Bori_Aron_solution-1 |     0.795532 |       11.1393  |   0.8198   |
| k-d_tree_sklearn     |     0.817338 |       16.8322  |   1.06883  |
| k-d_tree_polars      |     0.813428 |        5.01202 |   6.80787  |
| barab-szabi-1        |     0.80214  |        5.075   |   6.84326  |
| k-d_tree_pandas      |     0.804182 |        4.00903 |   7.1441   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.19748  |        75.5458 |    3.76018 |
| k-d_tree_sklearn     |     0.974645 |       236.569  |    4.60251 |
| Bori_Aron_solution-1 |     0.797595 |       151.536  |   18.7324  |