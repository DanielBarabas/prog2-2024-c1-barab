# 2025-11-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.523515 |       0.522183 |   0.425142 |
| barab-szabi-1        |     0.528958 |       0.401592 |   0.428092 |
| k-d_tree_polars      |     0.530044 |       0.400114 |   0.431336 |
| solution-1           |     8.80592  |       1e-06    |   0.482678 |
| Bori_Aron_solution-1 |     0.51966  |       0.551637 |   0.550271 |
| k-d_tree_pandas      |     9.67241  |       0.413588 |   0.670988 |
| k-d_tree_sklearn     |     3.32629  |       1.30317  |   1.06802  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.52812  |       0.41121  |   0.432455 |
| barab-szabi-2        |     0.528073 |       0.429437 |   0.433073 |
| k-d_tree_polars      |     0.528365 |       0.409024 |   0.440594 |
| k-d_tree_pandas      |     0.527609 |       0.40162  |   0.554022 |
| Bori_Aron_solution-1 |     0.521229 |       0.557385 |   0.562889 |
| k-d_tree_sklearn     |     0.534468 |       0.975925 |   1.06362  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528588 |       0.435249 |   0.439274 |
| k-d_tree_polars      |     0.536464 |       0.439348 |   0.45977  |
| barab-szabi-1        |     0.530121 |       0.435581 |   0.470662 |
| Bori_Aron_solution-1 |     0.526949 |       0.605869 |   0.555032 |
| k-d_tree_pandas      |     0.535746 |       0.41421  |   0.606261 |
| k-d_tree_sklearn     |     0.535233 |       1.03117  |   1.09776  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528234 |       0.500358 |   0.470356 |
| k-d_tree_polars      |     0.52853  |       0.54954  |   0.559308 |
| Bori_Aron_solution-1 |     0.51844  |       0.787471 |   0.565121 |
| barab-szabi-1        |     0.528369 |       0.559075 |   0.571756 |
| k-d_tree_pandas      |     0.534642 |       0.505821 |   0.735095 |
| k-d_tree_sklearn     |     0.538359 |       1.25175  |   1.13056  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527217 |       0.746303 |   0.507276 |
| Bori_Aron_solution-1 |     0.524405 |       1.45721  |   0.588555 |
| k-d_tree_polars      |     0.531306 |       0.920395 |   0.903508 |
| barab-szabi-1        |     0.531142 |       0.907332 |   0.953601 |
| k-d_tree_pandas      |     0.52775  |       0.826234 |   1.17455  |
| k-d_tree_sklearn     |     0.52937  |       2.11075  |   1.21593  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528383 |        5.29353 |   0.744223 |
| Bori_Aron_solution-1 |     0.521051 |       11.1607  |   0.843143 |
| k-d_tree_sklearn     |     0.533377 |       16.6446  |   1.33044  |
| k-d_tree_polars      |     0.533294 |        5.38117 |   6.55972  |
| barab-szabi-1        |     0.539399 |        5.41059 |   6.62528  |
| k-d_tree_pandas      |     0.53161  |        4.41961 |   7.03988  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532267 |        75.8685 |    2.69024 |
| k-d_tree_sklearn     |     0.537753 |       231.485  |    4.10448 |
| Bori_Aron_solution-1 |     0.638823 |       148.816  |   16.7163  |