# 2025-11-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533803 |       0.510956 |   0.445982 |
| k-d_tree_polars      |     0.550754 |       0.429142 |   0.447342 |
| barab-szabi-1        |     0.548478 |       0.427852 |   0.455171 |
| solution-1           |     8.8333   |       1e-06    |   0.456768 |
| Bori_Aron_solution-1 |     0.54825  |       0.583942 |   0.588488 |
| k-d_tree_pandas      |     9.1173   |       0.441897 |   0.661546 |
| k-d_tree_sklearn     |     3.90156  |       1.15016  |   1.1449   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546432 |       0.444161 |   0.444044 |
| barab-szabi-1        |     0.548588 |       0.440906 |   0.456261 |
| k-d_tree_polars      |     0.555557 |       0.42875  |   0.456317 |
| Bori_Aron_solution-1 |     0.536514 |       0.58324  |   0.576722 |
| k-d_tree_pandas      |     0.554827 |       0.417531 |   0.603806 |
| k-d_tree_sklearn     |     0.551614 |       1.05826  |   1.14982  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56205  |       0.458297 |   0.463654 |
| barab-szabi-1        |     0.546335 |       0.453582 |   0.480324 |
| k-d_tree_polars      |     0.552983 |       0.45572  |   0.484332 |
| Bori_Aron_solution-1 |     0.546195 |       0.638993 |   0.577473 |
| k-d_tree_pandas      |     0.555724 |       0.429135 |   0.6307   |
| k-d_tree_sklearn     |     0.548311 |       1.0542   |   1.17822  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579288 |       0.522667 |   0.506349 |
| k-d_tree_polars      |     0.550395 |       0.583428 |   0.578837 |
| Bori_Aron_solution-1 |     0.53934  |       0.806347 |   0.586273 |
| barab-szabi-1        |     0.556295 |       0.593293 |   0.593431 |
| k-d_tree_pandas      |     0.550558 |       0.53366  |   0.769717 |
| k-d_tree_sklearn     |     0.572487 |       1.34416  |   1.20857  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547048 |       0.80153  |   0.547475 |
| Bori_Aron_solution-1 |     0.551116 |       1.51144  |   0.613218 |
| k-d_tree_polars      |     0.548293 |       0.956077 |   0.949471 |
| barab-szabi-1        |     0.552496 |       0.961757 |   0.986891 |
| k-d_tree_pandas      |     0.569282 |       0.840304 |   1.21599  |
| k-d_tree_sklearn     |     0.549117 |       2.22379  |   1.26343  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555345 |        5.79723 |   0.793451 |
| Bori_Aron_solution-1 |     0.548354 |       11.7211  |   0.885066 |
| k-d_tree_sklearn     |     0.569594 |       18.1263  |   1.40842  |
| k-d_tree_polars      |     0.573948 |        5.50396 |   7.07402  |
| barab-szabi-1        |     0.552663 |        5.15512 |   7.26826  |
| k-d_tree_pandas      |     0.550401 |        4.50072 |   7.59231  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56434  |        82.0627 |    2.83979 |
| k-d_tree_sklearn     |     0.579886 |       245.327  |    4.27218 |
| Bori_Aron_solution-1 |     0.806839 |       155.751  |   17.1559  |