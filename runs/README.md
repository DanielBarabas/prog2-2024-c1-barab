# 2024-09-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.632066 |       0.418597 |   0.405196 |
| barab-szabi-2        |     0.65023  |       0.411089 |   0.415583 |
| solution-1           |     7.72486  |       1e-06    |   0.435269 |
| k-d_tree_polars      |     0.651049 |       0.442562 |   0.451471 |
| Bori_Aron_solution-1 |     4.50041  |       0.553676 |   0.488898 |
| k-d_tree_pandas      |     4.1039   |       0.435365 |   0.57557  |
| k-d_tree_sklearn     |     3.12488  |       1.02401  |   1.06585  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.652788 |       0.415727 |   0.410014 |
| barab-szabi-1        |     0.669426 |       0.442166 |   0.41526  |
| k-d_tree_polars      |     0.64924  |       0.440798 |   0.423193 |
| k-d_tree_pandas      |     0.683028 |       0.429971 |   0.579395 |
| Bori_Aron_solution-1 |     0.641638 |       0.576194 |   0.59705  |
| k-d_tree_sklearn     |     0.667566 |       1.00645  |   1.08812  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.655599 |       0.420659 |   0.42648  |
| k-d_tree_polars      |     0.659672 |       0.449521 |   0.442529 |
| barab-szabi-1        |     0.640325 |       0.477725 |   0.452092 |
| Bori_Aron_solution-1 |     0.649674 |       0.658532 |   0.578154 |
| k-d_tree_pandas      |     0.654081 |       0.447978 |   0.660319 |
| k-d_tree_sklearn     |     0.647613 |       1.06819  |   1.11621  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.657771 |       0.489809 |   0.446498 |
| barab-szabi-1        |     0.671956 |       0.57461  |   0.550213 |
| k-d_tree_polars      |     0.654388 |       0.589674 |   0.562395 |
| Bori_Aron_solution-1 |     0.640355 |       0.78973  |   0.604071 |
| k-d_tree_pandas      |     0.679573 |       0.516702 |   0.75782  |
| k-d_tree_sklearn     |     0.65597  |       1.23724  |   1.18095  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.637574 |       1.44165  |   0.604505 |
| barab-szabi-2        |     0.669706 |       0.772094 |   0.660928 |
| k-d_tree_polars      |     0.644868 |       0.884667 |   0.938422 |
| barab-szabi-1        |     0.669513 |       0.880679 |   0.957467 |
| k-d_tree_pandas      |     0.64447  |       0.770116 |   1.21334  |
| k-d_tree_sklearn     |     0.646232 |       2.15048  |   1.28085  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.689573 |        5.81892 |   0.817163 |
| Bori_Aron_solution-1 |     0.646942 |       11.1933  |   0.894209 |
| k-d_tree_sklearn     |     0.650404 |       17.757   |   1.34754  |
| barab-szabi-1        |     0.665551 |        4.92081 |   7.19359  |
| k-d_tree_polars      |     0.643244 |        4.87268 |   7.22028  |
| k-d_tree_pandas      |     0.672885 |        3.86403 |   7.54922  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.696319 |        77.5668 |    3.35042 |
| k-d_tree_sklearn     |     0.905129 |       247.811  |    4.32916 |
| Bori_Aron_solution-1 |     0.663854 |       149.987  |   17.1853  |