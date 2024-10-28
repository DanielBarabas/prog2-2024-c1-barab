# 2024-10-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.78616  |       1e-06    |   0.385921 |
| barab-szabi-2        |     0.6402   |       0.404755 |   0.406513 |
| barab-szabi-1        |     0.638221 |       0.427342 |   0.410065 |
| k-d_tree_polars      |     0.639298 |       0.422457 |   0.415085 |
| k-d_tree_pandas      |     0.628931 |       0.381816 |   0.527185 |
| Bori_Aron_solution-1 |     0.6377   |       0.547731 |   0.574935 |
| k-d_tree_sklearn     |    10.5791   |       1.05035  |   1.01328  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614947 |       0.389318 |   0.391211 |
| barab-szabi-1        |     0.618166 |       0.414272 |   0.394553 |
| k-d_tree_polars      |     0.62187  |       0.413837 |   0.398208 |
| Bori_Aron_solution-1 |     0.63551  |       0.533576 |   0.524234 |
| k-d_tree_pandas      |     0.629506 |       0.404929 |   0.560165 |
| k-d_tree_sklearn     |     0.62677  |       0.903359 |   0.989757 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620107 |       0.411784 |   0.412912 |
| k-d_tree_polars      |     0.630928 |       0.431004 |   0.422004 |
| barab-szabi-1        |     0.638322 |       0.456303 |   0.432695 |
| Bori_Aron_solution-1 |     0.628353 |       0.581783 |   0.538982 |
| k-d_tree_pandas      |     0.626299 |       0.40643  |   0.571329 |
| k-d_tree_sklearn     |     0.641169 |       1.01445  |   1.05025  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616781 |       0.465958 |   0.430097 |
| k-d_tree_polars      |     0.616911 |       0.542264 |   0.518659 |
| barab-szabi-1        |     0.615246 |       0.537841 |   0.526567 |
| Bori_Aron_solution-1 |     0.609647 |       0.747567 |   0.540392 |
| k-d_tree_pandas      |     0.621055 |       0.479095 |   0.710092 |
| k-d_tree_sklearn     |     0.622056 |       1.18021  |   1.03879  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.628695 |       0.722935 |   0.467619 |
| Bori_Aron_solution-1 |     0.612486 |       1.41355  |   0.559593 |
| k-d_tree_polars      |     0.616374 |       0.863983 |   0.876526 |
| barab-szabi-1        |     0.621484 |       0.863262 |   0.915641 |
| k-d_tree_sklearn     |     0.624778 |       1.9766   |   1.14137  |
| k-d_tree_pandas      |     0.612814 |       0.745366 |   1.14823  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611414 |        5.46062 |   0.739824 |
| Bori_Aron_solution-1 |     0.611986 |       10.6985  |   0.808001 |
| k-d_tree_sklearn     |     0.619012 |       16.1808  |   1.24168  |
| k-d_tree_polars      |     0.618441 |        4.90073 |   6.53926  |
| barab-szabi-1        |     0.617486 |        4.85891 |   6.61288  |
| k-d_tree_pandas      |     0.613418 |        3.88751 |   7.08979  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.64617  |        76.7518 |    3.10233 |
| k-d_tree_sklearn     |     0.628139 |       233.592  |    4.36036 |
| Bori_Aron_solution-1 |     0.656736 |       152.951  |   19.1266  |