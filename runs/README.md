# 2026-09-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.09767  |       1e-06    |   0.329562 |
| barab-szabi-2        |     0.382708 |       0.392115 |   0.388996 |
| k-d_tree_polars      |     0.373884 |       0.355562 |   0.395045 |
| Bori_Aron_solution-1 |     0.373029 |       0.471072 |   0.472688 |
| k-d_tree_pandas      |     0.375404 |       0.334676 |   0.476287 |
| barab-szabi-1        |     8.28749  |       0.394867 |   0.495441 |
| k-d_tree_sklearn     |     2.62259  |       0.957832 |   0.900891 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.381086 |       0.386289 |   0.383636 |
| barab-szabi-1        |     0.38336  |       0.359818 |   0.399929 |
| k-d_tree_polars      |     0.389833 |       0.373027 |   0.411313 |
| Bori_Aron_solution-1 |     0.377761 |       0.481145 |   0.471187 |
| k-d_tree_pandas      |     0.383956 |       0.340059 |   0.473142 |
| k-d_tree_sklearn     |     0.390888 |       0.851855 |   0.904567 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.386801 |       0.413933 |   0.398089 |
| k-d_tree_polars      |     0.383813 |       0.386678 |   0.411283 |
| barab-szabi-1        |     0.383623 |       0.384164 |   0.419847 |
| Bori_Aron_solution-1 |     0.376145 |       0.500862 |   0.468881 |
| k-d_tree_pandas      |     0.383156 |       0.357801 |   0.521933 |
| k-d_tree_sklearn     |     0.389194 |       0.877552 |   0.926097 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.381732 |       0.456812 |   0.421669 |
| k-d_tree_polars      |     0.382482 |       0.508221 |   0.476854 |
| barab-szabi-1        |     0.385971 |       0.514853 |   0.491821 |
| Bori_Aron_solution-1 |     0.375078 |       0.646237 |   0.539057 |
| k-d_tree_pandas      |     0.386157 |       0.421449 |   0.601244 |
| k-d_tree_sklearn     |     0.386402 |       1.11692  |   0.991136 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.384886 |       0.643325 |   0.466195 |
| Bori_Aron_solution-1 |     0.376741 |       1.20612  |   0.511375 |
| k-d_tree_polars      |     0.383049 |       0.817322 |   0.767604 |
| barab-szabi-1        |     0.38182  |       0.840273 |   0.796062 |
| k-d_tree_pandas      |     0.387454 |       0.652452 |   0.941917 |
| k-d_tree_sklearn     |     0.388784 |       1.91408  |   1.00347  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.381918 |        4.03149 |   0.641711 |
| Bori_Aron_solution-1 |     0.383622 |        8.61311 |   0.80654  |
| k-d_tree_sklearn     |     0.387617 |       13.3424  |   1.12309  |
| barab-szabi-1        |     0.38494  |        4.73582 |   5.28651  |
| k-d_tree_polars      |     0.384048 |        4.77999 |   5.32471  |
| k-d_tree_pandas      |     0.384156 |        3.33552 |   5.64877  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485229 |        58.3246 |    2.45863 |
| k-d_tree_sklearn     |     0.659117 |       167.169  |    3.75093 |
| Bori_Aron_solution-1 |     0.376698 |       136.686  |   27.8456  |