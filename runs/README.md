# 2024-08-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.632578 |       0.420705 |   0.39871  |
| barab-szabi-1        |     0.622928 |       0.420491 |   0.415373 |
| barab-szabi-2        |     8.12801  |       0.634503 |   0.418872 |
| Bori_Aron_solution-1 |     0.633069 |       0.54897  |   0.554986 |
| solution-1           |     7.82488  |       1e-06    |   0.573601 |
| k-d_tree_pandas      |     0.633482 |       0.459052 |   0.584843 |
| k-d_tree_sklearn     |     3.00624  |       1.13914  |   0.744364 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.637469 |       0.407646 |   0.40122  |
| barab-szabi-1        |     0.644171 |       0.427814 |   0.410843 |
| k-d_tree_polars      |     0.661389 |       0.445793 |   0.417446 |
| Bori_Aron_solution-1 |     0.624085 |       0.559619 |   0.545392 |
| k-d_tree_pandas      |     0.630604 |       0.395788 |   0.589466 |
| k-d_tree_sklearn     |     0.641221 |       0.924879 |   0.724211 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.63329  |       0.439172 |   0.425976 |
| barab-szabi-2        |     0.633259 |       0.421123 |   0.429881 |
| barab-szabi-1        |     0.650757 |       0.446361 |   0.436053 |
| Bori_Aron_solution-1 |     0.622338 |       0.59805  |   0.561946 |
| k-d_tree_pandas      |     0.620586 |       0.428075 |   0.608238 |
| k-d_tree_sklearn     |     0.623587 |       0.989768 |   0.775578 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620582 |       0.486357 |   0.445368 |
| k-d_tree_polars      |     0.6112   |       0.534836 |   0.51795  |
| barab-szabi-1        |     0.612717 |       0.539743 |   0.529998 |
| Bori_Aron_solution-1 |     0.616027 |       0.749872 |   0.545944 |
| k-d_tree_pandas      |     0.62288  |       0.515513 |   0.720192 |
| k-d_tree_sklearn     |     0.615909 |       1.17932  |   0.806074 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61803  |       0.718844 |   0.46385  |
| Bori_Aron_solution-1 |     0.607895 |       1.40039  |   0.570436 |
| k-d_tree_sklearn     |     0.61147  |       1.99197  |   0.875493 |
| k-d_tree_polars      |     0.619598 |       0.867336 |   0.902223 |
| barab-szabi-1        |     0.622651 |       0.89156  |   0.9088   |
| k-d_tree_pandas      |     0.607946 |       0.755607 |   1.19038  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611888 |        5.56366 |   0.757631 |
| Bori_Aron_solution-1 |     0.609956 |       10.7961  |   0.818979 |
| k-d_tree_sklearn     |     0.626198 |       16.5634  |   1.00392  |
| k-d_tree_polars      |     0.617969 |        4.85756 |   6.73945  |
| barab-szabi-1        |     0.616722 |        4.83647 |   6.91615  |
| k-d_tree_pandas      |     0.611548 |        3.88084 |   7.09623  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604045 |         76.04  |    3.21743 |
| k-d_tree_sklearn     |     0.660425 |        240.225 |    4.05861 |
| Bori_Aron_solution-1 |     0.728891 |        153.809 |   17.0307  |