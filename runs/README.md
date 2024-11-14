# 2024-11-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618875 |       0.394115 |   0.385413 |
| k-d_tree_polars      |     0.650153 |       0.399412 |   0.389647 |
| barab-szabi-1        |     0.620209 |       0.394359 |   0.396857 |
| solution-1           |     7.62383  |       1e-06    |   0.432724 |
| Bori_Aron_solution-1 |     0.61249  |       0.529754 |   0.51873  |
| k-d_tree_pandas      |     0.620594 |       0.378668 |   0.533481 |
| k-d_tree_sklearn     |    10.4864   |       1.17313  |   0.978482 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61131  |       0.387569 |   0.388192 |
| k-d_tree_polars      |     0.615481 |       0.402218 |   0.389745 |
| barab-szabi-1        |     0.617377 |       0.41699  |   0.398385 |
| Bori_Aron_solution-1 |     0.605924 |       0.533282 |   0.525199 |
| k-d_tree_pandas      |     0.618842 |       0.381969 |   0.532369 |
| k-d_tree_sklearn     |     0.619028 |       0.907115 |   0.960495 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615418 |       0.405651 |   0.400363 |
| k-d_tree_polars      |     0.619403 |       0.427991 |   0.424201 |
| barab-szabi-1        |     0.650412 |       0.437013 |   0.42476  |
| Bori_Aron_solution-1 |     0.611708 |       0.565341 |   0.523021 |
| k-d_tree_pandas      |     0.616678 |       0.405162 |   0.573846 |
| k-d_tree_sklearn     |     0.634793 |       0.945567 |   1.00116  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617193 |       0.47068  |   0.425898 |
| k-d_tree_polars      |     0.621061 |       0.541466 |   0.521599 |
| barab-szabi-1        |     0.625494 |       0.540972 |   0.53405  |
| Bori_Aron_solution-1 |     0.62037  |       0.751732 |   0.545141 |
| k-d_tree_pandas      |     0.622808 |       0.484039 |   0.705561 |
| k-d_tree_sklearn     |     0.645549 |       1.18306  |   1.05595  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.6201   |       0.719532 |   0.467622 |
| Bori_Aron_solution-1 |     0.608684 |       1.4037   |   0.577341 |
| k-d_tree_polars      |     0.620009 |       0.866589 |   0.85894  |
| barab-szabi-1        |     0.616325 |       0.887475 |   0.904444 |
| k-d_tree_pandas      |     0.620071 |       0.739563 |   1.1435   |
| k-d_tree_sklearn     |     0.628862 |       2.00584  |   1.14481  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614087 |        5.47673 |   0.756016 |
| Bori_Aron_solution-1 |     0.60937  |       11.0397  |   0.826686 |
| k-d_tree_sklearn     |     0.61958  |       16.7761  |   1.24343  |
| k-d_tree_polars      |     0.617582 |        4.86261 |   6.66327  |
| barab-szabi-1        |     0.621477 |        4.9414  |   6.73086  |
| k-d_tree_pandas      |     0.617813 |        3.93447 |   7.35486  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.639773 |        81.7513 |    3.5706  |
| k-d_tree_sklearn     |     0.625443 |       238.639  |    4.24578 |
| Bori_Aron_solution-1 |     0.673694 |       152.07   |   18.3283  |