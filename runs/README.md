# 2026-03-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.78074  |       1e-06    |   0.381988 |
| barab-szabi-2        |     0.491546 |       0.459141 |   0.43835  |
| k-d_tree_polars      |     0.497143 |       0.406813 |   0.446475 |
| barab-szabi-1        |     8.1552   |       0.450945 |   0.58099  |
| Bori_Aron_solution-1 |     0.482422 |       0.570971 |   0.583303 |
| k-d_tree_pandas      |     0.498657 |       0.410997 |   0.593242 |
| k-d_tree_sklearn     |     2.96091  |       1.34048  |   1.12338  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.500454 |       0.441506 |   0.449394 |
| barab-szabi-1        |     0.511853 |       0.448464 |   0.449536 |
| k-d_tree_polars      |     0.5206   |       0.437871 |   0.496052 |
| Bori_Aron_solution-1 |     0.500654 |       0.571002 |   0.582697 |
| k-d_tree_pandas      |     0.526476 |       0.418203 |   0.593325 |
| k-d_tree_sklearn     |     0.512732 |       1.00265  |   1.08341  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.51152  |       0.451325 |   0.466352 |
| barab-szabi-2        |     0.520921 |       0.480114 |   0.466697 |
| barab-szabi-1        |     0.501727 |       0.44901  |   0.49052  |
| Bori_Aron_solution-1 |     0.488322 |       0.609543 |   0.565766 |
| k-d_tree_pandas      |     0.497115 |       0.43038  |   0.625978 |
| k-d_tree_sklearn     |     0.50354  |       1.03153  |   1.15831  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.51228  |       0.532743 |   0.501809 |
| Bori_Aron_solution-1 |     0.505727 |       0.826051 |   0.580654 |
| k-d_tree_polars      |     0.50929  |       0.586642 |   0.589105 |
| barab-szabi-1        |     0.510168 |       0.588747 |   0.60316  |
| k-d_tree_pandas      |     0.522288 |       0.518344 |   0.77741  |
| k-d_tree_sklearn     |     0.511778 |       1.30442  |   1.16113  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525592 |       0.747521 |   0.51318  |
| Bori_Aron_solution-1 |     0.487095 |       1.5446   |   0.619224 |
| k-d_tree_polars      |     0.515891 |       0.966464 |   0.980884 |
| barab-szabi-1        |     0.498725 |       0.957783 |   0.991848 |
| k-d_tree_pandas      |     0.530942 |       0.825668 |   1.2229   |
| k-d_tree_sklearn     |     0.512111 |       2.29026  |   1.27467  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535239 |        5.35311 |   0.782828 |
| Bori_Aron_solution-1 |     0.50277  |       11.6382  |   0.836829 |
| k-d_tree_sklearn     |     0.513305 |       18.3505  |   1.36442  |
| k-d_tree_polars      |     0.539441 |        5.70269 |   7.08779  |
| barab-szabi-1        |     0.513876 |        5.68672 |   7.11803  |
| k-d_tree_pandas      |     0.511605 |        4.61812 |   7.34905  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.504192 |        77.9214 |    2.83506 |
| k-d_tree_sklearn     |     0.886303 |       242.714  |    4.06643 |
| Bori_Aron_solution-1 |     0.525276 |       159.488  |   18.0754  |