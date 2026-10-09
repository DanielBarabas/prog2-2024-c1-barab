# 2026-10-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.367213 |       0.3593   |   0.358869 |
| k-d_tree_polars      |     0.398736 |       0.348222 |   0.372562 |
| k-d_tree_pandas      |     0.3931   |       0.339757 |   0.463827 |
| Bori_Aron_solution-1 |     0.377575 |       0.473107 |   0.486121 |
| solution-1           |     6.73207  |       2e-06    |   0.531235 |
| barab-szabi-1        |     8.12025  |       0.387795 |   0.534309 |
| k-d_tree_sklearn     |     2.61756  |       1.00418  |   0.912018 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.369385 |       0.346995 |   0.338731 |
| k-d_tree_polars      |     0.372086 |       0.361706 |   0.358252 |
| barab-szabi-1        |     0.373023 |       0.410328 |   0.361912 |
| Bori_Aron_solution-1 |     0.366051 |       0.452503 |   0.451612 |
| k-d_tree_pandas      |     0.38233  |       0.320409 |   0.452123 |
| k-d_tree_sklearn     |     0.386178 |       0.822607 |   0.8615   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.381374 |       0.380889 |   0.371704 |
| barab-szabi-1        |     0.368825 |       0.373515 |   0.375529 |
| k-d_tree_polars      |     0.385054 |       0.407957 |   0.386071 |
| Bori_Aron_solution-1 |     0.405956 |       0.514759 |   0.482204 |
| k-d_tree_pandas      |     0.38201  |       0.352579 |   0.542186 |
| k-d_tree_sklearn     |     0.399547 |       0.888865 |   0.946758 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.373523 |       0.446694 |   0.41704  |
| Bori_Aron_solution-1 |     0.37475  |       0.623922 |   0.456625 |
| k-d_tree_polars      |     0.389332 |       0.461228 |   0.458609 |
| barab-szabi-1        |     0.366673 |       0.476874 |   0.462163 |
| k-d_tree_pandas      |     0.369691 |       0.410438 |   0.585824 |
| k-d_tree_sklearn     |     0.391156 |       1.08432  |   1.00622  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.377302 |       0.631564 |   0.427484 |
| Bori_Aron_solution-1 |     0.367971 |       1.18368  |   0.491004 |
| k-d_tree_polars      |     0.379936 |       0.722748 |   0.757928 |
| barab-szabi-1        |     0.395464 |       0.712068 |   0.787887 |
| k-d_tree_pandas      |     0.428343 |       0.614745 |   0.947014 |
| k-d_tree_sklearn     |     0.372235 |       1.72831  |   0.955265 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.371433 |        4.57686 |   0.627295 |
| Bori_Aron_solution-1 |     0.370281 |        9.01484 |   0.664259 |
| k-d_tree_sklearn     |     0.38262  |       14.8893  |   1.02733  |
| k-d_tree_polars      |     0.374819 |        4.63908 |   5.95326  |
| barab-szabi-1        |     0.367815 |        4.69705 |   6.04077  |
| k-d_tree_pandas      |     0.37461  |        3.17698 |   6.19455  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.755742 |        69.8571 |    2.87395 |
| k-d_tree_sklearn     |     0.495971 |       219.734  |    3.07216 |
| Bori_Aron_solution-1 |     0.361289 |       149.629  |   20.4377  |