# 2026-01-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.962932 |       0.600549 |   0.462228 |
| barab-szabi-1        |     0.56189  |       0.436534 |   0.465401 |
| k-d_tree_polars      |     0.568012 |       0.440789 |   0.480094 |
| Bori_Aron_solution-1 |     0.556264 |       0.573509 |   0.576289 |
| solution-1           |     8.35593  |       2e-06    |   0.662148 |
| k-d_tree_pandas      |     8.92876  |       0.477571 |   0.810257 |
| k-d_tree_sklearn     |     3.2643   |       1.35924  |   1.14437  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.57443  |       0.449224 |   0.459657 |
| k-d_tree_polars      |     0.572801 |       0.449496 |   0.479213 |
| barab-szabi-2        |     0.595196 |       0.477796 |   0.498271 |
| Bori_Aron_solution-1 |     0.559911 |       0.609693 |   0.601157 |
| k-d_tree_pandas      |     0.559998 |       0.42136  |   0.641495 |
| k-d_tree_sklearn     |     0.569461 |       1.09179  |   1.14818  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586883 |       0.502682 |   0.48751  |
| k-d_tree_polars      |     0.555039 |       0.465601 |   0.50971  |
| barab-szabi-1        |     0.593829 |       0.481643 |   0.511268 |
| Bori_Aron_solution-1 |     0.575876 |       0.647074 |   0.605766 |
| k-d_tree_pandas      |     0.562603 |       0.438683 |   0.661598 |
| k-d_tree_sklearn     |     0.594634 |       1.13587  |   1.22844  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.576962 |       0.539146 |   0.524852 |
| k-d_tree_polars      |     0.560791 |       0.58621  |   0.60176  |
| barab-szabi-1        |     0.573824 |       0.595101 |   0.621706 |
| Bori_Aron_solution-1 |     0.567533 |       0.825219 |   0.636781 |
| k-d_tree_pandas      |     0.581675 |       0.54942  |   0.808879 |
| k-d_tree_sklearn     |     0.572025 |       1.34622  |   1.24454  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552428 |       0.82073  |   0.619977 |
| Bori_Aron_solution-1 |     0.569445 |       1.54953  |   0.654648 |
| k-d_tree_polars      |     0.559224 |       0.965809 |   1.00019  |
| barab-szabi-1        |     0.574253 |       0.983119 |   1.03177  |
| k-d_tree_pandas      |     0.582139 |       0.855011 |   1.26905  |
| k-d_tree_sklearn     |     0.566949 |       2.34201  |   1.38356  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566883 |        5.79674 |   0.859514 |
| Bori_Aron_solution-1 |     0.568509 |       11.7075  |   0.883282 |
| k-d_tree_sklearn     |     0.57687  |       19.1086  |   1.5065   |
| k-d_tree_polars      |     0.557649 |        5.56656 |   7.11051  |
| barab-szabi-1        |     0.579998 |        5.55529 |   7.22227  |
| k-d_tree_pandas      |     0.58808  |        4.54665 |   7.53027  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575546 |        85.8732 |    3.08364 |
| k-d_tree_sklearn     |     0.581278 |       257.511  |    4.47161 |
| Bori_Aron_solution-1 |     0.704463 |       159.042  |   18.1177  |