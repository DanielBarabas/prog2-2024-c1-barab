# 2024-12-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.90919  |       1e-06    |   0.39074  |
| barab-szabi-2        |     0.651615 |       0.416069 |   0.408872 |
| barab-szabi-1        |     0.673777 |       0.423759 |   0.415138 |
| k-d_tree_polars      |     0.667918 |       0.433419 |   0.430715 |
| Bori_Aron_solution-1 |     0.637319 |       0.568819 |   0.554451 |
| k-d_tree_pandas      |     0.649055 |       0.415171 |   0.577673 |
| k-d_tree_sklearn     |    10.7813   |       1.08996  |   1.06772  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.677071 |       0.416785 |   0.413782 |
| k-d_tree_polars      |     0.645732 |       0.436005 |   0.415135 |
| barab-szabi-1        |     0.654104 |       0.432678 |   0.417556 |
| Bori_Aron_solution-1 |     0.646289 |       0.570958 |   0.55545  |
| k-d_tree_pandas      |     0.647734 |       0.424433 |   0.569176 |
| k-d_tree_sklearn     |     0.655495 |       0.967453 |   1.05722  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.649682 |       0.426115 |   0.419858 |
| barab-szabi-1        |     0.641656 |       0.456398 |   0.451751 |
| k-d_tree_polars      |     0.665582 |       0.456132 |   0.46169  |
| Bori_Aron_solution-1 |     0.644702 |       0.614378 |   0.562098 |
| k-d_tree_pandas      |     0.64364  |       0.426023 |   0.613578 |
| k-d_tree_sklearn     |     0.661605 |       1.01376  |   1.0629   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.657388 |       0.506629 |   0.467946 |
| k-d_tree_polars      |     0.658799 |       0.568485 |   0.545907 |
| barab-szabi-1        |     0.660605 |       0.583439 |   0.554662 |
| Bori_Aron_solution-1 |     0.658606 |       0.797881 |   0.593148 |
| k-d_tree_pandas      |     0.655612 |       0.525743 |   0.750218 |
| k-d_tree_sklearn     |     0.669126 |       1.22864  |   1.16067  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.645063 |       0.767934 |   0.535364 |
| Bori_Aron_solution-1 |     0.637377 |       1.4489   |   0.597947 |
| k-d_tree_polars      |     0.662303 |       0.897297 |   0.906264 |
| barab-szabi-1        |     0.658417 |       0.899229 |   0.964662 |
| k-d_tree_pandas      |     0.648028 |       0.775356 |   1.20793  |
| k-d_tree_sklearn     |     0.66515  |       2.20042  |   1.25377  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.645258 |        5.83167 |   0.777532 |
| Bori_Aron_solution-1 |     0.642589 |       11.3166  |   0.856861 |
| k-d_tree_sklearn     |     0.652802 |       17.815   |   1.35312  |
| k-d_tree_polars      |     0.64321  |        4.96831 |   7.12261  |
| barab-szabi-1        |     0.647845 |        4.99337 |   7.12356  |
| k-d_tree_pandas      |     0.654781 |        3.95306 |   7.63605  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.666347 |        75.6311 |    2.99019 |
| k-d_tree_sklearn     |     0.65753  |       240.046  |    4.36493 |
| Bori_Aron_solution-1 |     0.662235 |       154.606  |   17.0101  |