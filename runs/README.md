# 2025-12-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |    13.3637   |       1e-06    |   0.375034 |
| k-d_tree_polars      |     0.575639 |       0.4189   |   0.454915 |
| barab-szabi-2        |     0.530979 |       0.471153 |   0.45927  |
| barab-szabi-1        |     0.562368 |       0.437603 |   0.462251 |
| Bori_Aron_solution-1 |     0.556303 |       0.575159 |   0.591895 |
| k-d_tree_pandas      |    10.1049   |       0.427449 |   0.623349 |
| k-d_tree_sklearn     |     3.55972  |       1.14824  |   1.15036  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.560272 |       0.428523 |   0.459134 |
| k-d_tree_polars      |     0.546537 |       0.44314  |   0.461225 |
| barab-szabi-2        |     0.568769 |       0.467686 |   0.462202 |
| k-d_tree_pandas      |     0.651547 |       0.410046 |   0.613316 |
| Bori_Aron_solution-1 |     0.54653  |       0.587141 |   0.616108 |
| k-d_tree_sklearn     |     0.567347 |       1.02135  |   1.16288  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551934 |       0.470035 |   0.463476 |
| k-d_tree_polars      |     0.585147 |       0.497591 |   0.522258 |
| barab-szabi-1        |     0.553742 |       0.477136 |   0.529749 |
| Bori_Aron_solution-1 |     0.573546 |       0.652674 |   0.602931 |
| k-d_tree_pandas      |     0.579831 |       0.443269 |   0.637722 |
| k-d_tree_sklearn     |     0.565055 |       1.08211  |   1.18925  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583099 |       0.585082 |   0.527531 |
| k-d_tree_polars      |     0.603401 |       0.616394 |   0.626157 |
| barab-szabi-1        |     0.591717 |       0.609589 |   0.641012 |
| Bori_Aron_solution-1 |     0.585042 |       0.883884 |   0.653022 |
| k-d_tree_pandas      |     0.573853 |       0.544121 |   0.902989 |
| k-d_tree_sklearn     |     0.603922 |       1.43821  |   1.29372  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.565162 |       1.53417  |   0.64434  |
| barab-szabi-2        |     0.570309 |       0.813424 |   0.659951 |
| k-d_tree_polars      |     0.573    |       0.987551 |   1.00023  |
| barab-szabi-1        |     0.574373 |       0.961782 |   1.02744  |
| k-d_tree_pandas      |     0.604302 |       0.87996  |   1.30218  |
| k-d_tree_sklearn     |     0.570653 |       2.36923  |   1.34739  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562124 |        5.88444 |   0.805297 |
| Bori_Aron_solution-1 |     0.544377 |       11.8873  |   0.877839 |
| k-d_tree_sklearn     |     0.579879 |       19.0638  |   1.40969  |
| k-d_tree_polars      |     0.572129 |        5.55374 |   7.37165  |
| barab-szabi-1        |     0.570026 |        5.53376 |   7.49841  |
| k-d_tree_pandas      |     0.56835  |        4.48997 |   7.73496  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560081 |         86.287 |    2.92097 |
| k-d_tree_sklearn     |     0.570561 |        252.029 |    4.36109 |
| Bori_Aron_solution-1 |     0.694875 |        157.493 |   18.3716  |