# 2024-07-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.08219  |       1e-06    |   0.37593  |
| barab-szabi-2        |     0.550918 |       0.385111 |   0.382461 |
| k-d_tree_polars      |     0.58163  |       0.394328 |   0.383085 |
| barab-szabi-1        |     0.554365 |       0.396518 |   0.384418 |
| Bori_Aron_solution-1 |     0.566225 |       0.532884 |   0.511202 |
| k-d_tree_pandas      |     0.553759 |       0.381193 |   0.51513  |
| k-d_tree_sklearn     |    10.8328   |       1.08627  |   0.692187 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567361 |       0.386654 |   0.383942 |
| k-d_tree_polars      |     0.549364 |       0.408023 |   0.388375 |
| barab-szabi-1        |     0.546535 |       0.402623 |   0.389812 |
| Bori_Aron_solution-1 |     0.544054 |       0.523617 |   0.516661 |
| k-d_tree_pandas      |     0.546767 |       0.379171 |   0.535674 |
| k-d_tree_sklearn     |     0.555868 |       0.895878 |   0.698638 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570399 |       0.412461 |   0.406214 |
| k-d_tree_polars      |     0.601509 |       0.435441 |   0.422673 |
| barab-szabi-1        |     0.558472 |       0.444963 |   0.436807 |
| Bori_Aron_solution-1 |     0.56252  |       0.581779 |   0.55102  |
| k-d_tree_pandas      |     0.595711 |       0.404648 |   0.578417 |
| k-d_tree_sklearn     |     0.54997  |       0.935808 |   0.746785 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569372 |       0.469813 |   0.442367 |
| k-d_tree_polars      |     0.550752 |       0.534718 |   0.512622 |
| barab-szabi-1        |     0.56514  |       0.536669 |   0.526342 |
| Bori_Aron_solution-1 |     0.553644 |       0.75665  |   0.547559 |
| k-d_tree_pandas      |     0.554732 |       0.494544 |   0.736974 |
| k-d_tree_sklearn     |     0.569834 |       1.18936  |   0.798614 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.572715 |       0.714767 |   0.464942 |
| Bori_Aron_solution-1 |     0.54676  |       1.38699  |   0.562801 |
| k-d_tree_polars      |     0.557005 |       0.848837 |   0.856518 |
| k-d_tree_sklearn     |     0.573046 |       1.98405  |   0.873203 |
| barab-szabi-1        |     0.557343 |       0.850581 |   0.90808  |
| k-d_tree_pandas      |     0.552125 |       0.74598  |   1.13477  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562532 |        5.51756 |   0.732139 |
| Bori_Aron_solution-1 |     0.546381 |       10.8288  |   0.851059 |
| k-d_tree_sklearn     |     0.581422 |       15.8991  |   0.985133 |
| k-d_tree_polars      |     0.588255 |        4.88327 |   6.45629  |
| barab-szabi-1        |     0.575737 |        4.88098 |   6.79     |
| k-d_tree_pandas      |     0.563201 |        3.87211 |   6.85441  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.939132 |         71.253 |    3.24006 |
| k-d_tree_sklearn     |     0.555594 |        226.667 |    3.85468 |
| Bori_Aron_solution-1 |     0.571171 |        150.699 |   17.7416  |