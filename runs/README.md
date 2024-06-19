# 2024-06-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.783381 |       0.39629  |   0.392853 |
| barab-szabi-1        |     0.824331 |       0.41488  |   0.397797 |
| k-d_tree_polars      |     0.783928 |       0.421097 |   0.446202 |
| Bori_Aron_solution-1 |     0.771788 |       0.518184 |   0.540914 |
| solution-1           |     8.3382   |       1e-06    |   0.618268 |
| k-d_tree_pandas      |     8.48168  |       0.502316 |   0.774916 |
| k-d_tree_sklearn     |     3.46217  |       1.12215  |   0.790173 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.806197 |       0.411945 |   0.398416 |
| barab-szabi-1        |     0.825316 |       0.433372 |   0.408058 |
| barab-szabi-2        |     0.815059 |       0.397968 |   0.410528 |
| Bori_Aron_solution-1 |     0.794275 |       0.538938 |   0.528435 |
| k-d_tree_pandas      |     0.819722 |       0.387912 |   0.531631 |
| k-d_tree_sklearn     |     0.825315 |       0.958321 |   0.761741 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.825878 |       0.418814 |   0.412966 |
| k-d_tree_polars      |     0.821595 |       0.444371 |   0.430034 |
| barab-szabi-1        |     0.815823 |       0.431737 |   0.433735 |
| Bori_Aron_solution-1 |     0.81471  |       0.580976 |   0.550452 |
| k-d_tree_pandas      |     0.830559 |       0.416866 |   0.609385 |
| k-d_tree_sklearn     |     0.8359   |       1.01575  |   0.78699  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.823288 |       0.484427 |   0.464363 |
| k-d_tree_polars      |     0.811618 |       0.548515 |   0.53371  |
| barab-szabi-1        |     0.829747 |       0.554131 |   0.543076 |
| Bori_Aron_solution-1 |     0.80319  |       0.787311 |   0.567035 |
| k-d_tree_pandas      |     0.821854 |       0.490505 |   0.720258 |
| k-d_tree_sklearn     |     0.841615 |       1.24448  |   0.843213 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.806272 |       0.723474 |   0.480719 |
| Bori_Aron_solution-1 |     0.813022 |       1.42282  |   0.573139 |
| k-d_tree_polars      |     0.810379 |       0.871703 |   0.90414  |
| k-d_tree_sklearn     |     0.816975 |       2.09411  |   0.953088 |
| barab-szabi-1        |     0.811241 |       0.887807 |   0.960395 |
| k-d_tree_pandas      |     0.803219 |       0.759691 |   1.17778  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.813399 |        5.60788 |   0.784023 |
| Bori_Aron_solution-1 |     0.804272 |       11.2184  |   0.870654 |
| k-d_tree_sklearn     |     0.813274 |       17.0013  |   1.11155  |
| k-d_tree_polars      |     0.83415  |        5.03022 |   6.88346  |
| barab-szabi-1        |     0.829925 |        5.02598 |   6.9206   |
| k-d_tree_pandas      |     0.820326 |        4.01832 |   7.25288  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.14147  |        78.6172 |     4.088  |
| k-d_tree_sklearn     |     0.928347 |       242.812  |     4.5311 |
| Bori_Aron_solution-1 |     0.82203  |       152.263  |    17.8936 |