# 2025-07-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     1.03662  |       0.425716 |   0.438775 |
| barab-szabi-2        |     0.581415 |       0.441133 |   0.446971 |
| k-d_tree_polars      |     0.653573 |       0.425337 |   0.474024 |
| k-d_tree_pandas      |     0.594169 |       0.405921 |   0.5844   |
| Bori_Aron_solution-1 |     0.569738 |       0.580188 |   0.58594  |
| solution-1           |     8.27961  |       1e-06    |   0.604007 |
| k-d_tree_sklearn     |    10.7956   |       1.48101  |   1.11525  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559252 |       0.432458 |   0.430994 |
| barab-szabi-1        |     0.577526 |       0.429373 |   0.447039 |
| k-d_tree_polars      |     0.574202 |       0.437088 |   0.477018 |
| Bori_Aron_solution-1 |     0.560546 |       0.57409  |   0.554098 |
| k-d_tree_pandas      |     0.579798 |       0.410288 |   0.582827 |
| k-d_tree_sklearn     |     0.577678 |       1.04299  |   1.13175  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563142 |       0.441564 |   0.441652 |
| barab-szabi-1        |     0.554807 |       0.440985 |   0.459817 |
| k-d_tree_polars      |     0.577202 |       0.481266 |   0.461195 |
| Bori_Aron_solution-1 |     0.554623 |       0.620732 |   0.558029 |
| k-d_tree_pandas      |     0.560493 |       0.410961 |   0.603181 |
| k-d_tree_sklearn     |     0.564687 |       1.0319   |   1.09344  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591418 |       0.544596 |   0.493938 |
| k-d_tree_polars      |     0.55904  |       0.553645 |   0.553109 |
| barab-szabi-1        |     0.578969 |       0.553586 |   0.570714 |
| Bori_Aron_solution-1 |     0.569036 |       0.81298  |   0.607705 |
| k-d_tree_pandas      |     0.567866 |       0.504134 |   0.772561 |
| k-d_tree_sklearn     |     0.574353 |       1.26626  |   1.16581  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567133 |       0.803411 |   0.601989 |
| Bori_Aron_solution-1 |     0.568755 |       1.46574  |   0.607439 |
| k-d_tree_polars      |     0.579672 |       0.912217 |   0.963622 |
| barab-szabi-1        |     0.588977 |       0.914005 |   1.02215  |
| k-d_tree_pandas      |     0.570614 |       0.772461 |   1.23054  |
| k-d_tree_sklearn     |     0.586689 |       2.22599  |   1.32137  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546151 |        5.39339 |   0.746831 |
| Bori_Aron_solution-1 |     0.544743 |       10.6221  |   0.854878 |
| k-d_tree_sklearn     |     0.573417 |       16.5419  |   1.2987   |
| barab-szabi-1        |     0.551416 |        4.96294 |   6.69555  |
| k-d_tree_polars      |     0.548639 |        4.92029 |   6.7107   |
| k-d_tree_pandas      |     0.546897 |        3.95721 |   7.03899  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569409 |        76.7541 |    3.00687 |
| k-d_tree_sklearn     |     0.553453 |       237.748  |    4.06046 |
| Bori_Aron_solution-1 |     0.572797 |       143.317  |   17.6901  |