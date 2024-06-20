# 2024-06-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.795439 |       0.40482  |   0.392385 |
| barab-szabi-2        |     0.761896 |       0.392729 |   0.397207 |
| k-d_tree_polars      |     0.771275 |       0.418312 |   0.408477 |
| Bori_Aron_solution-1 |     0.759191 |       0.519142 |   0.517245 |
| solution-1           |    11.1694   |       1e-06    |   0.527202 |
| k-d_tree_sklearn     |     6.64909  |       1.17641  |   0.729757 |
| k-d_tree_pandas      |     9.13154  |       0.414099 |   0.806058 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.818647 |       0.40567  |   0.395679 |
| barab-szabi-2        |     0.806871 |       0.392199 |   0.4045   |
| barab-szabi-1        |     0.814723 |       0.431131 |   0.406991 |
| k-d_tree_pandas      |     0.807932 |       0.389027 |   0.534566 |
| Bori_Aron_solution-1 |     0.794992 |       0.575915 |   0.535823 |
| k-d_tree_sklearn     |     0.816125 |       0.930866 |   0.757381 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.810972 |       0.403927 |   0.412299 |
| k-d_tree_polars      |     0.816118 |       0.470923 |   0.423204 |
| barab-szabi-1        |     0.80586  |       0.432556 |   0.431012 |
| Bori_Aron_solution-1 |     0.801058 |       0.568523 |   0.529766 |
| k-d_tree_pandas      |     0.812704 |       0.403868 |   0.574347 |
| k-d_tree_sklearn     |     0.820184 |       0.990377 |   0.770754 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.818478 |       0.471634 |   0.445912 |
| k-d_tree_polars      |     0.81824  |       0.553917 |   0.539409 |
| barab-szabi-1        |     0.817996 |       0.541635 |   0.544752 |
| Bori_Aron_solution-1 |     0.814814 |       0.766662 |   0.558789 |
| k-d_tree_pandas      |     0.807378 |       0.496276 |   0.724316 |
| k-d_tree_sklearn     |     0.823501 |       1.20395  |   0.843709 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.826655 |       0.734286 |   0.474134 |
| Bori_Aron_solution-1 |     0.821466 |       1.48587  |   0.594333 |
| k-d_tree_polars      |     0.813194 |       0.886063 |   0.901136 |
| k-d_tree_sklearn     |     0.820905 |       2.11575  |   0.955978 |
| barab-szabi-1        |     0.831395 |       0.89758  |   0.959601 |
| k-d_tree_pandas      |     0.809929 |       0.761443 |   1.16016  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.826575 |        5.67731 |   0.812488 |
| Bori_Aron_solution-1 |     0.812517 |       11.5238  |   0.913837 |
| k-d_tree_sklearn     |     0.830672 |       18.1625  |   1.15008  |
| k-d_tree_polars      |     0.831141 |        5.06456 |   7.17221  |
| barab-szabi-1        |     0.838045 |        5.11497 |   7.20786  |
| k-d_tree_pandas      |     0.829395 |        4.03581 |   7.55491  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.13504  |         77.79  |    4.1872  |
| k-d_tree_sklearn     |     0.977323 |        243.291 |    4.57171 |
| Bori_Aron_solution-1 |     0.834929 |        153.802 |   17.4431  |