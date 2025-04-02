# 2025-04-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.584969 |       0.437627 |   0.4089   |
| barab-szabi-2        |     0.551367 |       0.409725 |   0.41463  |
| solution-1           |     7.3536   |       1e-06    |   0.51342  |
| Bori_Aron_solution-1 |     0.554344 |       0.569013 |   0.549563 |
| k-d_tree_pandas      |     7.78511  |       0.438032 |   0.673603 |
| barab-szabi-1        |     0.555633 |       0.422829 |   0.687453 |
| k-d_tree_sklearn     |     2.93731  |       1.15263  |   1.08698  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567371 |       0.421595 |   0.413858 |
| barab-szabi-1        |     0.584122 |       0.417933 |   0.417533 |
| k-d_tree_polars      |     0.567072 |       0.415743 |   0.421763 |
| Bori_Aron_solution-1 |     0.569116 |       0.563354 |   0.552892 |
| k-d_tree_pandas      |     0.587365 |       0.404062 |   0.567241 |
| k-d_tree_sklearn     |     0.573907 |       1.0013   |   1.05459  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.568993 |       0.422245 |   0.419222 |
| k-d_tree_polars      |     0.566789 |       0.433361 |   0.439826 |
| barab-szabi-1        |     0.570043 |       0.438144 |   0.446955 |
| Bori_Aron_solution-1 |     0.568377 |       0.602951 |   0.556961 |
| k-d_tree_pandas      |     0.577712 |       0.416209 |   0.60624  |
| k-d_tree_sklearn     |     0.575292 |       1.00766  |   1.06507  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569141 |       0.48314  |   0.462913 |
| k-d_tree_polars      |     0.569104 |       0.538529 |   0.542766 |
| barab-szabi-1        |     0.571409 |       0.543421 |   0.544417 |
| Bori_Aron_solution-1 |     0.563345 |       0.768268 |   0.580944 |
| k-d_tree_pandas      |     0.567132 |       0.483547 |   0.734806 |
| k-d_tree_sklearn     |     0.577337 |       1.23876  |   1.11683  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57073  |       0.738369 |   0.488761 |
| Bori_Aron_solution-1 |     0.561592 |       1.40106  |   0.608257 |
| k-d_tree_polars      |     0.568482 |       0.872476 |   0.901314 |
| barab-szabi-1        |     0.583127 |       0.880284 |   0.938879 |
| k-d_tree_pandas      |     0.572663 |       0.740011 |   1.17922  |
| k-d_tree_sklearn     |     0.571876 |       2.07269  |   1.21635  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570432 |        5.41797 |   0.740473 |
| Bori_Aron_solution-1 |     0.578386 |       10.7329  |   0.892498 |
| k-d_tree_sklearn     |     0.585113 |       16.2532  |   1.34728  |
| k-d_tree_polars      |     0.578625 |        5.0026  |   6.67931  |
| barab-szabi-1        |     0.579121 |        4.97886 |   6.73741  |
| k-d_tree_pandas      |     0.571778 |        3.84362 |   7.07878  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.875869 |        72.3576 |    2.8718  |
| k-d_tree_sklearn     |     0.679007 |       227.007  |    4.37987 |
| Bori_Aron_solution-1 |     0.558639 |       148.911  |   16.4921  |