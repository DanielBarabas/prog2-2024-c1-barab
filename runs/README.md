# 2025-01-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.590195 |       0.405216 |   0.409209 |
| barab-szabi-1        |     0.601613 |       0.415992 |   0.422338 |
| barab-szabi-2        |     8.2369   |       0.743714 |   0.42522  |
| solution-1           |     7.92757  |       1e-06    |   0.494198 |
| Bori_Aron_solution-1 |     0.592032 |       0.549242 |   0.552315 |
| k-d_tree_pandas      |     0.601506 |       0.390197 |   0.556274 |
| k-d_tree_sklearn     |     3.123    |       1.16488  |   1.03438  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.602272 |       0.42146  |   0.408273 |
| k-d_tree_polars      |     0.618959 |       0.415596 |   0.414756 |
| barab-szabi-1        |     0.611368 |       0.429575 |   0.419413 |
| Bori_Aron_solution-1 |     0.599947 |       0.575001 |   0.55544  |
| k-d_tree_pandas      |     0.615529 |       0.414708 |   0.579049 |
| k-d_tree_sklearn     |     0.599584 |       0.961835 |   1.08361  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.607896 |       0.4512   |   0.446706 |
| barab-szabi-2        |     0.605492 |       0.435451 |   0.447149 |
| k-d_tree_polars      |     0.610447 |       0.45387  |   0.454648 |
| Bori_Aron_solution-1 |     0.58833  |       0.59269  |   0.562252 |
| k-d_tree_pandas      |     0.602224 |       0.411523 |   0.603978 |
| k-d_tree_sklearn     |     0.618348 |       1.03643  |   1.08238  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.597049 |       0.493221 |   0.449562 |
| k-d_tree_polars      |     0.603867 |       0.562166 |   0.541258 |
| barab-szabi-1        |     0.597815 |       0.538843 |   0.549622 |
| Bori_Aron_solution-1 |     0.591175 |       0.750487 |   0.553595 |
| k-d_tree_pandas      |     0.595369 |       0.487197 |   0.730163 |
| k-d_tree_sklearn     |     0.593611 |       1.23016  |   1.12131  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590301 |       0.724194 |   0.482707 |
| Bori_Aron_solution-1 |     0.590691 |       1.3975   |   0.602462 |
| k-d_tree_polars      |     0.595922 |       0.87288  |   0.894468 |
| barab-szabi-1        |     0.594616 |       0.88981  |   0.974302 |
| k-d_tree_sklearn     |     0.595245 |       2.08738  |   1.23775  |
| k-d_tree_pandas      |     0.609299 |       0.774877 |   1.24321  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629332 |        5.55551 |   0.757916 |
| Bori_Aron_solution-1 |     0.58731  |       10.9672  |   0.884472 |
| k-d_tree_sklearn     |     0.62069  |       16.9357  |   1.36175  |
| barab-szabi-1        |     0.606829 |        4.93248 |   6.80734  |
| k-d_tree_polars      |     0.620196 |        4.92778 |   6.95097  |
| k-d_tree_pandas      |     0.596925 |        3.87299 |   7.26556  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.599733 |        75.5609 |    3.01025 |
| k-d_tree_sklearn     |     0.61063  |       230.829  |    4.48751 |
| Bori_Aron_solution-1 |     0.682818 |       143.386  |   19.1073  |