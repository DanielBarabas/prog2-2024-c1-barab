# 2026-01-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.543306 |       0.420643 |   0.43881  |
| barab-szabi-2        |     0.539021 |       0.510806 |   0.45137  |
| solution-1           |     7.94109  |       1e-06    |   0.466252 |
| k-d_tree_polars      |     0.544962 |       0.431906 |   0.478506 |
| Bori_Aron_solution-1 |     0.537924 |       0.570822 |   0.567122 |
| k-d_tree_pandas      |     8.53352  |       0.441752 |   0.662207 |
| k-d_tree_sklearn     |     3.23774  |       1.13296  |   1.14584  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.548974 |       0.434481 |   0.453422 |
| k-d_tree_polars      |     0.557261 |       0.425996 |   0.461474 |
| barab-szabi-2        |     0.545217 |       0.445024 |   0.463435 |
| Bori_Aron_solution-1 |     0.549498 |       0.586502 |   0.569171 |
| k-d_tree_pandas      |     0.538794 |       0.404003 |   0.582308 |
| k-d_tree_sklearn     |     0.565224 |       1.06444  |   1.125    |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548245 |       0.500544 |   0.473019 |
| k-d_tree_polars      |     0.566572 |       0.460025 |   0.491406 |
| barab-szabi-1        |     0.562325 |       0.459806 |   0.517393 |
| Bori_Aron_solution-1 |     0.578995 |       0.607858 |   0.570147 |
| k-d_tree_pandas      |     0.544739 |       0.425835 |   0.630745 |
| k-d_tree_sklearn     |     0.544665 |       1.07474  |   1.16524  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541241 |       0.526356 |   0.485857 |
| k-d_tree_polars      |     0.546437 |       0.579506 |   0.583368 |
| barab-szabi-1        |     0.558899 |       0.594534 |   0.58723  |
| Bori_Aron_solution-1 |     0.547234 |       0.810164 |   0.587947 |
| k-d_tree_pandas      |     0.554271 |       0.535797 |   0.762717 |
| k-d_tree_sklearn     |     0.551652 |       1.3003   |   1.17889  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548915 |       0.751518 |   0.533564 |
| Bori_Aron_solution-1 |     0.538995 |       1.49803  |   0.619994 |
| k-d_tree_polars      |     0.564388 |       0.944705 |   0.959863 |
| barab-szabi-1        |     0.547742 |       0.946251 |   0.987269 |
| k-d_tree_pandas      |     0.55351  |       0.826119 |   1.19528  |
| k-d_tree_sklearn     |     0.553879 |       2.21028  |   1.28781  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54467  |        5.34758 |   0.766434 |
| Bori_Aron_solution-1 |     0.538007 |       11.477   |   0.888134 |
| k-d_tree_sklearn     |     0.549517 |       17.8591  |   1.35566  |
| barab-szabi-1        |     0.534631 |        5.39495 |   6.81531  |
| k-d_tree_polars      |     0.551577 |        5.45316 |   6.90377  |
| k-d_tree_pandas      |     0.555336 |        4.54885 |   7.31761  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552027 |        82.0862 |    2.85881 |
| k-d_tree_sklearn     |     0.553767 |       252.198  |    4.34054 |
| Bori_Aron_solution-1 |     0.707254 |       153.767  |   17.8943  |