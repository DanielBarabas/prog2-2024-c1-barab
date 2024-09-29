# 2024-09-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.79644  |       1e-06    |   0.346485 |
| barab-szabi-2        |     0.614038 |       0.385746 |   0.382676 |
| barab-szabi-1        |     0.598821 |       0.400028 |   0.387919 |
| k-d_tree_polars      |     0.597342 |       0.397792 |   0.40798  |
| Bori_Aron_solution-1 |     4.44358  |       0.480039 |   0.444309 |
| k-d_tree_pandas      |     4.37995  |       0.39945  |   0.524606 |
| k-d_tree_sklearn     |     3.07075  |       0.937259 |   0.95659  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617421 |       0.387272 |   0.382306 |
| k-d_tree_polars      |     0.610789 |       0.407311 |   0.390898 |
| barab-szabi-1        |     0.611789 |       0.401576 |   0.40535  |
| Bori_Aron_solution-1 |     0.624909 |       0.533724 |   0.528342 |
| k-d_tree_pandas      |     0.616902 |       0.384807 |   0.537562 |
| k-d_tree_sklearn     |     0.618572 |       0.877706 |   0.956175 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615166 |       0.39712  |   0.400681 |
| k-d_tree_polars      |     0.623214 |       0.430947 |   0.41793  |
| barab-szabi-1        |     0.621175 |       0.433089 |   0.424632 |
| Bori_Aron_solution-1 |     0.607191 |       0.569243 |   0.524599 |
| k-d_tree_pandas      |     0.610266 |       0.400167 |   0.574557 |
| k-d_tree_sklearn     |     0.617836 |       0.926846 |   1.00943  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.633301 |       0.470787 |   0.435775 |
| k-d_tree_polars      |     0.624283 |       0.540088 |   0.521498 |
| Bori_Aron_solution-1 |     0.626456 |       0.750851 |   0.548568 |
| barab-szabi-1        |     0.632173 |       0.557765 |   0.55607  |
| k-d_tree_pandas      |     0.627393 |       0.479918 |   0.749481 |
| k-d_tree_sklearn     |     0.651341 |       1.18871  |   1.09848  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.636379 |       0.754819 |   0.477445 |
| Bori_Aron_solution-1 |     0.623035 |       1.39906  |   0.576584 |
| k-d_tree_polars      |     0.636538 |       0.869352 |   0.89091  |
| barab-szabi-1        |     0.622083 |       0.862442 |   0.936571 |
| k-d_tree_sklearn     |     0.633056 |       2.07042  |   1.1883   |
| k-d_tree_pandas      |     0.626607 |       0.765503 |   1.20482  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618129 |        5.39592 |   0.752833 |
| Bori_Aron_solution-1 |     0.617422 |       10.7878  |   0.831155 |
| k-d_tree_sklearn     |     0.620574 |       16.3625  |   1.26507  |
| barab-szabi-1        |     0.622949 |        4.84333 |   6.73025  |
| k-d_tree_polars      |     0.608646 |        4.82892 |   6.74873  |
| k-d_tree_pandas      |     0.618138 |        3.84448 |   7.02854  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.711873 |        72.2387 |    3.34986 |
| k-d_tree_sklearn     |     0.886287 |       231.191  |    4.32594 |
| Bori_Aron_solution-1 |     0.609319 |       148.302  |   15.1541  |