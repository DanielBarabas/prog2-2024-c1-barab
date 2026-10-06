# 2026-10-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.350298 |       0.398031 |   0.349508 |
| k-d_tree_polars      |     0.347937 |       0.38416  |   0.360814 |
| k-d_tree_pandas      |     0.351277 |       0.310137 |   0.425788 |
| Bori_Aron_solution-1 |     0.338804 |       0.429008 |   0.426649 |
| solution-1           |     6.39946  |       1e-06    |   0.426842 |
| barab-szabi-1        |     8.34687  |       0.388896 |   0.513414 |
| k-d_tree_sklearn     |     2.39589  |       0.910643 |   0.826818 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.356112 |       0.360302 |   0.356551 |
| barab-szabi-1        |     0.356274 |       0.328754 |   0.36717  |
| k-d_tree_polars      |     0.354622 |       0.348321 |   0.370192 |
| Bori_Aron_solution-1 |     0.347766 |       0.438081 |   0.422299 |
| k-d_tree_pandas      |     0.352824 |       0.314492 |   0.431122 |
| k-d_tree_sklearn     |     0.360927 |       0.768259 |   0.827972 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.356138 |       0.365619 |   0.369662 |
| k-d_tree_polars      |     0.360082 |       0.358268 |   0.388638 |
| Bori_Aron_solution-1 |     0.349236 |       0.472127 |   0.441054 |
| k-d_tree_pandas      |     0.358778 |       0.329964 |   0.462099 |
| barab-szabi-1        |     0.357009 |       0.35872  |   0.699405 |
| k-d_tree_sklearn     |     0.358062 |       0.808589 |   0.831354 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.359629 |       0.425871 |   0.401223 |
| Bori_Aron_solution-1 |     0.352392 |       0.614393 |   0.443458 |
| barab-szabi-1        |     0.356355 |       0.45993  |   0.467752 |
| k-d_tree_polars      |     0.358342 |       0.46653  |   0.477063 |
| k-d_tree_pandas      |     0.362799 |       0.399685 |   0.561062 |
| k-d_tree_sklearn     |     0.359625 |       0.992673 |   0.864794 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.357967 |       0.606272 |   0.430623 |
| Bori_Aron_solution-1 |     0.354267 |       1.11046  |   0.475877 |
| k-d_tree_polars      |     0.359887 |       0.724948 |   0.719186 |
| barab-szabi-1        |     0.357604 |       0.738278 |   0.74532  |
| k-d_tree_pandas      |     0.361649 |       0.617277 |   0.884818 |
| k-d_tree_sklearn     |     0.35862  |       1.68104  |   0.91366  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.361704 |        3.45246 |   0.580107 |
| Bori_Aron_solution-1 |     0.357254 |        7.84442 |   0.774672 |
| k-d_tree_sklearn     |     0.367585 |       12.3633  |   1.06462  |
| k-d_tree_polars      |     0.358062 |        4.52112 |   4.59157  |
| barab-szabi-1        |     0.358261 |        4.81003 |   4.6101   |
| k-d_tree_pandas      |     0.359983 |        3.25255 |   4.88029  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.647984 |        54.4348 |    2.52231 |
| k-d_tree_sklearn     |     0.461391 |       148.548  |    3.44055 |
| Bori_Aron_solution-1 |     0.362813 |       133.356  |   24.3417  |