# 2025-11-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.511432 |       0.509707 |   0.423573 |
| barab-szabi-1        |     0.525902 |       0.419295 |   0.425506 |
| k-d_tree_polars      |     0.528691 |       0.400836 |   0.429667 |
| Bori_Aron_solution-1 |     0.519104 |       0.542569 |   0.54457  |
| solution-1           |     8.01876  |       1e-06    |   0.548942 |
| k-d_tree_pandas      |     8.70166  |       0.423314 |   0.728081 |
| k-d_tree_sklearn     |     3.23803  |       1.18771  |   1.06019  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.52708  |       0.410677 |   0.432052 |
| barab-szabi-2        |     0.526858 |       0.434967 |   0.433486 |
| barab-szabi-1        |     0.527436 |       0.414906 |   0.436758 |
| Bori_Aron_solution-1 |     0.528651 |       0.555541 |   0.551567 |
| k-d_tree_pandas      |     0.528959 |       0.395988 |   0.559267 |
| k-d_tree_sklearn     |     0.541633 |       0.972838 |   1.07706  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536346 |       0.440861 |   0.444573 |
| k-d_tree_polars      |     0.530773 |       0.441488 |   0.458724 |
| barab-szabi-1        |     0.524497 |       0.494009 |   0.461591 |
| Bori_Aron_solution-1 |     0.522285 |       0.59452  |   0.550429 |
| k-d_tree_pandas      |     0.529829 |       0.418543 |   0.603286 |
| k-d_tree_sklearn     |     0.529631 |       1.01863  |   1.07631  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553191 |       0.521077 |   0.485158 |
| Bori_Aron_solution-1 |     0.538399 |       0.786758 |   0.569322 |
| k-d_tree_polars      |     0.556145 |       0.572421 |   0.577756 |
| barab-szabi-1        |     0.55157  |       0.581326 |   0.591766 |
| k-d_tree_pandas      |     0.533188 |       0.510124 |   0.768614 |
| k-d_tree_sklearn     |     0.552    |       1.33313  |   1.17285  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544279 |       0.763268 |   0.529785 |
| Bori_Aron_solution-1 |     0.535264 |       1.4614   |   0.585027 |
| k-d_tree_polars      |     0.524645 |       0.946991 |   0.94335  |
| barab-szabi-1        |     0.536621 |       0.938343 |   0.946761 |
| k-d_tree_pandas      |     0.534087 |       0.829494 |   1.21948  |
| k-d_tree_sklearn     |     0.545837 |       2.16098  |   1.23553  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.524224 |        5.35403 |   0.728917 |
| Bori_Aron_solution-1 |     0.52547  |       11.3605  |   0.840555 |
| k-d_tree_sklearn     |     0.528116 |       17.43    |   1.37465  |
| k-d_tree_polars      |     0.565081 |        5.4656  |   6.87739  |
| barab-szabi-1        |     0.557867 |        5.4257  |   6.98937  |
| k-d_tree_pandas      |     0.530428 |        4.4785  |   7.11231  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529745 |        77.1065 |    2.58869 |
| k-d_tree_sklearn     |     0.533748 |       230.211  |    4.15576 |
| Bori_Aron_solution-1 |     0.667265 |       148.696  |   16.2638  |