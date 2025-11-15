# 2025-11-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.534409 |       0.408238 |   0.432964 |
| k-d_tree_polars      |     0.531471 |       0.406083 |   0.436682 |
| barab-szabi-2        |     0.548006 |       0.584591 |   0.454155 |
| Bori_Aron_solution-1 |     0.518066 |       0.552314 |   0.560438 |
| solution-1           |     8.28229  |       1e-06    |   0.592232 |
| k-d_tree_pandas      |     8.89648  |       0.447955 |   0.751503 |
| k-d_tree_sklearn     |     3.20571  |       1.22682  |   1.08374  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535956 |       0.430252 |   0.432534 |
| k-d_tree_polars      |     0.540553 |       0.415801 |   0.440485 |
| barab-szabi-1        |     0.528611 |       0.415409 |   0.449947 |
| Bori_Aron_solution-1 |     0.538626 |       0.553718 |   0.544812 |
| k-d_tree_pandas      |     0.53572  |       0.393634 |   0.574038 |
| k-d_tree_sklearn     |     0.545838 |       0.975005 |   1.0745   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527326 |       0.438898 |   0.438382 |
| k-d_tree_polars      |     0.534145 |       0.439304 |   0.458277 |
| barab-szabi-1        |     0.530626 |       0.438514 |   0.460596 |
| Bori_Aron_solution-1 |     0.519758 |       0.599959 |   0.551121 |
| k-d_tree_pandas      |     0.580784 |       0.419338 |   0.605345 |
| k-d_tree_sklearn     |     0.532209 |       1.01377  |   1.09365  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.523638 |       0.51411  |   0.471191 |
| Bori_Aron_solution-1 |     0.52028  |       0.778026 |   0.560785 |
| k-d_tree_polars      |     0.527143 |       0.569142 |   0.564061 |
| barab-szabi-1        |     0.527156 |       0.553433 |   0.566437 |
| k-d_tree_pandas      |     0.528235 |       0.499433 |   0.733418 |
| k-d_tree_sklearn     |     0.530392 |       1.25676  |   1.14181  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525338 |       0.743884 |   0.502789 |
| Bori_Aron_solution-1 |     0.516604 |       1.45505  |   0.584689 |
| k-d_tree_polars      |     0.526161 |       0.93002  |   0.900641 |
| barab-szabi-1        |     0.534129 |       0.925235 |   0.937296 |
| k-d_tree_pandas      |     0.52518  |       0.814027 |   1.156    |
| k-d_tree_sklearn     |     0.530056 |       2.10819  |   1.21988  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.526911 |        5.50071 |   0.758604 |
| Bori_Aron_solution-1 |     0.519574 |       11.5864  |   0.854843 |
| k-d_tree_sklearn     |     0.5457   |       16.9989  |   1.3162   |
| barab-szabi-1        |     0.52713  |        5.52611 |   6.74048  |
| k-d_tree_polars      |     0.521808 |        5.4304  |   6.79008  |
| k-d_tree_pandas      |     0.529373 |        4.463   |   7.15355  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537477 |        77.9876 |    2.86429 |
| k-d_tree_sklearn     |     0.541056 |       239.454  |    4.16138 |
| Bori_Aron_solution-1 |     0.633287 |       149.93   |   17.8671  |