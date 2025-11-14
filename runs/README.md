# 2025-11-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.71377  |       1e-06    |   0.374172 |
| k-d_tree_polars      |     0.544266 |       0.409629 |   0.435194 |
| barab-szabi-2        |     0.529431 |       0.506806 |   0.440361 |
| barab-szabi-1        |     0.544508 |       0.412095 |   0.442372 |
| Bori_Aron_solution-1 |     0.532403 |       0.563339 |   0.552267 |
| k-d_tree_pandas      |     8.31489  |       0.435364 |   0.783758 |
| k-d_tree_sklearn     |     3.0062   |       1.23035  |   1.12431  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.532079 |       0.415748 |   0.437299 |
| k-d_tree_polars      |     0.535421 |       0.423565 |   0.438824 |
| barab-szabi-2        |     0.53378  |       0.432131 |   0.442776 |
| Bori_Aron_solution-1 |     0.528944 |       0.564699 |   0.554479 |
| k-d_tree_pandas      |     0.53514  |       0.397279 |   0.564801 |
| k-d_tree_sklearn     |     0.539818 |       1.00484  |   1.08382  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540083 |       0.457027 |   0.45284  |
| barab-szabi-1        |     0.537013 |       0.442934 |   0.462638 |
| k-d_tree_polars      |     0.535309 |       0.465358 |   0.467248 |
| Bori_Aron_solution-1 |     0.521642 |       0.609652 |   0.573424 |
| k-d_tree_pandas      |     0.532587 |       0.41763  |   0.614239 |
| k-d_tree_sklearn     |     0.537303 |       1.0541   |   1.09486  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537729 |       0.517898 |   0.475008 |
| k-d_tree_polars      |     0.545663 |       0.560063 |   0.560967 |
| barab-szabi-1        |     0.530744 |       0.560178 |   0.565971 |
| Bori_Aron_solution-1 |     0.521297 |       0.783886 |   0.571106 |
| k-d_tree_pandas      |     0.544069 |       0.5064   |   0.754284 |
| k-d_tree_sklearn     |     0.541287 |       1.26612  |   1.14184  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539254 |       0.746409 |   0.51129  |
| Bori_Aron_solution-1 |     0.528852 |       1.48164  |   0.59619  |
| k-d_tree_polars      |     0.543353 |       0.919942 |   0.947594 |
| barab-szabi-1        |     0.536928 |       0.938072 |   0.971683 |
| k-d_tree_pandas      |     0.538876 |       0.815701 |   1.18921  |
| k-d_tree_sklearn     |     0.541378 |       2.16031  |   1.24214  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529141 |        5.87646 |   0.763957 |
| Bori_Aron_solution-1 |     0.529797 |       11.4783  |   0.846053 |
| k-d_tree_sklearn     |     0.535964 |       17.9783  |   1.35075  |
| k-d_tree_polars      |     0.542785 |        5.4753  |   7.01963  |
| barab-szabi-1        |     0.540605 |        5.40676 |   7.2656   |
| k-d_tree_pandas      |     0.53492  |        4.44712 |   7.2941   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536973 |        81.5489 |    2.71453 |
| k-d_tree_sklearn     |     0.554511 |       241.583  |    4.26139 |
| Bori_Aron_solution-1 |     0.66014  |       143.475  |   17.9489  |