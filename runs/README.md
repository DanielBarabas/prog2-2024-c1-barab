# 2025-07-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.30797  |       1e-06    |   0.431944 |
| k-d_tree_polars      |     0.573895 |       0.413614 |   0.433465 |
| barab-szabi-1        |     0.569594 |       0.419865 |   0.457663 |
| barab-szabi-2        |     0.573009 |       0.445381 |   0.475224 |
| k-d_tree_pandas      |     0.571719 |       0.400437 |   0.576388 |
| Bori_Aron_solution-1 |     0.564433 |       0.598997 |   0.606421 |
| k-d_tree_sklearn     |    10.9108   |       1.28785  |   1.10118  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.576848 |       0.443363 |   0.440504 |
| barab-szabi-1        |     0.577322 |       0.443551 |   0.443456 |
| k-d_tree_polars      |     0.586892 |       0.451355 |   0.469487 |
| k-d_tree_pandas      |     0.587289 |       0.443534 |   0.588125 |
| Bori_Aron_solution-1 |     0.574354 |       0.591898 |   0.589557 |
| k-d_tree_sklearn     |     0.571747 |       1.01564  |   1.08842  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.776749 |       0.446243 |   0.449831 |
| barab-szabi-1        |     0.573518 |       0.4653   |   0.474331 |
| k-d_tree_polars      |     0.574376 |       0.456501 |   0.474935 |
| Bori_Aron_solution-1 |     0.574105 |       0.635048 |   0.592573 |
| k-d_tree_pandas      |     0.571371 |       0.424046 |   0.636082 |
| k-d_tree_sklearn     |     0.604338 |       1.10921  |   1.16874  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.573059 |       0.522993 |   0.509299 |
| k-d_tree_polars      |     0.589193 |       0.581712 |   0.577109 |
| Bori_Aron_solution-1 |     0.585728 |       0.782154 |   0.58901  |
| barab-szabi-1        |     0.564348 |       0.590524 |   0.60004  |
| k-d_tree_pandas      |     0.572722 |       0.524336 |   0.779085 |
| k-d_tree_sklearn     |     0.589129 |       1.33302  |   1.2015   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571327 |       0.775706 |   0.540799 |
| Bori_Aron_solution-1 |     0.588022 |       1.42601  |   0.611182 |
| k-d_tree_polars      |     0.574605 |       0.904026 |   0.94528  |
| barab-szabi-1        |     0.571008 |       0.895529 |   0.96781  |
| k-d_tree_pandas      |     0.587337 |       0.771705 |   1.20909  |
| k-d_tree_sklearn     |     0.571266 |       2.1631   |   1.28536  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58567  |        6.15793 |   0.827876 |
| Bori_Aron_solution-1 |     0.567604 |       11.4159  |   0.876429 |
| k-d_tree_sklearn     |     0.584602 |       17.9779  |   1.40353  |
| barab-szabi-1        |     0.577558 |        5.06807 |   7.35701  |
| k-d_tree_polars      |     0.597283 |        5.02135 |   7.5224   |
| k-d_tree_pandas      |     0.567862 |        4.01334 |   7.77007  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585965 |        81.3978 |    3.03685 |
| k-d_tree_sklearn     |     0.577783 |       247.819  |    4.1084  |
| Bori_Aron_solution-1 |     0.587244 |       155.381  |   18.213   |