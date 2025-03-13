# 2025-03-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.56984  |       0.423629 |   0.422399 |
| barab-szabi-2        |     0.590981 |       0.452985 |   0.429069 |
| barab-szabi-1        |     0.56994  |       0.426428 |   0.457034 |
| solution-1           |     7.87496  |       2e-06    |   0.475605 |
| Bori_Aron_solution-1 |     0.56952  |       0.570502 |   0.576868 |
| k-d_tree_pandas      |     8.25512  |       0.455377 |   0.667308 |
| k-d_tree_sklearn     |     3.10617  |       1.13315  |   1.08416  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586097 |       0.434368 |   0.431466 |
| k-d_tree_polars      |     0.593538 |       0.44163  |   0.43195  |
| barab-szabi-1        |     0.589878 |       0.439293 |   0.443088 |
| Bori_Aron_solution-1 |     0.586886 |       0.578871 |   0.571663 |
| k-d_tree_pandas      |     0.593166 |       0.424066 |   0.622846 |
| k-d_tree_sklearn     |     0.597199 |       1.02162  |   1.09211  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585346 |       0.43597  |   0.435404 |
| k-d_tree_polars      |     0.598674 |       0.45173  |   0.450242 |
| barab-szabi-1        |     0.583979 |       0.455899 |   0.462489 |
| Bori_Aron_solution-1 |     0.583317 |       0.610571 |   0.566057 |
| k-d_tree_pandas      |     0.587594 |       0.430701 |   0.615124 |
| k-d_tree_sklearn     |     0.583139 |       1.04853  |   1.11033  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584785 |       0.515136 |   0.469463 |
| k-d_tree_polars      |     0.583722 |       0.561998 |   0.54857  |
| barab-szabi-1        |     0.585017 |       0.55285  |   0.560095 |
| Bori_Aron_solution-1 |     0.583203 |       0.779229 |   0.578226 |
| k-d_tree_pandas      |     0.603374 |       0.493985 |   0.767698 |
| k-d_tree_sklearn     |     0.59862  |       1.2661   |   1.19381  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58253  |       0.77403  |   0.538962 |
| Bori_Aron_solution-1 |     0.574153 |       1.45826  |   0.617784 |
| k-d_tree_polars      |     0.588666 |       0.88809  |   0.942731 |
| barab-szabi-1        |     0.601185 |       0.888714 |   0.974794 |
| k-d_tree_pandas      |     0.586182 |       0.765731 |   1.24181  |
| k-d_tree_sklearn     |     0.593845 |       2.17992  |   1.26885  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584974 |        5.77164 |   0.792067 |
| Bori_Aron_solution-1 |     0.576192 |       11.1755  |   0.903589 |
| k-d_tree_sklearn     |     0.58941  |       17.2832  |   1.36224  |
| k-d_tree_polars      |     0.589611 |        5.01398 |   7.21043  |
| barab-szabi-1        |     0.586004 |        4.99751 |   7.25287  |
| k-d_tree_pandas      |     0.581232 |        3.86302 |   7.64494  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.863863 |        76.7584 |    3.16038 |
| k-d_tree_sklearn     |     0.67772  |       240.195  |    4.33723 |
| Bori_Aron_solution-1 |     0.575454 |       157.256  |   16.0992  |