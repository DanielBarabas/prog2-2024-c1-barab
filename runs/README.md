# 2025-02-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.39742  |       1e-06    |   0.354865 |
| barab-szabi-2        |     3.96718  |       0.404173 |   0.399745 |
| k-d_tree_polars      |     0.590741 |       0.40044  |   0.406094 |
| barab-szabi-1        |     0.604348 |       0.401877 |   0.436126 |
| Bori_Aron_solution-1 |     4.47867  |       0.610653 |   0.48353  |
| k-d_tree_pandas      |     0.5907   |       0.381475 |   0.54381  |
| k-d_tree_sklearn     |     3.07943  |       1.07951  |   1.04844  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.58817  |       0.412413 |   0.4074   |
| barab-szabi-2        |     0.608794 |       0.414116 |   0.415779 |
| barab-szabi-1        |     0.59113  |       0.409945 |   0.417913 |
| k-d_tree_pandas      |     0.586809 |       0.386744 |   0.549913 |
| Bori_Aron_solution-1 |     0.593721 |       0.553284 |   0.551402 |
| k-d_tree_sklearn     |     0.589628 |       0.971001 |   1.07241  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585922 |       0.42505  |   0.431315 |
| barab-szabi-1        |     0.591836 |       0.430056 |   0.440359 |
| k-d_tree_polars      |     0.589502 |       0.429701 |   0.442519 |
| Bori_Aron_solution-1 |     0.597812 |       0.58725  |   0.548775 |
| k-d_tree_pandas      |     0.590451 |       0.407904 |   0.596553 |
| k-d_tree_sklearn     |     0.603121 |       1.01999  |   1.04654  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58597  |       0.48734  |   0.448538 |
| k-d_tree_polars      |     0.594355 |       0.540143 |   0.53582  |
| barab-szabi-1        |     0.584574 |       0.540706 |   0.544914 |
| Bori_Aron_solution-1 |     0.580583 |       0.75584  |   0.556434 |
| k-d_tree_pandas      |     0.589993 |       0.486762 |   0.726322 |
| k-d_tree_sklearn     |     0.590763 |       1.21562  |   1.1292   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598567 |       0.730967 |   0.48321  |
| Bori_Aron_solution-1 |     0.590843 |       1.38891  |   0.59228  |
| k-d_tree_polars      |     0.585789 |       0.869732 |   0.877423 |
| barab-szabi-1        |     0.590068 |       0.855153 |   0.917017 |
| k-d_tree_pandas      |     0.601673 |       0.744174 |   1.16413  |
| k-d_tree_sklearn     |     0.597308 |       2.07432  |   1.21207  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591852 |        5.42567 |   0.74818  |
| Bori_Aron_solution-1 |     0.578889 |       10.6685  |   0.885262 |
| k-d_tree_sklearn     |     0.610627 |       16.3218  |   1.33513  |
| barab-szabi-1        |     0.592988 |        4.89574 |   6.67726  |
| k-d_tree_polars      |     0.611788 |        4.93349 |   6.71427  |
| k-d_tree_pandas      |     0.586499 |        3.84918 |   7.07091  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.721286 |        72.0319 |    3.71422 |
| k-d_tree_sklearn     |     0.650421 |       227.908  |    4.19511 |
| Bori_Aron_solution-1 |     0.579893 |       147.071  |   15.9083  |