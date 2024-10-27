# 2024-10-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.65914  |       1e-06    |   0.375749 |
| barab-szabi-2        |     0.636714 |       0.406831 |   0.40536  |
| k-d_tree_polars      |     0.648784 |       0.418693 |   0.406483 |
| barab-szabi-1        |     0.650787 |       0.419925 |   0.409976 |
| Bori_Aron_solution-1 |     0.640415 |       0.549391 |   0.549908 |
| k-d_tree_pandas      |     0.643531 |       0.403636 |   0.564763 |
| k-d_tree_sklearn     |    10.5224   |       1.03109  |   1.02053  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.654881 |       0.409874 |   0.410151 |
| barab-szabi-1        |     0.649796 |       0.446828 |   0.419683 |
| k-d_tree_polars      |     0.667825 |       0.446522 |   0.428232 |
| Bori_Aron_solution-1 |     0.640804 |       0.594947 |   0.553601 |
| k-d_tree_pandas      |     0.671315 |       0.424552 |   0.561109 |
| k-d_tree_sklearn     |     0.664449 |       0.973166 |   1.02488  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.645651 |       0.41173  |   0.408286 |
| k-d_tree_polars      |     0.631296 |       0.446757 |   0.43272  |
| barab-szabi-1        |     0.633785 |       0.440447 |   0.457968 |
| Bori_Aron_solution-1 |     0.633457 |       0.589903 |   0.551437 |
| k-d_tree_pandas      |     0.634061 |       0.414913 |   0.588495 |
| k-d_tree_sklearn     |     0.652216 |       0.972626 |   1.04324  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.636057 |       0.491727 |   0.452811 |
| k-d_tree_polars      |     0.642901 |       0.549977 |   0.531867 |
| barab-szabi-1        |     0.675079 |       0.550765 |   0.532683 |
| Bori_Aron_solution-1 |     0.619075 |       0.759553 |   0.549018 |
| k-d_tree_pandas      |     0.629253 |       0.489178 |   0.721552 |
| k-d_tree_sklearn     |     0.631384 |       1.21334  |   1.10664  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629349 |       0.72366  |   0.509769 |
| Bori_Aron_solution-1 |     0.628459 |       1.41843  |   0.581901 |
| k-d_tree_polars      |     0.622573 |       0.878367 |   0.882146 |
| barab-szabi-1        |     0.630252 |       0.863192 |   0.926577 |
| k-d_tree_pandas      |     0.637796 |       0.75565  |   1.18199  |
| k-d_tree_sklearn     |     0.632138 |       2.03293  |   1.19588  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.630969 |        5.58322 |   0.753989 |
| Bori_Aron_solution-1 |     0.637526 |       11.0726  |   0.828778 |
| k-d_tree_sklearn     |     0.650613 |       16.9742  |   1.29053  |
| k-d_tree_polars      |     0.632149 |        4.90806 |   6.9374   |
| barab-szabi-1        |     0.641987 |        4.8736  |   6.97525  |
| k-d_tree_pandas      |     0.637032 |        3.97799 |   7.20746  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.649217 |         75.792 |    2.96154 |
| k-d_tree_sklearn     |     0.64703  |        238.629 |    4.26187 |
| Bori_Aron_solution-1 |     0.641912 |        155.555 |   15.8326  |