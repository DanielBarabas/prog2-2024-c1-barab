# 2026-05-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474566 |       0.437702 |   0.434871 |
| k-d_tree_polars      |     0.467629 |       0.412596 |   0.43932  |
| solution-1           |     8.0475   |       2e-06    |   0.445569 |
| Bori_Aron_solution-1 |     0.467466 |       0.557549 |   0.554363 |
| k-d_tree_pandas      |     0.470348 |       0.387145 |   0.563154 |
| barab-szabi-1        |     8.575    |       0.4677   |   0.594857 |
| k-d_tree_sklearn     |     3.07064  |       1.20609  |   1.11294  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482321 |       0.439392 |   0.437503 |
| barab-szabi-1        |     0.478101 |       0.429168 |   0.441348 |
| k-d_tree_polars      |     0.476039 |       0.416313 |   0.450418 |
| k-d_tree_pandas      |     0.483348 |       0.406731 |   0.57442  |
| Bori_Aron_solution-1 |     0.476222 |       0.574607 |   0.586055 |
| k-d_tree_sklearn     |     0.481896 |       1.05678  |   1.10203  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482279 |       0.449141 |   0.443861 |
| k-d_tree_polars      |     0.48474  |       0.446125 |   0.469443 |
| barab-szabi-1        |     0.481971 |       0.445909 |   0.472469 |
| Bori_Aron_solution-1 |     0.455675 |       0.608042 |   0.567616 |
| k-d_tree_pandas      |     0.483243 |       0.422209 |   0.597318 |
| k-d_tree_sklearn     |     0.466398 |       1.03114  |   1.07329  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472176 |       0.543612 |   0.483416 |
| k-d_tree_polars      |     0.480468 |       0.565887 |   0.563671 |
| barab-szabi-1        |     0.477832 |       0.590097 |   0.569989 |
| Bori_Aron_solution-1 |     0.47535  |       0.785337 |   0.580428 |
| k-d_tree_pandas      |     0.470985 |       0.512345 |   0.744987 |
| k-d_tree_sklearn     |     0.469962 |       1.26177  |   1.15182  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.495702 |       1.50138  |   0.60034  |
| barab-szabi-2        |     0.486844 |       0.782664 |   0.613612 |
| k-d_tree_polars      |     0.487782 |       0.936167 |   0.995235 |
| barab-szabi-1        |     0.47466  |       0.929848 |   1.0157   |
| k-d_tree_sklearn     |     0.486141 |       2.23613  |   1.2112   |
| k-d_tree_pandas      |     0.508722 |       0.836905 |   1.23313  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479356 |        5.51136 |   0.704037 |
| Bori_Aron_solution-1 |     0.494596 |       11.4756  |   0.828479 |
| k-d_tree_sklearn     |     0.487018 |       18.2079  |   1.3301   |
| barab-szabi-1        |     0.486874 |        5.17641 |   7.40595  |
| k-d_tree_polars      |     0.488556 |        5.27048 |   7.462    |
| k-d_tree_pandas      |     0.476406 |        4.17967 |   7.85301  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486007 |        76.8801 |    2.33414 |
| k-d_tree_sklearn     |     0.480649 |       261.082  |    3.25657 |
| Bori_Aron_solution-1 |     0.482899 |       150.633  |   23.4751  |