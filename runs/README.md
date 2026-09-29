# 2026-09-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.36765  |       1e-06    |   0.411756 |
| barab-szabi-2        |     0.451856 |       0.44614  |   0.449958 |
| k-d_tree_polars      |     0.462811 |       0.421476 |   0.455034 |
| Bori_Aron_solution-1 |     0.451508 |       0.54915  |   0.546463 |
| k-d_tree_pandas      |     0.463199 |       0.390974 |   0.550356 |
| barab-szabi-1        |     7.91532  |       0.477003 |   0.590407 |
| k-d_tree_sklearn     |     3.36341  |       1.13837  |   1.06982  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473774 |       0.450982 |   0.457948 |
| k-d_tree_polars      |     0.476755 |       0.438231 |   0.458663 |
| barab-szabi-1        |     0.47876  |       0.423899 |   0.465875 |
| Bori_Aron_solution-1 |     0.464332 |       0.57754  |   0.550694 |
| k-d_tree_pandas      |     0.471206 |       0.3938   |   0.556645 |
| k-d_tree_sklearn     |     0.483644 |       1.00212  |   1.08048  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472591 |       0.459456 |   0.45461  |
| barab-szabi-1        |     0.473346 |       0.459291 |   0.485025 |
| k-d_tree_polars      |     0.480283 |       0.458608 |   0.486208 |
| Bori_Aron_solution-1 |     0.474063 |       0.596374 |   0.566701 |
| k-d_tree_pandas      |     0.485482 |       0.419717 |   0.602722 |
| k-d_tree_sklearn     |     0.477211 |       1.04293  |   1.10034  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470046 |       0.517059 |   0.478281 |
| Bori_Aron_solution-1 |     0.475771 |       0.78701  |   0.571222 |
| k-d_tree_polars      |     0.475829 |       0.567552 |   0.583899 |
| barab-szabi-1        |     0.474892 |       0.565588 |   0.596846 |
| k-d_tree_pandas      |     0.477242 |       0.497765 |   0.737571 |
| k-d_tree_sklearn     |     0.479646 |       1.28686  |   1.16609  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470465 |       0.73288  |   0.515436 |
| Bori_Aron_solution-1 |     0.467263 |       1.43956  |   0.582534 |
| k-d_tree_polars      |     0.471581 |       0.959506 |   0.943717 |
| barab-szabi-1        |     0.486811 |       0.930189 |   0.962865 |
| k-d_tree_pandas      |     0.472686 |       0.814155 |   1.19502  |
| k-d_tree_sklearn     |     0.47935  |       2.13063  |   1.2462   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474962 |        4.97555 |   0.756369 |
| Bori_Aron_solution-1 |     0.474184 |       10.7198  |   0.806135 |
| k-d_tree_sklearn     |     0.480378 |       16.1079  |   1.30854  |
| barab-szabi-1        |     0.474432 |        5.33325 |   6.49111  |
| k-d_tree_polars      |     0.472487 |        5.33969 |   6.52574  |
| k-d_tree_pandas      |     0.473929 |        4.37189 |   6.92513  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.723694 |        69.1749 |    2.76711 |
| k-d_tree_sklearn     |     0.617219 |       229.963  |    3.75455 |
| Bori_Aron_solution-1 |     0.468557 |       151.168  |   16.1825  |