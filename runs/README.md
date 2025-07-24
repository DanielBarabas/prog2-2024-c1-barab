# 2025-07-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.550515 |       0.397626 |   0.423324 |
| barab-szabi-1        |     0.535309 |       0.405622 |   0.423931 |
| barab-szabi-2        |     7.49264  |       0.633563 |   0.427573 |
| solution-1           |     7.19312  |       1e-06    |   0.462166 |
| Bori_Aron_solution-1 |     0.528727 |       0.546475 |   0.540157 |
| k-d_tree_pandas      |     0.559327 |       0.380332 |   0.543838 |
| k-d_tree_sklearn     |     3.012    |       1.13106  |   1.03631  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546578 |       0.414943 |   0.418903 |
| k-d_tree_polars      |     0.550136 |       0.407309 |   0.424183 |
| barab-szabi-1        |     0.552516 |       0.405933 |   0.425509 |
| Bori_Aron_solution-1 |     0.541922 |       0.550965 |   0.539667 |
| k-d_tree_pandas      |     0.550213 |       0.390803 |   0.556696 |
| k-d_tree_sklearn     |     0.553562 |       0.967886 |   1.05765  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549545 |       0.436033 |   0.432882 |
| k-d_tree_polars      |     0.547626 |       0.431291 |   0.449476 |
| barab-szabi-1        |     0.546625 |       0.429931 |   0.457512 |
| Bori_Aron_solution-1 |     0.544923 |       0.586845 |   0.547184 |
| k-d_tree_pandas      |     0.549966 |       0.401759 |   0.596475 |
| k-d_tree_sklearn     |     0.556628 |       1.00787  |   1.06939  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548856 |       0.498281 |   0.462521 |
| k-d_tree_polars      |     0.550832 |       0.547568 |   0.543715 |
| Bori_Aron_solution-1 |     0.547021 |       0.767208 |   0.563333 |
| barab-szabi-1        |     0.547726 |       0.555611 |   0.58823  |
| k-d_tree_pandas      |     0.54886  |       0.484251 |   0.722547 |
| k-d_tree_sklearn     |     0.552174 |       1.24329  |   1.11939  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543077 |       0.742579 |   0.492508 |
| Bori_Aron_solution-1 |     0.540977 |       1.40651  |   0.591032 |
| k-d_tree_polars      |     0.549512 |       0.8874   |   0.901774 |
| barab-szabi-1        |     0.547343 |       0.888901 |   0.944802 |
| k-d_tree_pandas      |     0.551778 |       0.766532 |   1.17229  |
| k-d_tree_sklearn     |     0.554991 |       2.06195  |   1.20535  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549599 |        5.1871  |   0.774132 |
| Bori_Aron_solution-1 |     0.545422 |       10.6888  |   0.852672 |
| k-d_tree_sklearn     |     0.553994 |       15.9654  |   1.28052  |
| k-d_tree_polars      |     0.546441 |        5.02679 |   6.46007  |
| barab-szabi-1        |     0.553416 |        4.99738 |   6.49126  |
| k-d_tree_pandas      |     0.552363 |        3.98679 |   6.9678   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550715 |         70.423 |    2.84987 |
| k-d_tree_sklearn     |     0.710743 |        230.564 |    4.0401  |
| Bori_Aron_solution-1 |     0.54909  |        145.301 |   16.9702  |