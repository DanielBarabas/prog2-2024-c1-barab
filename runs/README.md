# 2026-06-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.461126 |       0.406814 |   0.443513 |
| barab-szabi-2        |     8.11969  |       0.64795  |   0.446917 |
| barab-szabi-1        |     0.472169 |       0.424202 |   0.449621 |
| solution-1           |     7.3116   |       1e-06    |   0.451524 |
| Bori_Aron_solution-1 |     0.458021 |       0.542338 |   0.547106 |
| k-d_tree_pandas      |     0.520289 |       0.41646  |   0.553297 |
| k-d_tree_sklearn     |     2.89008  |       1.13638  |   1.08956  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480114 |       0.450459 |   0.441753 |
| k-d_tree_polars      |     0.47705  |       0.412693 |   0.451355 |
| barab-szabi-1        |     0.476927 |       0.423175 |   0.459419 |
| Bori_Aron_solution-1 |     0.471817 |       0.568124 |   0.549527 |
| k-d_tree_pandas      |     0.478594 |       0.389259 |   0.585363 |
| k-d_tree_sklearn     |     0.48138  |       0.98614  |   1.07861  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466939 |       0.455769 |   0.460251 |
| k-d_tree_polars      |     0.471968 |       0.448013 |   0.476985 |
| barab-szabi-1        |     0.47493  |       0.444721 |   0.480934 |
| Bori_Aron_solution-1 |     0.468148 |       0.595217 |   0.591642 |
| k-d_tree_pandas      |     0.484301 |       0.414895 |   0.602619 |
| k-d_tree_sklearn     |     0.478446 |       1.01978  |   1.09665  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474295 |       0.515008 |   0.481957 |
| Bori_Aron_solution-1 |     0.470765 |       0.798696 |   0.561368 |
| k-d_tree_polars      |     0.47126  |       0.567291 |   0.574003 |
| barab-szabi-1        |     0.473467 |       0.570161 |   0.581679 |
| k-d_tree_pandas      |     0.479585 |       0.51063  |   0.753613 |
| k-d_tree_sklearn     |     0.47937  |       1.25618  |   1.14938  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470653 |       0.727803 |   0.510256 |
| Bori_Aron_solution-1 |     0.477561 |       1.465    |   0.600335 |
| k-d_tree_polars      |     0.473259 |       0.952325 |   0.918823 |
| barab-szabi-1        |     0.473192 |       0.942583 |   0.978873 |
| k-d_tree_pandas      |     0.479425 |       0.833472 |   1.18121  |
| k-d_tree_sklearn     |     0.47333  |       2.12631  |   1.28493  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485961 |        5.08552 |   0.757459 |
| Bori_Aron_solution-1 |     0.482653 |       11.4496  |   0.851593 |
| k-d_tree_sklearn     |     0.485822 |       16.8356  |   1.30436  |
| barab-szabi-1        |     0.46929  |        5.516   |   6.6457   |
| k-d_tree_polars      |     0.486481 |        5.57464 |   6.80797  |
| k-d_tree_pandas      |     0.46711  |        4.45126 |   7.1046   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477253 |        76.4599 |    2.99813 |
| k-d_tree_sklearn     |     0.772151 |       248.291  |    4.26036 |
| Bori_Aron_solution-1 |     0.472007 |       161.313  |   18.4329  |