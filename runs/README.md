# 2024-05-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.61345  |       0.354358 |   0.346198 |
| barab-szabi-1        |     0.793211 |       0.415152 |   0.355579 |
| k-d_tree_polars      |     0.78566  |       0.416766 |   0.401053 |
| Bori_Aron_solution-1 |     4.58807  |       0.42278  |   0.416724 |
| k-d_tree_pandas      |     0.810119 |       0.386505 |   0.483452 |
| solution-1           |     7.91579  |       1e-06    |   0.665598 |
| k-d_tree_sklearn     |     3.40288  |       1.13193  |   0.683377 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.793792 |       0.349885 |   0.347429 |
| barab-szabi-1        |     0.790949 |       0.412022 |   0.353762 |
| k-d_tree_polars      |     0.796454 |       0.429258 |   0.357277 |
| Bori_Aron_solution-1 |     0.789011 |       0.491875 |   0.483361 |
| k-d_tree_pandas      |     0.802767 |       0.40144  |   0.493633 |
| k-d_tree_sklearn     |     0.798012 |       0.876928 |   0.688546 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.789415 |       0.362988 |   0.360175 |
| barab-szabi-1        |     0.799789 |       0.44174  |   0.379389 |
| k-d_tree_polars      |     0.795158 |       0.439513 |   0.387506 |
| Bori_Aron_solution-1 |     0.786488 |       0.526921 |   0.488842 |
| k-d_tree_pandas      |     0.793777 |       0.410245 |   0.565486 |
| k-d_tree_sklearn     |     0.797826 |       0.918497 |   0.715813 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.802348 |       0.438244 |   0.397926 |
| k-d_tree_polars      |     0.792417 |       0.546677 |   0.47754  |
| barab-szabi-1        |     0.795849 |       0.549179 |   0.491464 |
| Bori_Aron_solution-1 |     0.792383 |       0.707587 |   0.506755 |
| k-d_tree_pandas      |     0.796214 |       0.49285  |   0.663374 |
| k-d_tree_sklearn     |     0.806978 |       1.15688  |   0.778255 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.796    |       0.683228 |   0.431636 |
| Bori_Aron_solution-1 |     0.786639 |       1.36285  |   0.519197 |
| k-d_tree_polars      |     0.795318 |       0.889241 |   0.837685 |
| barab-szabi-1        |     0.79679  |       0.871605 |   0.877831 |
| k-d_tree_sklearn     |     0.792641 |       1.99002  |   0.879198 |
| k-d_tree_pandas      |     0.794518 |       0.762205 |   1.11258  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.792517 |        5.48848 |   0.736369 |
| Bori_Aron_solution-1 |     0.78617  |       10.9132  |   0.773959 |
| k-d_tree_sklearn     |     0.815275 |       16.5847  |   1.05448  |
| barab-szabi-1        |     0.795949 |        5.05251 |   6.72013  |
| k-d_tree_polars      |     0.799913 |        4.95742 |   6.85644  |
| k-d_tree_pandas      |     0.793315 |        4.0103  |   7.03988  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.00368  |        72.7226 |    4.05891 |
| k-d_tree_sklearn     |     0.902597 |       230.084  |    4.45025 |
| Bori_Aron_solution-1 |     0.785417 |       154.7    |   15.1486  |