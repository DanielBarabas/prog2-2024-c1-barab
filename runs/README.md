# 2025-12-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495347 |       0.432605 |   0.406488 |
| solution-1           |     7.16615  |       1e-06    |   0.408694 |
| barab-szabi-1        |     0.486006 |       0.39293  |   0.418821 |
| k-d_tree_polars      |     0.497993 |       0.403142 |   0.424484 |
| Bori_Aron_solution-1 |     0.504391 |       0.523557 |   0.568259 |
| k-d_tree_pandas      |     8.20802  |       0.400277 |   0.61243  |
| k-d_tree_sklearn     |     3.03344  |       0.91983  |   1.00164  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496776 |       0.409412 |   0.407851 |
| k-d_tree_polars      |     0.494944 |       0.397632 |   0.428776 |
| barab-szabi-1        |     0.505179 |       0.402019 |   0.431366 |
| k-d_tree_pandas      |     0.514316 |       0.382667 |   0.536806 |
| Bori_Aron_solution-1 |     0.488724 |       0.558806 |   0.553319 |
| k-d_tree_sklearn     |     0.492666 |       0.976614 |   1.03896  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.501058 |       0.43382  |   0.421447 |
| k-d_tree_polars      |     0.507022 |       0.436051 |   0.457525 |
| barab-szabi-1        |     0.50789  |       0.429224 |   0.463761 |
| Bori_Aron_solution-1 |     0.495775 |       0.631907 |   0.551572 |
| k-d_tree_pandas      |     0.488476 |       0.390529 |   0.5669   |
| k-d_tree_sklearn     |     0.49863  |       1.00175  |   1.03919  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480384 |       0.513136 |   0.456261 |
| k-d_tree_polars      |     0.492222 |       0.542773 |   0.523891 |
| Bori_Aron_solution-1 |     0.473447 |       0.742732 |   0.534119 |
| barab-szabi-1        |     0.486961 |       0.547498 |   0.536986 |
| k-d_tree_pandas      |     0.51029  |       0.460763 |   0.69088  |
| k-d_tree_sklearn     |     0.520786 |       1.17693  |   1.09073  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.490751 |       0.72427  |   0.521365 |
| Bori_Aron_solution-1 |     0.495654 |       1.33293  |   0.558366 |
| k-d_tree_polars      |     0.485775 |       0.847006 |   0.862934 |
| barab-szabi-1        |     0.494126 |       0.874786 |   0.889077 |
| k-d_tree_pandas      |     0.50153  |       0.734451 |   1.09592  |
| k-d_tree_sklearn     |     0.499479 |       2.01166  |   1.14728  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491431 |        5.30327 |   0.755054 |
| Bori_Aron_solution-1 |     0.507964 |       10.3771  |   0.933442 |
| k-d_tree_sklearn     |     0.500198 |       14.9826  |   1.33487  |
| barab-szabi-1        |     0.49792  |        4.95512 |   6.52239  |
| k-d_tree_pandas      |     0.476691 |        3.80051 |   6.59584  |
| k-d_tree_polars      |     0.501383 |        4.87399 |   6.69382  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.50561  |        92.1912 |    2.86434 |
| k-d_tree_sklearn     |     0.502083 |       180.238  |    4.33006 |
| Bori_Aron_solution-1 |     0.581476 |       137.637  |   16.7519  |