# 2026-03-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482551 |       0.437674 |   0.43607  |
| k-d_tree_polars      |     0.486861 |       0.411201 |   0.441253 |
| solution-1           |     7.87407  |       1e-06    |   0.485519 |
| Bori_Aron_solution-1 |     0.48237  |       0.551258 |   0.556344 |
| k-d_tree_pandas      |     0.48779  |       0.388856 |   0.566098 |
| barab-szabi-1        |     8.73441  |       0.462775 |   0.616337 |
| k-d_tree_sklearn     |     3.11104  |       1.12666  |   1.10807  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498654 |       0.436921 |   0.440001 |
| k-d_tree_polars      |     0.500391 |       0.414373 |   0.443441 |
| barab-szabi-1        |     0.504178 |       0.41516  |   0.447131 |
| Bori_Aron_solution-1 |     0.500602 |       0.5707   |   0.561306 |
| k-d_tree_pandas      |     0.50823  |       0.414064 |   0.572678 |
| k-d_tree_sklearn     |     0.499919 |       1.0471   |   1.08498  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.496728 |       0.439551 |   0.463983 |
| barab-szabi-1        |     0.496261 |       0.458254 |   0.480081 |
| barab-szabi-2        |     0.504513 |       0.46185  |   0.50265  |
| Bori_Aron_solution-1 |     0.491089 |       0.601437 |   0.561605 |
| k-d_tree_pandas      |     0.512937 |       0.436389 |   0.659881 |
| k-d_tree_sklearn     |     0.503024 |       1.03645  |   1.12652  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.500815 |       0.511306 |   0.48443  |
| k-d_tree_polars      |     0.496918 |       0.563993 |   0.565192 |
| Bori_Aron_solution-1 |     0.488387 |       0.800545 |   0.572079 |
| barab-szabi-1        |     0.505042 |       0.571754 |   0.58848  |
| k-d_tree_pandas      |     0.49796  |       0.504011 |   0.73958  |
| k-d_tree_sklearn     |     0.500746 |       1.27417  |   1.15915  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.507792 |       0.738244 |   0.511103 |
| Bori_Aron_solution-1 |     0.485147 |       1.49073  |   0.610368 |
| k-d_tree_polars      |     0.495926 |       0.933697 |   0.920578 |
| barab-szabi-1        |     0.496364 |       0.936591 |   0.977802 |
| k-d_tree_pandas      |     0.499764 |       0.811053 |   1.20766  |
| k-d_tree_sklearn     |     0.500701 |       2.17224  |   1.27818  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.494796 |        5.22969 |   0.774105 |
| Bori_Aron_solution-1 |     0.508562 |       11.3941  |   0.827291 |
| k-d_tree_sklearn     |     0.499819 |       17.4322  |   1.32782  |
| barab-szabi-1        |     0.506127 |        5.55492 |   6.67701  |
| k-d_tree_polars      |     0.502106 |        5.39415 |   6.75868  |
| k-d_tree_pandas      |     0.512185 |        4.34896 |   7.16681  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.502321 |        70.9126 |    2.6119  |
| k-d_tree_sklearn     |     0.906032 |       237.28   |    3.83135 |
| Bori_Aron_solution-1 |     0.514313 |       146.307  |   23.9515  |