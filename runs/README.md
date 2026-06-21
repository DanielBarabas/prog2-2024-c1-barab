# 2026-06-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.81405  |       0.779821 |   0.433486 |
| barab-szabi-1        |     0.472928 |       0.406736 |   0.440861 |
| k-d_tree_polars      |     0.472109 |       0.42202  |   0.444542 |
| solution-1           |     8.17586  |       1e-06    |   0.505387 |
| Bori_Aron_solution-1 |     0.475913 |       0.553959 |   0.565453 |
| k-d_tree_pandas      |     0.482215 |       0.398009 |   0.576132 |
| k-d_tree_sklearn     |     3.24969  |       1.14899  |   1.11986  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.473373 |       0.419632 |   0.44332  |
| barab-szabi-2        |     0.470551 |       0.432591 |   0.443414 |
| k-d_tree_polars      |     0.47792  |       0.425129 |   0.463576 |
| Bori_Aron_solution-1 |     0.46526  |       0.575347 |   0.55002  |
| k-d_tree_pandas      |     0.500552 |       0.418902 |   0.599549 |
| k-d_tree_sklearn     |     0.491024 |       1.0252   |   1.13119  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491161 |       0.46545  |   0.454288 |
| k-d_tree_polars      |     0.478478 |       0.447552 |   0.464799 |
| barab-szabi-1        |     0.499551 |       0.454453 |   0.469725 |
| Bori_Aron_solution-1 |     0.46133  |       0.631133 |   0.563555 |
| k-d_tree_pandas      |     0.487443 |       0.418728 |   0.591067 |
| k-d_tree_sklearn     |     0.48033  |       1.0977   |   1.15469  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466947 |       0.515004 |   0.478072 |
| k-d_tree_polars      |     0.475724 |       0.561396 |   0.578375 |
| Bori_Aron_solution-1 |     0.465515 |       0.785837 |   0.57884  |
| barab-szabi-1        |     0.470929 |       0.565173 |   0.591521 |
| k-d_tree_pandas      |     0.471962 |       0.506189 |   0.73196  |
| k-d_tree_sklearn     |     0.477385 |       1.26429  |   1.17577  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476217 |       0.790056 |   0.556509 |
| Bori_Aron_solution-1 |     0.457942 |       1.5207   |   0.605695 |
| barab-szabi-1        |     0.482773 |       0.923365 |   0.996698 |
| k-d_tree_polars      |     0.480459 |       0.934241 |   1.01362  |
| k-d_tree_sklearn     |     0.507862 |       2.17204  |   1.18055  |
| k-d_tree_pandas      |     0.471978 |       0.792754 |   1.19562  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470103 |        5.48936 |   0.726095 |
| Bori_Aron_solution-1 |     0.458439 |       11.364   |   0.829226 |
| k-d_tree_sklearn     |     0.467023 |       17.5236  |   1.26105  |
| k-d_tree_polars      |     0.473676 |        5.26299 |   7.28275  |
| barab-szabi-1        |     0.463377 |        5.26777 |   7.40103  |
| k-d_tree_pandas      |     0.473827 |        4.22224 |   7.93459  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485414 |        80.4264 |    2.59019 |
| k-d_tree_sklearn     |     0.709115 |       264.581  |    3.41959 |
| Bori_Aron_solution-1 |     0.491886 |       163.749  |   15.6659  |