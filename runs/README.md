# 2025-08-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.26192  |       0.639756 |   0.43505  |
| solution-1           |     8.12008  |       1e-06    |   0.45029  |
| barab-szabi-1        |     0.552175 |       0.424738 |   0.457956 |
| k-d_tree_polars      |     0.555827 |       0.435301 |   0.467232 |
| Bori_Aron_solution-1 |     0.549494 |       0.574873 |   0.563721 |
| k-d_tree_pandas      |     0.5395   |       0.396089 |   0.582416 |
| k-d_tree_sklearn     |     3.13027  |       1.16083  |   1.10133  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5577   |       0.435916 |   0.440307 |
| barab-szabi-1        |     0.552175 |       0.424345 |   0.448539 |
| k-d_tree_polars      |     0.557545 |       0.424213 |   0.448728 |
| Bori_Aron_solution-1 |     0.555641 |       0.582887 |   0.576016 |
| k-d_tree_pandas      |     0.555772 |       0.411587 |   0.58276  |
| k-d_tree_sklearn     |     0.561932 |       1.01309  |   1.11922  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554988 |       0.449087 |   0.454086 |
| k-d_tree_polars      |     0.560249 |       0.447867 |   0.463555 |
| barab-szabi-1        |     0.571825 |       0.452563 |   0.469338 |
| Bori_Aron_solution-1 |     0.550365 |       0.613414 |   0.58502  |
| k-d_tree_pandas      |     0.560071 |       0.424123 |   0.623093 |
| k-d_tree_sklearn     |     0.557811 |       1.04725  |   1.15451  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550032 |       0.53126  |   0.48145  |
| k-d_tree_polars      |     0.554521 |       0.566228 |   0.563379 |
| Bori_Aron_solution-1 |     0.543547 |       0.782004 |   0.58126  |
| barab-szabi-1        |     0.550711 |       0.566111 |   0.58412  |
| k-d_tree_pandas      |     0.558361 |       0.502865 |   0.762632 |
| k-d_tree_sklearn     |     0.559206 |       1.29393  |   1.19759  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565201 |       0.778452 |   0.530331 |
| Bori_Aron_solution-1 |     0.548748 |       1.44959  |   0.607122 |
| k-d_tree_polars      |     0.565503 |       0.90743  |   0.955874 |
| barab-szabi-1        |     0.565557 |       0.905306 |   0.979382 |
| k-d_tree_pandas      |     0.56497  |       0.781006 |   1.25411  |
| k-d_tree_sklearn     |     0.583965 |       2.31204  |   1.32957  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563651 |        5.53224 |   0.774925 |
| Bori_Aron_solution-1 |     0.54364  |       10.9232  |   0.878537 |
| k-d_tree_sklearn     |     0.554033 |       17.1795  |   1.40366  |
| barab-szabi-1        |     0.577287 |        5.04999 |   6.86955  |
| k-d_tree_polars      |     0.552485 |        5.04722 |   6.92929  |
| k-d_tree_pandas      |     0.559242 |        3.97963 |   7.23535  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.568915 |        77.4682 |    2.85566 |
| k-d_tree_sklearn     |     0.743752 |       249.241  |    4.08926 |
| Bori_Aron_solution-1 |     0.558531 |       146.237  |   17.5409  |