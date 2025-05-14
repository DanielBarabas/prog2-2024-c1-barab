# 2025-05-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.99027  |       0.410767 |   0.412196 |
| barab-szabi-1        |     0.999555 |       0.399631 |   0.414274 |
| Bori_Aron_solution-1 |     0.990899 |       0.538676 |   0.540409 |
| k-d_tree_pandas      |     0.994114 |       0.384213 |   0.542767 |
| solution-1           |     7.8727   |       1e-06    |   0.817794 |
| k-d_tree_polars      |     8.21302  |       3.18973  |   0.882463 |
| k-d_tree_sklearn     |     3.49085  |       1.27459  |   1.03572  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |      1.00996 |       0.412589 |   0.414321 |
| k-d_tree_polars      |      1.01426 |       0.40975  |   0.416913 |
| barab-szabi-1        |      1.00658 |       0.413393 |   0.424853 |
| k-d_tree_pandas      |      1.00991 |       0.386302 |   0.554237 |
| Bori_Aron_solution-1 |      1.00216 |       0.557922 |   0.556416 |
| k-d_tree_sklearn     |      1.01315 |       0.968837 |   1.07731  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52092  |       0.424932 |   0.424419 |
| k-d_tree_polars      |     1.00901  |       0.435622 |   0.443634 |
| barab-szabi-1        |     0.961565 |       0.435095 |   0.445256 |
| Bori_Aron_solution-1 |     0.518027 |       0.586302 |   0.546963 |
| k-d_tree_pandas      |     0.518367 |       0.405172 |   0.596103 |
| k-d_tree_sklearn     |     0.523831 |       1.00414  |   1.07047  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.524007 |       0.485048 |   0.456367 |
| k-d_tree_polars      |     0.538821 |       0.547077 |   0.545856 |
| barab-szabi-1        |     0.524487 |       0.545667 |   0.555149 |
| Bori_Aron_solution-1 |     0.514721 |       0.765828 |   0.561868 |
| k-d_tree_pandas      |     0.519331 |       0.491239 |   0.735998 |
| k-d_tree_sklearn     |     0.524487 |       1.23684  |   1.12324  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.518653 |       0.732416 |   0.490922 |
| Bori_Aron_solution-1 |     0.510154 |       1.40305  |   0.592985 |
| k-d_tree_polars      |     0.53567  |       0.884106 |   0.90039  |
| barab-szabi-1        |     0.518162 |       0.883417 |   0.932262 |
| k-d_tree_pandas      |     0.520599 |       0.763937 |   1.17511  |
| k-d_tree_sklearn     |     0.525656 |       2.05218  |   1.22216  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.523216 |        5.56698 |   0.735731 |
| Bori_Aron_solution-1 |     0.524644 |       10.8052  |   0.886707 |
| k-d_tree_sklearn     |     0.527441 |       16.7992  |   1.32422  |
| barab-szabi-1        |     0.54848  |        5.05474 |   6.90614  |
| k-d_tree_polars      |     0.520043 |        5.05355 |   6.98672  |
| k-d_tree_pandas      |     0.523762 |        4.00631 |   7.29501  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.523054 |        73.7759 |    2.83234 |
| k-d_tree_sklearn     |     0.709398 |       233.324  |    4.17269 |
| Bori_Aron_solution-1 |     0.532704 |       151.57   |   17.5459  |