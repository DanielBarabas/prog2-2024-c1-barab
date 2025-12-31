# 2025-12-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.518158 |       0.499507 |   0.436979 |
| k-d_tree_polars      |     0.533015 |       0.414295 |   0.43754  |
| barab-szabi-1        |     0.53995  |       0.410176 |   0.437892 |
| solution-1           |     7.9288   |       1e-06    |   0.444217 |
| Bori_Aron_solution-1 |     0.526096 |       0.549526 |   0.538975 |
| k-d_tree_pandas      |     8.64745  |       0.411942 |   0.659672 |
| k-d_tree_sklearn     |     3.31005  |       1.05939  |   1.06681  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581044 |       0.433466 |   0.429059 |
| k-d_tree_polars      |     0.544863 |       0.409411 |   0.432338 |
| barab-szabi-1        |     0.534889 |       0.410812 |   0.43266  |
| Bori_Aron_solution-1 |     0.522819 |       0.551236 |   0.544072 |
| k-d_tree_pandas      |     0.52704  |       0.388098 |   0.558553 |
| k-d_tree_sklearn     |     0.534781 |       0.973382 |   1.07477  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546282 |       0.446761 |   0.446107 |
| k-d_tree_polars      |     0.528703 |       0.440584 |   0.458517 |
| barab-szabi-1        |     0.537372 |       0.473655 |   0.464618 |
| Bori_Aron_solution-1 |     0.521643 |       0.591678 |   0.546335 |
| k-d_tree_pandas      |     0.529227 |       0.412341 |   0.602629 |
| k-d_tree_sklearn     |     0.537218 |       1.0177   |   1.09557  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525285 |       0.503985 |   0.471095 |
| k-d_tree_polars      |     0.529826 |       0.558192 |   0.555405 |
| Bori_Aron_solution-1 |     0.519241 |       0.773074 |   0.560308 |
| barab-szabi-1        |     0.526694 |       0.5541   |   0.562147 |
| k-d_tree_pandas      |     0.528836 |       0.500662 |   0.731306 |
| k-d_tree_sklearn     |     0.527318 |       1.2409   |   1.13125  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525509 |       0.733861 |   0.506351 |
| Bori_Aron_solution-1 |     0.547268 |       1.44966  |   0.58519  |
| k-d_tree_polars      |     0.528071 |       0.916408 |   0.905482 |
| barab-szabi-1        |     0.527949 |       0.919995 |   0.945291 |
| k-d_tree_pandas      |     0.524516 |       0.81291  |   1.1692   |
| k-d_tree_sklearn     |     0.532716 |       2.09602  |   1.21124  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533213 |        5.01697 |   0.737408 |
| Bori_Aron_solution-1 |     0.522661 |       11.12    |   0.839503 |
| k-d_tree_sklearn     |     0.529746 |       16.83    |   1.34634  |
| k-d_tree_polars      |     0.531635 |        5.39787 |   6.50702  |
| barab-szabi-1        |     0.575765 |        5.43166 |   6.60826  |
| k-d_tree_pandas      |     0.531015 |        4.39734 |   6.984    |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530819 |        77.1271 |    2.6917  |
| k-d_tree_sklearn     |     0.548382 |       236.607  |    4.10242 |
| Bori_Aron_solution-1 |     0.624637 |       147.43   |   18.3485  |