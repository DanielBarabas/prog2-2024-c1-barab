# 2024-09-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.52867  |       1e-06    |   0.351876 |
| barab-szabi-2        |     0.614944 |       0.383426 |   0.380745 |
| barab-szabi-1        |     0.598229 |       0.395525 |   0.386904 |
| k-d_tree_polars      |     0.601084 |       0.396019 |   0.392159 |
| Bori_Aron_solution-1 |     4.32154  |       0.524493 |   0.454052 |
| k-d_tree_pandas      |     4.19102  |       0.396243 |   0.521961 |
| k-d_tree_sklearn     |     2.96471  |       0.924491 |   0.9548   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614633 |       0.385285 |   0.38291  |
| k-d_tree_polars      |     0.608589 |       0.407113 |   0.391758 |
| barab-szabi-1        |     0.612795 |       0.406327 |   0.396996 |
| Bori_Aron_solution-1 |     0.605275 |       0.524318 |   0.521785 |
| k-d_tree_pandas      |     0.629168 |       0.381532 |   0.539374 |
| k-d_tree_sklearn     |     0.612785 |       0.901476 |   0.958633 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610128 |       0.400445 |   0.395589 |
| k-d_tree_polars      |     0.61136  |       0.429994 |   0.418517 |
| barab-szabi-1        |     0.612573 |       0.427777 |   0.421933 |
| Bori_Aron_solution-1 |     0.60048  |       0.566138 |   0.53088  |
| k-d_tree_pandas      |     0.614148 |       0.427003 |   0.575072 |
| k-d_tree_sklearn     |     0.616028 |       0.941411 |   0.987042 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.607109 |       0.461234 |   0.429743 |
| k-d_tree_polars      |     0.618732 |       0.534334 |   0.514569 |
| barab-szabi-1        |     0.611906 |       0.525194 |   0.521419 |
| Bori_Aron_solution-1 |     0.611725 |       0.740548 |   0.534474 |
| k-d_tree_pandas      |     0.610315 |       0.46447  |   0.706368 |
| k-d_tree_sklearn     |     0.612702 |       1.14187  |   1.05059  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60848  |       0.70509  |   0.465063 |
| Bori_Aron_solution-1 |     0.608429 |       1.38523  |   0.567238 |
| k-d_tree_polars      |     0.611853 |       0.834118 |   0.863537 |
| barab-szabi-1        |     0.608027 |       0.829781 |   0.905071 |
| k-d_tree_sklearn     |     0.617255 |       1.97684  |   1.1291   |
| k-d_tree_pandas      |     0.604411 |       0.741711 |   1.15193  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618562 |        5.31356 |   0.745634 |
| Bori_Aron_solution-1 |     0.598183 |       10.6019  |   0.814989 |
| k-d_tree_sklearn     |     0.616311 |       16.2143  |   1.27197  |
| k-d_tree_polars      |     0.615064 |        4.81417 |   6.62955  |
| barab-szabi-1        |     0.61194  |        4.83898 |   6.64417  |
| k-d_tree_pandas      |     0.618469 |        3.85896 |   6.94615  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.721032 |        75.2411 |    3.37924 |
| k-d_tree_sklearn     |     0.86613  |       232.775  |    4.35879 |
| Bori_Aron_solution-1 |     0.604755 |       157.887  |   16.4168  |