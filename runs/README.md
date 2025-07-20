# 2025-07-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.76895  |       0.684832 |   0.430939 |
| k-d_tree_polars      |     0.567626 |       0.418813 |   0.434796 |
| barab-szabi-1        |     0.558033 |       0.416615 |   0.437584 |
| solution-1           |     7.42324  |       1e-06    |   0.460025 |
| Bori_Aron_solution-1 |     0.553424 |       0.564183 |   0.573871 |
| k-d_tree_pandas      |     0.574367 |       0.414802 |   0.577098 |
| k-d_tree_sklearn     |     2.9925   |       1.19348  |   1.08361  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.57059  |       0.432574 |   0.433685 |
| barab-szabi-2        |     0.57267  |       0.443305 |   0.434434 |
| k-d_tree_polars      |     0.567091 |       0.422374 |   0.43697  |
| Bori_Aron_solution-1 |     0.564225 |       0.572329 |   0.556843 |
| k-d_tree_pandas      |     0.565433 |       0.399002 |   0.569525 |
| k-d_tree_sklearn     |     0.566842 |       0.982213 |   1.09192  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567805 |       0.445787 |   0.442901 |
| k-d_tree_polars      |     0.577625 |       0.45373  |   0.467916 |
| barab-szabi-1        |     0.574885 |       0.465626 |   0.485257 |
| k-d_tree_pandas      |     0.581015 |       0.434793 |   0.618567 |
| Bori_Aron_solution-1 |     0.564599 |       0.601938 |   0.626051 |
| k-d_tree_sklearn     |     0.573897 |       1.05313  |   1.11772  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569082 |       0.514301 |   0.470515 |
| k-d_tree_polars      |     0.571859 |       0.562754 |   0.56366  |
| barab-szabi-1        |     0.581096 |       0.565123 |   0.582922 |
| Bori_Aron_solution-1 |     0.570425 |       0.791068 |   0.590259 |
| k-d_tree_pandas      |     0.570937 |       0.495887 |   0.745645 |
| k-d_tree_sklearn     |     0.580038 |       1.27472  |   1.16285  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571877 |       0.763192 |   0.521394 |
| Bori_Aron_solution-1 |     0.557584 |       1.43096  |   0.604032 |
| k-d_tree_polars      |     0.554548 |       0.902647 |   0.906199 |
| barab-szabi-1        |     0.571453 |       0.906852 |   0.979464 |
| k-d_tree_pandas      |     0.566893 |       0.772432 |   1.20075  |
| k-d_tree_sklearn     |     0.576213 |       2.16402  |   1.25359  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559005 |        5.37417 |   0.729569 |
| Bori_Aron_solution-1 |     0.554781 |       10.813   |   0.883194 |
| k-d_tree_sklearn     |     0.574449 |       16.9273  |   1.36804  |
| barab-szabi-1        |     0.566134 |        5.05881 |   6.67764  |
| k-d_tree_polars      |     0.573533 |        5.07916 |   6.76504  |
| k-d_tree_pandas      |     0.578001 |        3.9604  |   7.13784  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565917 |        72.3625 |    2.68329 |
| k-d_tree_sklearn     |     0.768645 |       232.535  |    4.10112 |
| Bori_Aron_solution-1 |     0.569865 |       142.338  |   18.0309  |