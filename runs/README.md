# 2025-05-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.41298  |       1e-06    |   0.372336 |
| k-d_tree_polars      |     0.540341 |       0.408675 |   0.422335 |
| barab-szabi-2        |     0.556774 |       0.419118 |   0.422713 |
| barab-szabi-1        |     7.95718  |       0.43214  |   0.491872 |
| k-d_tree_pandas      |     0.557269 |       0.384789 |   0.54501  |
| Bori_Aron_solution-1 |     0.537939 |       0.557291 |   0.559964 |
| k-d_tree_sklearn     |     2.97707  |       1.01762  |   1.06659  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566417 |       0.426277 |   0.432242 |
| k-d_tree_polars      |     0.578516 |       0.436262 |   0.434192 |
| barab-szabi-1        |     0.558247 |       0.420732 |   0.434406 |
| k-d_tree_pandas      |     0.570367 |       0.406449 |   0.568034 |
| Bori_Aron_solution-1 |     0.557201 |       0.582734 |   0.610254 |
| k-d_tree_sklearn     |     0.576241 |       0.986718 |   1.10918  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551374 |       0.431039 |   0.438042 |
| k-d_tree_polars      |     0.575821 |       0.436388 |   0.458702 |
| barab-szabi-1        |     0.571591 |       0.454901 |   0.469276 |
| Bori_Aron_solution-1 |     0.57005  |       0.614152 |   0.569146 |
| k-d_tree_pandas      |     0.558943 |       0.428358 |   0.605318 |
| k-d_tree_sklearn     |     0.569274 |       1.0589   |   1.08654  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564386 |       0.511747 |   0.477278 |
| k-d_tree_polars      |     0.555818 |       0.550741 |   0.544601 |
| barab-szabi-1        |     0.549987 |       0.546371 |   0.56513  |
| Bori_Aron_solution-1 |     0.565089 |       0.782463 |   0.578659 |
| k-d_tree_pandas      |     0.551136 |       0.490389 |   0.750835 |
| k-d_tree_sklearn     |     0.572256 |       1.27308  |   1.17864  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565742 |       0.742774 |   0.509834 |
| Bori_Aron_solution-1 |     0.547966 |       1.4232   |   0.597063 |
| k-d_tree_polars      |     0.566328 |       0.89073  |   0.901351 |
| barab-szabi-1        |     0.582511 |       0.898703 |   0.951733 |
| k-d_tree_pandas      |     0.565182 |       0.766119 |   1.20632  |
| k-d_tree_sklearn     |     0.561038 |       2.11131  |   1.26993  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563083 |        5.88946 |   0.771958 |
| Bori_Aron_solution-1 |     0.546623 |       11.12    |   0.897647 |
| k-d_tree_sklearn     |     0.565724 |       16.9301  |   1.37997  |
| k-d_tree_polars      |     0.564382 |        5.04811 |   7.03026  |
| barab-szabi-1        |     0.561704 |        5.0438  |   7.15372  |
| k-d_tree_pandas      |     0.561657 |        3.98194 |   7.32078  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.837249 |        74.6222 |    3.03459 |
| k-d_tree_sklearn     |     0.791811 |       237.298  |    4.29918 |
| Bori_Aron_solution-1 |     0.564513 |       148.161  |   14.7714  |