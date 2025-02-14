# 2025-02-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.31825  |       1e-06    |   0.381184 |
| barab-szabi-1        |     0.608703 |       0.419831 |   0.41496  |
| k-d_tree_polars      |     0.607936 |       0.416203 |   0.417997 |
| barab-szabi-2        |     3.77726  |       0.43267  |   0.420993 |
| Bori_Aron_solution-1 |     4.47577  |       0.560094 |   0.494955 |
| k-d_tree_pandas      |     0.610271 |       0.401311 |   0.585228 |
| k-d_tree_sklearn     |     3.16009  |       1.04909  |   1.06684  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606056 |       0.42927  |   0.423023 |
| barab-szabi-1        |     0.592766 |       0.44495  |   0.437007 |
| k-d_tree_polars      |     0.601401 |       0.423054 |   0.437809 |
| Bori_Aron_solution-1 |     0.609804 |       0.584692 |   0.562127 |
| k-d_tree_pandas      |     0.625181 |       0.444878 |   0.58364  |
| k-d_tree_sklearn     |     0.612842 |       1.00752  |   1.06732  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.628618 |       0.45277  |   0.434256 |
| barab-szabi-1        |     0.607776 |       0.451141 |   0.452595 |
| k-d_tree_polars      |     0.605647 |       0.482835 |   0.463537 |
| Bori_Aron_solution-1 |     0.620322 |       0.628774 |   0.580161 |
| k-d_tree_pandas      |     0.605319 |       0.415654 |   0.615218 |
| k-d_tree_sklearn     |     0.609433 |       1.05215  |   1.09211  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604007 |       0.498558 |   0.46007  |
| k-d_tree_polars      |     0.602067 |       0.570871 |   0.549342 |
| barab-szabi-1        |     0.609837 |       0.56427  |   0.549595 |
| Bori_Aron_solution-1 |     0.603217 |       0.776197 |   0.571139 |
| k-d_tree_pandas      |     0.598659 |       0.497473 |   0.766667 |
| k-d_tree_sklearn     |     0.614389 |       1.24192  |   1.13834  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591014 |       0.774228 |   0.567835 |
| Bori_Aron_solution-1 |     0.59727  |       1.42529  |   0.600011 |
| k-d_tree_polars      |     0.609813 |       0.888807 |   0.91497  |
| barab-szabi-1        |     0.599683 |       0.873987 |   0.956458 |
| k-d_tree_pandas      |     0.606781 |       0.757858 |   1.23047  |
| k-d_tree_sklearn     |     0.609001 |       2.19652  |   1.27741  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.597566 |        5.5689  |   0.785309 |
| Bori_Aron_solution-1 |     0.591989 |       10.7848  |   0.899265 |
| k-d_tree_sklearn     |     0.622681 |       17.561   |   1.45875  |
| k-d_tree_polars      |     0.639591 |        4.95795 |   7.12093  |
| barab-szabi-1        |     0.611904 |        4.92824 |   7.16191  |
| k-d_tree_pandas      |     0.631285 |        3.83055 |   7.17357  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.85737  |        79.5894 |    3.75706 |
| k-d_tree_sklearn     |     0.695564 |       236.058  |    4.36277 |
| Bori_Aron_solution-1 |     0.650513 |       159.582  |   16.1958  |