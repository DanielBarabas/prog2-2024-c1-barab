# 2025-06-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544442 |       0.421766 |   0.426723 |
| k-d_tree_polars      |     0.547313 |       0.414948 |   0.437615 |
| solution-1           |     7.39958  |       1e-06    |   0.442206 |
| barab-szabi-1        |     0.557753 |       0.451802 |   0.484754 |
| Bori_Aron_solution-1 |     0.583318 |       0.565455 |   0.598045 |
| k-d_tree_pandas      |     7.8381   |       0.460039 |   0.698398 |
| k-d_tree_sklearn     |     3.49286  |       1.092    |   1.10778  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564757 |       0.430926 |   0.430079 |
| k-d_tree_polars      |     0.571203 |       0.421284 |   0.43084  |
| barab-szabi-1        |     0.564908 |       0.415795 |   0.453197 |
| Bori_Aron_solution-1 |     0.556135 |       0.570434 |   0.563726 |
| k-d_tree_pandas      |     0.560043 |       0.39851  |   0.56926  |
| k-d_tree_sklearn     |     0.581238 |       1.05255  |   1.08007  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55951  |       0.438404 |   0.44439  |
| barab-szabi-1        |     0.562275 |       0.441059 |   0.46066  |
| k-d_tree_polars      |     0.563903 |       0.445404 |   0.460662 |
| Bori_Aron_solution-1 |     0.55726  |       0.592997 |   0.560194 |
| k-d_tree_pandas      |     0.564961 |       0.417084 |   0.606261 |
| k-d_tree_sklearn     |     0.568002 |       1.07352  |   1.10441  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560882 |       0.512232 |   0.475479 |
| k-d_tree_polars      |     0.562146 |       0.550066 |   0.559169 |
| barab-szabi-1        |     0.561164 |       0.558415 |   0.572347 |
| Bori_Aron_solution-1 |     0.567298 |       0.780081 |   0.572989 |
| k-d_tree_pandas      |     0.568241 |       0.508102 |   0.777137 |
| k-d_tree_sklearn     |     0.563005 |       1.26975  |   1.18804  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569498 |       0.789976 |   0.585005 |
| Bori_Aron_solution-1 |     0.560074 |       1.45447  |   0.610451 |
| k-d_tree_polars      |     0.57108  |       0.895609 |   0.942645 |
| barab-szabi-1        |     0.573401 |       0.896715 |   0.974814 |
| k-d_tree_pandas      |     0.559423 |       0.777505 |   1.23208  |
| k-d_tree_sklearn     |     0.583471 |       2.17821  |   1.26257  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558783 |        5.11629 |    0.75485 |
| Bori_Aron_solution-1 |     0.546743 |       10.3589  |    0.84233 |
| k-d_tree_sklearn     |     0.557874 |       15.8036  |    1.31721 |
| barab-szabi-1        |     0.549655 |        4.87692 |    6.37961 |
| k-d_tree_polars      |     0.549549 |        4.9878  |    6.65838 |
| k-d_tree_pandas      |     0.562051 |        3.94239 |    6.77246 |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.655364 |        73.3664 |    2.87583 |
| k-d_tree_sklearn     |     0.622678 |       238.67   |    3.8962  |
| Bori_Aron_solution-1 |     0.552719 |       141.254  |   17.6941  |