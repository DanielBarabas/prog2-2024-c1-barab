# 2024-03-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.71431  |       0.472062 |   0.363352 |
| k-d_tree_polars      |     0.746489 |       0.397391 |   0.3655   |
| barab-szabi-1        |     0.739794 |       0.393993 |   0.366191 |
| Bori_Aron_solution-1 |     0.696585 |       0.503684 |   0.501217 |
| k-d_tree_sklearn     |     3.39767  |       1.04442  |   0.676816 |
| solution-1           |     8.41691  |       1e-06    |   0.687598 |
| k-d_tree_pandas      |     9.17718  |       0.469915 |   0.725335 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.729778 |       0.374726 |   0.365606 |
| k-d_tree_polars      |     0.74292  |       0.40334  |   0.374297 |
| barab-szabi-1        |     0.735534 |       0.404873 |   0.376669 |
| Bori_Aron_solution-1 |     0.730746 |       0.509751 |   0.502507 |
| k-d_tree_pandas      |     0.734915 |       0.39873  |   0.510775 |
| k-d_tree_sklearn     |     0.748673 |       0.929292 |   0.69109  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.748045 |       0.386    |   0.379711 |
| k-d_tree_polars      |     0.738855 |       0.427511 |   0.397711 |
| barab-szabi-1        |     0.74095  |       0.431236 |   0.400056 |
| Bori_Aron_solution-1 |     0.721719 |       0.549709 |   0.506194 |
| k-d_tree_pandas      |     0.744034 |       0.401626 |   0.555171 |
| k-d_tree_sklearn     |     0.747838 |       0.898605 |   0.739579 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.733012 |       0.445615 |   0.416136 |
| barab-szabi-1        |     0.743793 |       0.546835 |   0.505092 |
| k-d_tree_polars      |     0.742219 |       0.538657 |   0.505404 |
| Bori_Aron_solution-1 |     0.719097 |       0.729093 |   0.53626  |
| k-d_tree_pandas      |     0.742271 |       0.482423 |   0.684997 |
| k-d_tree_sklearn     |     0.760236 |       1.13767  |   0.78176  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732858 |       0.699631 |   0.44598  |
| Bori_Aron_solution-1 |     0.730473 |       1.36406  |   0.540788 |
| k-d_tree_polars      |     0.738818 |       0.864838 |   0.84696  |
| k-d_tree_sklearn     |     0.744377 |       1.9163   |   0.877324 |
| barab-szabi-1        |     0.748255 |       0.853096 |   0.878548 |
| k-d_tree_pandas      |     0.732428 |       0.752143 |   1.11961  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.730645 |        5.13524 |   0.746135 |
| Bori_Aron_solution-1 |     0.728336 |       10.4845  |   0.794117 |
| k-d_tree_sklearn     |     0.745707 |       15.6698  |   1.0742   |
| k-d_tree_polars      |     0.749382 |        4.8141  |   6.45708  |
| barab-szabi-1        |     0.745116 |        4.8267  |   6.49875  |
| k-d_tree_pandas      |     0.742588 |        3.91729 |   6.71822  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.741712 |        72.5403 |    3.62464 |
| k-d_tree_sklearn     |     1.03695  |       226.551  |    4.84188 |
| Bori_Aron_solution-1 |     0.897603 |       146.092  |   13.931   |