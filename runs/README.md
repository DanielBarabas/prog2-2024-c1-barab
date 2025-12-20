# 2025-12-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571491 |       0.511698 |   0.436396 |
| k-d_tree_polars      |     0.596587 |       0.413621 |   0.440785 |
| barab-szabi-1        |     0.535151 |       0.409574 |   0.441381 |
| solution-1           |     7.82628  |       1e-06    |   0.462705 |
| Bori_Aron_solution-1 |     0.530101 |       0.554192 |   0.547385 |
| k-d_tree_pandas      |     8.72295  |       0.448171 |   0.68777  |
| k-d_tree_sklearn     |     2.98822  |       1.1273   |   1.08124  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.536222 |       0.432136 |   0.437379 |
| barab-szabi-2        |     0.535964 |       0.446058 |   0.452478 |
| barab-szabi-1        |     0.557825 |       0.445305 |   0.454741 |
| k-d_tree_pandas      |     0.537865 |       0.40007  |   0.569199 |
| Bori_Aron_solution-1 |     0.536754 |       0.582357 |   0.57884  |
| k-d_tree_sklearn     |     0.539715 |       1.00519  |   1.13157  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556142 |       0.472229 |   0.45002  |
| k-d_tree_polars      |     0.574033 |       0.46659  |   0.474265 |
| barab-szabi-1        |     0.544015 |       0.451246 |   0.474653 |
| Bori_Aron_solution-1 |     0.540255 |       0.601276 |   0.56748  |
| k-d_tree_pandas      |     0.546753 |       0.426718 |   0.608922 |
| k-d_tree_sklearn     |     0.541582 |       1.02999  |   1.12274  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557306 |       0.510446 |   0.481291 |
| k-d_tree_polars      |     0.529948 |       0.575486 |   0.566922 |
| Bori_Aron_solution-1 |     0.535657 |       0.79356  |   0.567029 |
| barab-szabi-1        |     0.544542 |       0.5609   |   0.584562 |
| k-d_tree_pandas      |     0.550696 |       0.521467 |   0.774518 |
| k-d_tree_sklearn     |     0.537435 |       1.27717  |   1.19596  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541505 |       0.740019 |   0.524417 |
| Bori_Aron_solution-1 |     0.5278   |       1.52084  |   0.623943 |
| k-d_tree_polars      |     0.546866 |       0.930862 |   0.917649 |
| barab-szabi-1        |     0.536871 |       0.929098 |   0.994922 |
| k-d_tree_pandas      |     0.536816 |       0.819979 |   1.19201  |
| k-d_tree_sklearn     |     0.54246  |       2.14487  |   1.23197  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534846 |        5.22332 |   0.765667 |
| Bori_Aron_solution-1 |     0.526493 |       11.3141  |   0.862975 |
| k-d_tree_sklearn     |     0.559509 |       17.1596  |   1.38803  |
| k-d_tree_polars      |     0.532508 |        5.43908 |   6.70861  |
| barab-szabi-1        |     0.550905 |        6.00375 |   6.79224  |
| k-d_tree_pandas      |     0.54109  |        4.48906 |   7.3367   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550151 |        81.6884 |    2.86858 |
| k-d_tree_sklearn     |     0.546775 |       243.024  |    4.20748 |
| Bori_Aron_solution-1 |     0.661746 |       152.099  |   17.7598  |