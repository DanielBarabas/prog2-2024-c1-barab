# 2025-08-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.65544  |       1e-06    |   0.40619  |
| barab-szabi-2        |     0.522688 |       0.415536 |   0.419894 |
| k-d_tree_polars      |     0.538358 |       0.399491 |   0.426713 |
| barab-szabi-1        |     0.525569 |       0.413376 |   0.452088 |
| Bori_Aron_solution-1 |     0.52399  |       0.552699 |   0.544123 |
| k-d_tree_pandas      |     8.46815  |       0.423472 |   0.637402 |
| k-d_tree_sklearn     |     3.13808  |       1.04213  |   1.04532  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.533214 |       0.402615 |   0.423905 |
| barab-szabi-2        |     0.531688 |       0.416783 |   0.424458 |
| barab-szabi-1        |     0.535297 |       0.406402 |   0.430659 |
| Bori_Aron_solution-1 |     0.527314 |       0.545501 |   0.537621 |
| k-d_tree_pandas      |     0.532587 |       0.385942 |   0.548586 |
| k-d_tree_sklearn     |     0.559567 |       0.976819 |   1.0453   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531499 |       0.434567 |   0.43519  |
| k-d_tree_polars      |     0.535234 |       0.432287 |   0.454299 |
| barab-szabi-1        |     0.536108 |       0.429735 |   0.454654 |
| Bori_Aron_solution-1 |     0.528215 |       0.594878 |   0.541356 |
| k-d_tree_pandas      |     0.532077 |       0.40126  |   0.593161 |
| k-d_tree_sklearn     |     0.53651  |       1.00555  |   1.06059  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533765 |       0.493081 |   0.462892 |
| k-d_tree_polars      |     0.532659 |       0.551296 |   0.544783 |
| Bori_Aron_solution-1 |     0.527722 |       0.760684 |   0.558589 |
| barab-szabi-1        |     0.535466 |       0.549112 |   0.560058 |
| k-d_tree_pandas      |     0.534329 |       0.483632 |   0.726259 |
| k-d_tree_sklearn     |     0.5374   |       1.23744  |   1.12423  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528611 |       0.754637 |   0.493124 |
| Bori_Aron_solution-1 |     0.527317 |       1.39392  |   0.578526 |
| k-d_tree_polars      |     0.532379 |       0.882015 |   0.89159  |
| barab-szabi-1        |     0.531726 |       0.884876 |   0.932552 |
| k-d_tree_pandas      |     0.533786 |       0.754776 |   1.16166  |
| k-d_tree_sklearn     |     0.535568 |       2.03052  |   1.1967   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53297  |        5.04608 |   0.719366 |
| Bori_Aron_solution-1 |     0.530855 |       10.3028  |   0.836986 |
| k-d_tree_sklearn     |     0.539131 |       15.6133  |   1.29009  |
| barab-szabi-1        |     0.531855 |        4.99244 |   6.34178  |
| k-d_tree_polars      |     0.536591 |        4.99079 |   6.34748  |
| k-d_tree_pandas      |     0.532382 |        3.94301 |   6.74723  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53358  |        70.9163 |    2.61032 |
| k-d_tree_sklearn     |     0.550547 |       225.279  |    4.28121 |
| Bori_Aron_solution-1 |     0.646937 |       142.547  |   18.6403  |