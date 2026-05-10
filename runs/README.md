# 2026-05-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.471198 |       0.406249 |   0.432887 |
| barab-szabi-1        |     0.45953  |       0.398736 |   0.437505 |
| barab-szabi-2        |     0.461353 |       0.433895 |   0.437864 |
| solution-1           |     8.09977  |       1e-06    |   0.460834 |
| Bori_Aron_solution-1 |     0.677293 |       0.555203 |   0.556021 |
| k-d_tree_pandas      |     0.510948 |       0.382978 |   0.562065 |
| k-d_tree_sklearn     |    11.3546   |       1.28014  |   1.09514  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478258 |       0.437523 |   0.436369 |
| k-d_tree_polars      |     0.463944 |       0.408533 |   0.439835 |
| barab-szabi-1        |     0.480567 |       0.428835 |   0.450038 |
| Bori_Aron_solution-1 |     0.463299 |       0.555292 |   0.552857 |
| k-d_tree_pandas      |     0.486461 |       0.397646 |   0.583271 |
| k-d_tree_sklearn     |     0.465038 |       0.975256 |   1.06186  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466743 |       0.44392  |   0.452451 |
| barab-szabi-1        |     0.469205 |       0.445544 |   0.467692 |
| k-d_tree_polars      |     0.470306 |       0.449163 |   0.471585 |
| Bori_Aron_solution-1 |     0.461993 |       0.606542 |   0.556673 |
| k-d_tree_pandas      |     0.471933 |       0.419917 |   0.600951 |
| k-d_tree_sklearn     |     0.476513 |       1.05149  |   1.10335  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462907 |       0.507562 |   0.475538 |
| Bori_Aron_solution-1 |     0.455973 |       0.786303 |   0.56225  |
| k-d_tree_polars      |     0.461089 |       0.55881  |   0.568438 |
| barab-szabi-1        |     0.464706 |       0.564931 |   0.577752 |
| k-d_tree_pandas      |     0.46327  |       0.50507  |   0.738081 |
| k-d_tree_sklearn     |     0.467339 |       1.29212  |   1.1423   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462218 |       0.731569 |   0.520607 |
| Bori_Aron_solution-1 |     0.459619 |       1.45148  |   0.585945 |
| k-d_tree_polars      |     0.468815 |       0.934924 |   0.925935 |
| barab-szabi-1        |     0.46283  |       0.887577 |   0.94233  |
| k-d_tree_pandas      |     0.463932 |       0.815826 |   1.18945  |
| k-d_tree_sklearn     |     0.468571 |       2.13913  |   1.21647  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.454307 |        4.9194  |   0.723582 |
| Bori_Aron_solution-1 |     0.454005 |       10.8937  |   0.801908 |
| k-d_tree_sklearn     |     0.45517  |       16.3067  |   1.27011  |
| k-d_tree_polars      |     0.456389 |        5.43703 |   6.43904  |
| barab-szabi-1        |     0.454085 |        5.38956 |   6.48259  |
| k-d_tree_pandas      |     0.454508 |        4.50442 |   6.88608  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.764026 |         67.31  |    2.62543 |
| k-d_tree_sklearn     |     0.457564 |        226.913 |    3.7268  |
| Bori_Aron_solution-1 |     0.454462 |        150.999 |   18.0661  |