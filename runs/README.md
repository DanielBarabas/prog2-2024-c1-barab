# 2025-08-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542899 |       0.433314 |   0.437697 |
| k-d_tree_polars      |     0.551428 |       0.420682 |   0.439024 |
| solution-1           |     8.04363  |       1e-06    |   0.444746 |
| barab-szabi-1        |     0.556327 |       0.43772  |   0.484592 |
| Bori_Aron_solution-1 |     0.554505 |       0.569602 |   0.560606 |
| k-d_tree_pandas      |     8.48484  |       0.434591 |   0.69029  |
| k-d_tree_sklearn     |     3.58075  |       1.08385  |   1.07167  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55499  |       0.438506 |   0.447954 |
| k-d_tree_polars      |     0.568906 |       0.439191 |   0.452909 |
| barab-szabi-1        |     0.566906 |       0.436215 |   0.4545   |
| Bori_Aron_solution-1 |     0.547822 |       0.580262 |   0.57445  |
| k-d_tree_pandas      |     0.560074 |       0.406365 |   0.587643 |
| k-d_tree_sklearn     |     0.557895 |       1.02358  |   1.12943  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565904 |       0.466583 |   0.461245 |
| k-d_tree_polars      |     0.557395 |       0.452833 |   0.469273 |
| barab-szabi-1        |     0.560991 |       0.471601 |   0.489476 |
| Bori_Aron_solution-1 |     0.551811 |       0.614035 |   0.574922 |
| k-d_tree_pandas      |     0.560323 |       0.427585 |   0.630225 |
| k-d_tree_sklearn     |     0.566963 |       1.0636   |   1.14152  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552124 |       0.509904 |   0.485761 |
| k-d_tree_polars      |     0.557122 |       0.564019 |   0.567437 |
| barab-szabi-1        |     0.556124 |       0.561468 |   0.572744 |
| Bori_Aron_solution-1 |     0.545708 |       0.787419 |   0.574117 |
| k-d_tree_pandas      |     0.56175  |       0.509783 |   0.754599 |
| k-d_tree_sklearn     |     0.554832 |       1.27193  |   1.16536  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556468 |       0.764134 |   0.514758 |
| Bori_Aron_solution-1 |     0.548868 |       1.45058  |   0.611813 |
| k-d_tree_polars      |     0.551575 |       0.907336 |   0.946301 |
| barab-szabi-1        |     0.569449 |       0.909446 |   0.986261 |
| k-d_tree_pandas      |     0.554472 |       0.774793 |   1.22525  |
| k-d_tree_sklearn     |     0.562833 |       2.14382  |   1.27405  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556289 |        5.75304 |   0.770701 |
| Bori_Aron_solution-1 |     0.55775  |       11.1351  |   0.871042 |
| k-d_tree_sklearn     |     0.555499 |       17.5073  |   1.37412  |
| barab-szabi-1        |     0.552368 |        5.09717 |   7.05492  |
| k-d_tree_polars      |     0.559382 |        5.10201 |   7.06042  |
| k-d_tree_pandas      |     0.553104 |        4.00555 |   7.42193  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553976 |        78.1168 |    2.90646 |
| k-d_tree_sklearn     |     0.575947 |       247.446  |    4.25045 |
| Bori_Aron_solution-1 |     0.620427 |       147.986  |   17.0454  |