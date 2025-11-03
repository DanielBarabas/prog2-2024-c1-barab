# 2025-11-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.97255  |       0.740371 |   0.434649 |
| k-d_tree_polars      |     0.530783 |       0.408387 |   0.436571 |
| barab-szabi-1        |     0.660297 |       0.409919 |   0.438881 |
| Bori_Aron_solution-1 |     0.520273 |       0.552565 |   0.547313 |
| k-d_tree_pandas      |    11.2915   |       0.460107 |   0.889616 |
| solution-1           |     8.96588  |       1e-06    |   0.957625 |
| k-d_tree_sklearn     |     3.72189  |       1.29264  |   1.0686   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.549542 |       0.415831 |   0.437812 |
| barab-szabi-2        |     0.533192 |       0.433265 |   0.439225 |
| barab-szabi-1        |     0.534062 |       0.413371 |   0.439584 |
| Bori_Aron_solution-1 |     0.524398 |       0.57151  |   0.562035 |
| k-d_tree_pandas      |     0.531273 |       0.394895 |   0.565127 |
| k-d_tree_sklearn     |     0.536135 |       0.971244 |   1.07523  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525166 |       0.442284 |   0.45171  |
| k-d_tree_polars      |     0.52978  |       0.448977 |   0.462419 |
| barab-szabi-1        |     0.52831  |       0.4433   |   0.465807 |
| Bori_Aron_solution-1 |     0.522476 |       0.601491 |   0.550555 |
| k-d_tree_pandas      |     0.538426 |       0.427335 |   0.598455 |
| k-d_tree_sklearn     |     0.534145 |       1.03697  |   1.09684  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531711 |       0.499453 |   0.478746 |
| k-d_tree_polars      |     0.52979  |       0.562648 |   0.564716 |
| Bori_Aron_solution-1 |     0.51971  |       0.780327 |   0.569362 |
| barab-szabi-1        |     0.530823 |       0.557871 |   0.569955 |
| k-d_tree_pandas      |     0.528194 |       0.509769 |   0.745547 |
| k-d_tree_sklearn     |     0.536988 |       1.25628  |   1.15672  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529172 |       0.750776 |   0.507674 |
| Bori_Aron_solution-1 |     0.530321 |       1.49542  |   0.605108 |
| k-d_tree_polars      |     0.539417 |       0.935486 |   0.930925 |
| barab-szabi-1        |     0.536498 |       0.947221 |   0.993406 |
| k-d_tree_pandas      |     0.529637 |       0.804469 |   1.18768  |
| k-d_tree_sklearn     |     0.540629 |       2.17949  |   1.23548  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539384 |        5.3923  |   0.78148  |
| Bori_Aron_solution-1 |     0.524606 |       11.5405  |   0.865891 |
| k-d_tree_sklearn     |     0.535983 |       17.5439  |   1.34855  |
| k-d_tree_polars      |     0.530694 |        5.53368 |   6.76816  |
| barab-szabi-1        |     0.535462 |        5.45778 |   6.90178  |
| k-d_tree_pandas      |     0.531697 |        4.56986 |   7.2312   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539003 |        86.9944 |    3.34226 |
| k-d_tree_sklearn     |     0.564538 |       245.28   |    4.23634 |
| Bori_Aron_solution-1 |     0.757005 |       156.774  |   16.8621  |