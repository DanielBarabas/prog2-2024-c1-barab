# 2026-01-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.575929 |       0.462432 |   0.473822 |
| barab-szabi-1        |     0.590076 |       0.454916 |   0.476905 |
| barab-szabi-2        |     0.556948 |       0.528682 |   0.482205 |
| solution-1           |     8.52995  |       1e-06    |   0.487872 |
| Bori_Aron_solution-1 |     0.575337 |       0.619048 |   0.615462 |
| k-d_tree_pandas      |     9.64926  |       0.494579 |   0.732836 |
| k-d_tree_sklearn     |     3.42061  |       1.1864   |   1.16613  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.573925 |       0.472319 |   0.476394 |
| barab-szabi-1        |     0.595917 |       0.461099 |   0.476429 |
| k-d_tree_polars      |     0.578989 |       0.452246 |   0.478816 |
| Bori_Aron_solution-1 |     0.577098 |       0.629596 |   0.600924 |
| k-d_tree_pandas      |     0.590384 |       0.448693 |   0.618799 |
| k-d_tree_sklearn     |     0.596447 |       1.11857  |   1.22219  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585784 |       0.487757 |   0.494938 |
| barab-szabi-1        |     0.576905 |       0.478782 |   0.501384 |
| k-d_tree_polars      |     0.569656 |       0.500768 |   0.518628 |
| Bori_Aron_solution-1 |     0.567266 |       0.664284 |   0.601985 |
| k-d_tree_pandas      |     0.569661 |       0.468651 |   0.655056 |
| k-d_tree_sklearn     |     0.576633 |       1.17031  |   1.23031  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579567 |       0.54511  |   0.519413 |
| k-d_tree_polars      |     0.577537 |       0.610422 |   0.601947 |
| barab-szabi-1        |     0.58575  |       0.590621 |   0.626325 |
| Bori_Aron_solution-1 |     0.568188 |       0.846424 |   0.638833 |
| k-d_tree_pandas      |     0.579026 |       0.540243 |   0.802845 |
| k-d_tree_sklearn     |     0.587941 |       1.39008  |   1.248    |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.575    |       1.55291  |   0.654498 |
| barab-szabi-2        |     0.576607 |       0.811027 |   0.701054 |
| k-d_tree_polars      |     0.578856 |       0.980744 |   0.990254 |
| barab-szabi-1        |     0.588229 |       0.938991 |   1.02628  |
| k-d_tree_pandas      |     0.580756 |       0.855779 |   1.27137  |
| k-d_tree_sklearn     |     0.581995 |       2.43432  |   1.40664  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579704 |        5.62278 |   0.801902 |
| Bori_Aron_solution-1 |     0.571895 |       11.4948  |   0.90895  |
| k-d_tree_sklearn     |     0.594315 |       19.0874  |   1.47691  |
| barab-szabi-1        |     0.575946 |        5.74062 |   7.25974  |
| k-d_tree_polars      |     0.597973 |        5.80168 |   7.26098  |
| k-d_tree_pandas      |     0.571167 |        4.54666 |   7.61443  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574344 |        78.8987 |    2.85013 |
| k-d_tree_sklearn     |     0.604272 |       254.259  |    4.30481 |
| Bori_Aron_solution-1 |     0.719841 |       155.576  |   18.2371  |