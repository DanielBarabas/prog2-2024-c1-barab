# 2025-08-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.08202  |       1e-06    |   0.415972 |
| barab-szabi-2        |     0.518867 |       0.423069 |   0.424816 |
| k-d_tree_polars      |     0.536583 |       0.398974 |   0.426656 |
| barab-szabi-1        |     0.523621 |       0.414307 |   0.467925 |
| Bori_Aron_solution-1 |     0.525813 |       0.575225 |   0.549872 |
| k-d_tree_pandas      |     8.29282  |       0.407582 |   0.658999 |
| k-d_tree_sklearn     |     3.09451  |       1.05332  |   1.04377  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532726 |       0.422291 |   0.41987  |
| k-d_tree_polars      |     0.529737 |       0.405298 |   0.430001 |
| barab-szabi-1        |     0.530116 |       0.412365 |   0.430704 |
| Bori_Aron_solution-1 |     0.527969 |       0.547367 |   0.547518 |
| k-d_tree_pandas      |     0.531946 |       0.390034 |   0.551688 |
| k-d_tree_sklearn     |     0.55393  |       0.952713 |   1.03566  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.530093 |       0.43153  |   0.451161 |
| barab-szabi-1        |     0.537259 |       0.433542 |   0.452668 |
| barab-szabi-2        |     0.529885 |       0.43303  |   0.456041 |
| Bori_Aron_solution-1 |     0.531609 |       0.583739 |   0.546557 |
| k-d_tree_pandas      |     0.53344  |       0.404904 |   0.596219 |
| k-d_tree_sklearn     |     0.540415 |       1.00301  |   1.06794  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531101 |       0.490719 |   0.464204 |
| k-d_tree_polars      |     0.532422 |       0.54745  |   0.546956 |
| Bori_Aron_solution-1 |     0.527505 |       0.760576 |   0.553486 |
| barab-szabi-1        |     0.557054 |       0.543948 |   0.557935 |
| k-d_tree_pandas      |     0.535638 |       0.487226 |   0.727276 |
| k-d_tree_sklearn     |     0.537228 |       1.23363  |   1.12968  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53458  |       0.748672 |   0.490276 |
| Bori_Aron_solution-1 |     0.522497 |       1.39055  |   0.575386 |
| k-d_tree_polars      |     0.533941 |       0.884212 |   0.900109 |
| barab-szabi-1        |     0.532827 |       0.880789 |   0.939936 |
| k-d_tree_pandas      |     0.530215 |       0.760104 |   1.17199  |
| k-d_tree_sklearn     |     0.53707  |       2.07298  |   1.20038  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533859 |        5.23439 |   0.722479 |
| Bori_Aron_solution-1 |     0.529296 |       10.6309  |   0.837237 |
| k-d_tree_sklearn     |     0.554073 |       16.0547  |   1.30033  |
| barab-szabi-1        |     0.529112 |        5.00474 |   6.5195   |
| k-d_tree_polars      |     0.535336 |        4.93091 |   6.5632   |
| k-d_tree_pandas      |     0.531553 |        3.93017 |   6.91152  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533921 |        72.5629 |    2.64316 |
| k-d_tree_sklearn     |     0.554976 |       229.236  |    4.19976 |
| Bori_Aron_solution-1 |     0.619963 |       145.257  |   18.1776  |