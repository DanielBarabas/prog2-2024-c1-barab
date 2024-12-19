# 2024-12-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.50615  |       1e-06    |   0.349724 |
| barab-szabi-2        |     0.621025 |       0.387769 |   0.380445 |
| barab-szabi-1        |     0.631231 |       0.397772 |   0.38549  |
| k-d_tree_polars      |     0.616212 |       0.39961  |   0.38645  |
| Bori_Aron_solution-1 |     0.62376  |       0.523464 |   0.525347 |
| k-d_tree_pandas      |     0.628252 |       0.385442 |   0.526892 |
| k-d_tree_sklearn     |    10.1921   |       0.975667 |   0.956878 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613451 |       0.391303 |   0.387087 |
| k-d_tree_polars      |     0.616323 |       0.401879 |   0.38793  |
| barab-szabi-1        |     0.617102 |       0.420946 |   0.390552 |
| Bori_Aron_solution-1 |     0.610835 |       0.532844 |   0.521326 |
| k-d_tree_pandas      |     0.617269 |       0.38342  |   0.530998 |
| k-d_tree_sklearn     |     0.620826 |       0.947432 |   0.975435 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612267 |       0.400977 |   0.401942 |
| k-d_tree_polars      |     0.611407 |       0.424389 |   0.415178 |
| barab-szabi-1        |     0.644534 |       0.426309 |   0.419645 |
| Bori_Aron_solution-1 |     0.609039 |       0.565696 |   0.520592 |
| k-d_tree_pandas      |     0.61728  |       0.397856 |   0.564206 |
| k-d_tree_sklearn     |     0.617815 |       0.939842 |   0.987858 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617452 |       0.464947 |   0.424109 |
| k-d_tree_polars      |     0.60955  |       0.545491 |   0.515327 |
| barab-szabi-1        |     0.620994 |       0.544298 |   0.522008 |
| Bori_Aron_solution-1 |     0.605374 |       0.740788 |   0.536378 |
| k-d_tree_pandas      |     0.615089 |       0.480278 |   0.698262 |
| k-d_tree_sklearn     |     0.63324  |       1.15094  |   1.04203  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607808 |       0.739816 |   0.470981 |
| Bori_Aron_solution-1 |     0.615769 |       1.40227  |   0.56345  |
| k-d_tree_polars      |     0.611028 |       0.83933  |   0.858035 |
| barab-szabi-1        |     0.618858 |       0.873731 |   0.940327 |
| k-d_tree_sklearn     |     0.626883 |       1.98449  |   1.13669  |
| k-d_tree_pandas      |     0.619419 |       0.759189 |   1.14406  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611828 |        5.45846 |   0.733907 |
| Bori_Aron_solution-1 |     0.617018 |       10.8924  |   0.810211 |
| k-d_tree_sklearn     |     0.619693 |       16.0484  |   1.31625  |
| k-d_tree_polars      |     0.616458 |        4.85668 |   6.51387  |
| barab-szabi-1        |     0.63314  |        4.85801 |   6.54439  |
| k-d_tree_pandas      |     0.621239 |        3.87654 |   6.93312  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623637 |        70.1172 |    2.89075 |
| k-d_tree_sklearn     |     0.624716 |       221.061  |    4.10917 |
| Bori_Aron_solution-1 |     0.650664 |       143.951  |   18.9405  |