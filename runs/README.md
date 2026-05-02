# 2026-05-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.483821 |       0.427182 |   0.445551 |
| barab-szabi-2        |     0.477911 |       0.447242 |   0.446901 |
| k-d_tree_polars      |     0.483242 |       0.418004 |   0.45053  |
| solution-1           |     7.86467  |       1e-06    |   0.452806 |
| Bori_Aron_solution-1 |     0.469747 |       0.567543 |   0.571392 |
| k-d_tree_pandas      |     0.523219 |       0.40678  |   0.589201 |
| k-d_tree_sklearn     |    10.6669   |       1.32326  |   1.12617  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.473459 |       0.420543 |   0.448331 |
| barab-szabi-2        |     0.47987  |       0.459311 |   0.45486  |
| k-d_tree_polars      |     0.478865 |       0.430571 |   0.489531 |
| Bori_Aron_solution-1 |     0.458021 |       0.561318 |   0.553911 |
| k-d_tree_pandas      |     0.489767 |       0.433895 |   0.582009 |
| k-d_tree_sklearn     |     0.489044 |       1.0045   |   1.1082   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467107 |       0.46025  |   0.456775 |
| k-d_tree_polars      |     0.478909 |       0.444268 |   0.470379 |
| barab-szabi-1        |     0.468532 |       0.44304  |   0.473819 |
| Bori_Aron_solution-1 |     0.47288  |       0.606137 |   0.562576 |
| k-d_tree_pandas      |     0.468366 |       0.41963  |   0.615246 |
| k-d_tree_sklearn     |     0.475907 |       1.0571   |   1.12388  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467499 |       0.507433 |   0.491635 |
| Bori_Aron_solution-1 |     0.461194 |       0.782855 |   0.566332 |
| k-d_tree_polars      |     0.468981 |       0.568142 |   0.57025  |
| barab-szabi-1        |     0.48894  |       0.577951 |   0.585056 |
| k-d_tree_pandas      |     0.468173 |       0.517608 |   0.764172 |
| k-d_tree_sklearn     |     0.471125 |       1.28047  |   1.15081  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495508 |       0.762201 |   0.525277 |
| Bori_Aron_solution-1 |     0.461377 |       1.49185  |   0.599222 |
| k-d_tree_polars      |     0.482952 |       0.949908 |   0.956231 |
| barab-szabi-1        |     0.484339 |       0.928079 |   0.980444 |
| k-d_tree_pandas      |     0.484746 |       0.81046  |   1.22453  |
| k-d_tree_sklearn     |     0.480602 |       2.22998  |   1.26182  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474593 |        5.20628 |   0.757461 |
| Bori_Aron_solution-1 |     0.460228 |       10.8941  |   0.819664 |
| k-d_tree_sklearn     |     0.480152 |       16.6788  |   1.30599  |
| k-d_tree_polars      |     0.466477 |        5.51694 |   6.79385  |
| k-d_tree_pandas      |     0.472843 |        4.52629 |   6.9405   |
| barab-szabi-1        |     0.469547 |        5.63508 |   7.01691  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.765205 |        71.1174 |    2.68873 |
| k-d_tree_sklearn     |     0.497233 |       239.338  |    3.83933 |
| Bori_Aron_solution-1 |     0.466111 |       151.322  |   23.8471  |