# 2026-02-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.497144 |       0.52307  |   0.454341 |
| k-d_tree_polars      |     0.520321 |       0.436839 |   0.457121 |
| barab-szabi-1        |     0.515206 |       0.436476 |   0.458131 |
| solution-1           |     7.81301  |       1e-06    |   0.562596 |
| Bori_Aron_solution-1 |     0.502826 |       0.594498 |   0.582973 |
| k-d_tree_pandas      |    10.7515   |       0.458955 |   0.697345 |
| k-d_tree_sklearn     |     3.11278  |       1.16606  |   1.11275  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.516976 |       0.426482 |   0.45113  |
| barab-szabi-2        |     0.513516 |       0.456715 |   0.45207  |
| barab-szabi-1        |     0.529927 |       0.442439 |   0.455156 |
| Bori_Aron_solution-1 |     0.502891 |       0.58211  |   0.558775 |
| k-d_tree_pandas      |     0.518771 |       0.413261 |   0.610177 |
| k-d_tree_sklearn     |     0.532558 |       1.03781  |   1.14365  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.524925 |       0.459817 |   0.457574 |
| k-d_tree_polars      |     0.527042 |       0.472861 |   0.485546 |
| barab-szabi-1        |     0.506193 |       0.460043 |   0.492043 |
| Bori_Aron_solution-1 |     0.498537 |       0.644375 |   0.56848  |
| k-d_tree_pandas      |     0.494894 |       0.420364 |   0.623901 |
| k-d_tree_sklearn     |     0.508292 |       1.11944  |   1.13018  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.505403 |       0.521206 |   0.499057 |
| k-d_tree_polars      |     0.511731 |       0.616801 |   0.581046 |
| barab-szabi-1        |     0.516056 |       0.585665 |   0.590867 |
| Bori_Aron_solution-1 |     0.50501  |       0.840684 |   0.595809 |
| k-d_tree_pandas      |     0.510903 |       0.509485 |   0.754773 |
| k-d_tree_sklearn     |     0.525439 |       1.29643  |   1.19176  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.507193 |       0.783156 |   0.569811 |
| Bori_Aron_solution-1 |     0.498083 |       1.51611  |   0.60547  |
| k-d_tree_polars      |     0.505291 |       0.965631 |   0.981063 |
| barab-szabi-1        |     0.507811 |       0.955161 |   0.998393 |
| k-d_tree_pandas      |     0.506886 |       0.833873 |   1.23699  |
| k-d_tree_sklearn     |     0.508648 |       2.31235  |   1.27876  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.507597 |        5.39998 |   0.76188  |
| Bori_Aron_solution-1 |     0.497794 |       11.4119  |   0.862447 |
| k-d_tree_sklearn     |     0.517717 |       17.4346  |   1.35038  |
| barab-szabi-1        |     0.49829  |        5.5988  |   6.71685  |
| k-d_tree_polars      |     0.49988  |        5.47156 |   6.74203  |
| k-d_tree_pandas      |     0.509638 |        4.51283 |   7.30329  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.500621 |        74.0052 |    2.76899 |
| k-d_tree_sklearn     |     0.509084 |       241.24   |    4.2078  |
| Bori_Aron_solution-1 |     0.681743 |       147.873  |   18.3447  |