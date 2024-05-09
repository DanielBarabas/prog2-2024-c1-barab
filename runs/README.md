# 2024-05-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.743195 |       0.420157 |   0.363404 |
| barab-szabi-2        |     0.722467 |       0.363285 |   0.364832 |
| barab-szabi-1        |     8.85765  |       0.449362 |   0.368388 |
| solution-1           |     8.52542  |       1e-06    |   0.383155 |
| k-d_tree_pandas      |     0.73297  |       0.409439 |   0.499444 |
| Bori_Aron_solution-1 |     0.726642 |       0.51044  |   0.510468 |
| k-d_tree_sklearn     |     3.44454  |       0.943959 |   0.691928 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.761643 |       0.366059 |   0.353619 |
| barab-szabi-1        |     0.765486 |       0.425406 |   0.367115 |
| k-d_tree_polars      |     0.758786 |       0.434167 |   0.368881 |
| k-d_tree_pandas      |     0.759098 |       0.402532 |   0.496111 |
| Bori_Aron_solution-1 |     0.745975 |       0.509173 |   0.506441 |
| k-d_tree_sklearn     |     0.793071 |       0.881207 |   0.700474 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.776147 |       0.381877 |   0.373019 |
| k-d_tree_polars      |     0.757769 |       0.444005 |   0.3924   |
| barab-szabi-1        |     0.762056 |       0.446595 |   0.393914 |
| Bori_Aron_solution-1 |     0.744585 |       0.545596 |   0.500115 |
| k-d_tree_pandas      |     0.795002 |       0.418252 |   0.544172 |
| k-d_tree_sklearn     |     0.775596 |       0.937974 |   0.744619 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.766394 |       0.447839 |   0.417607 |
| k-d_tree_polars      |     0.772249 |       0.569057 |   0.495905 |
| barab-szabi-1        |     0.744521 |       0.565285 |   0.502887 |
| Bori_Aron_solution-1 |     0.754993 |       0.728715 |   0.521693 |
| k-d_tree_pandas      |     0.774084 |       0.509582 |   0.687084 |
| k-d_tree_sklearn     |     0.761837 |       1.16678  |   0.79935  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.760215 |       0.698693 |   0.453679 |
| Bori_Aron_solution-1 |     0.756368 |       1.41616  |   0.534048 |
| k-d_tree_polars      |     0.754936 |       0.887394 |   0.863198 |
| k-d_tree_sklearn     |     0.760458 |       2.03431  |   0.881299 |
| barab-szabi-1        |     0.752595 |       0.868822 |   0.919569 |
| k-d_tree_pandas      |     0.752846 |       0.778322 |   1.1374   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.755656 |        5.46422 |   0.746703 |
| Bori_Aron_solution-1 |     0.750655 |       10.813   |   0.791887 |
| k-d_tree_sklearn     |     0.778926 |       16.9427  |   1.08649  |
| k-d_tree_polars      |     0.754317 |        4.87625 |   6.83608  |
| barab-szabi-1        |     0.753711 |        4.90045 |   6.94196  |
| k-d_tree_pandas      |     0.753139 |        3.88735 |   7.04099  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.05998  |        78.2238 |    4.03977 |
| k-d_tree_sklearn     |     0.835377 |       252.128  |    4.92249 |
| Bori_Aron_solution-1 |     0.762999 |       149.649  |   18.5861  |