# 2025-01-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565719 |       0.467687 |   0.391375 |
| barab-szabi-1        |     0.56956  |       0.398458 |   0.397583 |
| k-d_tree_polars      |     0.610744 |       0.398288 |   0.400708 |
| solution-1           |     7.7003   |       1e-06    |   0.449765 |
| Bori_Aron_solution-1 |     0.579149 |       0.527831 |   0.532367 |
| k-d_tree_pandas      |     8.17794  |       0.405379 |   0.683035 |
| k-d_tree_sklearn     |     3.21336  |       1.07252  |   1.00872  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579204 |       0.398273 |   0.402753 |
| barab-szabi-1        |     0.588123 |       0.407088 |   0.4325   |
| k-d_tree_polars      |     0.582793 |       0.406671 |   0.440323 |
| Bori_Aron_solution-1 |     0.579119 |       0.539351 |   0.529108 |
| k-d_tree_pandas      |     0.581958 |       0.381752 |   0.539951 |
| k-d_tree_sklearn     |     0.584324 |       0.940949 |   1.0093   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580582 |       0.413476 |   0.407648 |
| barab-szabi-1        |     0.605578 |       0.428627 |   0.432034 |
| k-d_tree_polars      |     0.584333 |       0.431884 |   0.444732 |
| Bori_Aron_solution-1 |     0.575102 |       0.574025 |   0.530704 |
| k-d_tree_pandas      |     0.581895 |       0.400398 |   0.580388 |
| k-d_tree_sklearn     |     0.592466 |       0.980376 |   1.03516  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5875   |       0.474047 |   0.436909 |
| k-d_tree_polars      |     0.580321 |       0.533914 |   0.526244 |
| barab-szabi-1        |     0.585716 |       0.532731 |   0.534535 |
| Bori_Aron_solution-1 |     0.577033 |       0.739935 |   0.543606 |
| k-d_tree_pandas      |     0.580914 |       0.476113 |   0.713161 |
| k-d_tree_sklearn     |     0.584281 |       1.20193  |   1.0904   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584087 |       0.718835 |   0.476682 |
| Bori_Aron_solution-1 |     0.575117 |       1.36799  |   0.572442 |
| k-d_tree_polars      |     0.580798 |       0.857367 |   0.871789 |
| barab-szabi-1        |     0.582765 |       0.848519 |   0.910692 |
| k-d_tree_pandas      |     0.584314 |       0.743094 |   1.15675  |
| k-d_tree_sklearn     |     0.586836 |       1.99984  |   1.19564  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581274 |        5.40167 |   0.735406 |
| Bori_Aron_solution-1 |     0.576873 |       10.7354  |   0.864928 |
| k-d_tree_sklearn     |     0.586102 |       16.0364  |   1.31201  |
| barab-szabi-1        |     0.584265 |        4.74525 |   6.61476  |
| k-d_tree_polars      |     0.583439 |        4.77098 |   6.65595  |
| k-d_tree_pandas      |     0.580777 |        3.75183 |   7.05769  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589257 |         74.906 |    2.99517 |
| k-d_tree_sklearn     |     0.60024  |        228.68  |    4.49555 |
| Bori_Aron_solution-1 |     0.658098 |        149.419 |   18.1207  |