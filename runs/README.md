# 2025-12-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.509833 |       0.523674 |   0.422971 |
| barab-szabi-1        |     0.527984 |       0.405424 |   0.42809  |
| k-d_tree_polars      |     0.53205  |       0.402752 |   0.430199 |
| Bori_Aron_solution-1 |     0.523156 |       0.550197 |   0.547391 |
| solution-1           |     8.24432  |       2e-06    |   0.563328 |
| k-d_tree_pandas      |     8.9682   |       0.406697 |   0.690933 |
| k-d_tree_sklearn     |     3.06062  |       1.27975  |   1.05846  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528245 |       0.430357 |   0.434973 |
| k-d_tree_polars      |     0.530027 |       0.412832 |   0.43844  |
| barab-szabi-1        |     0.526887 |       0.412137 |   0.438692 |
| Bori_Aron_solution-1 |     0.516477 |       0.557146 |   0.543785 |
| k-d_tree_pandas      |     0.525799 |       0.387678 |   0.556258 |
| k-d_tree_sklearn     |     0.528955 |       0.976709 |   1.07198  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528431 |       0.437941 |   0.439623 |
| barab-szabi-1        |     0.530197 |       0.440136 |   0.459989 |
| k-d_tree_polars      |     0.533271 |       0.436385 |   0.461886 |
| Bori_Aron_solution-1 |     0.522386 |       0.60203  |   0.551225 |
| k-d_tree_pandas      |     0.534576 |       0.40755  |   0.598103 |
| k-d_tree_sklearn     |     0.530519 |       1.01878  |   1.07146  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528596 |       0.50264  |   0.475713 |
| k-d_tree_polars      |     0.530877 |       0.558995 |   0.561034 |
| Bori_Aron_solution-1 |     0.51763  |       0.782282 |   0.564499 |
| barab-szabi-1        |     0.527696 |       0.557899 |   0.566606 |
| k-d_tree_pandas      |     0.528404 |       0.53434  |   0.745809 |
| k-d_tree_sklearn     |     0.534179 |       1.26472  |   1.14072  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52603  |       0.743992 |   0.504057 |
| Bori_Aron_solution-1 |     0.518532 |       1.45659  |   0.584537 |
| k-d_tree_polars      |     0.52538  |       0.926268 |   0.907293 |
| barab-szabi-1        |     0.529944 |       0.920067 |   0.951533 |
| k-d_tree_pandas      |     0.54093  |       0.809538 |   1.17248  |
| k-d_tree_sklearn     |     0.528928 |       2.13401  |   1.21142  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525437 |        5.52075 |   0.764184 |
| Bori_Aron_solution-1 |     0.515142 |       11.2556  |   0.834738 |
| k-d_tree_sklearn     |     0.542774 |       17.018   |   1.3273   |
| k-d_tree_polars      |     0.524812 |        5.45109 |   6.65924  |
| barab-szabi-1        |     0.528759 |        5.46453 |   6.67474  |
| k-d_tree_pandas      |     0.529374 |        4.40902 |   7.11049  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.524077 |        79.5773 |    2.74171 |
| k-d_tree_sklearn     |     0.536952 |       237.729  |    4.02747 |
| Bori_Aron_solution-1 |     0.650589 |       151.15   |   16.5012  |