# 2025-07-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.569828 |       0.435443 |   0.457707 |
| k-d_tree_polars      |     0.605027 |       0.455997 |   0.467593 |
| barab-szabi-2        |     9.04139  |       0.718776 |   0.468063 |
| solution-1           |     8.96713  |       2.5e-05  |   0.559051 |
| k-d_tree_pandas      |     0.620149 |       0.407328 |   0.567173 |
| Bori_Aron_solution-1 |     0.57452  |       0.602676 |   0.608094 |
| k-d_tree_sklearn     |     3.39451  |       1.32726  |   1.23358  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.625122 |       0.460932 |   0.473367 |
| barab-szabi-2        |     0.579149 |       0.501031 |   0.48873  |
| barab-szabi-1        |     0.680468 |       0.507423 |   0.490635 |
| k-d_tree_pandas      |     0.596439 |       0.42961  |   0.622176 |
| Bori_Aron_solution-1 |     0.59011  |       0.631992 |   0.650172 |
| k-d_tree_sklearn     |     0.63509  |       1.05979  |   1.17694  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.601158 |       0.475575 |   0.46435  |
| k-d_tree_polars      |     0.620918 |       0.466243 |   0.479736 |
| barab-szabi-2        |     0.59752  |       0.479811 |   0.48474  |
| Bori_Aron_solution-1 |     0.585111 |       0.659078 |   0.653757 |
| k-d_tree_pandas      |     0.630276 |       0.452192 |   0.68696  |
| k-d_tree_sklearn     |     0.599916 |       1.13588  |   1.16924  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.595236 |       0.529012 |   0.489484 |
| k-d_tree_polars      |     0.616379 |       0.610506 |   0.571062 |
| barab-szabi-1        |     0.628268 |       0.606604 |   0.60303  |
| Bori_Aron_solution-1 |     0.606667 |       0.864745 |   0.60594  |
| k-d_tree_pandas      |     0.578847 |       0.564703 |   0.847113 |
| k-d_tree_sklearn     |     0.615917 |       1.40677  |   1.28208  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.633924 |       0.832091 |   0.659537 |
| Bori_Aron_solution-1 |     0.624244 |       1.52817  |   0.667521 |
| k-d_tree_polars      |     0.635793 |       0.954906 |   0.99746  |
| barab-szabi-1        |     0.598837 |       0.947101 |   1.01334  |
| k-d_tree_pandas      |     0.605734 |       0.799402 |   1.2837   |
| k-d_tree_sklearn     |     0.599279 |       2.47396  |   1.37437  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610135 |        5.95807 |   0.866584 |
| Bori_Aron_solution-1 |     0.687677 |       11.4939  |   0.881466 |
| k-d_tree_sklearn     |     0.576603 |       18.4745  |   1.50546  |
| k-d_tree_polars      |     0.607    |        5.17898 |   7.22717  |
| barab-szabi-1        |     0.626165 |        5.16632 |   7.23571  |
| k-d_tree_pandas      |     0.654908 |        4.034   |   7.63964  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.599944 |        77.8231 |    2.87512 |
| k-d_tree_sklearn     |     0.877421 |       250.011  |    4.25015 |
| Bori_Aron_solution-1 |     0.611043 |       146.579  |   18.1479  |