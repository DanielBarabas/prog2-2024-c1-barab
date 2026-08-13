# 2026-08-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.47081  |       0.41086  |   0.435262 |
| barab-szabi-2        |     0.463286 |       0.437028 |   0.444487 |
| solution-1           |     7.39412  |       1e-06    |   0.466826 |
| k-d_tree_polars      |     8.04291  |       0.447839 |   0.497846 |
| Bori_Aron_solution-1 |     0.45248  |       0.553587 |   0.540666 |
| k-d_tree_pandas      |     0.462526 |       0.379226 |   0.541763 |
| k-d_tree_sklearn     |     2.88057  |       1.08034  |   1.10033  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.468444 |       0.422115 |   0.44628  |
| barab-szabi-2        |     0.477379 |       0.437686 |   0.450059 |
| k-d_tree_polars      |     0.482588 |       0.441893 |   0.455024 |
| Bori_Aron_solution-1 |     0.467729 |       0.561531 |   0.535479 |
| k-d_tree_pandas      |     0.461985 |       0.379631 |   0.542024 |
| k-d_tree_sklearn     |     0.470386 |       0.989738 |   1.06428  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478855 |       0.448513 |   0.451803 |
| barab-szabi-1        |     0.488163 |       0.464443 |   0.474477 |
| k-d_tree_polars      |     0.466558 |       0.459793 |   0.476384 |
| Bori_Aron_solution-1 |     0.467463 |       0.589134 |   0.544528 |
| k-d_tree_pandas      |     0.478523 |       0.415606 |   0.592393 |
| k-d_tree_sklearn     |     0.488056 |       1.04567  |   1.09468  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470399 |       0.511297 |   0.475834 |
| k-d_tree_polars      |     0.530893 |       0.559705 |   0.568967 |
| barab-szabi-1        |     0.47365  |       0.559248 |   0.574748 |
| Bori_Aron_solution-1 |     0.463688 |       0.810278 |   0.584541 |
| k-d_tree_pandas      |     0.465772 |       0.4921   |   0.732334 |
| k-d_tree_sklearn     |     0.48842  |       1.27997  |   1.11404  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.464901 |       1.46472  |   0.584983 |
| barab-szabi-2        |     0.485829 |       0.810641 |   0.653406 |
| k-d_tree_polars      |     0.469295 |       0.897976 |   0.962278 |
| barab-szabi-1        |     0.495116 |       0.927764 |   1.01959  |
| k-d_tree_pandas      |     0.481259 |       0.795196 |   1.21511  |
| k-d_tree_sklearn     |     0.475751 |       2.19814  |   1.23649  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480541 |        5.61801 |   0.730045 |
| Bori_Aron_solution-1 |     0.466374 |       10.9423  |   0.813945 |
| k-d_tree_sklearn     |     0.46654  |       16.9641  |   1.41367  |
| k-d_tree_polars      |     0.505402 |        5.11368 |   7.33778  |
| barab-szabi-1        |     0.538866 |        5.01891 |   7.3451   |
| k-d_tree_pandas      |     0.474692 |        4.04244 |   7.7996   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554054 |        76.0392 |    2.5478  |
| k-d_tree_sklearn     |     0.726753 |       263.139  |    3.53328 |
| Bori_Aron_solution-1 |     0.50255  |       158.169  |   15.3093  |