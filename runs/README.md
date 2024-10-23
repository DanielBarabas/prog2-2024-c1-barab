# 2024-10-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.636769 |       0.409227 |   0.400018 |
| barab-szabi-1        |     0.641981 |       0.409782 |   0.403801 |
| barab-szabi-2        |     0.669756 |       0.400298 |   0.413754 |
| solution-1           |     7.71969  |       1e-06    |   0.457551 |
| Bori_Aron_solution-1 |     0.628419 |       0.542501 |   0.543117 |
| k-d_tree_pandas      |     0.629038 |       0.396245 |   0.553738 |
| k-d_tree_sklearn     |    10.4587   |       1.10711  |   0.996675 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.630594 |       0.404314 |   0.404569 |
| k-d_tree_polars      |     0.631071 |       0.420113 |   0.406202 |
| barab-szabi-1        |     0.661597 |       0.416262 |   0.406515 |
| Bori_Aron_solution-1 |     0.628294 |       0.553464 |   0.522094 |
| k-d_tree_pandas      |     0.633358 |       0.39838  |   0.548103 |
| k-d_tree_sklearn     |     0.641783 |       0.953376 |   0.994183 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.637806 |       0.443092 |   0.425712 |
| barab-szabi-1        |     0.638802 |       0.443548 |   0.434157 |
| barab-szabi-2        |     0.649813 |       0.419592 |   0.446377 |
| Bori_Aron_solution-1 |     0.62176  |       0.581443 |   0.541367 |
| k-d_tree_pandas      |     0.635302 |       0.417706 |   0.612386 |
| k-d_tree_sklearn     |     0.634713 |       0.978218 |   1.02625  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626643 |       0.477198 |   0.445188 |
| k-d_tree_polars      |     0.650782 |       0.538665 |   0.52062  |
| barab-szabi-1        |     0.639076 |       0.535397 |   0.529851 |
| Bori_Aron_solution-1 |     0.615695 |       0.753566 |   0.544746 |
| k-d_tree_pandas      |     0.632595 |       0.481969 |   0.70561  |
| k-d_tree_sklearn     |     0.640113 |       1.19486  |   1.09007  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.638953 |       0.729463 |   0.486735 |
| Bori_Aron_solution-1 |     0.609859 |       1.41385  |   0.587323 |
| k-d_tree_polars      |     0.621319 |       0.854993 |   0.893438 |
| barab-szabi-1        |     0.612861 |       0.858915 |   0.920432 |
| k-d_tree_pandas      |     0.635608 |       0.749512 |   1.13662  |
| k-d_tree_sklearn     |     0.630483 |       1.97744  |   1.14013  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613373 |        5.37258 |   0.734087 |
| Bori_Aron_solution-1 |     0.618571 |       10.695   |   0.804861 |
| k-d_tree_sklearn     |     0.618148 |       16.162   |   1.23961  |
| k-d_tree_polars      |     0.613898 |        4.83419 |   6.53105  |
| barab-szabi-1        |     0.613972 |        4.83675 |   6.62787  |
| k-d_tree_pandas      |     0.613568 |        3.90604 |   6.96883  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634036 |        73.0094 |    3.00223 |
| k-d_tree_sklearn     |     0.618437 |       236.155  |    4.16466 |
| Bori_Aron_solution-1 |     0.63488  |       153.951  |   14.781   |