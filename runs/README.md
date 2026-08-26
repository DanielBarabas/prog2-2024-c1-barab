# 2026-08-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     5.2975   |       0.406574 |   0.352423 |
| solution-1           |     6.61413  |       1e-06    |   0.353984 |
| barab-szabi-1        |     0.358806 |       0.341569 |   0.354482 |
| k-d_tree_polars      |     0.355416 |       0.369561 |   0.374177 |
| Bori_Aron_solution-1 |     4.16995  |       0.773839 |   0.385796 |
| k-d_tree_pandas      |     0.355333 |       0.331939 |   0.438767 |
| k-d_tree_sklearn     |     2.96103  |       0.89252  |   0.845013 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.366858 |       0.337605 |   0.354649 |
| barab-szabi-2        |     0.360006 |       0.37067  |   0.355302 |
| barab-szabi-1        |     0.360899 |       0.339011 |   0.359103 |
| Bori_Aron_solution-1 |     0.357727 |       0.444022 |   0.435758 |
| k-d_tree_pandas      |     0.376203 |       0.316865 |   0.439176 |
| k-d_tree_sklearn     |     0.366782 |       0.799134 |   0.846058 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.361959 |       0.358631 |   0.365141 |
| k-d_tree_polars      |     0.373688 |       0.365127 |   0.37335  |
| barab-szabi-1        |     0.362481 |       0.362699 |   0.373721 |
| Bori_Aron_solution-1 |     0.359429 |       0.472862 |   0.43685  |
| k-d_tree_pandas      |     0.361413 |       0.325097 |   0.464528 |
| k-d_tree_sklearn     |     0.362535 |       0.84418  |   0.873712 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.363564 |       0.429585 |   0.383953 |
| k-d_tree_polars      |     0.363577 |       0.466202 |   0.447839 |
| Bori_Aron_solution-1 |     0.359661 |       0.619671 |   0.453749 |
| barab-szabi-1        |     0.368745 |       0.450755 |   0.454806 |
| k-d_tree_pandas      |     0.361875 |       0.395058 |   0.612599 |
| k-d_tree_sklearn     |     0.362596 |       1.02093  |   0.88706  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.365736 |       0.632308 |   0.419336 |
| Bori_Aron_solution-1 |     0.360083 |       1.15185  |   0.468287 |
| k-d_tree_polars      |     0.365382 |       0.70785  |   0.750556 |
| barab-szabi-1        |     0.365088 |       0.725132 |   0.781858 |
| k-d_tree_pandas      |     0.373102 |       0.629175 |   0.92803  |
| k-d_tree_sklearn     |     0.367182 |       1.68036  |   0.933253 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.36131  |        4.53942 |   0.625478 |
| Bori_Aron_solution-1 |     0.358772 |        9.01201 |   0.647229 |
| k-d_tree_sklearn     |     0.367695 |       14.5764  |   1.04868  |
| k-d_tree_polars      |     0.359749 |        4.62538 |   5.96619  |
| barab-szabi-1        |     0.362293 |        4.57002 |   5.97311  |
| k-d_tree_pandas      |     0.365788 |        3.23215 |   6.21401  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626046 |        73.1636 |    3.42478 |
| k-d_tree_sklearn     |     0.444595 |       222.403  |    3.49565 |
| Bori_Aron_solution-1 |     0.380518 |       149.332  |   22.4677  |