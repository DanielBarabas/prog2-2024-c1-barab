# 2025-03-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.40965  |       1e-06    |   0.353907 |
| barab-szabi-2        |     0.567564 |       0.403635 |   0.398629 |
| k-d_tree_polars      |     0.575242 |       0.398169 |   0.402607 |
| barab-szabi-1        |     0.573411 |       0.403925 |   0.411805 |
| Bori_Aron_solution-1 |     0.569361 |       0.541825 |   0.535051 |
| k-d_tree_pandas      |     7.78443  |       0.403344 |   0.581198 |
| k-d_tree_sklearn     |     2.92371  |       0.982071 |   1.01698  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.58539  |       0.447635 |   0.402961 |
| k-d_tree_polars      |     0.586041 |       0.407387 |   0.408129 |
| barab-szabi-1        |     0.587181 |       0.412031 |   0.412281 |
| Bori_Aron_solution-1 |     0.610358 |       0.547444 |   0.542814 |
| k-d_tree_pandas      |     0.584152 |       0.385122 |   0.555367 |
| k-d_tree_sklearn     |     0.588111 |       0.969288 |   1.02565  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.601362 |       0.418167 |   0.41765  |
| k-d_tree_polars      |     0.585673 |       0.432713 |   0.43677  |
| barab-szabi-1        |     0.586563 |       0.433162 |   0.437594 |
| Bori_Aron_solution-1 |     0.57692  |       0.583934 |   0.542235 |
| k-d_tree_pandas      |     0.586523 |       0.406413 |   0.590735 |
| k-d_tree_sklearn     |     0.58935  |       0.98992  |   1.03971  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584885 |       0.487298 |   0.447688 |
| k-d_tree_polars      |     0.596273 |       0.536488 |   0.530593 |
| barab-szabi-1        |     0.58842  |       0.539754 |   0.539953 |
| Bori_Aron_solution-1 |     0.578578 |       0.75516  |   0.553954 |
| k-d_tree_pandas      |     0.58475  |       0.481031 |   0.727797 |
| k-d_tree_sklearn     |     0.587059 |       1.21942  |   1.11088  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581844 |       0.729162 |   0.481109 |
| Bori_Aron_solution-1 |     0.580694 |       1.38211  |   0.585215 |
| k-d_tree_polars      |     0.587941 |       0.969486 |   0.875429 |
| barab-szabi-1        |     0.586433 |       0.867718 |   0.91681  |
| k-d_tree_pandas      |     0.588011 |       0.741686 |   1.1654   |
| k-d_tree_sklearn     |     0.586072 |       2.03525  |   1.19492  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586261 |        5.43133 |   0.760298 |
| Bori_Aron_solution-1 |     0.578938 |       10.6298  |   0.891753 |
| k-d_tree_sklearn     |     0.58933  |       16.1737  |   1.30425  |
| barab-szabi-1        |     0.58351  |        4.85074 |   6.69616  |
| k-d_tree_polars      |     0.585064 |        4.91312 |   6.69996  |
| k-d_tree_pandas      |     0.585083 |        3.81154 |   7.02974  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.708171 |        74.4077 |    3.65343 |
| k-d_tree_sklearn     |     0.636587 |       233.307  |    4.26733 |
| Bori_Aron_solution-1 |     0.581626 |       152.438  |   16.1483  |