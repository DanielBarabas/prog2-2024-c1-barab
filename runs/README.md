# 2025-02-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.61899  |       0.460678 |   0.435057 |
| barab-szabi-2        |     3.98944  |       0.442036 |   0.435075 |
| barab-szabi-1        |     0.664674 |       0.425498 |   0.436189 |
| solution-1           |     7.83238  |       1e-06    |   0.462299 |
| Bori_Aron_solution-1 |     4.96458  |       0.567772 |   0.516326 |
| k-d_tree_pandas      |     0.628915 |       0.414081 |   0.578128 |
| k-d_tree_sklearn     |     3.19222  |       1.11694  |   1.09804  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622509 |       0.440625 |   0.42742  |
| barab-szabi-1        |     0.627517 |       0.447119 |   0.429654 |
| k-d_tree_polars      |     0.62749  |       0.450675 |   0.444775 |
| Bori_Aron_solution-1 |     0.611413 |       0.582125 |   0.587741 |
| k-d_tree_pandas      |     0.61168  |       0.411719 |   0.592833 |
| k-d_tree_sklearn     |     0.62262  |       1.04803  |   1.10123  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62005  |       0.434806 |   0.438942 |
| k-d_tree_polars      |     0.616194 |       0.461904 |   0.459413 |
| barab-szabi-1        |     0.613547 |       0.461489 |   0.474009 |
| Bori_Aron_solution-1 |     0.60822  |       0.614614 |   0.579972 |
| k-d_tree_pandas      |     0.625232 |       0.461854 |   0.622814 |
| k-d_tree_sklearn     |     0.64113  |       1.11068  |   1.11059  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.644448 |       0.531408 |   0.471712 |
| k-d_tree_polars      |     0.633629 |       0.567678 |   0.56267  |
| barab-szabi-1        |     0.605118 |       0.571891 |   0.563358 |
| Bori_Aron_solution-1 |     0.621642 |       0.803223 |   0.612691 |
| k-d_tree_pandas      |     0.628308 |       0.504024 |   0.787386 |
| k-d_tree_sklearn     |     0.626887 |       1.34129  |   1.21813  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617931 |       0.764981 |   0.499806 |
| Bori_Aron_solution-1 |     0.613943 |       1.46239  |   0.621716 |
| k-d_tree_polars      |     0.611252 |       0.908535 |   0.922    |
| barab-szabi-1        |     0.610671 |       0.919756 |   0.970165 |
| k-d_tree_pandas      |     0.605926 |       0.782851 |   1.22857  |
| k-d_tree_sklearn     |     0.611676 |       2.187    |   1.2764   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615919 |        5.89259 |   0.811848 |
| Bori_Aron_solution-1 |     0.612865 |       11.262   |   0.951065 |
| k-d_tree_sklearn     |     0.627674 |       18.8032  |   1.38478  |
| barab-szabi-1        |     0.612047 |        5.10738 |   7.10897  |
| k-d_tree_polars      |     0.611963 |        5.11632 |   7.12397  |
| k-d_tree_pandas      |     0.614502 |        3.94795 |   7.57126  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.803002 |        78.2469 |    3.68228 |
| k-d_tree_sklearn     |     0.69195  |       245.945  |    4.31186 |
| Bori_Aron_solution-1 |     0.607872 |       160.151  |   15.3812  |