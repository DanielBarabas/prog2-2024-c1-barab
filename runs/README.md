# 2025-04-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.08083  |       1e-06    |   0.358666 |
| k-d_tree_polars      |     0.553954 |       0.402076 |   0.413744 |
| barab-szabi-2        |     0.557934 |       0.422806 |   0.418768 |
| barab-szabi-1        |     0.576376 |       0.409736 |   0.421123 |
| Bori_Aron_solution-1 |     0.557904 |       0.542731 |   0.5568   |
| k-d_tree_pandas      |     7.44634  |       0.404774 |   0.612513 |
| k-d_tree_sklearn     |     3.22233  |       0.997598 |   1.03744  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.570141 |       0.415024 |   0.417445 |
| k-d_tree_polars      |     0.577637 |       0.416842 |   0.420393 |
| barab-szabi-2        |     0.574907 |       0.414102 |   0.456771 |
| Bori_Aron_solution-1 |     0.572405 |       0.565893 |   0.547177 |
| k-d_tree_pandas      |     0.570404 |       0.395365 |   0.560582 |
| k-d_tree_sklearn     |     0.580076 |       0.994376 |   1.04351  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.567295 |       0.451141 |   0.450901 |
| k-d_tree_polars      |     0.572963 |       0.448669 |   0.454389 |
| barab-szabi-2        |     0.576392 |       0.43301  |   0.458671 |
| Bori_Aron_solution-1 |     0.559471 |       0.615994 |   0.552716 |
| k-d_tree_pandas      |     0.57942  |       0.419036 |   0.611094 |
| k-d_tree_sklearn     |     0.589679 |       1.0356   |   1.06661  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561486 |       0.481678 |   0.451644 |
| k-d_tree_polars      |     0.572525 |       0.542387 |   0.542295 |
| barab-szabi-1        |     0.565245 |       0.556196 |   0.556326 |
| Bori_Aron_solution-1 |     0.563991 |       0.764548 |   0.571653 |
| k-d_tree_pandas      |     0.566209 |       0.485783 |   0.739697 |
| k-d_tree_sklearn     |     0.569201 |       1.22277  |   1.12075  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57802  |       0.735509 |   0.484449 |
| Bori_Aron_solution-1 |     0.565909 |       1.42585  |   0.600276 |
| k-d_tree_polars      |     0.568294 |       0.884301 |   0.905647 |
| barab-szabi-1        |     0.576789 |       0.894632 |   0.926997 |
| k-d_tree_pandas      |     0.570583 |       0.770312 |   1.18096  |
| k-d_tree_sklearn     |     0.572048 |       2.06646  |   1.24039  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.576956 |        5.78959 |   0.754101 |
| Bori_Aron_solution-1 |     0.572828 |       11.1409  |   0.889832 |
| k-d_tree_sklearn     |     0.592215 |       17.1543  |   1.33045  |
| barab-szabi-1        |     0.57067  |        5.08958 |   6.99683  |
| k-d_tree_polars      |     0.587158 |        5.06836 |   7.00867  |
| k-d_tree_pandas      |     0.583457 |        3.99781 |   7.40878  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.773418 |        74.7285 |    3.32467 |
| k-d_tree_sklearn     |     0.652089 |       237.284  |    4.19737 |
| Bori_Aron_solution-1 |     0.561709 |       155.145  |   15.0536  |