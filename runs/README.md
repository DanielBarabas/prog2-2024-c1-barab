# 2026-01-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.91842  |       1e-06    |   0.434098 |
| barab-szabi-2        |     0.521631 |       0.488898 |   0.434577 |
| k-d_tree_polars      |     0.53463  |       0.408892 |   0.435348 |
| barab-szabi-1        |     0.611745 |       0.415823 |   0.437978 |
| Bori_Aron_solution-1 |     0.531382 |       0.557826 |   0.555666 |
| k-d_tree_pandas      |     9.16093  |       0.41369  |   0.649283 |
| k-d_tree_sklearn     |     3.21576  |       1.10423  |   1.11629  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539606 |       0.43445  |   0.437885 |
| barab-szabi-1        |     0.543356 |       0.431402 |   0.441084 |
| k-d_tree_polars      |     0.535172 |       0.416464 |   0.44413  |
| Bori_Aron_solution-1 |     0.530884 |       0.558921 |   0.564639 |
| k-d_tree_pandas      |     0.542499 |       0.399718 |   0.575758 |
| k-d_tree_sklearn     |     0.542717 |       1.00367  |   1.09646  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535885 |       0.451427 |   0.459327 |
| k-d_tree_polars      |     0.536346 |       0.451364 |   0.46667  |
| barab-szabi-1        |     0.845677 |       0.444422 |   0.472533 |
| Bori_Aron_solution-1 |     0.525163 |       0.619161 |   0.594035 |
| k-d_tree_pandas      |     0.541412 |       0.426716 |   0.607913 |
| k-d_tree_sklearn     |     0.540219 |       1.03621  |   1.13642  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546306 |       0.508213 |   0.477811 |
| k-d_tree_polars      |     0.545573 |       0.561908 |   0.565741 |
| Bori_Aron_solution-1 |     0.539393 |       0.788089 |   0.570657 |
| barab-szabi-1        |     0.538146 |       0.564968 |   0.577951 |
| k-d_tree_pandas      |     0.558286 |       0.549988 |   0.763325 |
| k-d_tree_sklearn     |     0.541397 |       1.26745  |   1.14951  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537611 |       0.76107  |   0.587289 |
| Bori_Aron_solution-1 |     0.525509 |       1.47004  |   0.604597 |
| k-d_tree_polars      |     0.536998 |       0.930192 |   0.932395 |
| barab-szabi-1        |     0.548399 |       0.941926 |   0.963799 |
| k-d_tree_pandas      |     0.531903 |       0.832066 |   1.19637  |
| k-d_tree_sklearn     |     0.562748 |       2.15349  |   1.27205  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543453 |        5.18804 |   0.742932 |
| Bori_Aron_solution-1 |     0.538826 |       11.2363  |   0.849721 |
| k-d_tree_sklearn     |     0.549019 |       17.1736  |   1.33121  |
| k-d_tree_polars      |     0.541367 |        5.42564 |   6.80137  |
| barab-szabi-1        |     0.54224  |        5.44192 |   6.89276  |
| k-d_tree_pandas      |     0.549234 |        4.51108 |   7.19421  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534878 |        77.1144 |    2.75347 |
| k-d_tree_sklearn     |     0.552469 |       237.812  |    4.23719 |
| Bori_Aron_solution-1 |     0.689688 |       148.019  |   17.7159  |