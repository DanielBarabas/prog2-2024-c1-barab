# 2026-05-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.15771  |       1e-06    |   0.417897 |
| k-d_tree_polars      |     0.45251  |       0.393172 |   0.42306  |
| barab-szabi-2        |     0.456062 |       0.427086 |   0.434454 |
| Bori_Aron_solution-1 |     0.459341 |       0.533874 |   0.53142  |
| k-d_tree_pandas      |     0.455078 |       0.372554 |   0.536802 |
| barab-szabi-1        |     7.76779  |       0.455683 |   0.607129 |
| k-d_tree_sklearn     |     2.8203   |       1.08837  |   1.04172  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.459483 |       0.430234 |   0.422755 |
| k-d_tree_polars      |     0.460878 |       0.403553 |   0.430919 |
| barab-szabi-1        |     0.564073 |       0.401982 |   0.443206 |
| k-d_tree_pandas      |     0.464355 |       0.37749  |   0.538152 |
| Bori_Aron_solution-1 |     0.456743 |       0.540106 |   0.540974 |
| k-d_tree_sklearn     |     0.489816 |       0.940617 |   1.03431  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.461876 |       0.44793  |   0.439749 |
| k-d_tree_polars      |     0.460888 |       0.430377 |   0.467407 |
| barab-szabi-1        |     0.465252 |       0.425548 |   0.481012 |
| Bori_Aron_solution-1 |     0.459674 |       0.589688 |   0.544769 |
| k-d_tree_pandas      |     0.461565 |       0.405818 |   0.611047 |
| k-d_tree_sklearn     |     0.472532 |       1.01518  |   1.077    |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.457247 |       0.501956 |   0.473662 |
| Bori_Aron_solution-1 |     0.452337 |       0.765096 |   0.545089 |
| k-d_tree_polars      |     0.473338 |       0.54996  |   0.553967 |
| barab-szabi-1        |     0.478596 |       0.548357 |   0.567631 |
| k-d_tree_pandas      |     0.460665 |       0.494451 |   0.719905 |
| k-d_tree_sklearn     |     0.463133 |       1.23201  |   1.10473  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460739 |       0.721179 |   0.498677 |
| Bori_Aron_solution-1 |     0.449517 |       1.40973  |   0.571351 |
| k-d_tree_polars      |     0.460637 |       0.911342 |   0.896922 |
| barab-szabi-1        |     0.457499 |       0.919713 |   0.940233 |
| k-d_tree_pandas      |     0.460536 |       0.81431  |   1.15889  |
| k-d_tree_sklearn     |     0.465997 |       2.07881  |   1.18148  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.452651 |        4.94078 |   0.73826  |
| Bori_Aron_solution-1 |     0.450765 |       10.8807  |   0.799536 |
| k-d_tree_sklearn     |     0.467712 |       16.2208  |   1.28309  |
| barab-szabi-1        |     0.459504 |        5.6132  |   6.40737  |
| k-d_tree_polars      |     0.458616 |        5.40368 |   6.43498  |
| k-d_tree_pandas      |     0.467911 |        4.43018 |   6.82307  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.457564 |        69.1538 |    2.62295 |
| k-d_tree_sklearn     |     0.472382 |       232.3    |    3.57563 |
| Bori_Aron_solution-1 |     0.461485 |       152.486  |   16.1645  |