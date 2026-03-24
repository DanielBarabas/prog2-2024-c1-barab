# 2026-03-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491255 |       0.443983 |   0.443003 |
| k-d_tree_polars      |     0.488037 |       0.415561 |   0.461812 |
| solution-1           |     7.89145  |       1e-06    |   0.461946 |
| Bori_Aron_solution-1 |     0.48801  |       0.549155 |   0.550332 |
| k-d_tree_pandas      |     0.485057 |       0.396882 |   0.552428 |
| barab-szabi-1        |     8.54595  |       0.464264 |   0.600429 |
| k-d_tree_sklearn     |     3.04435  |       1.08894  |   1.08202  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495135 |       0.448789 |   0.444836 |
| barab-szabi-1        |     0.495678 |       0.414508 |   0.446494 |
| k-d_tree_polars      |     0.496545 |       0.420629 |   0.453409 |
| Bori_Aron_solution-1 |     0.487454 |       0.565513 |   0.552771 |
| k-d_tree_pandas      |     0.495432 |       0.3992   |   0.561449 |
| k-d_tree_sklearn     |     0.501532 |       0.981034 |   1.11259  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.493124 |       0.454262 |   0.44928  |
| barab-szabi-1        |     0.496631 |       0.445163 |   0.47274  |
| k-d_tree_polars      |     0.495304 |       0.447904 |   0.477856 |
| Bori_Aron_solution-1 |     0.503855 |       0.608296 |   0.553128 |
| k-d_tree_pandas      |     0.496377 |       0.41959  |   0.613455 |
| k-d_tree_sklearn     |     0.496691 |       1.04537  |   1.11764  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.500224 |       0.519704 |   0.486807 |
| k-d_tree_polars      |     0.495374 |       0.568455 |   0.566014 |
| Bori_Aron_solution-1 |     0.493441 |       0.793247 |   0.577329 |
| barab-szabi-1        |     0.498905 |       0.580094 |   0.5874   |
| k-d_tree_pandas      |     0.498263 |       0.508595 |   0.741963 |
| k-d_tree_sklearn     |     0.498827 |       1.2941   |   1.15413  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492677 |       0.741855 |   0.508776 |
| Bori_Aron_solution-1 |     0.487445 |       1.47748  |   0.587085 |
| k-d_tree_polars      |     0.495447 |       0.943038 |   0.923374 |
| barab-szabi-1        |     0.496325 |       0.949406 |   0.977307 |
| k-d_tree_pandas      |     0.498015 |       0.856361 |   1.19343  |
| k-d_tree_sklearn     |     0.501875 |       2.17044  |   1.23425  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.518705 |        5.46476 |   0.774347 |
| Bori_Aron_solution-1 |     0.503794 |       11.729   |   0.850997 |
| k-d_tree_sklearn     |     0.505315 |       17.596   |   1.36269  |
| k-d_tree_polars      |     0.529698 |        5.62356 |   6.89374  |
| barab-szabi-1        |     0.506511 |        5.77262 |   7.00249  |
| k-d_tree_pandas      |     0.500607 |        4.61135 |   7.183    |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.506891 |        70.8898 |    2.74062 |
| k-d_tree_sklearn     |     0.753795 |       241.75   |    3.95263 |
| Bori_Aron_solution-1 |     0.496472 |       149.579  |   14.7187  |