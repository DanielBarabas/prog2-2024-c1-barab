# 2026-04-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.470891 |       0.39871  |   0.441346 |
| barab-szabi-2        |     0.470848 |       0.452194 |   0.452667 |
| solution-1           |     8.22131  |       1e-06    |   0.459185 |
| Bori_Aron_solution-1 |     0.460536 |       0.548532 |   0.552694 |
| k-d_tree_pandas      |     0.467803 |       0.387953 |   0.576674 |
| barab-szabi-1        |     7.85386  |       0.453466 |   0.596221 |
| k-d_tree_sklearn     |     2.95359  |       1.20703  |   1.10007  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477413 |       0.452098 |   0.440186 |
| k-d_tree_polars      |     0.466678 |       0.412328 |   0.447182 |
| barab-szabi-1        |     0.478953 |       0.417475 |   0.453577 |
| Bori_Aron_solution-1 |     0.470676 |       0.589988 |   0.560597 |
| k-d_tree_pandas      |     0.478747 |       0.407901 |   0.562401 |
| k-d_tree_sklearn     |     0.486131 |       1.04126  |   1.08428  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472649 |       0.458912 |   0.454165 |
| barab-szabi-1        |     0.465601 |       0.445621 |   0.47358  |
| k-d_tree_polars      |     0.473129 |       0.440382 |   0.480075 |
| Bori_Aron_solution-1 |     0.469142 |       0.615333 |   0.56153  |
| k-d_tree_pandas      |     0.461994 |       0.420402 |   0.623461 |
| k-d_tree_sklearn     |     0.474995 |       1.05072  |   1.11202  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473215 |       0.514729 |   0.488974 |
| k-d_tree_polars      |     0.477271 |       0.566791 |   0.563395 |
| Bori_Aron_solution-1 |     0.462829 |       0.790872 |   0.566375 |
| barab-szabi-1        |     0.493501 |       0.58278  |   0.595763 |
| k-d_tree_pandas      |     0.48363  |       0.512824 |   0.74651  |
| k-d_tree_sklearn     |     0.482288 |       1.33254  |   1.19053  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479994 |       0.761349 |   0.540258 |
| Bori_Aron_solution-1 |     0.475108 |       1.49949  |   0.608173 |
| k-d_tree_polars      |     0.478628 |       0.946312 |   0.96391  |
| barab-szabi-1        |     0.476268 |       0.943881 |   0.970954 |
| k-d_tree_pandas      |     0.4745   |       0.825612 |   1.22111  |
| k-d_tree_sklearn     |     0.472856 |       2.20968  |   1.30168  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470965 |        5.11973 |   0.74971  |
| Bori_Aron_solution-1 |     0.46338  |       11.0895  |   0.833287 |
| k-d_tree_sklearn     |     0.478917 |       17.1534  |   1.31143  |
| barab-szabi-1        |     0.493163 |        5.62667 |   6.63361  |
| k-d_tree_polars      |     0.469885 |        5.58659 |   6.68415  |
| k-d_tree_pandas      |     0.465214 |        4.51918 |   6.98515  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.810879 |         70.339 |    2.72408 |
| k-d_tree_sklearn     |     0.479527 |        246.185 |    3.86342 |
| Bori_Aron_solution-1 |     0.480107 |        152.54  |   17.7335  |