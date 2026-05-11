# 2026-05-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.497469 |       0.42221  |   0.445212 |
| barab-szabi-2        |     0.501012 |       0.471809 |   0.447895 |
| k-d_tree_polars      |     0.490854 |       0.429742 |   0.467582 |
| solution-1           |     8.23437  |       2e-06    |   0.494933 |
| Bori_Aron_solution-1 |     0.68025  |       0.572167 |   0.572061 |
| k-d_tree_pandas      |     0.480646 |       0.396691 |   0.595576 |
| k-d_tree_sklearn     |    11.0429   |       1.92037  |   1.14596  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.477133 |       0.420603 |   0.441527 |
| barab-szabi-2        |     0.502372 |       0.442455 |   0.444001 |
| barab-szabi-1        |     0.473292 |       0.41369  |   0.450707 |
| Bori_Aron_solution-1 |     0.461731 |       0.567564 |   0.55219  |
| k-d_tree_pandas      |     0.467787 |       0.394073 |   0.565187 |
| k-d_tree_sklearn     |     0.467053 |       0.983851 |   1.08624  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465927 |       0.447766 |   0.452958 |
| barab-szabi-1        |     0.472905 |       0.448275 |   0.47522  |
| k-d_tree_polars      |     0.467904 |       0.456777 |   0.517083 |
| Bori_Aron_solution-1 |     0.469923 |       0.612271 |   0.565103 |
| k-d_tree_pandas      |     0.475139 |       0.414417 |   0.610179 |
| k-d_tree_sklearn     |     0.469498 |       1.06083  |   1.12808  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486741 |       0.535269 |   0.490461 |
| barab-szabi-1        |     0.459908 |       0.561154 |   0.572612 |
| Bori_Aron_solution-1 |     0.454205 |       0.792972 |   0.577248 |
| k-d_tree_polars      |     0.47082  |       0.579078 |   0.599487 |
| k-d_tree_pandas      |     0.470155 |       0.497355 |   0.73833  |
| k-d_tree_sklearn     |     0.481189 |       1.33953  |   1.18983  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.458319 |       0.722233 |   0.504527 |
| Bori_Aron_solution-1 |     0.461664 |       1.47244  |   0.603031 |
| k-d_tree_polars      |     0.464477 |       0.929383 |   0.916366 |
| barab-szabi-1        |     0.459069 |       0.928427 |   0.941814 |
| k-d_tree_pandas      |     0.457772 |       0.808631 |   1.17349  |
| k-d_tree_sklearn     |     0.465118 |       2.13582  |   1.24121  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.459327 |        5.00705 |   0.764393 |
| Bori_Aron_solution-1 |     0.452775 |       11.0503  |   0.809407 |
| k-d_tree_sklearn     |     0.464871 |       16.695   |   1.30085  |
| barab-szabi-1        |     0.458317 |        5.51968 |   6.57015  |
| k-d_tree_polars      |     0.463236 |        5.45303 |   6.72545  |
| k-d_tree_pandas      |     0.461218 |        4.48906 |   6.96495  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.789279 |        72.6592 |    2.88484 |
| k-d_tree_sklearn     |     0.461059 |       240.609  |    3.83074 |
| Bori_Aron_solution-1 |     0.463951 |       154.657  |   21.6065  |