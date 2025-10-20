# 2025-10-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.563959 |       0.412905 |   0.438463 |
| barab-szabi-2        |     0.579856 |       0.454262 |   0.44441  |
| Bori_Aron_solution-1 |     0.989728 |       0.566608 |   0.557859 |
| solution-1           |     8.0877   |       1e-06    |   0.645341 |
| barab-szabi-1        |     0.839488 |       0.436812 |   0.670109 |
| k-d_tree_pandas      |    11.9091   |       0.470951 |   0.774244 |
| k-d_tree_sklearn     |     3.14169  |       1.2499   |   1.1098   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566178 |       0.435877 |   0.434058 |
| barab-szabi-1        |     0.568599 |       0.432455 |   0.451203 |
| k-d_tree_polars      |     0.56855  |       0.425051 |   0.451933 |
| k-d_tree_pandas      |     0.562    |       0.40443  |   0.582521 |
| Bori_Aron_solution-1 |     0.554776 |       0.570696 |   0.596697 |
| k-d_tree_sklearn     |     0.567437 |       1.00888  |   1.11849  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559079 |       0.44609  |   0.454099 |
| k-d_tree_polars      |     0.563711 |       0.456937 |   0.476083 |
| barab-szabi-1        |     0.565881 |       0.453018 |   0.479747 |
| Bori_Aron_solution-1 |     0.554227 |       0.609008 |   0.577015 |
| k-d_tree_pandas      |     0.562376 |       0.425126 |   0.622206 |
| k-d_tree_sklearn     |     0.568837 |       1.0575   |   1.13543  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561773 |       0.514135 |   0.477321 |
| Bori_Aron_solution-1 |     0.55847  |       0.797267 |   0.566409 |
| k-d_tree_polars      |     0.56113  |       0.577781 |   0.573532 |
| barab-szabi-1        |     0.56134  |       0.581398 |   0.574487 |
| k-d_tree_pandas      |     0.557165 |       0.511958 |   0.754213 |
| k-d_tree_sklearn     |     0.562886 |       1.29875  |   1.19476  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556031 |       0.774709 |   0.514916 |
| Bori_Aron_solution-1 |     0.564165 |       1.49453  |   0.600163 |
| k-d_tree_polars      |     0.562758 |       0.959998 |   0.937544 |
| barab-szabi-1        |     0.559143 |       0.952791 |   0.979371 |
| k-d_tree_pandas      |     0.566187 |       0.821846 |   1.21504  |
| k-d_tree_sklearn     |     0.566429 |       2.17771  |   1.24867  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55986  |        5.58299 |   0.815452 |
| Bori_Aron_solution-1 |     0.558975 |       11.465   |   0.834269 |
| k-d_tree_sklearn     |     0.563189 |       17.7151  |   1.3744   |
| barab-szabi-1        |     0.560482 |        5.55442 |   6.91004  |
| k-d_tree_polars      |     0.551014 |        5.59321 |   7.10281  |
| k-d_tree_pandas      |     0.556163 |        4.49446 |   7.50136  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.725947 |         73.203 |    2.70082 |
| k-d_tree_sklearn     |     1.12228  |        239.144 |    4.11521 |
| Bori_Aron_solution-1 |     0.55581  |        156.724 |   13.3356  |