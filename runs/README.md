# 2024-04-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.713892 |       0.342937 |   0.347223 |
| k-d_tree_polars      |     0.735073 |       0.420181 |   0.354087 |
| barab-szabi-1        |     8.26541  |       0.428759 |   0.363392 |
| Bori_Aron_solution-1 |     0.702064 |       0.481197 |   0.484542 |
| k-d_tree_pandas      |     0.72767  |       0.402468 |   0.492695 |
| solution-1           |     8.06435  |       1e-06    |   0.527335 |
| k-d_tree_sklearn     |     3.19812  |       0.887729 |   0.663256 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.742998 |       0.353132 |   0.351033 |
| k-d_tree_polars      |     0.742242 |       0.418674 |   0.351369 |
| barab-szabi-1        |     0.739776 |       0.416365 |   0.354625 |
| Bori_Aron_solution-1 |     0.727487 |       0.492652 |   0.481949 |
| k-d_tree_pandas      |     0.746668 |       0.419806 |   0.543667 |
| k-d_tree_sklearn     |     0.756699 |       0.868305 |   0.66423  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.754133 |       0.371991 |   0.363886 |
| k-d_tree_polars      |     0.748458 |       0.439289 |   0.374306 |
| barab-szabi-1        |     0.737582 |       0.437771 |   0.377223 |
| Bori_Aron_solution-1 |     0.724743 |       0.53344  |   0.479507 |
| k-d_tree_pandas      |     0.744279 |       0.410253 |   0.543902 |
| k-d_tree_sklearn     |     0.759117 |       0.931494 |   0.701375 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.741415 |       0.433476 |   0.397752 |
| k-d_tree_polars      |     0.743102 |       0.551904 |   0.481614 |
| barab-szabi-1        |     0.749127 |       0.545408 |   0.493156 |
| Bori_Aron_solution-1 |     0.730779 |       0.704989 |   0.506943 |
| k-d_tree_pandas      |     0.748026 |       0.50879  |   0.696067 |
| k-d_tree_sklearn     |     0.774909 |       1.18245  |   0.763658 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.749593 |       0.694137 |   0.449048 |
| Bori_Aron_solution-1 |     0.741391 |       1.36428  |   0.519087 |
| k-d_tree_polars      |     0.740823 |       0.857492 |   0.835154 |
| k-d_tree_sklearn     |     0.744604 |       1.99882  |   0.87769  |
| barab-szabi-1        |     0.74501  |       0.881634 |   0.889909 |
| k-d_tree_pandas      |     0.749362 |       0.75513  |   1.10559  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.760586 |        5.58036 |   0.758722 |
| Bori_Aron_solution-1 |     0.732471 |       11.0756  |   0.803812 |
| k-d_tree_sklearn     |     0.754922 |       16.6891  |   1.07513  |
| barab-szabi-1        |     0.743757 |        4.87282 |   6.97551  |
| k-d_tree_polars      |     0.759703 |        4.85179 |   7.0471   |
| k-d_tree_pandas      |     0.751485 |        3.91398 |   7.11832  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.11886  |        74.3958 |    3.97527 |
| k-d_tree_sklearn     |     0.839636 |       237.537  |    4.83979 |
| Bori_Aron_solution-1 |     0.735325 |       159.551  |   15.1129  |