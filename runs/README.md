# 2026-07-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.38051  |       1e-06    |   0.373945 |
| k-d_tree_polars      |     0.429968 |       0.379833 |   0.410442 |
| barab-szabi-2        |     0.415475 |       0.41597  |   0.436656 |
| Bori_Aron_solution-1 |     0.426695 |       0.494329 |   0.502397 |
| k-d_tree_pandas      |     0.414825 |       0.34917  |   0.518368 |
| barab-szabi-1        |     8.10706  |       0.408081 |   0.556299 |
| k-d_tree_sklearn     |     2.67574  |       1.0042   |   0.955748 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.413838 |       0.413121 |   0.408427 |
| barab-szabi-1        |     0.415836 |       0.380495 |   0.41685  |
| k-d_tree_polars      |     0.430355 |       0.391556 |   0.419823 |
| Bori_Aron_solution-1 |     0.430292 |       0.5056   |   0.495085 |
| k-d_tree_pandas      |     0.421357 |       0.357649 |   0.510334 |
| k-d_tree_sklearn     |     0.452958 |       0.920744 |   0.984586 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.418614 |       0.431082 |   0.42309  |
| barab-szabi-1        |     0.416592 |       0.430644 |   0.439338 |
| k-d_tree_polars      |     0.418673 |       0.412612 |   0.446944 |
| Bori_Aron_solution-1 |     0.415637 |       0.550896 |   0.510765 |
| k-d_tree_pandas      |     0.425673 |       0.389693 |   0.543134 |
| k-d_tree_sklearn     |     0.424536 |       0.964192 |   0.985445 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.415417 |       0.48586  |   0.465332 |
| Bori_Aron_solution-1 |     0.441832 |       0.734522 |   0.528726 |
| barab-szabi-1        |     0.415604 |       0.520849 |   0.529344 |
| k-d_tree_polars      |     0.431418 |       0.541294 |   0.535978 |
| k-d_tree_pandas      |     0.435681 |       0.487766 |   0.68397  |
| k-d_tree_sklearn     |     0.431782 |       1.17904  |   1.05272  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.439293 |       0.713646 |   0.509618 |
| Bori_Aron_solution-1 |     0.423651 |       1.29943  |   0.556832 |
| k-d_tree_polars      |     0.428821 |       0.854466 |   0.851237 |
| barab-szabi-1        |     0.432405 |       0.870344 |   0.880001 |
| k-d_tree_pandas      |     0.436787 |       0.720699 |   1.06537  |
| k-d_tree_sklearn     |     0.436764 |       1.95048  |   1.15213  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.432306 |        4.84798 |   0.719161 |
| Bori_Aron_solution-1 |     0.430224 |       10.0591  |   0.893666 |
| k-d_tree_sklearn     |     0.441297 |       15.131   |   1.26623  |
| k-d_tree_polars      |     0.439241 |        4.73165 |   6.1917   |
| barab-szabi-1        |     0.431933 |        4.75594 |   6.26535  |
| k-d_tree_pandas      |     0.43738  |        3.72606 |   6.55211  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.431434 |        67.0727 |    2.66863 |
| k-d_tree_sklearn     |     0.770965 |       176.972  |    4.26865 |
| Bori_Aron_solution-1 |     0.431947 |       138.504  |   31.6503  |