# 2026-10-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.40671  |       1e-06    |   0.433891 |
| barab-szabi-2        |     0.482929 |       0.474375 |   0.453379 |
| k-d_tree_polars      |     0.486655 |       0.460198 |   0.459985 |
| barab-szabi-1        |     9.27618  |       0.514269 |   0.546857 |
| Bori_Aron_solution-1 |     0.49273  |       0.589111 |   0.588719 |
| k-d_tree_pandas      |     0.513783 |       0.422079 |   0.599217 |
| k-d_tree_sklearn     |     3.38787  |       1.23354  |   1.18252  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.501503 |       0.455005 |   0.458379 |
| barab-szabi-1        |     0.514713 |       0.451715 |   0.4607   |
| k-d_tree_polars      |     0.50039  |       0.460226 |   0.463264 |
| Bori_Aron_solution-1 |     0.501544 |       0.566277 |   0.595387 |
| k-d_tree_pandas      |     0.498359 |       0.418064 |   0.599125 |
| k-d_tree_sklearn     |     0.507858 |       1.03385  |   1.09357  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.509385 |       0.469398 |   0.458264 |
| barab-szabi-1        |     0.479547 |       0.49278  |   0.474841 |
| k-d_tree_polars      |     0.50757  |       0.48993  |   0.503542 |
| Bori_Aron_solution-1 |     0.485332 |       0.644149 |   0.579574 |
| k-d_tree_pandas      |     0.485343 |       0.445908 |   0.624982 |
| k-d_tree_sklearn     |     0.483398 |       1.11195  |   1.13095  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480051 |       0.543569 |   0.517454 |
| k-d_tree_polars      |     0.492126 |       0.603433 |   0.575988 |
| Bori_Aron_solution-1 |     0.49069  |       0.826787 |   0.578003 |
| barab-szabi-1        |     0.489844 |       0.585583 |   0.587396 |
| k-d_tree_pandas      |     0.49229  |       0.525636 |   0.779927 |
| k-d_tree_sklearn     |     0.507449 |       1.34604  |   1.27935  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496888 |       0.762326 |   0.526392 |
| Bori_Aron_solution-1 |     0.520412 |       1.4948   |   0.619353 |
| k-d_tree_polars      |     0.497404 |       0.973459 |   0.969284 |
| barab-szabi-1        |     0.510954 |       0.962422 |   1.01788  |
| k-d_tree_pandas      |     0.513546 |       0.832265 |   1.24434  |
| k-d_tree_sklearn     |     0.520882 |       2.25087  |   1.30064  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.490814 |        5.61039 |   0.770067 |
| Bori_Aron_solution-1 |     0.487878 |       11.1267  |   0.838972 |
| k-d_tree_sklearn     |     0.496426 |       17.7765  |   1.39016  |
| k-d_tree_polars      |     0.488414 |        5.18527 |   7.079    |
| barab-szabi-1        |     0.502733 |        5.21936 |   7.1618   |
| k-d_tree_pandas      |     0.486938 |        4.37    |   7.456    |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.681336 |        77.4206 |    2.97337 |
| k-d_tree_sklearn     |     0.607229 |       248.692  |    4.03779 |
| Bori_Aron_solution-1 |     0.49052  |       157.249  |   25.9607  |