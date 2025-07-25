# 2025-07-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.59503  |       0.57457  |   0.420765 |
| barab-szabi-1        |     0.543395 |       0.405646 |   0.421085 |
| k-d_tree_polars      |     0.550367 |       0.402194 |   0.429001 |
| solution-1           |     7.44688  |       1e-06    |   0.437869 |
| Bori_Aron_solution-1 |     0.527946 |       0.551117 |   0.539335 |
| k-d_tree_pandas      |     0.550897 |       0.438611 |   0.550236 |
| k-d_tree_sklearn     |     2.92347  |       1.09428  |   1.04528  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.546148 |       0.412353 |   0.424876 |
| k-d_tree_polars      |     0.550297 |       0.407813 |   0.425575 |
| barab-szabi-2        |     0.547588 |       0.422121 |   0.437025 |
| Bori_Aron_solution-1 |     0.545536 |       0.552974 |   0.540789 |
| k-d_tree_pandas      |     0.555227 |       0.392279 |   0.56565  |
| k-d_tree_sklearn     |     0.556337 |       0.956633 |   1.04283  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548981 |       0.437502 |   0.43574  |
| k-d_tree_polars      |     0.551421 |       0.43601  |   0.451398 |
| barab-szabi-1        |     0.55141  |       0.431684 |   0.452598 |
| Bori_Aron_solution-1 |     0.540305 |       0.587267 |   0.559435 |
| k-d_tree_pandas      |     0.55381  |       0.406235 |   0.596594 |
| k-d_tree_sklearn     |     0.554321 |       1.03187  |   1.07627  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558309 |       0.492412 |   0.463987 |
| k-d_tree_polars      |     0.553428 |       0.544231 |   0.545697 |
| barab-szabi-1        |     0.553224 |       0.54703  |   0.561287 |
| Bori_Aron_solution-1 |     0.546342 |       0.76425  |   0.564006 |
| k-d_tree_pandas      |     0.552167 |       0.48564  |   0.731114 |
| k-d_tree_sklearn     |     0.55701  |       1.24056  |   1.11969  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549018 |       0.745128 |   0.49931  |
| Bori_Aron_solution-1 |     0.543222 |       1.40011  |   0.582741 |
| k-d_tree_polars      |     0.550254 |       0.893853 |   0.919616 |
| barab-szabi-1        |     0.554241 |       0.881566 |   0.946653 |
| k-d_tree_pandas      |     0.56165  |       0.763853 |   1.17452  |
| k-d_tree_sklearn     |     0.55273  |       2.07857  |   1.20683  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548471 |        5.35693 |   0.727201 |
| Bori_Aron_solution-1 |     0.543351 |       10.5781  |   0.839268 |
| k-d_tree_sklearn     |     0.557709 |       16.3859  |   1.31494  |
| k-d_tree_polars      |     0.552503 |        5.03196 |   6.56727  |
| barab-szabi-1        |     0.570666 |        5.09367 |   6.62281  |
| k-d_tree_pandas      |     0.551064 |        3.93473 |   7.10742  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551039 |        69.7224 |    2.76978 |
| k-d_tree_sklearn     |     0.765937 |       237.614  |    4.03293 |
| Bori_Aron_solution-1 |     0.563568 |       143.763  |   18.8912  |