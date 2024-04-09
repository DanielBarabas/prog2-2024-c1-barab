# 2024-04-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.729925 |       0.362855 |   0.335983 |
| barab-szabi-1        |     0.731685 |       0.40423  |   0.342746 |
| k-d_tree_polars      |     9.39004  |       0.487576 |   0.403017 |
| k-d_tree_pandas      |     1.63481  |       0.378052 |   0.471575 |
| Bori_Aron_solution-1 |     0.716825 |       0.468486 |   0.479268 |
| k-d_tree_sklearn     |     3.78274  |       1.0404   |   0.656964 |
| solution-1           |     9.0216   |       1e-06    |   0.843004 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.727975 |       0.406662 |   0.342618 |
| k-d_tree_polars      |     0.731894 |       0.403672 |   0.352807 |
| barab-szabi-2        |     0.726995 |       0.343463 |   0.355547 |
| Bori_Aron_solution-1 |     0.72771  |       0.483176 |   0.467511 |
| k-d_tree_pandas      |     0.727715 |       0.380929 |   0.48691  |
| k-d_tree_sklearn     |     0.752539 |       0.834099 |   0.655966 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.739778 |       0.356811 |   0.35684  |
| barab-szabi-1        |     0.734541 |       0.428708 |   0.371516 |
| k-d_tree_polars      |     0.728985 |       0.427739 |   0.402393 |
| Bori_Aron_solution-1 |     0.719405 |       0.516226 |   0.478314 |
| k-d_tree_pandas      |     0.732702 |       0.398    |   0.535486 |
| k-d_tree_sklearn     |     0.742696 |       0.87616  |   0.686022 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.73328  |       0.423506 |   0.38465  |
| k-d_tree_polars      |     0.735877 |       0.551913 |   0.471893 |
| barab-szabi-1        |     0.740331 |       0.536168 |   0.485553 |
| Bori_Aron_solution-1 |     0.719759 |       0.692612 |   0.495302 |
| k-d_tree_pandas      |     0.727193 |       0.478309 |   0.66176  |
| k-d_tree_sklearn     |     0.74303  |       1.10054  |   0.740567 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.741262 |       0.682275 |   0.423253 |
| Bori_Aron_solution-1 |     0.721692 |       1.328    |   0.517431 |
| k-d_tree_polars      |     0.746003 |       0.87303  |   0.851247 |
| k-d_tree_sklearn     |     0.743852 |       1.98262  |   0.862611 |
| barab-szabi-1        |     0.731511 |       0.856315 |   0.87708  |
| k-d_tree_pandas      |     0.728071 |       0.764868 |   1.09357  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.730121 |        5.32621 |   0.733784 |
| Bori_Aron_solution-1 |     0.718212 |       10.8246  |   0.792425 |
| k-d_tree_sklearn     |     0.747388 |       15.7334  |   1.05048  |
| k-d_tree_polars      |     0.7302   |        4.75416 |   6.63126  |
| barab-szabi-1        |     0.732526 |        4.85791 |   6.65881  |
| k-d_tree_pandas      |     0.734916 |        3.87437 |   6.88508  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.807076 |        75.1774 |    3.68792 |
| k-d_tree_sklearn     |     0.733383 |       235.418  |    5.18419 |
| Bori_Aron_solution-1 |     0.785957 |       146.033  |   14.37    |