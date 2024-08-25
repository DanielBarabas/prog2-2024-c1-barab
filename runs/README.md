# 2024-08-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.59639  |       1e-06    |   0.352908 |
| barab-szabi-1        |     0.597705 |       0.405788 |   0.392311 |
| k-d_tree_polars      |     0.603548 |       0.392191 |   0.393421 |
| barab-szabi-2        |     7.84094  |       0.508192 |   0.393717 |
| Bori_Aron_solution-1 |     0.607401 |       0.520299 |   0.516845 |
| k-d_tree_pandas      |     0.612215 |       0.423847 |   0.539104 |
| k-d_tree_sklearn     |     2.97419  |       0.924135 |   0.716929 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617496 |       0.390465 |   0.383827 |
| barab-szabi-1        |     0.61333  |       0.415642 |   0.396687 |
| k-d_tree_polars      |     0.609856 |       0.39999  |   0.424186 |
| k-d_tree_pandas      |     0.608526 |       0.3844   |   0.535408 |
| Bori_Aron_solution-1 |     0.602486 |       0.535278 |   0.536665 |
| k-d_tree_sklearn     |     0.628823 |       0.909337 |   0.708444 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632986 |       0.424038 |   0.4044   |
| k-d_tree_polars      |     0.620682 |       0.42856  |   0.4239   |
| barab-szabi-1        |     0.631569 |       0.429678 |   0.425271 |
| Bori_Aron_solution-1 |     0.609015 |       0.571883 |   0.541575 |
| k-d_tree_pandas      |     0.619771 |       0.402387 |   0.58535  |
| k-d_tree_sklearn     |     0.623049 |       0.95768  |   0.744256 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610135 |       0.485525 |   0.435116 |
| k-d_tree_polars      |     0.63148  |       0.544009 |   0.532165 |
| barab-szabi-1        |     0.626929 |       0.541455 |   0.537988 |
| Bori_Aron_solution-1 |     0.606439 |       0.745749 |   0.542642 |
| k-d_tree_pandas      |     0.622332 |       0.496184 |   0.730855 |
| k-d_tree_sklearn     |     0.617631 |       1.17293  |   0.800043 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610359 |       0.729986 |   0.474317 |
| Bori_Aron_solution-1 |     0.618009 |       1.41552  |   0.578241 |
| k-d_tree_polars      |     0.636609 |       0.857867 |   0.89479  |
| k-d_tree_sklearn     |     0.636976 |       2.03964  |   0.898774 |
| barab-szabi-1        |     0.634008 |       0.881968 |   0.936747 |
| k-d_tree_pandas      |     0.619606 |       0.752278 |   1.18663  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627276 |        5.41866 |   0.716062 |
| Bori_Aron_solution-1 |     0.619766 |       10.6389  |   0.836318 |
| k-d_tree_sklearn     |     0.632161 |       16.4076  |   0.989833 |
| k-d_tree_polars      |     0.619568 |        4.88127 |   6.58902  |
| barab-szabi-1        |     0.62034  |        4.92741 |   6.69262  |
| k-d_tree_pandas      |     0.621372 |        3.91726 |   6.95599  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.633415 |        71.8657 |    2.85192 |
| k-d_tree_sklearn     |     0.669894 |       231.785  |    3.81323 |
| Bori_Aron_solution-1 |     0.703792 |       158.738  |   18.6909  |