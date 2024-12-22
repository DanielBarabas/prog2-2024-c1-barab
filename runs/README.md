# 2024-12-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620108 |       0.39438  |   0.387223 |
| k-d_tree_polars      |     0.61826  |       0.401278 |   0.388212 |
| barab-szabi-1        |     0.624568 |       0.394252 |   0.390453 |
| solution-1           |     7.70286  |       1e-06    |   0.448727 |
| k-d_tree_pandas      |     0.617508 |       0.388743 |   0.51921  |
| Bori_Aron_solution-1 |     0.606326 |       0.524689 |   0.527057 |
| k-d_tree_sklearn     |    10.4362   |       1.32121  |   0.980918 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631442 |       0.395439 |   0.38489  |
| k-d_tree_polars      |     0.613534 |       0.410636 |   0.393944 |
| barab-szabi-1        |     0.618561 |       0.415475 |   0.398051 |
| Bori_Aron_solution-1 |     0.609266 |       0.53154  |   0.518226 |
| k-d_tree_pandas      |     0.615352 |       0.397951 |   0.550406 |
| k-d_tree_sklearn     |     0.623406 |       0.90593  |   0.972142 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613431 |       0.406027 |   0.398241 |
| k-d_tree_polars      |     0.618319 |       0.434494 |   0.443891 |
| barab-szabi-1        |     0.630992 |       0.439875 |   0.450985 |
| Bori_Aron_solution-1 |     0.622434 |       0.569254 |   0.553063 |
| k-d_tree_pandas      |     0.62432  |       0.409959 |   0.568911 |
| k-d_tree_sklearn     |     0.619306 |       0.941805 |   0.991756 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618696 |       0.470903 |   0.430984 |
| k-d_tree_polars      |     0.611373 |       0.534631 |   0.515092 |
| barab-szabi-1        |     0.613421 |       0.538857 |   0.532195 |
| Bori_Aron_solution-1 |     0.608131 |       0.747479 |   0.539915 |
| k-d_tree_pandas      |     0.614201 |       0.484904 |   0.707226 |
| k-d_tree_sklearn     |     0.619557 |       1.17059  |   1.0544   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620501 |       0.716441 |   0.462448 |
| Bori_Aron_solution-1 |     0.611762 |       1.41495  |   0.586616 |
| k-d_tree_polars      |     0.621818 |       0.862901 |   0.864884 |
| barab-szabi-1        |     0.639274 |       0.865851 |   0.907491 |
| k-d_tree_pandas      |     0.61883  |       0.751962 |   1.12811  |
| k-d_tree_sklearn     |     0.620209 |       1.98525  |   1.13391  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618497 |        5.3462  |   0.730969 |
| Bori_Aron_solution-1 |     0.611694 |       10.7129  |   0.811002 |
| k-d_tree_sklearn     |     0.639436 |       16.1407  |   1.24586  |
| barab-szabi-1        |     0.619869 |        4.88582 |   6.54825  |
| k-d_tree_polars      |     0.610776 |        4.8791  |   6.66671  |
| k-d_tree_pandas      |     0.611254 |        3.89218 |   6.88259  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.668008 |        71.3567 |    3.03395 |
| k-d_tree_sklearn     |     0.620412 |       226.157  |    4.18253 |
| Bori_Aron_solution-1 |     0.6321   |       149.651  |   18.6355  |