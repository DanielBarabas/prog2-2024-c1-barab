# 2026-06-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.89522  |       0.625125 |   0.423086 |
| barab-szabi-1        |     0.456904 |       0.394053 |   0.437318 |
| k-d_tree_polars      |     0.452178 |       0.395998 |   0.442705 |
| solution-1           |     8.48141  |       1e-06    |   0.444295 |
| Bori_Aron_solution-1 |     0.440634 |       0.527674 |   0.531006 |
| k-d_tree_pandas      |     0.457771 |       0.374835 |   0.540344 |
| k-d_tree_sklearn     |     2.98407  |       1.26231  |   1.03536  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456876 |       0.425501 |   0.426393 |
| barab-szabi-1        |     0.45808  |       0.398657 |   0.427405 |
| k-d_tree_polars      |     0.462376 |       0.414361 |   0.440338 |
| Bori_Aron_solution-1 |     0.455205 |       0.54824  |   0.532677 |
| k-d_tree_pandas      |     0.464282 |       0.385626 |   0.549758 |
| k-d_tree_sklearn     |     0.471073 |       0.972172 |   1.06852  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462749 |       0.43551  |   0.438008 |
| k-d_tree_polars      |     0.479343 |       0.439218 |   0.460336 |
| barab-szabi-1        |     0.467119 |       0.428884 |   0.461461 |
| Bori_Aron_solution-1 |     0.467777 |       0.594421 |   0.553741 |
| k-d_tree_pandas      |     0.463358 |       0.408408 |   0.584574 |
| k-d_tree_sklearn     |     0.473422 |       1.02274  |   1.05168  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468879 |       0.511258 |   0.473802 |
| Bori_Aron_solution-1 |     0.481694 |       0.783845 |   0.55389  |
| k-d_tree_polars      |     0.465292 |       0.556231 |   0.561123 |
| barab-szabi-1        |     0.464926 |       0.573194 |   0.615034 |
| k-d_tree_pandas      |     0.463172 |       0.506418 |   0.720816 |
| k-d_tree_sklearn     |     0.465925 |       1.2566   |   1.10224  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470843 |       0.746042 |   0.511372 |
| Bori_Aron_solution-1 |     0.458042 |       1.45496  |   0.579615 |
| k-d_tree_polars      |     0.463856 |       0.918741 |   0.939828 |
| barab-szabi-1        |     0.463457 |       0.907838 |   0.991508 |
| k-d_tree_pandas      |     0.466662 |       0.785217 |   1.17271  |
| k-d_tree_sklearn     |     0.472335 |       2.10227  |   1.19245  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477387 |        5.54216 |   0.729697 |
| Bori_Aron_solution-1 |     0.469783 |       11.2339  |   0.800407 |
| k-d_tree_sklearn     |     0.463925 |       17.0799  |   1.24461  |
| k-d_tree_polars      |     0.468598 |        5.28304 |   7.20748  |
| barab-szabi-1        |     0.477319 |        5.29017 |   7.50839  |
| k-d_tree_pandas      |     0.46662  |        4.26966 |   7.51761  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456304 |        73.4338 |    2.49268 |
| k-d_tree_sklearn     |     0.699839 |       257.565  |    3.40087 |
| Bori_Aron_solution-1 |     0.45796  |       157.292  |   14.5316  |