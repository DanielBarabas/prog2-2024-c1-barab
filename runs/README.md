# 2024-08-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.609778 |       0.403244 |   0.391037 |
| barab-szabi-2        |     8.0678   |       0.457179 |   0.400113 |
| solution-1           |     7.83989  |       1e-06    |   0.411036 |
| barab-szabi-1        |     0.604995 |       0.405046 |   0.411168 |
| Bori_Aron_solution-1 |     0.633393 |       0.523877 |   0.520967 |
| k-d_tree_pandas      |     0.614841 |       0.438561 |   0.529718 |
| k-d_tree_sklearn     |     2.98692  |       0.961804 |   0.703957 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616893 |       0.391021 |   0.396773 |
| barab-szabi-1        |     0.625568 |       0.403198 |   0.397915 |
| k-d_tree_polars      |     0.646296 |       0.420409 |   0.398741 |
| Bori_Aron_solution-1 |     0.63084  |       0.549147 |   0.549922 |
| k-d_tree_pandas      |     0.631701 |       0.403001 |   0.565494 |
| k-d_tree_sklearn     |     0.621244 |       0.918118 |   0.714365 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62834  |       0.40452  |   0.403739 |
| barab-szabi-1        |     0.626831 |       0.431217 |   0.425257 |
| k-d_tree_polars      |     0.64536  |       0.436565 |   0.428104 |
| Bori_Aron_solution-1 |     0.615928 |       0.576679 |   0.540084 |
| k-d_tree_pandas      |     0.633673 |       0.413438 |   0.591661 |
| k-d_tree_sklearn     |     0.62411  |       0.956077 |   0.7576   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62599  |       0.469145 |   0.431337 |
| k-d_tree_polars      |     0.625818 |       0.543227 |   0.528736 |
| barab-szabi-1        |     0.625592 |       0.543719 |   0.53876  |
| Bori_Aron_solution-1 |     0.612898 |       0.753167 |   0.567339 |
| k-d_tree_pandas      |     0.631388 |       0.495353 |   0.717265 |
| k-d_tree_sklearn     |     0.63464  |       1.18457  |   0.813347 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631289 |       0.749451 |   0.531965 |
| Bori_Aron_solution-1 |     0.622374 |       1.43154  |   0.570641 |
| k-d_tree_polars      |     0.621486 |       0.859571 |   0.866733 |
| k-d_tree_sklearn     |     0.61909  |       2.00545  |   0.884863 |
| barab-szabi-1        |     0.616454 |       0.853036 |   0.913522 |
| k-d_tree_pandas      |     0.623741 |       0.746771 |   1.18377  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626069 |        5.54192 |   0.731173 |
| Bori_Aron_solution-1 |     0.612197 |       10.7052  |   0.864842 |
| k-d_tree_sklearn     |     0.621762 |       16.0901  |   0.987302 |
| k-d_tree_polars      |     0.621606 |        4.81366 |   6.51409  |
| barab-szabi-1        |     0.616478 |        4.82972 |   6.61032  |
| k-d_tree_pandas      |     0.623324 |        3.84907 |   6.99131  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623282 |        73.2413 |    3.00766 |
| k-d_tree_sklearn     |     0.662668 |       240.831  |    3.94113 |
| Bori_Aron_solution-1 |     0.696016 |       152.26   |   18.313   |