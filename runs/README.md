# 2024-04-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.703996 |       0.401716 |   0.339288 |
| barab-szabi-1        |     8.05439  |       0.420949 |   0.35597  |
| solution-1           |     7.93623  |       1e-06    |   0.358693 |
| barab-szabi-2        |     0.716111 |       0.341026 |   0.363218 |
| Bori_Aron_solution-1 |     0.698184 |       0.475083 |   0.472554 |
| k-d_tree_pandas      |     0.708455 |       0.381638 |   0.478564 |
| k-d_tree_sklearn     |     3.08218  |       0.869172 |   0.651746 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.731731 |       0.343675 |   0.33946  |
| barab-szabi-1        |     0.732364 |       0.409065 |   0.351025 |
| k-d_tree_polars      |     0.7349   |       0.407623 |   0.351323 |
| Bori_Aron_solution-1 |     0.746285 |       0.482543 |   0.473219 |
| k-d_tree_pandas      |     0.728745 |       0.400146 |   0.48227  |
| k-d_tree_sklearn     |     0.738116 |       0.83579  |   0.661784 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.728775 |       0.359225 |   0.35469  |
| k-d_tree_polars      |     0.731979 |       0.430617 |   0.371684 |
| barab-szabi-1        |     0.726912 |       0.428291 |   0.374122 |
| Bori_Aron_solution-1 |     0.726032 |       0.514435 |   0.469468 |
| k-d_tree_pandas      |     0.750866 |       0.403629 |   0.522852 |
| k-d_tree_sklearn     |     0.739982 |       0.88159  |   0.689962 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.728572 |       0.430781 |   0.395604 |
| k-d_tree_polars      |     0.729325 |       0.537677 |   0.47218  |
| barab-szabi-1        |     0.729074 |       0.537128 |   0.488832 |
| Bori_Aron_solution-1 |     0.720577 |       0.697661 |   0.491059 |
| k-d_tree_pandas      |     0.731534 |       0.478561 |   0.656488 |
| k-d_tree_sklearn     |     0.734727 |       1.112    |   0.745729 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.726143 |       0.685857 |   0.427762 |
| Bori_Aron_solution-1 |     0.720344 |       1.32751  |   0.510722 |
| k-d_tree_polars      |     0.729125 |       0.858056 |   0.821705 |
| k-d_tree_sklearn     |     0.735746 |       1.90556  |   0.849926 |
| barab-szabi-1        |     0.729323 |       0.854648 |   0.855217 |
| k-d_tree_pandas      |     0.728507 |       0.749017 |   1.08808  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.728261 |        5.27233 |   0.747481 |
| Bori_Aron_solution-1 |     0.72184  |       10.783   |   0.774055 |
| k-d_tree_sklearn     |     0.738043 |       15.5911  |   1.05126  |
| k-d_tree_polars      |     0.728881 |        4.83216 |   6.51445  |
| barab-szabi-1        |     0.730691 |        4.90775 |   6.61371  |
| k-d_tree_pandas      |     0.731463 |        3.89252 |   6.89477  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.992047 |        78.7547 |    4.00385 |
| k-d_tree_sklearn     |     0.802683 |       233.166  |    4.70859 |
| Bori_Aron_solution-1 |     0.721756 |       145.771  |   16.9082  |