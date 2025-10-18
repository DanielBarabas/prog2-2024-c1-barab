# 2025-10-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.557885 |       0.404269 |   0.430644 |
| barab-szabi-2        |     0.553796 |       0.429476 |   0.453873 |
| Bori_Aron_solution-1 |     1.00911  |       0.592171 |   0.560057 |
| barab-szabi-1        |     0.760492 |       0.407603 |   0.647114 |
| solution-1           |     8.14402  |       1e-06    |   0.655446 |
| k-d_tree_pandas      |     8.59922  |       0.450538 |   0.870462 |
| k-d_tree_sklearn     |     3.09197  |       1.29283  |   1.08025  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.561897 |       0.412471 |   0.435434 |
| barab-szabi-2        |     0.550248 |       0.425151 |   0.438464 |
| k-d_tree_polars      |     0.555407 |       0.411089 |   0.440596 |
| Bori_Aron_solution-1 |     0.547534 |       0.556096 |   0.55097  |
| k-d_tree_pandas      |     0.553332 |       0.402893 |   0.580488 |
| k-d_tree_sklearn     |     0.558207 |       0.991431 |   1.06332  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553897 |       0.440713 |   0.443141 |
| barab-szabi-1        |     0.55313  |       0.437774 |   0.467759 |
| k-d_tree_polars      |     0.56765  |       0.451514 |   0.469011 |
| Bori_Aron_solution-1 |     0.540171 |       0.592341 |   0.558082 |
| k-d_tree_pandas      |     0.551902 |       0.41467  |   0.600865 |
| k-d_tree_sklearn     |     0.553697 |       1.0344   |   1.08825  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550404 |       0.495535 |   0.474793 |
| k-d_tree_polars      |     0.550065 |       0.567001 |   0.55264  |
| barab-szabi-1        |     0.552214 |       0.565543 |   0.564898 |
| Bori_Aron_solution-1 |     0.544186 |       0.780471 |   0.565951 |
| k-d_tree_pandas      |     0.555597 |       0.505933 |   0.752    |
| k-d_tree_sklearn     |     0.553212 |       1.25814  |   1.13112  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562433 |       0.75737  |   0.511161 |
| Bori_Aron_solution-1 |     0.544299 |       1.44386  |   0.586684 |
| k-d_tree_polars      |     0.563445 |       0.946256 |   0.913959 |
| barab-szabi-1        |     0.554511 |       0.923696 |   0.954387 |
| k-d_tree_pandas      |     0.549762 |       0.800803 |   1.17309  |
| k-d_tree_sklearn     |     0.571697 |       2.14372  |   1.23198  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605607 |        5.56151 |   0.795211 |
| Bori_Aron_solution-1 |     0.577909 |       11.0143  |   0.832289 |
| k-d_tree_sklearn     |     0.570931 |       17.2523  |   1.44674  |
| barab-szabi-1        |     0.570748 |        5.55285 |   6.74775  |
| k-d_tree_polars      |     0.610042 |        5.5375  |   6.81008  |
| k-d_tree_pandas      |     0.549805 |        4.43254 |   7.23215  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.743813 |        76.1677 |    2.86157 |
| k-d_tree_sklearn     |     1.1202   |       239.996  |    3.8938  |
| Bori_Aron_solution-1 |     0.555028 |       147.306  |   18.0435  |