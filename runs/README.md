# 2024-07-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.20537  |       1e-06    |   0.391773 |
| barab-szabi-1        |     0.565903 |       0.414724 |   0.401073 |
| k-d_tree_polars      |     0.583747 |       0.413135 |   0.405881 |
| barab-szabi-2        |     0.586968 |       0.401134 |   0.422873 |
| Bori_Aron_solution-1 |     0.571327 |       0.548909 |   0.539044 |
| k-d_tree_pandas      |     0.572139 |       0.383651 |   0.540808 |
| k-d_tree_sklearn     |    11.0476   |       1.099    |   0.724535 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565561 |       0.401418 |   0.40177  |
| k-d_tree_polars      |     0.564481 |       0.425371 |   0.401929 |
| barab-szabi-1        |     0.569225 |       0.414709 |   0.403584 |
| Bori_Aron_solution-1 |     0.591346 |       0.536622 |   0.536744 |
| k-d_tree_pandas      |     0.586173 |       0.393811 |   0.543312 |
| k-d_tree_sklearn     |     0.569879 |       0.928091 |   0.737443 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574786 |       0.411331 |   0.410924 |
| barab-szabi-1        |     0.573116 |       0.447481 |   0.425689 |
| k-d_tree_polars      |     0.604337 |       0.445718 |   0.430161 |
| Bori_Aron_solution-1 |     0.559834 |       0.574736 |   0.539562 |
| k-d_tree_pandas      |     0.576205 |       0.417928 |   0.590492 |
| k-d_tree_sklearn     |     0.569762 |       0.970048 |   0.749952 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558561 |       0.480623 |   0.442385 |
| k-d_tree_polars      |     0.57881  |       0.562227 |   0.529641 |
| barab-szabi-1        |     0.581843 |       0.559597 |   0.546024 |
| Bori_Aron_solution-1 |     0.55656  |       0.752752 |   0.552066 |
| k-d_tree_pandas      |     0.565394 |       0.486746 |   0.729076 |
| k-d_tree_sklearn     |     0.584025 |       1.21669  |   0.8194   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577294 |       0.73789  |   0.48544  |
| Bori_Aron_solution-1 |     0.562162 |       1.41056  |   0.593666 |
| k-d_tree_sklearn     |     0.583615 |       2.04076  |   0.905561 |
| k-d_tree_polars      |     0.5631   |       0.870074 |   0.910053 |
| barab-szabi-1        |     0.575485 |       0.869632 |   0.951301 |
| k-d_tree_pandas      |     0.573813 |       0.758592 |   1.17789  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563308 |        5.56513 |   0.801829 |
| Bori_Aron_solution-1 |     0.564387 |       10.9917  |   0.859139 |
| k-d_tree_sklearn     |     0.565723 |       16.9038  |   1.06095  |
| barab-szabi-1        |     0.568671 |        4.89325 |   6.93878  |
| k-d_tree_polars      |     0.556786 |        4.90348 |   7.07977  |
| k-d_tree_pandas      |     0.579557 |        3.8521  |   7.33249  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.960394 |        76.2932 |    4.31216 |
| k-d_tree_sklearn     |     0.571033 |       234.959  |    4.42009 |
| Bori_Aron_solution-1 |     0.578005 |       153.792  |   17.7016  |