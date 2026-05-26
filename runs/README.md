# 2026-05-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.11832  |       1e-06    |   0.360531 |
| barab-szabi-2        |     0.450244 |       0.428978 |   0.428479 |
| k-d_tree_polars      |     0.453249 |       0.399695 |   0.434198 |
| barab-szabi-1        |     7.6025   |       0.416518 |   0.480927 |
| Bori_Aron_solution-1 |     0.461755 |       0.534853 |   0.540603 |
| k-d_tree_pandas      |     0.453338 |       0.384905 |   0.545037 |
| k-d_tree_sklearn     |     2.85773  |       1.01654  |   1.05321  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471567 |       0.433588 |   0.434278 |
| barab-szabi-1        |     0.466821 |       0.407773 |   0.446025 |
| k-d_tree_polars      |     0.467745 |       0.408715 |   0.470792 |
| Bori_Aron_solution-1 |     0.457301 |       0.548785 |   0.540605 |
| k-d_tree_pandas      |     0.464108 |       0.388041 |   0.549409 |
| k-d_tree_sklearn     |     0.467405 |       0.953484 |   1.08059  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474351 |       0.452385 |   0.445448 |
| k-d_tree_polars      |     0.465091 |       0.435233 |   0.464047 |
| barab-szabi-1        |     0.465953 |       0.436056 |   0.467448 |
| Bori_Aron_solution-1 |     0.458969 |       0.593079 |   0.557983 |
| k-d_tree_pandas      |     0.465044 |       0.406769 |   0.59192  |
| k-d_tree_sklearn     |     0.468548 |       1.01507  |   1.12629  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463714 |       0.510656 |   0.470745 |
| Bori_Aron_solution-1 |     0.464618 |       0.774686 |   0.554745 |
| k-d_tree_polars      |     0.468445 |       0.558018 |   0.567725 |
| barab-szabi-1        |     0.467642 |       0.558885 |   0.575737 |
| k-d_tree_pandas      |     0.468303 |       0.497518 |   0.726646 |
| k-d_tree_sklearn     |     0.472008 |       1.27823  |   1.12753  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460207 |       0.729311 |   0.505584 |
| Bori_Aron_solution-1 |     0.467744 |       1.46452  |   0.590669 |
| k-d_tree_polars      |     0.467913 |       0.923285 |   0.912331 |
| barab-szabi-1        |     0.46665  |       0.933092 |   0.957513 |
| k-d_tree_pandas      |     0.462412 |       0.813228 |   1.17388  |
| k-d_tree_sklearn     |     0.467883 |       2.11877  |   1.20812  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462159 |        5.23995 |   0.767333 |
| Bori_Aron_solution-1 |     0.455153 |       11.1591  |   0.811095 |
| k-d_tree_sklearn     |     0.471712 |       16.9189  |   1.28658  |
| barab-szabi-1        |     0.478412 |        5.48248 |   6.73096  |
| k-d_tree_polars      |     0.463432 |        5.47342 |   6.75384  |
| k-d_tree_pandas      |     0.46805  |        4.43131 |   7.1542   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.46663  |         74.387 |    2.63161 |
| k-d_tree_sklearn     |     0.476925 |        242.181 |    3.70364 |
| Bori_Aron_solution-1 |     0.464989 |        150.574 |   24.25    |