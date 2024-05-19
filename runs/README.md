# 2024-05-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.76451  |       0.439288 |   0.339115 |
| barab-szabi-1        |     0.791467 |       0.402086 |   0.342146 |
| k-d_tree_polars      |     0.782337 |       0.403047 |   0.344025 |
| Bori_Aron_solution-1 |     5.02129  |       0.405874 |   0.405951 |
| k-d_tree_pandas      |     0.78994  |       0.382543 |   0.47686  |
| solution-1           |     9.01206  |       1e-06    |   0.618319 |
| k-d_tree_sklearn     |     3.42839  |       1.05408  |   0.66064  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.811347 |       0.40729  |   0.35036  |
| barab-szabi-1        |     0.785983 |       0.408883 |   0.352587 |
| barab-szabi-2        |     0.778422 |       0.352732 |   0.35358  |
| k-d_tree_pandas      |     0.79642  |       0.387916 |   0.482558 |
| Bori_Aron_solution-1 |     0.779781 |       0.48357  |   0.487854 |
| k-d_tree_sklearn     |     0.804005 |       0.875251 |   0.657849 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.79053  |       0.369169 |   0.350862 |
| k-d_tree_polars      |     0.785095 |       0.427929 |   0.382092 |
| barab-szabi-1        |     0.784562 |       0.442044 |   0.386832 |
| Bori_Aron_solution-1 |     0.767347 |       0.519364 |   0.492826 |
| k-d_tree_pandas      |     0.789635 |       0.40739  |   0.535663 |
| k-d_tree_sklearn     |     0.821716 |       0.929688 |   0.69346  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.797639 |       0.433878 |   0.400891 |
| k-d_tree_polars      |     0.7819   |       0.53975  |   0.476845 |
| barab-szabi-1        |     0.78564  |       0.537199 |   0.49346  |
| Bori_Aron_solution-1 |     0.780564 |       0.733784 |   0.494313 |
| k-d_tree_pandas      |     0.781002 |       0.483479 |   0.662075 |
| k-d_tree_sklearn     |     0.797843 |       1.12405  |   0.748882 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.779655 |       0.679175 |   0.42958  |
| Bori_Aron_solution-1 |     0.765921 |       1.34374  |   0.514158 |
| k-d_tree_polars      |     0.785443 |       0.884317 |   0.848007 |
| k-d_tree_sklearn     |     0.784075 |       1.91229  |   0.862181 |
| barab-szabi-1        |     0.798072 |       0.872846 |   0.892326 |
| k-d_tree_pandas      |     0.788901 |       0.763236 |   1.11364  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.806108 |        5.31241 |   0.736259 |
| Bori_Aron_solution-1 |     0.779187 |       10.9848  |   0.783456 |
| k-d_tree_sklearn     |     0.788338 |       16.1315  |   1.0481   |
| barab-szabi-1        |     0.803167 |        5.00768 |   6.746    |
| k-d_tree_polars      |     0.785705 |        5.04284 |   7.03303  |
| k-d_tree_pandas      |     0.797369 |        4.02075 |   7.29267  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.15128  |        73.1083 |    3.8789  |
| k-d_tree_sklearn     |     0.875689 |       227.716  |    4.71931 |
| Bori_Aron_solution-1 |     0.783488 |       147.477  |   17.1789  |