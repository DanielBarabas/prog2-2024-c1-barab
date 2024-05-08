# 2024-05-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.705275 |       0.346431 |   0.336839 |
| k-d_tree_polars      |     0.727314 |       0.403201 |   0.351607 |
| barab-szabi-1        |     8.86746  |       0.424901 |   0.354565 |
| solution-1           |     8.54153  |       1e-06    |   0.366054 |
| Bori_Aron_solution-1 |     0.699927 |       0.48274  |   0.475405 |
| k-d_tree_pandas      |     0.734998 |       0.388775 |   0.481522 |
| k-d_tree_sklearn     |     3.5095   |       0.885417 |   0.686768 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.742124 |       0.35397  |   0.348175 |
| barab-szabi-1        |     0.742442 |       0.411661 |   0.352365 |
| k-d_tree_polars      |     0.739288 |       0.414922 |   0.355337 |
| Bori_Aron_solution-1 |     0.760541 |       0.539476 |   0.484435 |
| k-d_tree_pandas      |     0.766205 |       0.396563 |   0.495507 |
| k-d_tree_sklearn     |     0.747773 |       0.865016 |   0.675195 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.740039 |       0.436386 |   0.376551 |
| barab-szabi-1        |     0.751999 |       0.468765 |   0.380979 |
| barab-szabi-2        |     0.736903 |       0.366589 |   0.381407 |
| Bori_Aron_solution-1 |     0.73513  |       0.536039 |   0.508863 |
| k-d_tree_pandas      |     0.739225 |       0.405967 |   0.528853 |
| k-d_tree_sklearn     |     0.744056 |       0.945075 |   0.697102 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.745457 |       0.437075 |   0.403164 |
| k-d_tree_polars      |     0.749562 |       0.552566 |   0.485018 |
| barab-szabi-1        |     0.741377 |       0.545948 |   0.489108 |
| Bori_Aron_solution-1 |     0.734288 |       0.703119 |   0.49577  |
| k-d_tree_pandas      |     0.739962 |       0.488185 |   0.668156 |
| k-d_tree_sklearn     |     0.765242 |       1.13902  |   0.763893 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.741471 |       0.721688 |   0.486737 |
| Bori_Aron_solution-1 |     0.729351 |       1.36066  |   0.521673 |
| k-d_tree_polars      |     0.733016 |       0.871535 |   0.849263 |
| k-d_tree_sklearn     |     0.744558 |       1.98224  |   0.872924 |
| barab-szabi-1        |     0.746315 |       0.876267 |   0.888756 |
| k-d_tree_pandas      |     0.752001 |       0.753435 |   1.11731  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.733978 |        5.50465 |   0.748671 |
| Bori_Aron_solution-1 |     0.728616 |       10.99    |   0.789875 |
| k-d_tree_sklearn     |     0.743872 |       16.1488  |   1.07223  |
| k-d_tree_polars      |     0.755172 |        4.8848  |   6.78865  |
| barab-szabi-1        |     0.752481 |        5.00095 |   6.80441  |
| k-d_tree_pandas      |     0.747933 |        3.88721 |   6.97696  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.14713  |        74.9792 |    3.88372 |
| k-d_tree_sklearn     |     0.884234 |       232.484  |    4.83338 |
| Bori_Aron_solution-1 |     0.729937 |       149.982  |   17.4805  |