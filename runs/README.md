# 2025-10-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.87683  |       1e-06    |   0.350629 |
| k-d_tree_polars      |     0.514617 |       0.391188 |   0.415247 |
| barab-szabi-1        |     0.510173 |       0.400025 |   0.416133 |
| barab-szabi-2        |     0.487211 |       0.438    |   0.416725 |
| Bori_Aron_solution-1 |     0.501635 |       0.531764 |   0.545754 |
| k-d_tree_pandas      |     7.82226  |       0.397196 |   0.605489 |
| k-d_tree_sklearn     |     2.9036   |       0.955732 |   1.01035  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.507841 |       0.412814 |   0.419585 |
| k-d_tree_polars      |     0.505663 |       0.401246 |   0.422716 |
| barab-szabi-1        |     0.508764 |       0.399514 |   0.424911 |
| Bori_Aron_solution-1 |     0.503162 |       0.541506 |   0.542471 |
| k-d_tree_pandas      |     0.517896 |       0.379996 |   0.544104 |
| k-d_tree_sklearn     |     0.507251 |       0.925134 |   1.05588  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.504597 |       0.428859 |   0.430159 |
| k-d_tree_polars      |     0.504129 |       0.425189 |   0.438441 |
| barab-szabi-1        |     0.5076   |       0.415983 |   0.475212 |
| Bori_Aron_solution-1 |     0.497288 |       0.591813 |   0.540585 |
| k-d_tree_pandas      |     0.517037 |       0.393003 |   0.571301 |
| k-d_tree_sklearn     |     0.51076  |       1.00313  |   1.0541   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.502691 |       0.499701 |   0.454556 |
| barab-szabi-1        |     0.501198 |       0.537575 |   0.533899 |
| Bori_Aron_solution-1 |     0.49301  |       0.722381 |   0.535356 |
| k-d_tree_polars      |     0.508141 |       0.55536  |   0.540246 |
| k-d_tree_pandas      |     0.503421 |       0.484564 |   0.694829 |
| k-d_tree_sklearn     |     0.519338 |       1.18542  |   1.05523  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.50193  |       0.716465 |   0.508578 |
| Bori_Aron_solution-1 |     0.494324 |       1.32738  |   0.575361 |
| k-d_tree_polars      |     0.514301 |       0.89703  |   0.851185 |
| barab-szabi-1        |     0.500131 |       0.867932 |   0.88751  |
| k-d_tree_pandas      |     0.502285 |       0.743514 |   1.08364  |
| k-d_tree_sklearn     |     0.501274 |       1.97286  |   1.12329  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.510353 |        5.30331 |   0.702805 |
| Bori_Aron_solution-1 |     0.506635 |       10.4698  |   0.929516 |
| k-d_tree_sklearn     |     0.520399 |       15.0092  |   1.30414  |
| barab-szabi-1        |     0.50826  |        5.10645 |   6.27984  |
| k-d_tree_polars      |     0.497318 |        5.13659 |   6.46032  |
| k-d_tree_pandas      |     0.500661 |        3.96405 |   6.71243  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.511089 |        69.7293 |    2.64151 |
| k-d_tree_sklearn     |     0.52167  |       181.628  |    4.33466 |
| Bori_Aron_solution-1 |     0.636061 |       138.374  |   14.7376  |