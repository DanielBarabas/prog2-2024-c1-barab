# 2025-02-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.83911  |       0.627435 |   0.404356 |
| k-d_tree_polars      |     0.572544 |       0.406958 |   0.407534 |
| barab-szabi-1        |     0.584967 |       0.404884 |   0.409033 |
| solution-1           |     7.60889  |       1e-06    |   0.458566 |
| Bori_Aron_solution-1 |     0.581796 |       0.538682 |   0.530795 |
| k-d_tree_pandas      |     0.582519 |       0.37994  |   0.532974 |
| k-d_tree_sklearn     |     3.03129  |       1.05449  |   1.01063  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580191 |       0.407619 |   0.399249 |
| k-d_tree_polars      |     0.584897 |       0.411257 |   0.40906  |
| barab-szabi-1        |     0.58752  |       0.407545 |   0.414465 |
| Bori_Aron_solution-1 |     0.580527 |       0.544618 |   0.524574 |
| k-d_tree_pandas      |     0.611545 |       0.38548  |   0.538821 |
| k-d_tree_sklearn     |     0.585715 |       0.961448 |   1.00696  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.582623 |       0.416008 |   0.410307 |
| k-d_tree_polars      |     0.583188 |       0.429691 |   0.43576  |
| barab-szabi-1        |     0.600432 |       0.449996 |   0.461442 |
| Bori_Aron_solution-1 |     0.587529 |       0.569276 |   0.544439 |
| k-d_tree_pandas      |     0.590176 |       0.399882 |   0.583247 |
| k-d_tree_sklearn     |     0.61441  |       0.986977 |   1.06275  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580694 |       0.48105  |   0.442862 |
| barab-szabi-1        |     0.586971 |       0.533676 |   0.542912 |
| Bori_Aron_solution-1 |     0.579122 |       0.739514 |   0.551944 |
| k-d_tree_polars      |     0.593821 |       0.546358 |   0.553847 |
| k-d_tree_pandas      |     0.582879 |       0.4784   |   0.71405  |
| k-d_tree_sklearn     |     0.587477 |       1.19844  |   1.10048  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579233 |       0.719229 |   0.475398 |
| Bori_Aron_solution-1 |     0.589819 |       1.37599  |   0.576018 |
| k-d_tree_polars      |     0.587411 |       0.86626  |   0.886037 |
| barab-szabi-1        |     0.586306 |       0.860752 |   0.923903 |
| k-d_tree_pandas      |     0.593665 |       0.751953 |   1.18066  |
| k-d_tree_sklearn     |     0.587863 |       2.03287  |   1.21256  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581674 |        5.2293  |   0.728155 |
| Bori_Aron_solution-1 |     0.574789 |       10.4861  |   0.877965 |
| k-d_tree_sklearn     |     0.58441  |       16.1648  |   1.3092   |
| barab-szabi-1        |     0.584741 |        4.87181 |   6.56121  |
| k-d_tree_polars      |     0.596886 |        4.9109  |   6.65935  |
| k-d_tree_pandas      |     0.588484 |        3.82573 |   6.91731  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.582942 |        73.0002 |    2.88675 |
| k-d_tree_sklearn     |     0.597138 |       225.71   |    4.5363  |
| Bori_Aron_solution-1 |     0.68424  |       151.139  |   18.4748  |