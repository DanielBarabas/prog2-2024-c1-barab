# 2025-01-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.77435  |       1e-06    |   0.354725 |
| barab-szabi-1        |     0.618635 |       0.39839  |   0.397682 |
| barab-szabi-2        |     0.613469 |       0.401495 |   0.403394 |
| k-d_tree_polars      |     0.608254 |       0.41305  |   0.403673 |
| Bori_Aron_solution-1 |     0.611922 |       0.530756 |   0.531193 |
| k-d_tree_pandas      |     0.614524 |       0.390619 |   0.53836  |
| k-d_tree_sklearn     |    10.7751   |       1.03971  |   1.00546  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.616898 |       0.408615 |   0.404229 |
| barab-szabi-2        |     0.631361 |       0.405025 |   0.406523 |
| k-d_tree_polars      |     0.616669 |       0.404275 |   0.409064 |
| k-d_tree_pandas      |     0.614718 |       0.430781 |   0.541957 |
| Bori_Aron_solution-1 |     0.609507 |       0.549706 |   0.583967 |
| k-d_tree_sklearn     |     0.619745 |       0.940463 |   1.03096  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615418 |       0.41407  |   0.41138  |
| barab-szabi-1        |     0.61437  |       0.432625 |   0.42967  |
| k-d_tree_polars      |     0.61811  |       0.435499 |   0.44266  |
| Bori_Aron_solution-1 |     0.609911 |       0.572583 |   0.552175 |
| k-d_tree_pandas      |     0.612076 |       0.408265 |   0.582577 |
| k-d_tree_sklearn     |     0.624045 |       0.990288 |   1.04798  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619982 |       0.478483 |   0.437999 |
| k-d_tree_polars      |     0.615775 |       0.539254 |   0.529225 |
| barab-szabi-1        |     0.61261  |       0.538789 |   0.53745  |
| Bori_Aron_solution-1 |     0.608169 |       0.752893 |   0.547477 |
| k-d_tree_pandas      |     0.611423 |       0.482899 |   0.717825 |
| k-d_tree_sklearn     |     0.613697 |       1.21568  |   1.09928  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615293 |       0.741008 |   0.490839 |
| Bori_Aron_solution-1 |     0.610387 |       1.40484  |   0.577117 |
| k-d_tree_polars      |     0.619812 |       0.87896  |   0.88292  |
| barab-szabi-1        |     0.627457 |       0.87606  |   0.946981 |
| k-d_tree_pandas      |     0.610688 |       0.758047 |   1.16203  |
| k-d_tree_sklearn     |     0.617801 |       2.13078  |   1.20992  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606817 |        5.36641 |   0.731192 |
| Bori_Aron_solution-1 |     0.604657 |       10.682   |   0.814374 |
| k-d_tree_sklearn     |     0.616804 |       16.4204  |   1.30059  |
| barab-szabi-1        |     0.611828 |        4.885   |   6.47198  |
| k-d_tree_polars      |     0.615825 |        4.84953 |   6.63412  |
| k-d_tree_pandas      |     0.607969 |        3.86127 |   6.93282  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.657724 |        71.1768 |    2.85322 |
| k-d_tree_sklearn     |     0.61407  |       227.408  |    4.31724 |
| Bori_Aron_solution-1 |     0.632537 |       145.678  |   18.1586  |