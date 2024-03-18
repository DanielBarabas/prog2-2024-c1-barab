# 2024-03-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.696727 |       0.378173 |   0.354033 |
| solution-1           |     7.90372  |       1e-06    |   0.358239 |
| barab-szabi-1        |     0.744694 |       0.396918 |   0.362096 |
| k-d_tree_polars      |     0.724824 |       0.40187  |   0.366233 |
| Bori_Aron_solution-1 |     0.685252 |       0.499312 |   0.50158  |
| k-d_tree_pandas      |     8.31599  |       0.402653 |   0.536923 |
| k-d_tree_sklearn     |     3.22784  |       0.926574 |   0.673445 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.74688  |       0.375546 |   0.374123 |
| k-d_tree_polars      |     0.772486 |       0.420436 |   0.3752   |
| barab-szabi-1        |     0.765405 |       0.410129 |   0.384406 |
| k-d_tree_pandas      |     0.73924  |       0.426946 |   0.539819 |
| Bori_Aron_solution-1 |     0.729325 |       0.526774 |   0.54329  |
| k-d_tree_sklearn     |     0.760293 |       0.875928 |   0.682926 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.749976 |       0.381692 |   0.372245 |
| k-d_tree_polars      |     0.730978 |       0.435471 |   0.391325 |
| barab-szabi-1        |     0.741021 |       0.447387 |   0.396862 |
| Bori_Aron_solution-1 |     0.725614 |       0.542122 |   0.504406 |
| k-d_tree_pandas      |     0.749524 |       0.410019 |   0.571911 |
| k-d_tree_sklearn     |     0.734761 |       0.904006 |   0.707532 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.738505 |       0.465584 |   0.416149 |
| k-d_tree_polars      |     0.735824 |       0.547119 |   0.509033 |
| Bori_Aron_solution-1 |     0.725381 |       0.736943 |   0.522794 |
| barab-szabi-1        |     0.758778 |       0.563043 |   0.524306 |
| k-d_tree_pandas      |     0.727323 |       0.486924 |   0.69188  |
| k-d_tree_sklearn     |     0.750489 |       1.12474  |   0.78343  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.768254 |       0.700303 |   0.463103 |
| Bori_Aron_solution-1 |     0.735487 |       1.44138  |   0.571069 |
| k-d_tree_sklearn     |     0.760161 |       2.01229  |   0.866369 |
| k-d_tree_polars      |     0.73839  |       0.880309 |   0.876469 |
| barab-szabi-1        |     0.743651 |       0.883769 |   0.905286 |
| k-d_tree_pandas      |     0.76878  |       0.790005 |   1.19315  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734848 |        5.67347 |   0.776325 |
| Bori_Aron_solution-1 |     0.738011 |       11.0505  |   0.806163 |
| k-d_tree_sklearn     |     0.752348 |       16.6979  |   1.06156  |
| barab-szabi-1        |     0.737121 |        4.94824 |   6.73989  |
| k-d_tree_polars      |     0.73161  |        5.01792 |   6.77457  |
| k-d_tree_pandas      |     0.733685 |        4.04368 |   7.15438  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.72628  |        73.2206 |    3.69143 |
| k-d_tree_sklearn     |     1.01337  |       230.221  |    4.94442 |
| Bori_Aron_solution-1 |     0.909524 |       143.735  |   18.4835  |