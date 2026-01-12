# 2026-01-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.97776  |       1e-06    |   0.424933 |
| barab-szabi-2        |     0.513819 |       0.442774 |   0.42611  |
| barab-szabi-1        |     0.525971 |       0.409055 |   0.428144 |
| k-d_tree_polars      |     0.525572 |       0.400642 |   0.433394 |
| Bori_Aron_solution-1 |     0.518707 |       0.543856 |   0.536357 |
| k-d_tree_pandas      |     8.59901  |       0.401607 |   0.659333 |
| k-d_tree_sklearn     |     3.05493  |       1.02728  |   1.05659  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52688  |       0.432574 |   0.433479 |
| k-d_tree_polars      |     0.525256 |       0.40735  |   0.439992 |
| barab-szabi-1        |     0.538933 |       0.409237 |   0.445142 |
| Bori_Aron_solution-1 |     0.520932 |       0.556213 |   0.541584 |
| k-d_tree_pandas      |     0.57414  |       0.387311 |   0.557073 |
| k-d_tree_sklearn     |     0.532809 |       0.967492 |   1.05863  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.523879 |       0.440378 |   0.448261 |
| k-d_tree_polars      |     0.530743 |       0.442469 |   0.460282 |
| barab-szabi-1        |     0.532196 |       0.43906  |   0.463567 |
| Bori_Aron_solution-1 |     0.522519 |       0.589249 |   0.544232 |
| k-d_tree_pandas      |     0.527618 |       0.414827 |   0.598233 |
| k-d_tree_sklearn     |     0.535547 |       1.01842  |   1.12821  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52536  |       0.506001 |   0.473732 |
| k-d_tree_polars      |     0.527366 |       0.559427 |   0.560096 |
| Bori_Aron_solution-1 |     0.521962 |       0.782523 |   0.560986 |
| barab-szabi-1        |     0.528715 |       0.559231 |   0.575279 |
| k-d_tree_pandas      |     0.529329 |       0.503637 |   0.748909 |
| k-d_tree_sklearn     |     0.532577 |       1.2552   |   1.14001  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531514 |       0.735427 |   0.502788 |
| Bori_Aron_solution-1 |     0.526198 |       1.46645  |   0.583812 |
| k-d_tree_polars      |     0.529967 |       0.934456 |   0.907882 |
| barab-szabi-1        |     0.529862 |       0.906944 |   0.955677 |
| k-d_tree_pandas      |     0.52515  |       0.814591 |   1.1769   |
| k-d_tree_sklearn     |     0.530882 |       2.10716  |   1.21978  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525357 |        5.09657 |   0.748545 |
| Bori_Aron_solution-1 |     0.529143 |       11.0186  |   0.844606 |
| k-d_tree_sklearn     |     0.534041 |       16.4089  |   1.3199   |
| k-d_tree_polars      |     0.527596 |        5.415   |   6.527    |
| barab-szabi-1        |     0.52566  |        5.40976 |   6.52803  |
| k-d_tree_pandas      |     0.525522 |        4.47789 |   7.06797  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5297   |        76.4752 |    2.88001 |
| k-d_tree_sklearn     |     0.538764 |       233.972  |    4.13318 |
| Bori_Aron_solution-1 |     0.647668 |       150.987  |   17.8036  |