# 2026-07-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.35939  |       1e-06    |   0.42031  |
| barab-szabi-2        |     7.93773  |       0.543041 |   0.437109 |
| barab-szabi-1        |     0.473092 |       0.433663 |   0.45661  |
| k-d_tree_polars      |     0.471941 |       0.421802 |   0.461947 |
| Bori_Aron_solution-1 |     0.484911 |       0.554999 |   0.554896 |
| k-d_tree_pandas      |     0.483903 |       0.398248 |   0.56746  |
| k-d_tree_sklearn     |     2.94231  |       1.16109  |   1.10498  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484939 |       0.450041 |   0.451739 |
| k-d_tree_polars      |     0.479896 |       0.431838 |   0.456148 |
| barab-szabi-1        |     0.478807 |       0.464712 |   0.489875 |
| Bori_Aron_solution-1 |     0.477646 |       0.57311  |   0.553541 |
| k-d_tree_pandas      |     0.481905 |       0.400094 |   0.581778 |
| k-d_tree_sklearn     |     0.484471 |       1.04896  |   1.10985  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485091 |       0.473672 |   0.473421 |
| k-d_tree_polars      |     0.481809 |       0.46569  |   0.482951 |
| barab-szabi-1        |     0.482871 |       0.463729 |   0.495441 |
| Bori_Aron_solution-1 |     0.478109 |       0.62714  |   0.562792 |
| k-d_tree_pandas      |     0.48506  |       0.418428 |   0.619564 |
| k-d_tree_sklearn     |     0.484047 |       1.08363  |   1.14822  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481387 |       0.521471 |   0.493116 |
| Bori_Aron_solution-1 |     0.48009  |       0.786805 |   0.575826 |
| k-d_tree_polars      |     0.487212 |       0.601902 |   0.585361 |
| barab-szabi-1        |     0.48108  |       0.587684 |   0.594353 |
| k-d_tree_pandas      |     0.488485 |       0.502973 |   0.747093 |
| k-d_tree_sklearn     |     0.48515  |       1.32035  |   1.19312  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483474 |       0.747734 |   0.516299 |
| Bori_Aron_solution-1 |     0.477298 |       1.44661  |   0.587474 |
| k-d_tree_polars      |     0.485889 |       0.925118 |   0.952533 |
| barab-szabi-1        |     0.479382 |       0.955344 |   0.974726 |
| k-d_tree_pandas      |     0.472174 |       0.80077  |   1.19941  |
| k-d_tree_sklearn     |     0.484362 |       2.19129  |   1.25735  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.4843   |        5.42653 |   0.791878 |
| Bori_Aron_solution-1 |     0.472828 |       11.1931  |   0.822145 |
| k-d_tree_sklearn     |     0.475543 |       17.2269  |   1.30598  |
| barab-szabi-1        |     0.492739 |        5.3549  |   6.80872  |
| k-d_tree_polars      |     0.481511 |        5.31795 |   6.97769  |
| k-d_tree_pandas      |     0.47411  |        4.28886 |   7.2561   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475495 |        72.8266 |    2.95731 |
| k-d_tree_sklearn     |     0.82812  |       242.525  |    4.00229 |
| Bori_Aron_solution-1 |     0.467816 |       145.841  |   24.4798  |