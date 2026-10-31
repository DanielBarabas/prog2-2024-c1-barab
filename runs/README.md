# 2026-10-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.97505  |       1e-06    |   0.366835 |
| barab-szabi-2        |     0.468952 |       0.476896 |   0.472072 |
| k-d_tree_polars      |     0.484592 |       0.451458 |   0.478948 |
| barab-szabi-1        |     8.24656  |       0.447272 |   0.485137 |
| k-d_tree_pandas      |     0.471903 |       0.400755 |   0.567699 |
| Bori_Aron_solution-1 |     0.48453  |       0.580989 |   0.583403 |
| k-d_tree_sklearn     |     3.01942  |       1.0778   |   1.14487  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492184 |       0.460357 |   0.449265 |
| barab-szabi-1        |     0.496793 |       0.443136 |   0.460167 |
| k-d_tree_polars      |     0.475772 |       0.437567 |   0.460344 |
| Bori_Aron_solution-1 |     0.477392 |       0.565378 |   0.557508 |
| k-d_tree_pandas      |     0.494704 |       0.413647 |   0.579993 |
| k-d_tree_sklearn     |     0.489197 |       1.0482   |   1.10296  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484789 |       0.458561 |   0.4474   |
| k-d_tree_polars      |     0.488691 |       0.472155 |   0.477957 |
| barab-szabi-1        |     0.475451 |       0.470391 |   0.486097 |
| k-d_tree_pandas      |     0.478311 |       0.416608 |   0.605275 |
| Bori_Aron_solution-1 |     0.485996 |       0.606493 |   0.91991  |
| k-d_tree_sklearn     |     0.49175  |       1.08064  |   1.15333  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495882 |       0.540069 |   0.489518 |
| Bori_Aron_solution-1 |     0.466408 |       0.81272  |   0.575328 |
| k-d_tree_polars      |     0.484942 |       0.586028 |   0.581501 |
| barab-szabi-1        |     0.479251 |       0.599421 |   0.588432 |
| k-d_tree_pandas      |     0.479763 |       0.533519 |   0.782297 |
| k-d_tree_sklearn     |     0.484208 |       1.41028  |   1.16545  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470046 |       0.769635 |   0.539222 |
| Bori_Aron_solution-1 |     0.46916  |       1.49342  |   0.61315  |
| k-d_tree_polars      |     0.485268 |       0.947332 |   0.992131 |
| barab-szabi-1        |     0.48465  |       0.922256 |   1.00734  |
| k-d_tree_pandas      |     0.473245 |       0.824234 |   1.21775  |
| k-d_tree_sklearn     |     0.486295 |       2.17725  |   1.26416  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498115 |        5.8829  |    0.94824 |
| Bori_Aron_solution-1 |     0.468827 |       11.5334  |    1.14759 |
| k-d_tree_sklearn     |     0.48437  |       17.7123  |    1.40105 |
| barab-szabi-1        |     0.478647 |        5.2216  |    7.16651 |
| k-d_tree_polars      |     0.486972 |        5.30763 |    7.22383 |
| k-d_tree_pandas      |     0.47753  |        4.4289  |    7.69914 |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.491809 |        240.114 |    4.24048 |
| barab-szabi-2        |     0.499193 |         77.304 |    4.44403 |
| Bori_Aron_solution-1 |     0.48802  |        159.492 |   23.8542  |