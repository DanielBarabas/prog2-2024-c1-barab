# 2025-02-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.27271  |       1e-06    |   0.355281 |
| barab-szabi-2        |     7.34585  |       0.464338 |   0.393322 |
| k-d_tree_polars      |     0.567529 |       0.398101 |   0.399103 |
| barab-szabi-1        |     0.586989 |       0.401365 |   0.406266 |
| k-d_tree_pandas      |     0.586303 |       0.381258 |   0.533601 |
| Bori_Aron_solution-1 |     0.576128 |       0.54354  |   0.534236 |
| k-d_tree_sklearn     |     2.87365  |       0.972008 |   1.00425  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583801 |       0.402683 |   0.401896 |
| barab-szabi-1        |     0.582034 |       0.406096 |   0.406981 |
| k-d_tree_polars      |     0.580754 |       0.405372 |   0.407229 |
| Bori_Aron_solution-1 |     0.581349 |       0.541226 |   0.528255 |
| k-d_tree_pandas      |     0.5813   |       0.388229 |   0.539111 |
| k-d_tree_sklearn     |     0.58686  |       1.03557  |   1.03122  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5831   |       0.415459 |   0.415296 |
| k-d_tree_polars      |     0.583064 |       0.432769 |   0.427621 |
| barab-szabi-1        |     0.58229  |       0.431725 |   0.436142 |
| Bori_Aron_solution-1 |     0.577608 |       0.576921 |   0.531548 |
| k-d_tree_pandas      |     0.585601 |       0.405329 |   0.579557 |
| k-d_tree_sklearn     |     0.582811 |       0.982305 |   1.04498  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580192 |       0.475473 |   0.437484 |
| k-d_tree_polars      |     0.579473 |       0.53838  |   0.526702 |
| barab-szabi-1        |     0.584476 |       0.534971 |   0.537499 |
| Bori_Aron_solution-1 |     0.574888 |       0.739304 |   0.540275 |
| k-d_tree_pandas      |     0.584295 |       0.475899 |   0.717832 |
| k-d_tree_sklearn     |     0.586513 |       1.20136  |   1.10356  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580244 |       0.719996 |   0.47787  |
| Bori_Aron_solution-1 |     0.577783 |       1.37479  |   0.574114 |
| k-d_tree_polars      |     0.583396 |       0.8666   |   0.873146 |
| barab-szabi-1        |     0.578448 |       0.867035 |   0.909805 |
| k-d_tree_pandas      |     0.583823 |       0.736064 |   1.14988  |
| k-d_tree_sklearn     |     0.584342 |       2.0135   |   1.18979  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58217  |        5.41506 |    0.74472 |
| Bori_Aron_solution-1 |     0.579667 |       10.6055  |    0.86096 |
| k-d_tree_sklearn     |     0.583089 |       16.1929  |    1.29573 |
| barab-szabi-1        |     0.582867 |        4.90218 |    6.68568 |
| k-d_tree_polars      |     0.584402 |        4.85266 |    6.68975 |
| k-d_tree_pandas      |     0.584693 |        3.84475 |    7.07313 |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579543 |        76.5761 |    3.01633 |
| k-d_tree_sklearn     |     0.590718 |       230.491  |    4.39778 |
| Bori_Aron_solution-1 |     0.618582 |       145.731  |   18.4338  |