# 2025-10-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.548787 |       0.413086 |   0.433751 |
| barab-szabi-1        |     0.558487 |       0.413819 |   0.439017 |
| barab-szabi-2        |     0.543814 |       0.448016 |   0.441252 |
| Bori_Aron_solution-1 |     0.545058 |       0.555901 |   0.553457 |
| solution-1           |     7.24146  |       1e-06    |   0.555794 |
| k-d_tree_pandas      |     8.06883  |       0.437279 |   0.731545 |
| k-d_tree_sklearn     |     2.92854  |       1.1063   |   1.07524  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.55357  |       0.415943 |   0.436443 |
| k-d_tree_polars      |     0.550819 |       0.418151 |   0.440871 |
| barab-szabi-2        |     0.553685 |       0.440523 |   0.451044 |
| Bori_Aron_solution-1 |     0.545177 |       0.561653 |   0.557923 |
| k-d_tree_pandas      |     0.554207 |       0.405966 |   0.561937 |
| k-d_tree_sklearn     |     0.551379 |       0.986583 |   1.07321  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551603 |       0.444952 |   0.444413 |
| k-d_tree_polars      |     0.557464 |       0.446236 |   0.46896  |
| barab-szabi-1        |     0.563195 |       0.449629 |   0.481643 |
| Bori_Aron_solution-1 |     0.548257 |       0.611465 |   0.558624 |
| k-d_tree_pandas      |     0.550043 |       0.418781 |   0.604279 |
| k-d_tree_sklearn     |     0.558051 |       1.03803  |   1.10485  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554154 |       0.526499 |   0.476898 |
| Bori_Aron_solution-1 |     0.543415 |       0.794101 |   0.568324 |
| barab-szabi-1        |     0.552711 |       0.586655 |   0.577264 |
| k-d_tree_polars      |     0.570502 |       0.587012 |   0.583949 |
| k-d_tree_pandas      |     0.552355 |       0.516024 |   0.752643 |
| k-d_tree_sklearn     |     0.555371 |       1.28698  |   1.15354  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549603 |       0.774913 |   0.521764 |
| Bori_Aron_solution-1 |     0.543227 |       1.48825  |   0.597921 |
| k-d_tree_polars      |     0.55315  |       0.95799  |   0.941708 |
| barab-szabi-1        |     0.549188 |       0.958088 |   0.974834 |
| k-d_tree_pandas      |     0.550829 |       0.842119 |   1.20412  |
| k-d_tree_sklearn     |     0.559257 |       2.19126  |   1.25065  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547857 |        5.41641 |   0.751988 |
| Bori_Aron_solution-1 |     0.546505 |       11.4228  |   0.850516 |
| k-d_tree_sklearn     |     0.556736 |       17.8069  |   1.33822  |
| k-d_tree_polars      |     0.557075 |        5.59982 |   6.7251   |
| barab-szabi-1        |     0.555773 |        5.57773 |   6.95641  |
| k-d_tree_pandas      |     0.553708 |        4.63756 |   7.12311  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550249 |         75.328 |    2.86659 |
| k-d_tree_sklearn     |     0.5718   |        242.418 |    4.35773 |
| Bori_Aron_solution-1 |     0.789789 |        157.214 |   17.8467  |