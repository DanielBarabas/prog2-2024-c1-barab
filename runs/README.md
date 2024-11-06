# 2024-11-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.643963 |       0.397726 |   0.386569 |
| barab-szabi-2        |     0.61826  |       0.387277 |   0.386874 |
| barab-szabi-1        |     0.617903 |       0.397423 |   0.393299 |
| solution-1           |     7.70305  |       1e-06    |   0.443341 |
| Bori_Aron_solution-1 |     0.613689 |       0.520399 |   0.519639 |
| k-d_tree_pandas      |     0.675672 |       0.37921  |   0.525366 |
| k-d_tree_sklearn     |    10.5343   |       1.29991  |   0.969917 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614967 |       0.391123 |   0.390333 |
| barab-szabi-1        |     0.614011 |       0.406457 |   0.391882 |
| k-d_tree_polars      |     0.642017 |       0.406165 |   0.409117 |
| Bori_Aron_solution-1 |     0.609811 |       0.528423 |   0.522195 |
| k-d_tree_pandas      |     0.641962 |       0.383253 |   0.536159 |
| k-d_tree_sklearn     |     0.616576 |       0.897376 |   0.96873  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.6215   |       0.40554  |   0.397628 |
| k-d_tree_polars      |     0.618139 |       0.451249 |   0.421393 |
| barab-szabi-1        |     0.612701 |       0.431172 |   0.42337  |
| Bori_Aron_solution-1 |     0.61184  |       0.586138 |   0.530862 |
| k-d_tree_pandas      |     0.613822 |       0.402491 |   0.57136  |
| k-d_tree_sklearn     |     0.619021 |       0.936723 |   0.984397 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614382 |       0.46429  |   0.428821 |
| k-d_tree_polars      |     0.614016 |       0.53592  |   0.51651  |
| barab-szabi-1        |     0.615145 |       0.539181 |   0.531139 |
| Bori_Aron_solution-1 |     0.619605 |       0.74377  |   0.536862 |
| k-d_tree_pandas      |     0.616018 |       0.484128 |   0.703105 |
| k-d_tree_sklearn     |     0.613815 |       1.16673  |   1.05096  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612175 |       0.718732 |   0.466249 |
| Bori_Aron_solution-1 |     0.608726 |       1.37696  |   0.557722 |
| k-d_tree_polars      |     0.61344  |       0.870768 |   0.869033 |
| barab-szabi-1        |     0.61063  |       0.863253 |   0.904809 |
| k-d_tree_sklearn     |     0.617211 |       1.9684   |   1.11996  |
| k-d_tree_pandas      |     0.625128 |       0.746457 |   1.14346  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617742 |        5.4255  |   0.726008 |
| Bori_Aron_solution-1 |     0.633659 |       10.8009  |   0.809045 |
| k-d_tree_sklearn     |     0.622639 |       16.2678  |   1.24797  |
| k-d_tree_polars      |     0.616163 |        4.89632 |   6.62864  |
| barab-szabi-1        |     0.611821 |        4.87528 |   6.68716  |
| k-d_tree_pandas      |     0.622295 |        3.89568 |   7.02511  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629245 |        72.0083 |    3.03903 |
| k-d_tree_sklearn     |     0.615754 |       224.682  |    4.29596 |
| Bori_Aron_solution-1 |     0.639415 |       154.771  |   16.3483  |