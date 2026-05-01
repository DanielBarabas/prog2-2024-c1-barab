# 2026-05-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.26013  |       1e-06    |   0.384216 |
| barab-szabi-2        |     0.467058 |       0.437064 |   0.435252 |
| k-d_tree_polars      |     0.472833 |       0.411198 |   0.444886 |
| barab-szabi-1        |     0.462125 |       0.408506 |   0.446549 |
| k-d_tree_pandas      |     0.463126 |       0.392326 |   0.556366 |
| Bori_Aron_solution-1 |     0.451622 |       0.554484 |   0.557912 |
| k-d_tree_sklearn     |    10.7398   |       1.11318  |   1.07585  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460775 |       0.435118 |   0.430452 |
| k-d_tree_polars      |     0.463578 |       0.412081 |   0.437428 |
| barab-szabi-1        |     0.460844 |       0.407592 |   0.440377 |
| Bori_Aron_solution-1 |     0.460536 |       0.550882 |   0.547108 |
| k-d_tree_pandas      |     0.463126 |       0.390218 |   0.559395 |
| k-d_tree_sklearn     |     0.498852 |       0.995221 |   1.08902  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463178 |       0.445625 |   0.444394 |
| k-d_tree_polars      |     0.463089 |       0.434936 |   0.459844 |
| barab-szabi-1        |     0.461525 |       0.434523 |   0.472579 |
| Bori_Aron_solution-1 |     0.456741 |       0.589875 |   0.548494 |
| k-d_tree_pandas      |     0.463048 |       0.408834 |   0.597287 |
| k-d_tree_sklearn     |     0.473097 |       1.02043  |   1.09469  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477215 |       0.505605 |   0.473055 |
| k-d_tree_polars      |     0.469702 |       0.559441 |   0.558498 |
| Bori_Aron_solution-1 |     0.462386 |       0.800313 |   0.562905 |
| barab-szabi-1        |     0.463742 |       0.5863   |   0.590591 |
| k-d_tree_pandas      |     0.462539 |       0.506654 |   0.74129  |
| k-d_tree_sklearn     |     0.468972 |       1.25383  |   1.14649  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.459186 |       0.738511 |   0.511988 |
| Bori_Aron_solution-1 |     0.452657 |       1.45775  |   0.58663  |
| k-d_tree_polars      |     0.465678 |       0.927612 |   0.916313 |
| barab-szabi-1        |     0.467476 |       0.945799 |   0.963475 |
| k-d_tree_sklearn     |     0.47709  |       2.12299  |   1.20534  |
| k-d_tree_pandas      |     0.461635 |       0.821146 |   1.20554  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466969 |        5.19505 |   0.759724 |
| Bori_Aron_solution-1 |     0.455523 |       10.874   |   0.811808 |
| k-d_tree_sklearn     |     0.468626 |       16.8051  |   1.30671  |
| k-d_tree_polars      |     0.462106 |        5.49729 |   6.58045  |
| barab-szabi-1        |     0.475507 |        5.54559 |   6.63326  |
| k-d_tree_pandas      |     0.485828 |        4.28051 |   7.1666   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.651319 |        72.8334 |    2.70018 |
| k-d_tree_sklearn     |     0.473027 |       242.591  |    3.97128 |
| Bori_Aron_solution-1 |     0.471643 |       151.642  |   22.5044  |