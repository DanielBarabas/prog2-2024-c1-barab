# 2024-10-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.41396  |       1e-06    |   0.364532 |
| k-d_tree_polars      |     0.655026 |       0.406556 |   0.393075 |
| barab-szabi-2        |     0.629973 |       0.396578 |   0.39746  |
| barab-szabi-1        |     0.616572 |       0.406036 |   0.397572 |
| Bori_Aron_solution-1 |     0.615819 |       0.52225  |   0.52887  |
| k-d_tree_pandas      |     0.623623 |       0.394591 |   0.540998 |
| k-d_tree_sklearn     |     9.99233  |       1.0335   |   1.01158  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.638602 |       0.420892 |   0.391479 |
| barab-szabi-1        |     0.636951 |       0.424336 |   0.401604 |
| barab-szabi-2        |     0.619721 |       0.390127 |   0.420989 |
| Bori_Aron_solution-1 |     0.610221 |       0.528365 |   0.515624 |
| k-d_tree_pandas      |     0.613994 |       0.383089 |   0.529124 |
| k-d_tree_sklearn     |     0.642908 |       0.926193 |   0.989542 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614882 |       0.40396  |   0.397539 |
| k-d_tree_polars      |     0.6147   |       0.425535 |   0.416913 |
| barab-szabi-1        |     0.631271 |       0.428997 |   0.426672 |
| Bori_Aron_solution-1 |     0.604775 |       0.576839 |   0.536113 |
| k-d_tree_pandas      |     0.628782 |       0.414328 |   0.584474 |
| k-d_tree_sklearn     |     0.618717 |       0.962408 |   1.01289  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620223 |       0.47     |   0.428777 |
| k-d_tree_polars      |     0.625184 |       0.539315 |   0.516951 |
| barab-szabi-1        |     0.617488 |       0.537741 |   0.532176 |
| Bori_Aron_solution-1 |     0.60148  |       0.737908 |   0.535798 |
| k-d_tree_pandas      |     0.604974 |       0.475419 |   0.706056 |
| k-d_tree_sklearn     |     0.623239 |       1.14532  |   1.05122  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.602887 |       0.710323 |   0.460368 |
| Bori_Aron_solution-1 |     0.602796 |       1.38434  |   0.554754 |
| k-d_tree_polars      |     0.605346 |       0.847423 |   0.860542 |
| barab-szabi-1        |     0.608415 |       0.855822 |   0.887348 |
| k-d_tree_sklearn     |     0.610725 |       1.95215  |   1.12332  |
| k-d_tree_pandas      |     0.617984 |       0.770985 |   1.19127  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615843 |        5.83123 |   0.759995 |
| Bori_Aron_solution-1 |     0.622534 |       10.8864  |   0.804507 |
| k-d_tree_sklearn     |     0.633832 |       16.7531  |   1.24775  |
| barab-szabi-1        |     0.651673 |        4.8562  |   6.78329  |
| k-d_tree_polars      |     0.618587 |        4.85145 |   6.80539  |
| k-d_tree_pandas      |     0.614861 |        3.89292 |   7.34543  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.643762 |        73.7183 |    2.98791 |
| k-d_tree_sklearn     |     0.638899 |       233.835  |    4.20741 |
| Bori_Aron_solution-1 |     0.615269 |       148.816  |   18.2462  |