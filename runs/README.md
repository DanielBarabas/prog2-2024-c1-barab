# 2026-08-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.35798  |       0.529574 |   0.439264 |
| k-d_tree_polars      |     0.461088 |       0.42134  |   0.439285 |
| barab-szabi-1        |     0.458623 |       0.424294 |   0.4404   |
| solution-1           |     8.23194  |       1e-06    |   0.462614 |
| Bori_Aron_solution-1 |     5.0022   |       0.710721 |   0.486505 |
| k-d_tree_pandas      |     0.468244 |       0.394296 |   0.548352 |
| k-d_tree_sklearn     |     3.0321   |       1.17938  |   1.06818  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464533 |       0.43952  |   0.430599 |
| k-d_tree_polars      |     0.465147 |       0.431143 |   0.440014 |
| barab-szabi-1        |     0.465193 |       0.420482 |   0.442914 |
| k-d_tree_pandas      |     0.468408 |       0.389763 |   0.546556 |
| Bori_Aron_solution-1 |     0.46134  |       0.55032  |   0.548238 |
| k-d_tree_sklearn     |     0.46928  |       1.00516  |   1.06413  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464465 |       0.447263 |   0.441883 |
| k-d_tree_polars      |     0.467871 |       0.44888  |   0.457778 |
| barab-szabi-1        |     0.465396 |       0.452165 |   0.465091 |
| Bori_Aron_solution-1 |     0.462559 |       0.58747  |   0.545269 |
| k-d_tree_pandas      |     0.467898 |       0.405629 |   0.581081 |
| k-d_tree_sklearn     |     0.472184 |       1.03663  |   1.09873  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.46615  |       0.511487 |   0.471476 |
| k-d_tree_polars      |     0.465281 |       0.572628 |   0.560666 |
| Bori_Aron_solution-1 |     0.46237  |       0.767824 |   0.560969 |
| barab-szabi-1        |     0.464237 |       0.572458 |   0.570651 |
| k-d_tree_pandas      |     0.464464 |       0.501831 |   0.708231 |
| k-d_tree_sklearn     |     0.469509 |       1.27601  |   1.13212  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468614 |       0.791244 |   0.540107 |
| Bori_Aron_solution-1 |     0.466884 |       1.46579  |   0.57722  |
| k-d_tree_polars      |     0.474538 |       0.90948  |   0.98675  |
| barab-szabi-1        |     0.484865 |       0.905626 |   1.00342  |
| k-d_tree_sklearn     |     0.484474 |       2.20557  |   1.17372  |
| k-d_tree_pandas      |     0.475242 |       0.779482 |   1.21721  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.490069 |        5.59911 |   0.734121 |
| Bori_Aron_solution-1 |     0.478136 |       11.374   |   0.847685 |
| k-d_tree_sklearn     |     0.489325 |       17.3562  |   1.31788  |
| k-d_tree_polars      |     0.493341 |        5.07448 |   7.45406  |
| barab-szabi-1        |     0.476294 |        5.09523 |   7.48836  |
| k-d_tree_pandas      |     0.492957 |        4.11977 |   7.7124   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734306 |        81.2521 |    2.64057 |
| k-d_tree_sklearn     |     0.566084 |       270.174  |    3.59668 |
| Bori_Aron_solution-1 |     0.481778 |       156.919  |   25.2886  |