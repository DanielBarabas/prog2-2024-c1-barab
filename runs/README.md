# 2025-01-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575878 |       0.413376 |   0.401578 |
| barab-szabi-1        |     0.577967 |       0.405918 |   0.404476 |
| k-d_tree_polars      |     0.601964 |       0.408993 |   0.410793 |
| solution-1           |     7.33997  |       1e-06    |   0.491377 |
| Bori_Aron_solution-1 |     0.59357  |       0.548599 |   0.546343 |
| k-d_tree_pandas      |     7.58332  |       0.393868 |   0.634644 |
| k-d_tree_sklearn     |     3.02712  |       0.977606 |   1.0358   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589003 |       0.404805 |   0.40107  |
| k-d_tree_polars      |     0.593446 |       0.404684 |   0.4124   |
| barab-szabi-1        |     0.59067  |       0.403718 |   0.455751 |
| Bori_Aron_solution-1 |     0.578123 |       0.55054  |   0.53117  |
| k-d_tree_pandas      |     0.593593 |       0.386017 |   0.543024 |
| k-d_tree_sklearn     |     0.595316 |       0.948309 |   1.02366  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590275 |       0.418085 |   0.418054 |
| k-d_tree_polars      |     0.585793 |       0.426356 |   0.433837 |
| barab-szabi-1        |     0.587234 |       0.445967 |   0.441749 |
| Bori_Aron_solution-1 |     0.598213 |       0.570503 |   0.537708 |
| k-d_tree_pandas      |     0.594191 |       0.403966 |   0.578246 |
| k-d_tree_sklearn     |     0.59346  |       1.05014  |   1.09837  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588327 |       0.479669 |   0.445382 |
| k-d_tree_polars      |     0.588537 |       0.53309  |   0.529174 |
| barab-szabi-1        |     0.591177 |       0.534383 |   0.541569 |
| Bori_Aron_solution-1 |     0.583773 |       0.751813 |   0.542305 |
| k-d_tree_pandas      |     0.585655 |       0.477711 |   0.721512 |
| k-d_tree_sklearn     |     0.594735 |       1.2174   |   1.10139  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.594388 |       0.709566 |   0.478154 |
| Bori_Aron_solution-1 |     0.587609 |       1.37597  |   0.571595 |
| k-d_tree_polars      |     0.585586 |       0.848133 |   0.874768 |
| barab-szabi-1        |     0.592532 |       0.862897 |   0.928851 |
| k-d_tree_pandas      |     0.589119 |       0.741906 |   1.15514  |
| k-d_tree_sklearn     |     0.604934 |       2.00746  |   1.20259  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591768 |        5.24055 |   0.733972 |
| Bori_Aron_solution-1 |     0.585593 |       10.5762  |   0.829225 |
| k-d_tree_sklearn     |     0.596337 |       15.8918  |   1.31153  |
| barab-szabi-1        |     0.592888 |        4.8006  |   6.51218  |
| k-d_tree_polars      |     0.594138 |        4.78676 |   6.53631  |
| k-d_tree_pandas      |     0.588821 |        3.81128 |   6.95978  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591411 |        75.8366 |    2.99522 |
| k-d_tree_sklearn     |     0.60024  |       228.054  |    4.57539 |
| Bori_Aron_solution-1 |     0.691075 |       151.034  |   16.5867  |