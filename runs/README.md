# 2025-06-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.530459 |       0.394376 |   0.418689 |
| barab-szabi-2        |     0.528465 |       0.408007 |   0.421572 |
| barab-szabi-1        |     0.533259 |       0.40181  |   0.437706 |
| solution-1           |     7.3359   |       1e-06    |   0.477308 |
| Bori_Aron_solution-1 |     0.525564 |       0.539102 |   0.54201  |
| k-d_tree_pandas      |     7.56814  |       0.400943 |   0.646913 |
| k-d_tree_sklearn     |     3.33514  |       1.0602   |   1.04946  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548767 |       0.416265 |   0.413366 |
| k-d_tree_polars      |     0.539961 |       0.398271 |   0.419984 |
| barab-szabi-1        |     0.541086 |       0.406213 |   0.421843 |
| Bori_Aron_solution-1 |     0.535958 |       0.547656 |   0.538908 |
| k-d_tree_pandas      |     0.543981 |       0.382561 |   0.543017 |
| k-d_tree_sklearn     |     0.549781 |       0.95007  |   1.0358   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544341 |       0.429336 |   0.426677 |
| k-d_tree_polars      |     0.543827 |       0.429686 |   0.451762 |
| barab-szabi-1        |     0.546262 |       0.428648 |   0.454387 |
| Bori_Aron_solution-1 |     0.539595 |       0.581278 |   0.539447 |
| k-d_tree_pandas      |     0.54526  |       0.400206 |   0.592166 |
| k-d_tree_sklearn     |     0.547575 |       0.998013 |   1.0571   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543924 |       0.498672 |   0.461653 |
| k-d_tree_polars      |     0.541747 |       0.540453 |   0.545205 |
| barab-szabi-1        |     0.545425 |       0.538642 |   0.554659 |
| Bori_Aron_solution-1 |     0.538063 |       0.754937 |   0.558847 |
| k-d_tree_pandas      |     0.547022 |       0.475064 |   0.720197 |
| k-d_tree_sklearn     |     0.551245 |       1.22696  |   1.11628  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540258 |       0.733202 |   0.489334 |
| Bori_Aron_solution-1 |     0.541116 |       1.39023  |   0.578849 |
| k-d_tree_polars      |     0.548993 |       0.879829 |   0.894028 |
| barab-szabi-1        |     0.542681 |       0.870974 |   0.936682 |
| k-d_tree_pandas      |     0.54348  |       0.750023 |   1.15504  |
| k-d_tree_sklearn     |     0.543551 |       2.03684  |   1.18234  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544036 |        5.11743 |   0.71598  |
| Bori_Aron_solution-1 |     0.542934 |       10.4598  |   0.833073 |
| k-d_tree_sklearn     |     0.543618 |       15.5429  |   1.29313  |
| barab-szabi-1        |     0.546194 |        4.9246  |   6.39437  |
| k-d_tree_polars      |     0.547681 |        5.0057  |   6.39767  |
| k-d_tree_pandas      |     0.54469  |        3.91854 |   7.12452  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.67708  |         68.528 |    2.65442 |
| k-d_tree_sklearn     |     0.595225 |        223.171 |    3.79478 |
| Bori_Aron_solution-1 |     0.539852 |        140.858 |   15.2314  |