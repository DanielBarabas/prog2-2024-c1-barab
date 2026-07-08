# 2026-07-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.3839   |       1e-06    |   0.399714 |
| barab-szabi-2        |     7.98629  |       0.588085 |   0.443389 |
| barab-szabi-1        |     0.462975 |       0.405999 |   0.446202 |
| k-d_tree_polars      |     0.457201 |       0.409012 |   0.448086 |
| k-d_tree_pandas      |     0.463292 |       0.385664 |   0.542033 |
| Bori_Aron_solution-1 |     0.457141 |       0.536726 |   0.544269 |
| k-d_tree_sklearn     |     2.96963  |       1.09676  |   1.05275  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465286 |       0.434021 |   0.44283  |
| k-d_tree_polars      |     0.466897 |       0.42299  |   0.446624 |
| barab-szabi-1        |     0.464485 |       0.417099 |   0.453834 |
| Bori_Aron_solution-1 |     0.453733 |       0.553263 |   0.542511 |
| k-d_tree_pandas      |     0.482751 |       0.387051 |   0.553005 |
| k-d_tree_sklearn     |     0.471867 |       0.991632 |   1.07627  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467491 |       0.447696 |   0.44805  |
| barab-szabi-1        |     0.468993 |       0.440211 |   0.479537 |
| k-d_tree_polars      |     0.463451 |       0.445535 |   0.479863 |
| Bori_Aron_solution-1 |     0.461685 |       0.584515 |   0.538784 |
| k-d_tree_pandas      |     0.468116 |       0.404472 |   0.589332 |
| k-d_tree_sklearn     |     0.4715   |       1.04557  |   1.10993  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464561 |       0.498577 |   0.479492 |
| Bori_Aron_solution-1 |     0.461521 |       0.766063 |   0.553776 |
| k-d_tree_polars      |     0.466553 |       0.561006 |   0.564005 |
| barab-szabi-1        |     0.470771 |       0.559805 |   0.583738 |
| k-d_tree_pandas      |     0.471812 |       0.494539 |   0.729949 |
| k-d_tree_sklearn     |     0.469644 |       1.25756  |   1.11867  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462763 |       0.727878 |   0.501029 |
| Bori_Aron_solution-1 |     0.457142 |       1.42059  |   0.577064 |
| k-d_tree_polars      |     0.4665   |       0.90718  |   0.905947 |
| barab-szabi-1        |     0.460346 |       0.920413 |   0.967023 |
| k-d_tree_pandas      |     0.460945 |       0.803778 |   1.17378  |
| k-d_tree_sklearn     |     0.464035 |       2.09704  |   1.23327  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465358 |        5.10684 |   0.740435 |
| Bori_Aron_solution-1 |     0.457893 |       10.9031  |   0.809795 |
| k-d_tree_sklearn     |     0.467024 |       16.5859  |   1.29999  |
| k-d_tree_polars      |     0.464279 |        5.27876 |   6.57744  |
| barab-szabi-1        |     0.469717 |        5.38511 |   6.78906  |
| k-d_tree_pandas      |     0.469213 |        4.35099 |   6.98207  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462126 |        71.3855 |    2.66994 |
| k-d_tree_sklearn     |     0.841456 |       237.519  |    3.96464 |
| Bori_Aron_solution-1 |     0.458918 |       151.628  |   26.2179  |