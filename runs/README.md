# 2025-10-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5323   |       0.611629 |   0.430078 |
| k-d_tree_polars      |     0.550711 |       0.408015 |   0.43761  |
| barab-szabi-1        |     0.605837 |       0.416556 |   0.447972 |
| solution-1           |     7.47783  |       1e-06    |   0.501796 |
| Bori_Aron_solution-1 |     0.545264 |       0.581139 |   0.561056 |
| k-d_tree_pandas      |     8.15486  |       0.464559 |   0.737902 |
| k-d_tree_sklearn     |     3.07918  |       1.19852  |   1.08735  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.566035 |       0.427662 |   0.434812 |
| k-d_tree_polars      |     0.556106 |       0.426968 |   0.438765 |
| barab-szabi-2        |     0.56034  |       0.438154 |   0.440544 |
| Bori_Aron_solution-1 |     0.546124 |       0.558085 |   0.560484 |
| k-d_tree_pandas      |     0.55307  |       0.411728 |   0.591406 |
| k-d_tree_sklearn     |     0.558493 |       0.989507 |   1.0896   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552511 |       0.447026 |   0.444384 |
| barab-szabi-1        |     0.561822 |       0.446119 |   0.468676 |
| k-d_tree_polars      |     0.548541 |       0.442199 |   0.469856 |
| Bori_Aron_solution-1 |     0.54573  |       0.613742 |   0.565618 |
| k-d_tree_pandas      |     0.565793 |       0.43327  |   0.608649 |
| k-d_tree_sklearn     |     0.565953 |       1.05027  |   1.13479  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552549 |       0.521236 |   0.474148 |
| Bori_Aron_solution-1 |     0.568361 |       0.805885 |   0.580901 |
| barab-szabi-1        |     0.561967 |       0.57924  |   0.581759 |
| k-d_tree_polars      |     0.558459 |       0.588249 |   0.591727 |
| k-d_tree_pandas      |     0.554208 |       0.509869 |   0.744003 |
| k-d_tree_sklearn     |     0.576665 |       1.32124  |   1.17657  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570347 |       0.759972 |   0.527385 |
| Bori_Aron_solution-1 |     0.54367  |       1.50645  |   0.601705 |
| k-d_tree_polars      |     0.554263 |       0.954851 |   0.959218 |
| barab-szabi-1        |     0.580661 |       1.00797  |   0.972538 |
| k-d_tree_pandas      |     0.558927 |       0.836565 |   1.21706  |
| k-d_tree_sklearn     |     0.553775 |       2.18557  |   1.24315  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550068 |        5.50349 |   0.765809 |
| Bori_Aron_solution-1 |     0.5508   |       11.4917  |   0.866478 |
| k-d_tree_sklearn     |     0.564125 |       17.6298  |   1.36145  |
| barab-szabi-1        |     0.559758 |        5.48703 |   6.88305  |
| k-d_tree_polars      |     0.560718 |        5.59038 |   6.88945  |
| k-d_tree_pandas      |     0.553833 |        4.61705 |   7.15896  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551045 |        74.0597 |    2.81989 |
| k-d_tree_sklearn     |     0.581589 |       244.42   |    4.15878 |
| Bori_Aron_solution-1 |     0.792723 |       150.873  |   17.4282  |