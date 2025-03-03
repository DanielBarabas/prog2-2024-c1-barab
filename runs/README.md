# 2025-03-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.576395 |       0.407246 |   0.411484 |
| barab-szabi-2        |     0.574073 |       0.427649 |   0.42708  |
| barab-szabi-1        |     0.583643 |       0.442482 |   0.479648 |
| solution-1           |     7.48621  |       1e-06    |   0.510316 |
| Bori_Aron_solution-1 |     0.576379 |       0.558099 |   0.543375 |
| k-d_tree_pandas      |     7.87479  |       0.487445 |   0.720404 |
| k-d_tree_sklearn     |     3.0603   |       1.19091  |   1.04228  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589689 |       0.412445 |   0.402262 |
| barab-szabi-1        |     0.603682 |       0.401842 |   0.411862 |
| k-d_tree_polars      |     0.58557  |       0.403468 |   0.415023 |
| Bori_Aron_solution-1 |     0.577523 |       0.544211 |   0.54536  |
| k-d_tree_pandas      |     0.581795 |       0.383883 |   0.550891 |
| k-d_tree_sklearn     |     0.594819 |       0.97412  |   1.03785  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581733 |       0.421379 |   0.419992 |
| barab-szabi-1        |     0.585932 |       0.431418 |   0.435514 |
| k-d_tree_polars      |     0.583251 |       0.431836 |   0.435977 |
| Bori_Aron_solution-1 |     0.576072 |       0.577312 |   0.551716 |
| k-d_tree_pandas      |     0.586489 |       0.401528 |   0.592187 |
| k-d_tree_sklearn     |     0.610283 |       1.00342  |   1.04797  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584871 |       0.483221 |   0.466859 |
| k-d_tree_polars      |     0.592947 |       0.534641 |   0.525525 |
| barab-szabi-1        |     0.583591 |       0.538491 |   0.542623 |
| Bori_Aron_solution-1 |     0.584416 |       0.755601 |   0.558132 |
| k-d_tree_pandas      |     0.587394 |       0.489331 |   0.73502  |
| k-d_tree_sklearn     |     0.587716 |       1.20903  |   1.09987  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58058  |       0.725986 |   0.47652  |
| Bori_Aron_solution-1 |     0.584978 |       1.40497  |   0.59232  |
| k-d_tree_polars      |     0.580987 |       0.866064 |   0.876539 |
| barab-szabi-1        |     0.591716 |       0.866577 |   0.917504 |
| k-d_tree_pandas      |     0.586859 |       0.747816 |   1.18292  |
| k-d_tree_sklearn     |     0.587671 |       2.05457  |   1.19697  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.582563 |        5.35605 |   0.747276 |
| Bori_Aron_solution-1 |     0.624753 |       10.822   |   0.898415 |
| k-d_tree_sklearn     |     0.589308 |       15.6352  |   1.35493  |
| k-d_tree_polars      |     0.625561 |        4.93625 |   6.51433  |
| barab-szabi-1        |     0.649856 |        4.97074 |   6.95653  |
| k-d_tree_pandas      |     0.585397 |        3.83155 |   7.00255  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.900626 |        74.4547 |    3.36837 |
| k-d_tree_sklearn     |     0.759709 |       229.869  |    4.16758 |
| Bori_Aron_solution-1 |     0.579024 |       156.245  |   15.1625  |