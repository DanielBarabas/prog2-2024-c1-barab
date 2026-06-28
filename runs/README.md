# 2026-06-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.32709  |       1e-06    |   0.435121 |
| barab-szabi-2        |     8.24352  |       0.692744 |   0.438862 |
| barab-szabi-1        |     0.462542 |       0.402878 |   0.441663 |
| k-d_tree_polars      |     0.4675   |       0.399825 |   0.449308 |
| Bori_Aron_solution-1 |     0.457254 |       0.555932 |   0.545882 |
| k-d_tree_pandas      |     0.472128 |       0.384701 |   0.577363 |
| k-d_tree_sklearn     |     2.93498  |       1.10313  |   1.06683  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492726 |       0.443615 |   0.43958  |
| barab-szabi-1        |     0.473298 |       0.407682 |   0.441866 |
| k-d_tree_polars      |     0.47374  |       0.423309 |   0.442069 |
| Bori_Aron_solution-1 |     0.461296 |       0.550156 |   0.542471 |
| k-d_tree_pandas      |     0.467291 |       0.395549 |   0.550955 |
| k-d_tree_sklearn     |     0.479256 |       0.966291 |   1.06055  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467266 |       0.454261 |   0.453016 |
| barab-szabi-1        |     0.472926 |       0.434881 |   0.470178 |
| k-d_tree_polars      |     0.482332 |       0.434215 |   0.472568 |
| Bori_Aron_solution-1 |     0.467963 |       0.587596 |   0.551533 |
| k-d_tree_pandas      |     0.465364 |       0.409137 |   0.648022 |
| k-d_tree_sklearn     |     0.473015 |       1.01906  |   1.09212  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477016 |       0.5084   |   0.481018 |
| k-d_tree_polars      |     0.468264 |       0.561701 |   0.564995 |
| barab-szabi-1        |     0.469646 |       0.564521 |   0.57683  |
| Bori_Aron_solution-1 |     0.460968 |       0.781051 |   0.578371 |
| k-d_tree_pandas      |     0.480341 |       0.498682 |   0.734258 |
| k-d_tree_sklearn     |     0.474808 |       1.26116  |   1.14086  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470487 |       0.730481 |   0.508669 |
| Bori_Aron_solution-1 |     0.467989 |       1.43144  |   0.583651 |
| k-d_tree_polars      |     0.471665 |       0.913808 |   0.916839 |
| barab-szabi-1        |     0.4708   |       0.929078 |   0.960738 |
| k-d_tree_pandas      |     0.471759 |       0.805096 |   1.18095  |
| k-d_tree_sklearn     |     0.474168 |       2.08781  |   1.24047  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472415 |        5.10615 |   0.738165 |
| Bori_Aron_solution-1 |     0.461027 |       10.7727  |   0.807641 |
| k-d_tree_sklearn     |     0.474012 |       16.7922  |   1.31073  |
| barab-szabi-1        |     0.46954  |        5.33416 |   6.69088  |
| k-d_tree_polars      |     0.467116 |        5.3019  |   6.70521  |
| k-d_tree_pandas      |     0.470983 |        4.29918 |   7.02937  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474312 |        71.7347 |    2.73916 |
| k-d_tree_sklearn     |     0.772374 |       236.919  |    4.0541  |
| Bori_Aron_solution-1 |     0.47438  |       150.985  |   24.3653  |