# 2026-05-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.457715 |       0.401103 |   0.416862 |
| barab-szabi-2        |     0.455272 |       0.420918 |   0.421301 |
| k-d_tree_pandas      |     0.45265  |       0.382049 |   0.538238 |
| Bori_Aron_solution-1 |     0.462559 |       0.531581 |   0.549582 |
| solution-1           |     8.22135  |       1e-06    |   0.668007 |
| barab-szabi-1        |     8.3984   |       0.505665 |   1.03343  |
| k-d_tree_sklearn     |     2.95484  |       1.45836  |   1.04677  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.461186 |       0.42446  |   0.419591 |
| k-d_tree_polars      |     0.46491  |       0.40773  |   0.423159 |
| barab-szabi-1        |     0.465352 |       0.407612 |   0.428269 |
| Bori_Aron_solution-1 |     0.466347 |       0.54044  |   0.530709 |
| k-d_tree_pandas      |     0.522676 |       0.391009 |   0.541502 |
| k-d_tree_sklearn     |     0.468929 |       0.953639 |   1.05367  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.458318 |       0.435705 |   0.431196 |
| k-d_tree_polars      |     0.461207 |       0.433523 |   0.445432 |
| barab-szabi-1        |     0.463351 |       0.432475 |   0.454442 |
| Bori_Aron_solution-1 |     0.458171 |       0.580609 |   0.533443 |
| k-d_tree_pandas      |     0.461252 |       0.401972 |   0.577209 |
| k-d_tree_sklearn     |     0.463208 |       1.02422  |   1.06155  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464437 |       0.502724 |   0.462911 |
| k-d_tree_polars      |     0.467819 |       0.562282 |   0.550698 |
| barab-szabi-1        |     0.466504 |       0.553039 |   0.562951 |
| Bori_Aron_solution-1 |     0.460222 |       0.793707 |   0.573058 |
| k-d_tree_pandas      |     0.464136 |       0.493994 |   0.704953 |
| k-d_tree_sklearn     |     0.467735 |       1.28773  |   1.10556  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478476 |       0.756944 |   0.503438 |
| Bori_Aron_solution-1 |     0.467498 |       1.50031  |   0.580666 |
| k-d_tree_polars      |     0.467206 |       0.946794 |   0.97137  |
| barab-szabi-1        |     0.470966 |       0.902073 |   0.986635 |
| k-d_tree_pandas      |     0.469844 |       0.785407 |   1.17376  |
| k-d_tree_sklearn     |     0.466424 |       2.22771  |   1.17487  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.516848 |        5.7405  |   0.736974 |
| Bori_Aron_solution-1 |     0.462709 |       11.237   |   0.798543 |
| k-d_tree_sklearn     |     0.460693 |       17.0076  |   1.24568  |
| k-d_tree_pandas      |     0.476379 |        4.19013 |   7.58575  |
| barab-szabi-1        |     0.479417 |        5.40718 |   7.94977  |
| k-d_tree_polars      |     0.514088 |        5.29031 |   7.95248  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.458457 |        81.0543 |    2.37508 |
| k-d_tree_sklearn     |     0.520078 |       258.505  |    3.04863 |
| Bori_Aron_solution-1 |     0.461392 |       153.498  |   23.6829  |