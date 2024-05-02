# 2024-05-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.708076 |       0.402092 |   0.345193 |
| barab-szabi-2        |     0.70558  |       0.344173 |   0.346269 |
| Bori_Aron_solution-1 |     1.27123  |       0.471843 |   0.477891 |
| k-d_tree_pandas      |     0.709101 |       0.376685 |   0.501045 |
| k-d_tree_sklearn     |     3.51318  |       1.62766  |   0.655102 |
| barab-szabi-1        |    11.0819   |       0.648875 |   1.01034  |
| solution-1           |     9.72427  |       1e-06    |   1.15167  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734075 |       0.349201 |   0.337241 |
| k-d_tree_polars      |     0.736032 |       0.409693 |   0.350124 |
| barab-szabi-1        |     0.738479 |       0.405596 |   0.350578 |
| Bori_Aron_solution-1 |     0.721938 |       0.487242 |   0.474749 |
| k-d_tree_pandas      |     0.739018 |       0.38742  |   0.510759 |
| k-d_tree_sklearn     |     0.746715 |       0.852245 |   0.682577 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.728002 |       0.365669 |   0.360146 |
| k-d_tree_polars      |     0.749303 |       0.447052 |   0.381403 |
| barab-szabi-1        |     0.740688 |       0.446779 |   0.409883 |
| Bori_Aron_solution-1 |     0.726008 |       0.516596 |   0.476565 |
| k-d_tree_pandas      |     0.7386   |       0.405334 |   0.529317 |
| k-d_tree_sklearn     |     0.748618 |       0.889233 |   0.687434 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.738169 |       0.432375 |   0.397322 |
| k-d_tree_polars      |     0.728862 |       0.536248 |   0.48278  |
| Bori_Aron_solution-1 |     0.722629 |       0.695268 |   0.483598 |
| barab-szabi-1        |     0.736581 |       0.561809 |   0.48893  |
| k-d_tree_pandas      |     0.73086  |       0.486678 |   0.660802 |
| k-d_tree_sklearn     |     0.747262 |       1.10616  |   0.745501 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.730802 |       0.68439  |   0.431746 |
| Bori_Aron_solution-1 |     0.728233 |       1.42284  |   0.520328 |
| k-d_tree_polars      |     0.736904 |       0.862226 |   0.827413 |
| k-d_tree_sklearn     |     0.748744 |       1.93783  |   0.855577 |
| barab-szabi-1        |     0.771977 |       0.871468 |   0.867408 |
| k-d_tree_pandas      |     0.739121 |       0.744097 |   1.10365  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.72928  |        5.34984 |   0.757735 |
| Bori_Aron_solution-1 |     0.720067 |       10.6251  |   0.775831 |
| k-d_tree_sklearn     |     0.758999 |       15.6921  |   1.05289  |
| k-d_tree_polars      |     0.741875 |        4.77528 |   6.47452  |
| barab-szabi-1        |     0.733885 |        4.90632 |   6.52449  |
| k-d_tree_pandas      |     0.735773 |        3.88356 |   7.01263  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.02151  |        75.4738 |    4.10294 |
| k-d_tree_sklearn     |     0.906401 |       237.146  |    4.80131 |
| Bori_Aron_solution-1 |     0.766177 |       161.525  |   15.1553  |