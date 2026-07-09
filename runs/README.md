# 2026-07-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     9.10256  |       0.900325 |   0.366959 |
| barab-szabi-1        |     0.848994 |       0.341772 |   0.372538 |
| k-d_tree_polars      |     0.357862 |       0.330665 |   0.376384 |
| Bori_Aron_solution-1 |     0.352934 |       0.438009 |   0.441959 |
| k-d_tree_pandas      |     0.362683 |       0.324259 |   0.456602 |
| solution-1           |     8.35656  |       1e-06    |   0.46522  |
| k-d_tree_sklearn     |     3.22695  |       1.44889  |   0.877343 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.373765 |       0.374678 |   0.366764 |
| barab-szabi-1        |     0.362203 |       0.346447 |   0.381698 |
| k-d_tree_polars      |     0.367165 |       0.350799 |   0.384197 |
| Bori_Aron_solution-1 |     0.362005 |       0.455556 |   0.445092 |
| k-d_tree_pandas      |     0.370454 |       0.326226 |   0.459924 |
| k-d_tree_sklearn     |     0.372037 |       0.80403  |   0.858261 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.368791 |       0.377349 |   0.370521 |
| k-d_tree_polars      |     0.36854  |       0.365669 |   0.400183 |
| barab-szabi-1        |     0.365604 |       0.374484 |   0.406017 |
| Bori_Aron_solution-1 |     0.382411 |       0.486403 |   0.447434 |
| k-d_tree_pandas      |     0.367891 |       0.338372 |   0.482774 |
| k-d_tree_sklearn     |     0.362105 |       0.839458 |   0.873138 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.363363 |       0.431746 |   0.41291  |
| Bori_Aron_solution-1 |     0.358667 |       0.613944 |   0.449418 |
| k-d_tree_polars      |     0.36153  |       0.468937 |   0.462079 |
| barab-szabi-1        |     0.360293 |       0.462337 |   0.463652 |
| k-d_tree_pandas      |     0.366091 |       0.399339 |   0.66484  |
| k-d_tree_sklearn     |     0.367441 |       1.09515  |   0.885695 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.375165 |       0.613458 |   0.460984 |
| Bori_Aron_solution-1 |     0.360245 |       1.12348  |   0.489441 |
| k-d_tree_polars      |     0.362804 |       0.768386 |   0.735592 |
| barab-szabi-1        |     0.370625 |       0.745736 |   0.769852 |
| k-d_tree_pandas      |     0.382215 |       0.633607 |   0.907926 |
| k-d_tree_sklearn     |     0.366333 |       1.69892  |   0.940601 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.36081  |        3.65807 |   0.581624 |
| Bori_Aron_solution-1 |     0.361761 |        8.12054 |   0.771609 |
| k-d_tree_sklearn     |     0.371007 |       12.7838  |   1.0936   |
| barab-szabi-1        |     0.359396 |        4.96512 |   4.8961   |
| k-d_tree_polars      |     0.365175 |        4.7424  |   5.01683  |
| k-d_tree_pandas      |     0.372769 |        3.29512 |   5.21647  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.368661 |        54.1613 |    3.28931 |
| k-d_tree_sklearn     |     1.77706  |       152.827  |    5.91195 |
| Bori_Aron_solution-1 |     0.381215 |       158.149  |   18.483   |