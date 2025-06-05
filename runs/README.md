# 2025-06-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.596677 |       0.4258   |   0.422041 |
| k-d_tree_polars      |     0.546928 |       0.403243 |   0.432419 |
| solution-1           |     8.20466  |       1e-06    |   0.482386 |
| Bori_Aron_solution-1 |     0.542353 |       0.550989 |   0.548972 |
| k-d_tree_pandas      |     0.565584 |       0.406172 |   0.557847 |
| barab-szabi-1        |     8.14062  |       0.497012 |   0.612316 |
| k-d_tree_sklearn     |     3.21926  |       1.10257  |   1.07886  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.562898 |       0.412857 |   0.429212 |
| barab-szabi-2        |     0.557508 |       0.426501 |   0.435081 |
| k-d_tree_polars      |     0.557194 |       0.429827 |   0.478615 |
| k-d_tree_pandas      |     0.556374 |       0.393196 |   0.557276 |
| Bori_Aron_solution-1 |     0.547305 |       0.55269  |   0.576068 |
| k-d_tree_sklearn     |     0.55798  |       0.970048 |   1.04961  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557436 |       0.437046 |   0.432374 |
| k-d_tree_polars      |     0.557846 |       0.438361 |   0.448564 |
| barab-szabi-1        |     0.571871 |       0.443005 |   0.454838 |
| Bori_Aron_solution-1 |     0.55336  |       0.593485 |   0.550716 |
| k-d_tree_pandas      |     0.563151 |       0.412659 |   0.63969  |
| k-d_tree_sklearn     |     0.553069 |       1.01238  |   1.07818  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552953 |       0.492287 |   0.460776 |
| k-d_tree_polars      |     0.562128 |       0.554322 |   0.55336  |
| Bori_Aron_solution-1 |     0.550754 |       0.77125  |   0.565997 |
| barab-szabi-1        |     0.559401 |       0.55079  |   0.57525  |
| k-d_tree_pandas      |     0.554336 |       0.489637 |   0.740671 |
| k-d_tree_sklearn     |     0.562122 |       1.243    |   1.13939  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557554 |       0.752069 |   0.499871 |
| Bori_Aron_solution-1 |     0.54888  |       1.40836  |   0.582324 |
| k-d_tree_polars      |     0.560726 |       0.880957 |   0.901601 |
| barab-szabi-1        |     0.559366 |       0.881654 |   0.940413 |
| k-d_tree_pandas      |     0.556424 |       0.754895 |   1.20226  |
| k-d_tree_sklearn     |     0.578886 |       2.09667  |   1.22192  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554235 |        5.35415 |   0.736642 |
| Bori_Aron_solution-1 |     0.548005 |       10.7053  |   0.836868 |
| k-d_tree_sklearn     |     0.568665 |       16.4455  |   1.3281   |
| barab-szabi-1        |     0.552874 |        5.01701 |   6.65931  |
| k-d_tree_polars      |     0.558561 |        4.97036 |   6.668    |
| k-d_tree_pandas      |     0.560604 |        3.9597  |   7.09313  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.672445 |        72.2608 |    2.8013  |
| k-d_tree_sklearn     |     0.876142 |       229.937  |    4.42352 |
| Bori_Aron_solution-1 |     0.546169 |       143.244  |   16.9901  |