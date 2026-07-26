# 2026-07-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.40146  |       1e-06    |   0.35403  |
| barab-szabi-2        |     0.462287 |       0.443779 |   0.437367 |
| barab-szabi-1        |     0.463403 |       0.404578 |   0.441783 |
| k-d_tree_pandas      |     0.465167 |       0.376995 |   0.539281 |
| Bori_Aron_solution-1 |     0.450179 |       0.536638 |   0.541164 |
| k-d_tree_polars      |     8.11038  |       0.516076 |   0.789146 |
| k-d_tree_sklearn     |     2.93406  |       1.17652  |   1.05619  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456296 |       0.434428 |   0.435666 |
| barab-szabi-1        |     0.46036  |       0.409949 |   0.453631 |
| k-d_tree_polars      |     0.461663 |       0.567398 |   0.484435 |
| Bori_Aron_solution-1 |     0.470433 |       0.546046 |   0.530504 |
| k-d_tree_pandas      |     0.465333 |       0.379856 |   0.549748 |
| k-d_tree_sklearn     |     0.470133 |       0.980319 |   1.05626  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.46254  |       0.444243 |   0.449996 |
| k-d_tree_polars      |     0.460041 |       0.449704 |   0.470059 |
| barab-szabi-1        |     0.461136 |       0.429701 |   0.475186 |
| Bori_Aron_solution-1 |     0.457558 |       0.585863 |   0.538087 |
| k-d_tree_pandas      |     0.459855 |       0.4008   |   0.587136 |
| k-d_tree_sklearn     |     0.46265  |       1.02524  |   1.06927  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.461253 |       0.504462 |   0.473997 |
| Bori_Aron_solution-1 |     0.461299 |       0.763427 |   0.554934 |
| barab-szabi-1        |     0.464112 |       0.557184 |   0.569042 |
| k-d_tree_polars      |     0.460649 |       0.549767 |   0.592    |
| k-d_tree_pandas      |     0.465047 |       0.491831 |   0.726321 |
| k-d_tree_sklearn     |     0.464118 |       1.29542  |   1.12397  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.458853 |       0.726587 |   0.5058   |
| Bori_Aron_solution-1 |     0.46231  |       1.41895  |   0.573506 |
| k-d_tree_polars      |     0.465705 |       0.909204 |   0.911017 |
| barab-szabi-1        |     0.465596 |       0.917158 |   0.949659 |
| k-d_tree_pandas      |     0.463615 |       0.791609 |   1.15962  |
| k-d_tree_sklearn     |     0.462897 |       2.07032  |   1.20254  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.461543 |        4.83149 |   0.741049 |
| Bori_Aron_solution-1 |     0.457306 |       10.4638  |   0.802276 |
| k-d_tree_sklearn     |     0.467805 |       16.0633  |   1.27447  |
| barab-szabi-1        |     0.462512 |        5.28977 |   6.40222  |
| k-d_tree_polars      |     0.465469 |        5.26821 |   6.4105   |
| k-d_tree_pandas      |     0.462846 |        4.3558  |   6.76615  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.592864 |        69.3808 |    2.83952 |
| k-d_tree_sklearn     |     0.856244 |       231.683  |    4.02257 |
| Bori_Aron_solution-1 |     0.457581 |       147.333  |   26.5531  |