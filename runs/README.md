# 2026-04-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.458105 |       0.428141 |   0.428589 |
| k-d_tree_polars      |     0.458032 |       0.399473 |   0.430063 |
| barab-szabi-1        |     0.452298 |       0.397504 |   0.43178  |
| solution-1           |     8.73975  |       1e-06    |   0.495155 |
| k-d_tree_pandas      |     0.45592  |       0.380486 |   0.548503 |
| Bori_Aron_solution-1 |     0.456187 |       0.541913 |   0.574595 |
| k-d_tree_sklearn     |    10.0472   |       1.29702  |   1.0902   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.452934 |       0.426269 |   0.422791 |
| k-d_tree_polars      |     0.454809 |       0.409916 |   0.429215 |
| barab-szabi-1        |     0.460465 |       0.406595 |   0.434622 |
| Bori_Aron_solution-1 |     0.456839 |       0.546926 |   0.538479 |
| k-d_tree_pandas      |     0.450649 |       0.37827  |   0.544867 |
| k-d_tree_sklearn     |     0.45838  |       0.98988  |   1.06512  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.457306 |       0.44136  |   0.436116 |
| barab-szabi-1        |     0.451818 |       0.432984 |   0.466189 |
| k-d_tree_polars      |     0.456677 |       0.432559 |   0.479157 |
| Bori_Aron_solution-1 |     0.456459 |       0.589563 |   0.546783 |
| k-d_tree_pandas      |     0.453141 |       0.40811  |   0.585151 |
| k-d_tree_sklearn     |     0.459125 |       1.00296  |   1.07195  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456398 |       0.503662 |   0.468847 |
| Bori_Aron_solution-1 |     0.460173 |       0.775515 |   0.553066 |
| k-d_tree_polars      |     0.456274 |       0.557031 |   0.557179 |
| barab-szabi-1        |     0.455092 |       0.565046 |   0.564882 |
| k-d_tree_pandas      |     0.456408 |       0.507691 |   0.730597 |
| k-d_tree_sklearn     |     0.457426 |       1.27755  |   1.14861  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.451409 |       0.7114   |   0.496588 |
| Bori_Aron_solution-1 |     0.451397 |       1.44035  |   0.574656 |
| k-d_tree_polars      |     0.460557 |       0.92429  |   0.894031 |
| barab-szabi-1        |     0.454043 |       0.924745 |   0.935795 |
| k-d_tree_pandas      |     0.454035 |       0.801205 |   1.15735  |
| k-d_tree_sklearn     |     0.459832 |       2.10506  |   1.20492  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496875 |        5.42658 |   0.780979 |
| Bori_Aron_solution-1 |     0.472763 |       11.702   |   0.892075 |
| k-d_tree_sklearn     |     0.457441 |       18.0616  |   1.34152  |
| barab-szabi-1        |     0.487432 |        5.5051  |   7.0074   |
| k-d_tree_polars      |     0.501298 |        5.67983 |   7.27144  |
| k-d_tree_pandas      |     0.467892 |        4.54097 |   7.68627  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.724933 |        74.2357 |    2.86196 |
| k-d_tree_sklearn     |     0.475471 |       257.027  |    4.00061 |
| Bori_Aron_solution-1 |     0.46887  |       155.472  |   17.7211  |