# 2024-07-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.71957  |       1e-06    |   0.382621 |
| barab-szabi-1        |     0.568239 |       0.411352 |   0.388297 |
| barab-szabi-2        |     0.581504 |       0.414362 |   0.388521 |
| k-d_tree_polars      |     0.573444 |       0.399875 |   0.390935 |
| Bori_Aron_solution-1 |     0.559632 |       0.539676 |   0.539086 |
| k-d_tree_pandas      |     0.57454  |       0.389087 |   0.544676 |
| k-d_tree_sklearn     |    10.5293   |       1.05615  |   0.722476 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566974 |       0.393021 |   0.389707 |
| k-d_tree_polars      |     0.572554 |       0.41318  |   0.394868 |
| barab-szabi-1        |     0.571446 |       0.414144 |   0.404862 |
| Bori_Aron_solution-1 |     0.572794 |       0.545817 |   0.542717 |
| k-d_tree_pandas      |     0.564662 |       0.396171 |   0.552925 |
| k-d_tree_sklearn     |     0.569224 |       0.93437  |   0.718696 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566918 |       0.406914 |   0.401626 |
| k-d_tree_polars      |     0.562276 |       0.430525 |   0.417511 |
| barab-szabi-1        |     0.568202 |       0.433003 |   0.448644 |
| Bori_Aron_solution-1 |     0.565358 |       0.581614 |   0.535651 |
| k-d_tree_pandas      |     0.569549 |       0.407943 |   0.583888 |
| k-d_tree_sklearn     |     0.593299 |       0.949292 |   0.75419  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558097 |       0.475281 |   0.430541 |
| k-d_tree_polars      |     0.575889 |       0.552503 |   0.530184 |
| barab-szabi-1        |     0.575677 |       0.53927  |   0.539961 |
| Bori_Aron_solution-1 |     0.557587 |       0.754626 |   0.546123 |
| k-d_tree_pandas      |     0.577658 |       0.491342 |   0.712494 |
| k-d_tree_sklearn     |     0.566592 |       1.17919  |   0.79436  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562556 |       0.726262 |   0.470879 |
| Bori_Aron_solution-1 |     0.567608 |       1.40642  |   0.574482 |
| k-d_tree_sklearn     |     0.561569 |       2.06648  |   0.888523 |
| k-d_tree_polars      |     0.562868 |       0.884522 |   0.904747 |
| barab-szabi-1        |     0.562956 |       0.863605 |   0.910892 |
| k-d_tree_pandas      |     0.599881 |       0.748946 |   1.15819  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587953 |        5.8052  |   0.771331 |
| Bori_Aron_solution-1 |     0.582705 |       11.2497  |   0.881579 |
| k-d_tree_sklearn     |     0.579111 |       17.3684  |   1.00312  |
| barab-szabi-1        |     0.578492 |        4.89806 |   7.04946  |
| k-d_tree_polars      |     0.580739 |        4.91463 |   7.1315   |
| k-d_tree_pandas      |     0.598707 |        3.91171 |   7.59393  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.906072 |         73.058 |    3.63909 |
| k-d_tree_sklearn     |     0.585943 |        232.75  |    3.9553  |
| Bori_Aron_solution-1 |     0.582455 |        146.933 |   17.662   |