# 2025-09-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.59396  |       0.932876 |   0.433008 |
| k-d_tree_polars      |     0.541635 |       0.421137 |   0.442498 |
| barab-szabi-1        |     0.593051 |       0.418288 |   0.449344 |
| solution-1           |     8.38377  |       1e-06    |   0.511117 |
| k-d_tree_pandas      |     0.5853   |       0.391357 |   0.564144 |
| Bori_Aron_solution-1 |     0.985762 |       0.55523  |   0.565653 |
| k-d_tree_sklearn     |     3.0742   |       1.24128  |   1.08187  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.548606 |       0.425197 |   0.43897  |
| barab-szabi-1        |     0.565707 |       0.423054 |   0.443267 |
| barab-szabi-2        |     0.548314 |       0.43573  |   0.444264 |
| Bori_Aron_solution-1 |     0.540253 |       0.565929 |   0.557654 |
| k-d_tree_pandas      |     0.548709 |       0.407855 |   0.567065 |
| k-d_tree_sklearn     |     0.555655 |       1.01288  |   1.14181  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55722  |       0.464742 |   0.456187 |
| k-d_tree_polars      |     0.568599 |       0.458416 |   0.483021 |
| barab-szabi-1        |     0.576715 |       0.473051 |   0.485127 |
| Bori_Aron_solution-1 |     0.560529 |       0.630794 |   0.573749 |
| k-d_tree_pandas      |     0.567542 |       0.426098 |   0.637602 |
| k-d_tree_sklearn     |     0.559667 |       1.07573  |   1.13755  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550488 |       0.522455 |   0.481668 |
| k-d_tree_polars      |     0.557693 |       0.557146 |   0.579304 |
| Bori_Aron_solution-1 |     0.559096 |       0.788439 |   0.581295 |
| barab-szabi-1        |     0.558816 |       0.56632  |   0.591858 |
| k-d_tree_pandas      |     0.550144 |       0.503038 |   0.761193 |
| k-d_tree_sklearn     |     0.562043 |       1.29158  |   1.18899  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558209 |       0.773048 |   0.534911 |
| Bori_Aron_solution-1 |     0.562499 |       1.45348  |   0.611719 |
| k-d_tree_polars      |     0.565238 |       0.945335 |   0.972204 |
| barab-szabi-1        |     0.56432  |       0.912508 |   0.981983 |
| k-d_tree_pandas      |     0.56468  |       0.781432 |   1.1964   |
| k-d_tree_sklearn     |     0.574094 |       2.21993  |   1.27165  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566476 |        5.47517 |   0.750071 |
| Bori_Aron_solution-1 |     0.569796 |       10.8867  |   0.871881 |
| k-d_tree_sklearn     |     0.560163 |       17.1948  |   1.42914  |
| k-d_tree_polars      |     0.556485 |        5.09239 |   6.7882   |
| barab-szabi-1        |     0.567655 |        5.11425 |   6.88159  |
| k-d_tree_pandas      |     0.560629 |        3.9993  |   7.31448  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569924 |        74.4493 |    2.74781 |
| k-d_tree_sklearn     |     1.11902  |       238.832  |    4.25589 |
| Bori_Aron_solution-1 |     0.559272 |       146.532  |   15.2133  |