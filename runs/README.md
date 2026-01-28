# 2026-01-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.526831 |       0.395972 |   0.427632 |
| barab-szabi-1        |     0.526017 |       0.397841 |   0.429957 |
| barab-szabi-2        |     0.51413  |       0.51878  |   0.440712 |
| solution-1           |     7.73736  |       1e-06    |   0.492255 |
| Bori_Aron_solution-1 |     0.518468 |       0.53151  |   0.532189 |
| k-d_tree_pandas      |     8.28212  |       0.435309 |   0.675023 |
| k-d_tree_sklearn     |     3.20121  |       1.09056  |   1.04595  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52514  |       0.42763  |   0.430069 |
| k-d_tree_polars      |     0.533538 |       0.408498 |   0.437509 |
| barab-szabi-1        |     0.532815 |       0.411894 |   0.45477  |
| Bori_Aron_solution-1 |     0.526157 |       0.548128 |   0.544    |
| k-d_tree_pandas      |     0.526047 |       0.385331 |   0.548975 |
| k-d_tree_sklearn     |     0.535868 |       0.958123 |   1.05807  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53785  |       0.447805 |   0.439647 |
| k-d_tree_polars      |     0.528367 |       0.436305 |   0.462389 |
| barab-szabi-1        |     0.525561 |       0.437959 |   0.47375  |
| Bori_Aron_solution-1 |     0.523991 |       0.596312 |   0.587132 |
| k-d_tree_pandas      |     0.529105 |       0.401545 |   0.594962 |
| k-d_tree_sklearn     |     0.541922 |       1.01281  |   1.09083  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534712 |       0.510658 |   0.472112 |
| k-d_tree_polars      |     0.538596 |       0.556706 |   0.554775 |
| Bori_Aron_solution-1 |     0.534595 |       0.767701 |   0.555832 |
| barab-szabi-1        |     0.533797 |       0.559104 |   0.574509 |
| k-d_tree_pandas      |     0.530887 |       0.498919 |   0.733703 |
| k-d_tree_sklearn     |     0.536785 |       1.26635  |   1.15175  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528761 |       0.72879  |   0.5112   |
| Bori_Aron_solution-1 |     0.528414 |       1.46697  |   0.595347 |
| k-d_tree_polars      |     0.52754  |       0.928674 |   0.916535 |
| barab-szabi-1        |     0.529734 |       0.938659 |   0.940868 |
| k-d_tree_pandas      |     0.531643 |       0.807513 |   1.17918  |
| k-d_tree_sklearn     |     0.531363 |       2.11284  |   1.21368  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529248 |        5.0716  |   0.73964  |
| Bori_Aron_solution-1 |     0.539634 |       11.1966  |   0.845319 |
| k-d_tree_sklearn     |     0.53356  |       16.5847  |   1.30192  |
| barab-szabi-1        |     0.525601 |        5.67655 |   6.54354  |
| k-d_tree_polars      |     0.535545 |        5.59263 |   6.61232  |
| k-d_tree_pandas      |     0.533183 |        4.57355 |   6.92696  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527421 |         76.491 |    2.62822 |
| k-d_tree_sklearn     |     0.538508 |        230.029 |    3.9998  |
| Bori_Aron_solution-1 |     0.629568 |        152.62  |   15.2292  |