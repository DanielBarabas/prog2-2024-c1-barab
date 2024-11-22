# 2024-11-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.619169 |       0.400941 |   0.392922 |
| k-d_tree_polars      |     0.621377 |       0.402511 |   0.396158 |
| barab-szabi-2        |     0.640163 |       0.402234 |   0.396396 |
| Bori_Aron_solution-1 |     0.617016 |       0.52896  |   0.527827 |
| k-d_tree_pandas      |     0.61813  |       0.38084  |   0.531263 |
| solution-1           |     7.73063  |       1e-06    |   0.532504 |
| k-d_tree_sklearn     |    11.3414   |       1.18989  |   0.982679 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.622997 |       0.407848 |   0.394384 |
| barab-szabi-2        |     0.624586 |       0.392118 |   0.40371  |
| barab-szabi-1        |     0.618845 |       0.414863 |   0.411469 |
| Bori_Aron_solution-1 |     0.60998  |       0.535535 |   0.524514 |
| k-d_tree_pandas      |     0.618519 |       0.383978 |   0.533698 |
| k-d_tree_sklearn     |     0.618411 |       0.892127 |   0.999792 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629549 |       0.407342 |   0.403285 |
| k-d_tree_polars      |     0.624399 |       0.433458 |   0.422388 |
| barab-szabi-1        |     0.64537  |       0.437769 |   0.425453 |
| Bori_Aron_solution-1 |     0.618138 |       0.565455 |   0.527818 |
| k-d_tree_pandas      |     0.626074 |       0.405031 |   0.592789 |
| k-d_tree_sklearn     |     0.630866 |       0.977485 |   1.00072  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621612 |       0.46584  |   0.428811 |
| k-d_tree_polars      |     0.61817  |       0.549783 |   0.517576 |
| barab-szabi-1        |     0.617934 |       0.547077 |   0.529108 |
| Bori_Aron_solution-1 |     0.60688  |       0.761719 |   0.534199 |
| k-d_tree_pandas      |     0.616571 |       0.483926 |   0.713168 |
| k-d_tree_sklearn     |     0.628722 |       1.16275  |   1.04821  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625764 |       0.720104 |   0.474165 |
| Bori_Aron_solution-1 |     0.61242  |       1.40588  |   0.568438 |
| k-d_tree_polars      |     0.61692  |       0.859868 |   0.870916 |
| barab-szabi-1        |     0.629129 |       0.865376 |   0.907241 |
| k-d_tree_sklearn     |     0.628719 |       1.9962   |   1.13687  |
| k-d_tree_pandas      |     0.619115 |       0.745598 |   1.15866  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615531 |        5.357   |   0.737263 |
| Bori_Aron_solution-1 |     0.617753 |       10.7394  |   0.82805  |
| k-d_tree_sklearn     |     0.630657 |       16.5617  |   1.24192  |
| k-d_tree_polars      |     0.630679 |        4.89698 |   6.57484  |
| barab-szabi-1        |     0.639319 |        4.95392 |   6.72279  |
| k-d_tree_pandas      |     0.632787 |        3.88663 |   7.00342  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.64461  |        71.6002 |    2.87538 |
| k-d_tree_sklearn     |     0.62536  |       227.048  |    4.23564 |
| Bori_Aron_solution-1 |     0.643414 |       149.086  |   18.7038  |