# 2025-04-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.42707  |       1e-06    |   0.358686 |
| barab-szabi-1        |     0.548239 |       0.397385 |   0.404714 |
| barab-szabi-2        |     0.547188 |       0.40254  |   0.406679 |
| k-d_tree_polars      |     7.5994   |       0.419707 |   0.484711 |
| Bori_Aron_solution-1 |     0.543142 |       0.536097 |   0.541061 |
| k-d_tree_pandas      |     0.543625 |       0.374561 |   0.541355 |
| k-d_tree_sklearn     |     2.9274   |       0.970558 |   1.0126   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556003 |       0.411177 |   0.409968 |
| barab-szabi-1        |     0.565214 |       0.412062 |   0.415728 |
| k-d_tree_polars      |     0.557944 |       0.426073 |   0.440035 |
| Bori_Aron_solution-1 |     0.558847 |       0.564631 |   0.542377 |
| k-d_tree_pandas      |     0.58072  |       0.39385  |   0.569481 |
| k-d_tree_sklearn     |     0.578761 |       0.954614 |   1.07045  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57814  |       0.42922  |   0.432071 |
| barab-szabi-1        |     0.575394 |       0.44157  |   0.451092 |
| k-d_tree_polars      |     0.571249 |       0.439669 |   0.454187 |
| k-d_tree_pandas      |     0.576532 |       0.406079 |   0.597189 |
| Bori_Aron_solution-1 |     0.569772 |       0.613752 |   0.598607 |
| k-d_tree_sklearn     |     0.563912 |       0.987611 |   1.04967  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577126 |       0.479332 |   0.449306 |
| k-d_tree_polars      |     0.55861  |       0.543824 |   0.538146 |
| barab-szabi-1        |     0.561829 |       0.543328 |   0.553424 |
| Bori_Aron_solution-1 |     0.557156 |       0.762951 |   0.567392 |
| k-d_tree_pandas      |     0.56862  |       0.495355 |   0.746545 |
| k-d_tree_sklearn     |     0.586166 |       1.20697  |   1.11209  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577394 |       0.723542 |   0.481291 |
| Bori_Aron_solution-1 |     0.552938 |       1.4132   |   0.590083 |
| k-d_tree_polars      |     0.564209 |       0.89186  |   0.889011 |
| barab-szabi-1        |     0.563506 |       0.875955 |   0.935363 |
| k-d_tree_pandas      |     0.563072 |       0.748184 |   1.16094  |
| k-d_tree_sklearn     |     0.563273 |       2.03686  |   1.21611  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566784 |        5.23923 |   0.712341 |
| Bori_Aron_solution-1 |     0.572264 |       10.7629  |   0.899115 |
| k-d_tree_sklearn     |     0.565267 |       15.9017  |   1.30907  |
| k-d_tree_polars      |     0.559971 |        5.02668 |   6.35628  |
| barab-szabi-1        |     0.558049 |        5.01907 |   6.44893  |
| k-d_tree_pandas      |     0.580552 |        3.96073 |   6.7722   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561239 |        77.0575 |    2.60296 |
| k-d_tree_sklearn     |     0.874561 |       228.346  |    4.24648 |
| Bori_Aron_solution-1 |     0.557805 |       148.845  |   15.5456  |