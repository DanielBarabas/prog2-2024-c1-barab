# 2025-06-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57148  |       0.45058  |   0.430636 |
| k-d_tree_polars      |     0.555086 |       0.41603  |   0.431789 |
| barab-szabi-1        |     0.5614   |       0.421338 |   0.456058 |
| solution-1           |     8.01522  |       1e-06    |   0.500921 |
| Bori_Aron_solution-1 |     0.544376 |       0.578685 |   0.559858 |
| k-d_tree_pandas      |     8.41796  |       0.420182 |   0.717665 |
| k-d_tree_sklearn     |     3.16814  |       1.14738  |   1.09344  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.572716 |       0.433637 |   0.431614 |
| barab-szabi-1        |     0.568649 |       0.423123 |   0.43619  |
| k-d_tree_polars      |     0.574556 |       0.422835 |   0.437099 |
| Bori_Aron_solution-1 |     0.572603 |       0.572094 |   0.567521 |
| k-d_tree_pandas      |     0.566452 |       0.407636 |   0.582056 |
| k-d_tree_sklearn     |     0.575703 |       1.0259   |   1.13215  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575206 |       0.45261  |   0.449433 |
| barab-szabi-1        |     0.577989 |       0.450046 |   0.464629 |
| k-d_tree_polars      |     0.564566 |       0.447824 |   0.467472 |
| Bori_Aron_solution-1 |     0.564045 |       0.60987  |   0.573771 |
| k-d_tree_pandas      |     0.57737  |       0.425946 |   0.620864 |
| k-d_tree_sklearn     |     0.570464 |       1.07274  |   1.12016  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579888 |       0.505733 |   0.473747 |
| k-d_tree_polars      |     0.575282 |       0.561417 |   0.556669 |
| barab-szabi-1        |     0.569006 |       0.559598 |   0.568531 |
| Bori_Aron_solution-1 |     0.575058 |       0.814729 |   0.59115  |
| k-d_tree_pandas      |     0.56625  |       0.499061 |   0.770484 |
| k-d_tree_sklearn     |     0.570687 |       1.29093  |   1.16726  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566968 |       0.768628 |   0.517454 |
| Bori_Aron_solution-1 |     0.56953  |       1.43657  |   0.606688 |
| k-d_tree_polars      |     0.566288 |       0.889502 |   0.938248 |
| barab-szabi-1        |     0.57565  |       0.905747 |   0.978819 |
| k-d_tree_pandas      |     0.563423 |       0.775783 |   1.21512  |
| k-d_tree_sklearn     |     0.580667 |       2.16869  |   1.25098  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57427  |        5.13927 |   0.722562 |
| Bori_Aron_solution-1 |     0.585006 |       10.8396  |   0.858874 |
| k-d_tree_sklearn     |     0.555862 |       16.8128  |   1.34157  |
| barab-szabi-1        |     0.569801 |        4.96249 |   6.53754  |
| k-d_tree_polars      |     0.558413 |        5.00379 |   6.76532  |
| k-d_tree_pandas      |     0.57243  |        3.97211 |   7.21781  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.927243 |        74.4623 |    2.88213 |
| k-d_tree_sklearn     |     0.685877 |       231.101  |    4.07797 |
| Bori_Aron_solution-1 |     0.562255 |       146.659  |   17.6794  |