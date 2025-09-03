# 2025-09-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.96826  |       0.625101 |   0.429925 |
| barab-szabi-1        |     0.530561 |       0.406237 |   0.437297 |
| solution-1           |     7.88923  |       1e-06    |   0.450282 |
| k-d_tree_polars      |     0.523928 |       0.404694 |   0.499392 |
| Bori_Aron_solution-1 |     0.520016 |       0.543042 |   0.5463   |
| k-d_tree_pandas      |     0.537408 |       0.389687 |   0.547424 |
| k-d_tree_sklearn     |     3.03805  |       1.11849  |   1.06257  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540237 |       0.428479 |   0.426805 |
| k-d_tree_polars      |     0.538663 |       0.410397 |   0.431954 |
| barab-szabi-1        |     0.54102  |       0.417969 |   0.434215 |
| Bori_Aron_solution-1 |     0.536034 |       0.557882 |   0.546932 |
| k-d_tree_pandas      |     0.541417 |       0.392687 |   0.553504 |
| k-d_tree_sklearn     |     0.544298 |       0.974136 |   1.05762  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539733 |       0.445232 |   0.442877 |
| barab-szabi-1        |     0.543419 |       0.436409 |   0.456787 |
| k-d_tree_polars      |     0.543574 |       0.434287 |   0.458574 |
| Bori_Aron_solution-1 |     0.541768 |       0.585422 |   0.548237 |
| k-d_tree_pandas      |     0.544188 |       0.407084 |   0.600523 |
| k-d_tree_sklearn     |     0.5418   |       1.01629  |   1.10122  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548497 |       0.505124 |   0.473137 |
| k-d_tree_polars      |     0.544675 |       0.55104  |   0.561898 |
| barab-szabi-1        |     0.549973 |       0.552706 |   0.564329 |
| Bori_Aron_solution-1 |     0.547395 |       0.776088 |   0.571886 |
| k-d_tree_pandas      |     0.548549 |       0.493914 |   0.755641 |
| k-d_tree_sklearn     |     0.543512 |       1.25399  |   1.15763  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542607 |       0.754173 |   0.502158 |
| Bori_Aron_solution-1 |     0.540251 |       1.41852  |   0.595092 |
| k-d_tree_polars      |     0.545997 |       0.893296 |   0.912312 |
| barab-szabi-1        |     0.546594 |       0.890416 |   0.961951 |
| k-d_tree_pandas      |     0.546199 |       0.769555 |   1.18362  |
| k-d_tree_sklearn     |     0.549263 |       2.07898  |   1.22862  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542151 |        5.62065 |   0.781257 |
| Bori_Aron_solution-1 |     0.539047 |       11.2652  |   0.86783  |
| k-d_tree_sklearn     |     0.544688 |       17.2483  |   1.33594  |
| barab-szabi-1        |     0.539747 |        5.0893  |   7.10716  |
| k-d_tree_polars      |     0.543432 |        5.04826 |   7.23803  |
| k-d_tree_pandas      |     0.545672 |        3.87921 |   7.30389  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544339 |        77.6466 |    3.29911 |
| k-d_tree_sklearn     |     0.671435 |       245.064  |    4.01308 |
| Bori_Aron_solution-1 |     0.545431 |       145.219  |   18.4433  |