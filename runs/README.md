# 2026-07-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.14654  |       1e-06    |   0.410577 |
| barab-szabi-2        |     0.475338 |       0.449367 |   0.451839 |
| barab-szabi-1        |     0.475899 |       0.418466 |   0.459508 |
| Bori_Aron_solution-1 |     0.459084 |       0.554293 |   0.555858 |
| k-d_tree_polars      |     8.6182   |       0.47219  |   0.592542 |
| k-d_tree_pandas      |     0.477059 |       0.43667  |   0.634847 |
| k-d_tree_sklearn     |     2.85102  |       1.13745  |   1.06272  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.490308 |       0.426294 |   0.45545  |
| barab-szabi-1        |     0.493337 |       0.438049 |   0.457297 |
| barab-szabi-2        |     0.491486 |       0.456021 |   0.466197 |
| k-d_tree_pandas      |     0.476118 |       0.392895 |   0.583069 |
| Bori_Aron_solution-1 |     0.471428 |       0.564934 |   0.59984  |
| k-d_tree_sklearn     |     0.484173 |       1.01938  |   1.1278   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48842  |       0.470404 |   0.476928 |
| k-d_tree_polars      |     0.496872 |       0.465761 |   0.499609 |
| barab-szabi-1        |     0.497469 |       0.467822 |   0.506526 |
| Bori_Aron_solution-1 |     0.478948 |       0.601115 |   0.575443 |
| k-d_tree_pandas      |     0.510576 |       0.429079 |   0.628087 |
| k-d_tree_sklearn     |     0.485314 |       1.11531  |   1.1515   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492119 |       0.544064 |   0.508028 |
| Bori_Aron_solution-1 |     0.477592 |       0.80399  |   0.582908 |
| k-d_tree_polars      |     0.489283 |       0.580287 |   0.592809 |
| barab-szabi-1        |     0.49125  |       0.609629 |   0.608848 |
| k-d_tree_pandas      |     0.499922 |       0.515858 |   0.748731 |
| k-d_tree_sklearn     |     0.480057 |       1.31667  |   1.19701  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.500763 |       0.766157 |   0.56671  |
| Bori_Aron_solution-1 |     0.492496 |       1.56604  |   0.640213 |
| k-d_tree_polars      |     0.505933 |       0.971086 |   0.98228  |
| barab-szabi-1        |     0.512538 |       0.978647 |   1.0377   |
| k-d_tree_pandas      |     0.50788  |       0.832117 |   1.30038  |
| k-d_tree_sklearn     |     0.527756 |       2.33793  |   1.34024  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481714 |        5.40649 |   0.790279 |
| Bori_Aron_solution-1 |     0.491239 |       11.2042  |   0.860714 |
| k-d_tree_sklearn     |     0.496882 |       17.2171  |   1.31836  |
| barab-szabi-1        |     0.468743 |        5.30518 |   6.66984  |
| k-d_tree_polars      |     0.49924  |        5.42293 |   6.98436  |
| k-d_tree_pandas      |     0.476375 |        4.38953 |   7.22443  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604215 |        70.8008 |    2.83863 |
| k-d_tree_sklearn     |     0.752623 |       242.126  |    4.25001 |
| Bori_Aron_solution-1 |     0.505483 |       154.842  |   24.9254  |