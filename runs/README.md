# 2025-04-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.97946  |       1e-06    |   0.37238  |
| barab-szabi-2        |     0.565148 |       0.415403 |   0.417049 |
| barab-szabi-1        |     0.56345  |       0.414133 |   0.420607 |
| k-d_tree_polars      |     8.32681  |       0.445962 |   0.513959 |
| k-d_tree_pandas      |     0.565106 |       0.402905 |   0.572565 |
| Bori_Aron_solution-1 |     0.554211 |       0.554743 |   0.585812 |
| k-d_tree_sklearn     |     3.10328  |       1.0389   |   1.09059  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.577578 |       0.422433 |   0.431943 |
| k-d_tree_polars      |     0.582568 |       0.417259 |   0.432331 |
| barab-szabi-2        |     0.585044 |       0.428988 |   0.453477 |
| Bori_Aron_solution-1 |     0.578302 |       0.583097 |   0.558353 |
| k-d_tree_pandas      |     0.576486 |       0.403848 |   0.57045  |
| k-d_tree_sklearn     |     0.585779 |       1.00212  |   1.08248  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.594184 |       0.445718 |   0.445577 |
| barab-szabi-1        |     0.586287 |       0.454103 |   0.458123 |
| k-d_tree_polars      |     0.584852 |       0.451689 |   0.465029 |
| Bori_Aron_solution-1 |     0.589328 |       0.606615 |   0.597639 |
| k-d_tree_pandas      |     0.606874 |       0.425562 |   0.649432 |
| k-d_tree_sklearn     |     0.600234 |       1.04818  |   1.10681  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575612 |       0.499837 |   0.462488 |
| k-d_tree_polars      |     0.577531 |       0.555725 |   0.560956 |
| barab-szabi-1        |     0.585766 |       0.566962 |   0.566324 |
| Bori_Aron_solution-1 |     0.56847  |       0.789155 |   0.591511 |
| k-d_tree_pandas      |     0.581771 |       0.526746 |   0.790227 |
| k-d_tree_sklearn     |     0.600739 |       1.37595  |   1.25875  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.604702 |       1.47632  |   0.634179 |
| barab-szabi-2        |     0.624309 |       0.802317 |   0.668831 |
| k-d_tree_polars      |     0.604815 |       0.922696 |   0.957282 |
| barab-szabi-1        |     0.625724 |       0.916837 |   1.03076  |
| k-d_tree_pandas      |     0.603067 |       0.777721 |   1.25066  |
| k-d_tree_sklearn     |     0.615569 |       2.30757  |   1.34066  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.573277 |        5.64823 |   0.770631 |
| Bori_Aron_solution-1 |     0.622361 |       11.038   |   0.962483 |
| k-d_tree_sklearn     |     0.588359 |       17.8661  |   1.39667  |
| k-d_tree_polars      |     0.592873 |        5.12723 |   6.74827  |
| barab-szabi-1        |     0.577955 |        5.11292 |   7.06487  |
| k-d_tree_pandas      |     0.582455 |        3.97598 |   7.45542  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.593198 |        74.6298 |    2.75843 |
| k-d_tree_sklearn     |     0.782012 |       233.488  |    4.53764 |
| Bori_Aron_solution-1 |     0.581599 |       144.986  |   18.1857  |