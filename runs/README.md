# 2025-11-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47422  |       0.563733 |   0.408719 |
| k-d_tree_polars      |     0.482819 |       0.38423  |   0.413948 |
| barab-szabi-1        |     0.47522  |       0.420912 |   0.416432 |
| solution-1           |     7.53952  |       1e-06    |   0.476586 |
| Bori_Aron_solution-1 |     0.487806 |       0.527733 |   0.515394 |
| k-d_tree_pandas      |     8.41195  |       0.401693 |   0.728362 |
| k-d_tree_sklearn     |     2.83533  |       1.08076  |   0.996523 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.483891 |       0.401628 |   0.417644 |
| barab-szabi-1        |     0.481806 |       0.390544 |   0.418987 |
| barab-szabi-2        |     0.484456 |       0.407749 |   0.421606 |
| Bori_Aron_solution-1 |     0.470497 |       0.521699 |   0.51669  |
| k-d_tree_pandas      |     0.484608 |       0.376938 |   0.537784 |
| k-d_tree_sklearn     |     0.491189 |       0.921424 |   0.99456  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478908 |       0.420742 |   0.431044 |
| barab-szabi-1        |     0.476134 |       0.4133   |   0.4411   |
| k-d_tree_polars      |     0.482791 |       0.446349 |   0.449048 |
| Bori_Aron_solution-1 |     0.484771 |       0.567128 |   0.51982  |
| k-d_tree_pandas      |     0.481363 |       0.384762 |   0.557075 |
| k-d_tree_sklearn     |     0.484047 |       0.951335 |   0.999188 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480681 |       0.491522 |   0.458703 |
| k-d_tree_polars      |     0.477655 |       0.530354 |   0.525753 |
| Bori_Aron_solution-1 |     0.474635 |       0.711323 |   0.527792 |
| barab-szabi-1        |     0.475937 |       0.532081 |   0.530045 |
| k-d_tree_pandas      |     0.483612 |       0.469675 |   0.676269 |
| k-d_tree_sklearn     |     0.494595 |       1.18226  |   1.06116  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48454  |       0.721204 |   0.480454 |
| Bori_Aron_solution-1 |     0.468981 |       1.31105  |   0.562226 |
| k-d_tree_polars      |     0.482752 |       0.945155 |   0.842901 |
| barab-szabi-1        |     0.484038 |       0.8563   |   0.873034 |
| k-d_tree_pandas      |     0.477872 |       0.739635 |   1.08394  |
| k-d_tree_sklearn     |     0.482162 |       1.98601  |   1.12646  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484487 |        5.00299 |   0.706405 |
| Bori_Aron_solution-1 |     0.478209 |       10.1643  |   0.92786  |
| k-d_tree_sklearn     |     0.489086 |       14.5126  |   1.28936  |
| k-d_tree_polars      |     0.486578 |        4.90852 |   6.15903  |
| barab-szabi-1        |     0.487249 |        4.92757 |   6.21321  |
| k-d_tree_pandas      |     0.4852   |        3.83936 |   6.49582  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488548 |        82.3194 |    2.74223 |
| k-d_tree_sklearn     |     0.500077 |       178.971  |    4.49293 |
| Bori_Aron_solution-1 |     0.695588 |       138.219  |   15.9664  |