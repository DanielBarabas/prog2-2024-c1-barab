# 2026-04-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.458026 |       0.431946 |   0.422479 |
| barab-szabi-1        |     0.45523  |       0.40057  |   0.430976 |
| k-d_tree_polars      |     0.459967 |       0.39844  |   0.431253 |
| solution-1           |     7.21373  |       1e-06    |   0.467546 |
| Bori_Aron_solution-1 |     0.447464 |       0.548329 |   0.534342 |
| k-d_tree_pandas      |     0.452557 |       0.380392 |   0.54415  |
| k-d_tree_sklearn     |    10.3877   |       1.45973  |   1.0591   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456283 |       0.429859 |   0.430233 |
| barab-szabi-1        |     0.454309 |       0.403005 |   0.431139 |
| k-d_tree_polars      |     0.466241 |       0.405821 |   0.434134 |
| Bori_Aron_solution-1 |     0.453036 |       0.552054 |   0.54213  |
| k-d_tree_pandas      |     0.454956 |       0.382939 |   0.557304 |
| k-d_tree_sklearn     |     0.459072 |       0.966963 |   1.05456  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.453196 |       0.448838 |   0.442235 |
| k-d_tree_polars      |     0.463639 |       0.433545 |   0.463113 |
| barab-szabi-1        |     0.461307 |       0.43288  |   0.465152 |
| Bori_Aron_solution-1 |     0.446538 |       0.604267 |   0.560176 |
| k-d_tree_pandas      |     0.453385 |       0.402979 |   0.601428 |
| k-d_tree_sklearn     |     0.459718 |       1.00799  |   1.08514  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456995 |       0.500592 |   0.467605 |
| Bori_Aron_solution-1 |     0.452446 |       0.773406 |   0.551385 |
| k-d_tree_polars      |     0.459377 |       0.554109 |   0.560057 |
| barab-szabi-1        |     0.457595 |       0.558902 |   0.568223 |
| k-d_tree_pandas      |     0.455414 |       0.501915 |   0.727139 |
| k-d_tree_sklearn     |     0.457625 |       1.26897  |   1.12786  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.454999 |       0.714948 |   0.5015   |
| Bori_Aron_solution-1 |     0.450071 |       1.43396  |   0.575649 |
| k-d_tree_polars      |     0.453768 |       0.938244 |   0.89813  |
| barab-szabi-1        |     0.452066 |       0.927634 |   0.932209 |
| k-d_tree_pandas      |     0.455131 |       0.804962 |   1.15677  |
| k-d_tree_sklearn     |     0.460491 |       2.12627  |   1.19988  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463838 |        5.18963 |   0.762276 |
| Bori_Aron_solution-1 |     0.448933 |       11.2156  |   0.818356 |
| k-d_tree_sklearn     |     0.457553 |       16.8067  |   1.2683   |
| barab-szabi-1        |     0.455198 |        5.65066 |   6.68764  |
| k-d_tree_polars      |     0.459429 |        5.56762 |   6.72141  |
| k-d_tree_pandas      |     0.454506 |        4.47429 |   7.122    |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.707516 |        71.2191 |    2.76444 |
| k-d_tree_sklearn     |     0.458266 |       236.1    |    3.97827 |
| Bori_Aron_solution-1 |     0.455997 |       154.963  |   15.7392  |