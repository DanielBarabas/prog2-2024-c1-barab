# 2024-09-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.00343  |       1e-06    |   0.36589  |
| barab-szabi-1        |     0.605884 |       0.472003 |   0.394588 |
| barab-szabi-2        |     8.5507   |       0.470897 |   0.395123 |
| k-d_tree_polars      |     0.611003 |       0.400946 |   0.396247 |
| Bori_Aron_solution-1 |     0.608042 |       0.53865  |   0.527532 |
| k-d_tree_pandas      |     0.600997 |       0.447558 |   0.551037 |
| k-d_tree_sklearn     |     3.22433  |       0.918247 |   0.713305 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.624177 |       0.397322 |   0.392774 |
| k-d_tree_polars      |     0.615462 |       0.406829 |   0.39984  |
| barab-szabi-1        |     0.645965 |       0.417924 |   0.404237 |
| k-d_tree_pandas      |     0.613205 |       0.389291 |   0.539567 |
| Bori_Aron_solution-1 |     0.61447  |       0.540442 |   0.540977 |
| k-d_tree_sklearn     |     0.63802  |       0.924275 |   0.730137 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.628777 |       0.436746 |   0.423032 |
| barab-szabi-2        |     0.613935 |       0.418884 |   0.42578  |
| barab-szabi-1        |     0.629571 |       0.457933 |   0.431775 |
| Bori_Aron_solution-1 |     0.610656 |       0.573688 |   0.548671 |
| k-d_tree_pandas      |     0.645907 |       0.423486 |   0.605064 |
| k-d_tree_sklearn     |     0.616485 |       0.955512 |   0.736067 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622516 |       0.471014 |   0.433962 |
| k-d_tree_polars      |     0.628381 |       0.538842 |   0.520049 |
| barab-szabi-1        |     0.622507 |       0.534964 |   0.529283 |
| Bori_Aron_solution-1 |     0.621979 |       0.770764 |   0.567343 |
| k-d_tree_pandas      |     0.627608 |       0.490928 |   0.716288 |
| k-d_tree_sklearn     |     0.617657 |       1.18202  |   0.817769 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622191 |       0.723533 |   0.48557  |
| Bori_Aron_solution-1 |     0.611425 |       1.40346  |   0.564323 |
| k-d_tree_sklearn     |     0.612405 |       2.02555  |   0.886516 |
| barab-szabi-1        |     0.62371  |       0.857419 |   0.89926  |
| k-d_tree_polars      |     0.630975 |       0.862246 |   0.900174 |
| k-d_tree_pandas      |     0.63062  |       0.760932 |   1.18672  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623089 |        5.56995 |   0.741009 |
| Bori_Aron_solution-1 |     0.601013 |       10.7186  |   0.823496 |
| k-d_tree_sklearn     |     0.618969 |       16.0843  |   0.985119 |
| barab-szabi-1        |     0.620847 |        4.83639 |   6.59111  |
| k-d_tree_polars      |     0.621472 |        4.83789 |   6.75587  |
| k-d_tree_pandas      |     0.619819 |        3.93196 |   7.22033  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608    |         74.711 |    3.08946 |
| k-d_tree_sklearn     |     0.652561 |        238.422 |    3.96293 |
| Bori_Aron_solution-1 |     0.705997 |        147.325 |   18.2907  |