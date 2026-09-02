# 2026-09-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     6.02817  |       0.444744 |   0.320915 |
| k-d_tree_polars      |     0.52459  |       0.291241 |   0.326342 |
| barab-szabi-1        |     0.849521 |       0.359513 |   0.375416 |
| Bori_Aron_solution-1 |     4.75399  |       1.16529  |   0.382318 |
| k-d_tree_pandas      |     0.812303 |       0.283434 |   0.421904 |
| solution-1           |     8.24309  |       1e-06    |   0.484791 |
| k-d_tree_sklearn     |     3.27251  |       1.04888  |   0.739274 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.315494 |       0.299248 |   0.316727 |
| barab-szabi-2        |     0.316221 |       0.335888 |   0.324906 |
| Bori_Aron_solution-1 |     0.315309 |       0.385916 |   0.375429 |
| k-d_tree_polars      |     0.317261 |       0.295979 |   0.390104 |
| k-d_tree_pandas      |     0.309876 |       0.274991 |   0.400266 |
| k-d_tree_sklearn     |     0.321671 |       0.679023 |   0.734479 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.310328 |       0.36413  |   0.309878 |
| k-d_tree_polars      |     0.31798  |       0.321196 |   0.336886 |
| barab-szabi-1        |     0.33728  |       0.317927 |   0.338452 |
| Bori_Aron_solution-1 |     0.316966 |       0.408485 |   0.377755 |
| k-d_tree_pandas      |     0.320193 |       0.313769 |   0.460114 |
| k-d_tree_sklearn     |     0.317214 |       0.725484 |   0.822549 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.317846 |       0.473089 |   0.354864 |
| barab-szabi-1        |     0.3197   |       0.415627 |   0.406114 |
| Bori_Aron_solution-1 |     0.313694 |       0.53636  |   0.40622  |
| k-d_tree_polars      |     0.322328 |       0.417465 |   0.454994 |
| k-d_tree_pandas      |     0.320081 |       0.349157 |   0.493553 |
| k-d_tree_sklearn     |     0.317421 |       0.940886 |   0.768335 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.318272 |       0.555931 |   0.394028 |
| Bori_Aron_solution-1 |     0.32027  |       0.995867 |   0.435049 |
| barab-szabi-1        |     0.355127 |       0.631951 |   0.676506 |
| k-d_tree_polars      |     0.318053 |       0.647562 |   0.724251 |
| k-d_tree_sklearn     |     0.366169 |       1.48229  |   0.831537 |
| k-d_tree_pandas      |     0.319296 |       0.577861 |   0.883052 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.348603 |        3.79464 |   0.679049 |
| Bori_Aron_solution-1 |     0.312994 |        7.44934 |   0.745204 |
| k-d_tree_sklearn     |     0.329326 |       12.4446  |   0.984802 |
| barab-szabi-1        |     0.316274 |        4.21798 |   4.94833  |
| k-d_tree_pandas      |     0.317601 |        2.69483 |   5.09971  |
| k-d_tree_polars      |     0.361712 |        4.30676 |   5.1344   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     5.19949  |        63.4301 |    3.14838 |
| k-d_tree_sklearn     |     0.910027 |       163.629  |    5.90309 |
| Bori_Aron_solution-1 |     0.326869 |       153.49   |  110.032   |