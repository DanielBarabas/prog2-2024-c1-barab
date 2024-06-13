# 2024-06-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.79273  |       0.367077 |   0.367124 |
| k-d_tree_polars      |     0.832846 |       0.433564 |   0.367655 |
| barab-szabi-1        |     0.823339 |       0.431622 |   0.375642 |
| solution-1           |     8.24081  |       1e-06    |   0.411035 |
| Bori_Aron_solution-1 |     4.77853  |       0.439123 |   0.435569 |
| k-d_tree_pandas      |     0.822402 |       0.41047  |   0.512501 |
| k-d_tree_sklearn     |     3.38119  |       0.96557  |   0.706711 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.82497  |       0.366662 |   0.365591 |
| barab-szabi-1        |     0.848586 |       0.438597 |   0.375494 |
| k-d_tree_polars      |     0.827324 |       0.430628 |   0.380004 |
| Bori_Aron_solution-1 |     0.807098 |       0.51047  |   0.508091 |
| k-d_tree_pandas      |     0.823867 |       0.422581 |   0.54447  |
| k-d_tree_sklearn     |     0.830155 |       0.918918 |   0.71822  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.817121 |       0.381517 |   0.373983 |
| barab-szabi-1        |     0.832324 |       0.455803 |   0.402344 |
| k-d_tree_polars      |     0.828013 |       0.472532 |   0.408923 |
| Bori_Aron_solution-1 |     0.838137 |       0.549661 |   0.515285 |
| k-d_tree_pandas      |     0.825571 |       0.432173 |   0.558763 |
| k-d_tree_sklearn     |     0.827813 |       0.986212 |   0.743981 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.828056 |       0.44834  |   0.407    |
| k-d_tree_polars      |     0.825058 |       0.564416 |   0.499932 |
| barab-szabi-1        |     0.844768 |       0.56431  |   0.507514 |
| Bori_Aron_solution-1 |     0.823018 |       0.726172 |   0.516804 |
| k-d_tree_pandas      |     0.818493 |       0.502145 |   0.696173 |
| k-d_tree_sklearn     |     0.841023 |       1.19337  |   0.796871 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.829608 |       0.718253 |   0.515777 |
| Bori_Aron_solution-1 |     0.817102 |       1.41447  |   0.547659 |
| k-d_tree_polars      |     0.8323   |       0.89013  |   0.887655 |
| barab-szabi-1        |     0.832789 |       0.898132 |   0.907975 |
| k-d_tree_sklearn     |     0.882869 |       2.07567  |   0.916235 |
| k-d_tree_pandas      |     0.824174 |       0.787209 |   1.16657  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.831254 |        5.56425 |   0.743437 |
| Bori_Aron_solution-1 |     0.808038 |       11.3866  |   0.800263 |
| k-d_tree_sklearn     |     0.807937 |       17.0129  |   1.0686   |
| barab-szabi-1        |     0.80323  |        5.04115 |   6.76253  |
| k-d_tree_polars      |     0.844708 |        5.05973 |   6.97957  |
| k-d_tree_pandas      |     0.810938 |        4.03984 |   7.66928  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.12557  |        78.1765 |    3.93478 |
| k-d_tree_sklearn     |     0.963011 |       237.013  |    4.68595 |
| Bori_Aron_solution-1 |     0.842657 |       148.708  |   18.245   |