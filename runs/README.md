# 2024-10-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613801 |       0.381137 |   0.379558 |
| barab-szabi-1        |     0.622352 |       0.399182 |   0.40205  |
| k-d_tree_polars      |     0.620814 |       0.405426 |   0.402111 |
| solution-1           |     7.4281   |       1e-06    |   0.43453  |
| Bori_Aron_solution-1 |     0.620743 |       0.53282  |   0.532996 |
| k-d_tree_pandas      |     0.632943 |       0.409062 |   0.53877  |
| k-d_tree_sklearn     |    10.0038   |       1.20736  |   0.979279 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.627284 |       0.405647 |   0.388438 |
| barab-szabi-1        |     0.613567 |       0.401485 |   0.395979 |
| barab-szabi-2        |     0.623363 |       0.385008 |   0.419635 |
| Bori_Aron_solution-1 |     0.607137 |       0.528092 |   0.512971 |
| k-d_tree_pandas      |     0.618311 |       0.389349 |   0.540491 |
| k-d_tree_sklearn     |     0.637067 |       0.903382 |   0.963573 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61167  |       0.446736 |   0.394446 |
| k-d_tree_polars      |     0.623468 |       0.424273 |   0.413106 |
| barab-szabi-1        |     0.614061 |       0.427294 |   0.415853 |
| Bori_Aron_solution-1 |     0.614033 |       0.578194 |   0.529456 |
| k-d_tree_pandas      |     0.620982 |       0.42049  |   0.573247 |
| k-d_tree_sklearn     |     0.639411 |       0.922014 |   0.983093 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623806 |       0.472428 |   0.430457 |
| k-d_tree_polars      |     0.62969  |       0.546876 |   0.521511 |
| Bori_Aron_solution-1 |     0.603172 |       0.741704 |   0.524335 |
| barab-szabi-1        |     0.624722 |       0.548305 |   0.527385 |
| k-d_tree_pandas      |     0.609945 |       0.472834 |   0.703238 |
| k-d_tree_sklearn     |     0.625632 |       1.18834  |   1.06922  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614407 |       0.723188 |   0.462334 |
| Bori_Aron_solution-1 |     0.604712 |       1.37472  |   0.560724 |
| k-d_tree_polars      |     0.615847 |       0.84645  |   0.866001 |
| barab-szabi-1        |     0.61722  |       0.856547 |   0.905683 |
| k-d_tree_sklearn     |     0.621714 |       1.95179  |   1.12572  |
| k-d_tree_pandas      |     0.6092   |       0.754226 |   1.13834  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610684 |        5.21983 |   0.728865 |
| Bori_Aron_solution-1 |     0.606786 |       10.6499  |   0.824254 |
| k-d_tree_sklearn     |     0.616266 |       15.5965  |   1.23511  |
| k-d_tree_polars      |     0.611463 |        4.84765 |   6.32053  |
| barab-szabi-1        |     0.628719 |        4.81216 |   6.4014   |
| k-d_tree_pandas      |     0.617969 |        3.90319 |   7.03216  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.639156 |         70.525 |    2.89606 |
| k-d_tree_sklearn     |     0.638878 |        234.946 |    4.25186 |
| Bori_Aron_solution-1 |     0.648271 |        140.071 |   18.4017  |