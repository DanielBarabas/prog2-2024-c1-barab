# 2026-08-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.72017  |       1e-06    |   0.43428  |
| barab-szabi-2        |     0.477053 |       0.444108 |   0.446452 |
| barab-szabi-1        |     0.482861 |       0.427005 |   0.454984 |
| Bori_Aron_solution-1 |     0.46775  |       0.56299  |   0.561967 |
| k-d_tree_pandas      |     0.478169 |       0.391442 |   0.567422 |
| k-d_tree_polars      |     8.62581  |       0.475137 |   0.609924 |
| k-d_tree_sklearn     |     3.01118  |       1.14985  |   1.09625  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478689 |       0.446071 |   0.463143 |
| k-d_tree_polars      |     0.480706 |       0.43495  |   0.463842 |
| barab-szabi-1        |     0.486276 |       0.43593  |   0.466565 |
| Bori_Aron_solution-1 |     0.471478 |       0.561496 |   0.565391 |
| k-d_tree_pandas      |     0.481399 |       0.396945 |   0.571063 |
| k-d_tree_sklearn     |     0.488938 |       1.03791  |   1.09757  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478312 |       0.463544 |   0.473271 |
| barab-szabi-1        |     0.491834 |       0.457505 |   0.489654 |
| k-d_tree_polars      |     0.477692 |       0.446753 |   0.489828 |
| Bori_Aron_solution-1 |     0.477782 |       0.605394 |   0.560031 |
| k-d_tree_pandas      |     0.47861  |       0.413228 |   0.610985 |
| k-d_tree_sklearn     |     0.484097 |       1.06818  |   1.13709  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479611 |       0.525002 |   0.48523  |
| k-d_tree_polars      |     0.482934 |       0.584391 |   0.57895  |
| Bori_Aron_solution-1 |     0.478246 |       0.783635 |   0.591779 |
| barab-szabi-1        |     0.483236 |       0.587395 |   0.597406 |
| k-d_tree_pandas      |     0.478061 |       0.507407 |   0.741241 |
| k-d_tree_sklearn     |     0.483119 |       1.28758  |   1.16964  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481419 |       0.746399 |   0.53262  |
| Bori_Aron_solution-1 |     0.470203 |       1.44857  |   0.606964 |
| k-d_tree_polars      |     0.482064 |       0.931965 |   0.929328 |
| barab-szabi-1        |     0.476525 |       0.939071 |   0.969726 |
| k-d_tree_pandas      |     0.480256 |       0.81844  |   1.20572  |
| k-d_tree_sklearn     |     0.494798 |       2.17589  |   1.25754  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49306  |        5.26793 |   0.77131  |
| Bori_Aron_solution-1 |     0.482291 |       11.1703  |   0.824488 |
| k-d_tree_sklearn     |     0.475832 |       17.4353  |   1.35244  |
| k-d_tree_polars      |     0.479889 |        5.28029 |   6.82234  |
| barab-szabi-1        |     0.483079 |        5.40164 |   6.82988  |
| k-d_tree_pandas      |     0.482808 |        4.39316 |   7.19423  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587374 |        74.8819 |    3.09157 |
| k-d_tree_sklearn     |     0.683753 |       244.388  |    4.2007  |
| Bori_Aron_solution-1 |     0.478864 |       155.202  |   26.3986  |