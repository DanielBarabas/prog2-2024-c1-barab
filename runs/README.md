# 2026-01-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467502 |       0.500459 |   0.404825 |
| barab-szabi-1        |     0.483558 |       0.381198 |   0.410378 |
| k-d_tree_polars      |     0.481145 |       0.377077 |   0.415738 |
| solution-1           |     8.11405  |       1e-06    |   0.438872 |
| Bori_Aron_solution-1 |     0.501637 |       0.508926 |   0.520715 |
| k-d_tree_pandas      |     9.25691  |       0.404044 |   0.673023 |
| k-d_tree_sklearn     |     2.96203  |       1.04492  |   1.01832  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484351 |       0.410598 |   0.415624 |
| k-d_tree_polars      |     0.495836 |       0.385982 |   0.422486 |
| barab-szabi-1        |     0.483469 |       0.381917 |   0.422837 |
| Bori_Aron_solution-1 |     0.480977 |       0.521909 |   0.517454 |
| k-d_tree_pandas      |     0.477639 |       0.360454 |   0.520655 |
| k-d_tree_sklearn     |     0.498849 |       0.906128 |   0.991535 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.494292 |       0.439519 |   0.415983 |
| k-d_tree_polars      |     0.494276 |       0.410702 |   0.448405 |
| barab-szabi-1        |     0.498404 |       0.416748 |   0.454414 |
| Bori_Aron_solution-1 |     0.4935   |       0.559639 |   0.50893  |
| k-d_tree_pandas      |     0.482819 |       0.3869   |   0.557438 |
| k-d_tree_sklearn     |     0.488963 |       0.96881  |   1.04014  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488394 |       0.479636 |   0.45439  |
| k-d_tree_polars      |     0.480149 |       0.52156  |   0.514279 |
| Bori_Aron_solution-1 |     0.469524 |       0.703431 |   0.517421 |
| barab-szabi-1        |     0.487926 |       0.539088 |   0.535057 |
| k-d_tree_pandas      |     0.475257 |       0.453744 |   0.676987 |
| k-d_tree_sklearn     |     0.48345  |       1.15955  |   1.05327  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477735 |       0.712661 |   0.488828 |
| Bori_Aron_solution-1 |     0.482244 |       1.32146  |   0.564961 |
| k-d_tree_polars      |     0.481222 |       0.854034 |   0.840139 |
| barab-szabi-1        |     0.486829 |       0.841139 |   0.882858 |
| k-d_tree_pandas      |     0.482754 |       0.714528 |   1.0586   |
| k-d_tree_sklearn     |     0.487322 |       1.98725  |   1.12224  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49134  |        5.19995 |   0.728282 |
| Bori_Aron_solution-1 |     0.482196 |       10.2775  |   0.91217  |
| k-d_tree_sklearn     |     0.495641 |       14.5685  |   1.27831  |
| barab-szabi-1        |     0.491319 |        4.87635 |   6.13229  |
| k-d_tree_polars      |     0.4882   |        4.91208 |   6.25468  |
| k-d_tree_pandas      |     0.484456 |        3.82449 |   6.58777  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491217 |        87.5401 |    2.6574  |
| k-d_tree_sklearn     |     0.498908 |       176.417  |    4.13854 |
| Bori_Aron_solution-1 |     0.576429 |       131.952  |   18.2503  |