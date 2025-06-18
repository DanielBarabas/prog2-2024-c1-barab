# 2025-06-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.51662  |       1e-06    |   0.377774 |
| k-d_tree_polars      |     0.549946 |       0.407688 |   0.428975 |
| barab-szabi-1        |     0.546379 |       0.407826 |   0.430874 |
| barab-szabi-2        |     0.549518 |       0.42306  |   0.434841 |
| Bori_Aron_solution-1 |     0.538762 |       0.557134 |   0.574398 |
| k-d_tree_pandas      |     7.87158  |       0.432683 |   0.629037 |
| k-d_tree_sklearn     |     3.0873   |       1.06397  |   1.09371  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621164 |       0.430839 |   0.434251 |
| barab-szabi-1        |     0.561172 |       0.412148 |   0.43762  |
| k-d_tree_polars      |     0.56456  |       0.433407 |   0.457118 |
| Bori_Aron_solution-1 |     0.558684 |       0.563608 |   0.554331 |
| k-d_tree_pandas      |     0.581909 |       0.398662 |   0.621353 |
| k-d_tree_sklearn     |     0.566885 |       0.991744 |   1.1134   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566118 |       0.439777 |   0.434698 |
| k-d_tree_polars      |     0.584764 |       0.477082 |   0.461611 |
| barab-szabi-1        |     0.581483 |       0.468384 |   0.496089 |
| Bori_Aron_solution-1 |     0.552518 |       0.610631 |   0.577455 |
| k-d_tree_pandas      |     0.56594  |       0.418538 |   0.61476  |
| k-d_tree_sklearn     |     0.579409 |       1.06651  |   1.14231  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559383 |       0.499741 |   0.47631  |
| k-d_tree_polars      |     0.561182 |       0.550708 |   0.556408 |
| barab-szabi-1        |     0.564981 |       0.562979 |   0.573659 |
| Bori_Aron_solution-1 |     0.553502 |       0.78849  |   0.589336 |
| k-d_tree_pandas      |     0.559103 |       0.497478 |   0.738086 |
| k-d_tree_sklearn     |     0.569962 |       1.27074  |   1.18295  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558611 |       0.761486 |   0.507394 |
| Bori_Aron_solution-1 |     0.556518 |       1.42414  |   0.59901  |
| k-d_tree_polars      |     0.554461 |       0.912121 |   0.94966  |
| barab-szabi-1        |     0.557766 |       0.897527 |   0.983197 |
| k-d_tree_pandas      |     0.55845  |       0.766732 |   1.19739  |
| k-d_tree_sklearn     |     0.559944 |       2.15565  |   1.23771  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570897 |        5.42471 |   0.749758 |
| Bori_Aron_solution-1 |     0.561112 |       10.7945  |   0.851824 |
| k-d_tree_sklearn     |     0.570494 |       16.6303  |   1.32773  |
| barab-szabi-1        |     0.557102 |        5.00403 |   6.68233  |
| k-d_tree_polars      |     0.559932 |        4.99646 |   6.8472   |
| k-d_tree_pandas      |     0.563472 |        3.90856 |   7.21485  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.701891 |        76.5092 |    2.89683 |
| k-d_tree_sklearn     |     0.677297 |       236.234  |    4.02345 |
| Bori_Aron_solution-1 |     0.551975 |       143.995  |   18.3168  |