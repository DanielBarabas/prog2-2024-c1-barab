# 2026-01-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.538412 |       0.407623 |   0.43613  |
| barab-szabi-2        |     0.530374 |       0.599661 |   0.437137 |
| k-d_tree_polars      |     0.5385   |       0.420612 |   0.44027  |
| Bori_Aron_solution-1 |     0.530456 |       0.552189 |   0.549027 |
| solution-1           |     9.08958  |       1e-06    |   0.645863 |
| k-d_tree_pandas      |     9.9194   |       0.417939 |   0.702704 |
| k-d_tree_sklearn     |     3.57464  |       1.20502  |   1.07455  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535742 |       0.433347 |   0.436944 |
| barab-szabi-1        |     0.543584 |       0.422523 |   0.447806 |
| k-d_tree_polars      |     0.543233 |       0.431294 |   0.450441 |
| k-d_tree_pandas      |     0.528559 |       0.390894 |   0.558517 |
| Bori_Aron_solution-1 |     0.570957 |       0.579711 |   0.571065 |
| k-d_tree_sklearn     |     0.540556 |       0.986076 |   1.0904   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535927 |       0.45575  |   0.448102 |
| k-d_tree_polars      |     0.527725 |       0.453846 |   0.467266 |
| barab-szabi-1        |     0.53497  |       0.44328  |   0.475171 |
| Bori_Aron_solution-1 |     0.549952 |       0.606263 |   0.566088 |
| k-d_tree_pandas      |     0.532971 |       0.417918 |   0.60089  |
| k-d_tree_sklearn     |     0.535998 |       1.01416  |   1.0897   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.523976 |       0.499707 |   0.469213 |
| k-d_tree_polars      |     0.535125 |       0.55716  |   0.556326 |
| Bori_Aron_solution-1 |     0.5239   |       0.772784 |   0.557478 |
| barab-szabi-1        |     0.526483 |       0.559159 |   0.56876  |
| k-d_tree_pandas      |     0.526978 |       0.495248 |   0.722548 |
| k-d_tree_sklearn     |     0.527308 |       1.25018  |   1.12969  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533645 |       0.73134  |   0.508248 |
| Bori_Aron_solution-1 |     0.516765 |       1.44615  |   0.592788 |
| k-d_tree_polars      |     0.536558 |       0.917404 |   0.89965  |
| barab-szabi-1        |     0.526007 |       0.918491 |   0.949436 |
| k-d_tree_pandas      |     0.52412  |       0.805775 |   1.17091  |
| k-d_tree_sklearn     |     0.531536 |       2.11142  |   1.21542  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527026 |        4.94544 |   0.731732 |
| Bori_Aron_solution-1 |     0.515854 |       11.0551  |   0.831249 |
| k-d_tree_sklearn     |     0.519818 |       15.9363  |   1.29096  |
| k-d_tree_polars      |     0.523956 |        5.37315 |   6.39074  |
| barab-szabi-1        |     0.530914 |        5.29433 |   6.45959  |
| k-d_tree_pandas      |     0.533765 |        4.48767 |   6.88812  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.522294 |        72.8571 |    2.61869 |
| k-d_tree_sklearn     |     0.538337 |       231.23   |    4.01152 |
| Bori_Aron_solution-1 |     0.635434 |       146.236  |   17.9052  |