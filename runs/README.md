# 2025-04-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.62312  |       1e-06    |   0.381641 |
| k-d_tree_polars      |     0.552636 |       0.40323  |   0.407267 |
| barab-szabi-2        |     0.546372 |       0.413007 |   0.409058 |
| barab-szabi-1        |     0.561502 |       0.415686 |   0.417472 |
| Bori_Aron_solution-1 |     0.541284 |       0.545092 |   0.542968 |
| k-d_tree_pandas      |     7.89842  |       0.427082 |   0.581859 |
| k-d_tree_sklearn     |     3.00147  |       1.07101  |   1.02024  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563266 |       0.412029 |   0.407696 |
| k-d_tree_polars      |     0.598175 |       0.409477 |   0.414099 |
| barab-szabi-1        |     0.569479 |       0.417256 |   0.435619 |
| Bori_Aron_solution-1 |     0.561792 |       0.558952 |   0.541464 |
| k-d_tree_pandas      |     0.56398  |       0.389066 |   0.555794 |
| k-d_tree_sklearn     |     0.566682 |       0.956251 |   1.03556  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562037 |       0.431998 |   0.435447 |
| k-d_tree_polars      |     0.56631  |       0.433242 |   0.451574 |
| barab-szabi-1        |     0.563684 |       0.438557 |   0.46613  |
| Bori_Aron_solution-1 |     0.55711  |       0.587527 |   0.543948 |
| k-d_tree_pandas      |     0.569915 |       0.407139 |   0.595892 |
| k-d_tree_sklearn     |     0.564246 |       1.00711  |   1.05012  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558972 |       0.488584 |   0.451214 |
| k-d_tree_polars      |     0.56461  |       0.541084 |   0.534519 |
| barab-szabi-1        |     0.571937 |       0.564311 |   0.554233 |
| Bori_Aron_solution-1 |     0.553504 |       0.750059 |   0.554893 |
| k-d_tree_pandas      |     0.573416 |       0.482696 |   0.723074 |
| k-d_tree_sklearn     |     0.591182 |       1.20796  |   1.10761  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575207 |       0.750567 |   0.504075 |
| Bori_Aron_solution-1 |     0.554142 |       1.43314  |   0.59374  |
| k-d_tree_polars      |     0.567838 |       0.89736  |   0.899911 |
| barab-szabi-1        |     0.569916 |       0.875441 |   0.93998  |
| k-d_tree_sklearn     |     0.581905 |       2.0543   |   1.20523  |
| k-d_tree_pandas      |     0.56653  |       0.765058 |   1.20526  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558954 |        5.4924  |   0.729157 |
| Bori_Aron_solution-1 |     0.561163 |       10.7406  |   0.868321 |
| k-d_tree_sklearn     |     0.586433 |       16.3743  |   1.33168  |
| k-d_tree_polars      |     0.566268 |        5.00698 |   6.57918  |
| barab-szabi-1        |     0.568058 |        5.05455 |   6.58592  |
| k-d_tree_pandas      |     0.55951  |        3.96315 |   6.98974  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.788652 |        71.0582 |    2.83147 |
| k-d_tree_sklearn     |     0.64996  |       230.855  |    4.2543  |
| Bori_Aron_solution-1 |     0.586506 |       157.346  |   13.3412  |