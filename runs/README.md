# 2024-12-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.679896 |       0.408114 |   0.393379 |
| k-d_tree_polars      |     0.63267  |       0.405499 |   0.397539 |
| barab-szabi-2        |     0.621019 |       0.396315 |   0.397844 |
| solution-1           |     8.05922  |       1e-06    |   0.502251 |
| Bori_Aron_solution-1 |     0.616906 |       0.533424 |   0.542026 |
| k-d_tree_pandas      |     0.626069 |       0.386498 |   0.545047 |
| k-d_tree_sklearn     |    10.4994   |       1.40317  |   1.02636  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.633925 |       0.430558 |   0.39791  |
| barab-szabi-2        |     0.639393 |       0.392772 |   0.399637 |
| k-d_tree_polars      |     0.623206 |       0.422453 |   0.400749 |
| k-d_tree_pandas      |     0.615096 |       0.397001 |   0.546924 |
| Bori_Aron_solution-1 |     0.61216  |       0.544547 |   0.568739 |
| k-d_tree_sklearn     |     0.644438 |       0.943653 |   1.00802  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627812 |       0.41052  |   0.401297 |
| k-d_tree_polars      |     0.640726 |       0.443498 |   0.419504 |
| barab-szabi-1        |     0.659185 |       0.438109 |   0.447073 |
| Bori_Aron_solution-1 |     0.673879 |       0.581352 |   0.527246 |
| k-d_tree_pandas      |     0.627916 |       0.413325 |   0.601189 |
| k-d_tree_sklearn     |     0.629541 |       1.00022  |   1.0614   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627285 |       0.476142 |   0.431787 |
| k-d_tree_polars      |     0.633952 |       0.536712 |   0.512224 |
| barab-szabi-1        |     0.617781 |       0.552353 |   0.53375  |
| Bori_Aron_solution-1 |     0.6209   |       0.776764 |   0.576762 |
| k-d_tree_pandas      |     0.631849 |       0.494428 |   0.746996 |
| k-d_tree_sklearn     |     0.66216  |       1.19046  |   1.07605  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629415 |       0.741457 |   0.467437 |
| Bori_Aron_solution-1 |     0.606156 |       1.40818  |   0.602065 |
| k-d_tree_polars      |     0.615777 |       0.863326 |   0.901328 |
| barab-szabi-1        |     0.622489 |       0.872009 |   0.906061 |
| k-d_tree_sklearn     |     0.632834 |       2.01905  |   1.13438  |
| k-d_tree_pandas      |     0.613829 |       0.76103  |   1.18236  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62474  |        5.38319 |   0.73263  |
| Bori_Aron_solution-1 |     0.621599 |       10.8004  |   0.826361 |
| k-d_tree_sklearn     |     0.621303 |       16.5496  |   1.25975  |
| k-d_tree_polars      |     0.607241 |        4.8984  |   6.63003  |
| barab-szabi-1        |     0.62622  |        4.92063 |   6.64062  |
| k-d_tree_pandas      |     0.607109 |        3.89751 |   7.01886  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634289 |        72.1977 |    3.02368 |
| k-d_tree_sklearn     |     0.62188  |       228.846  |    4.0923  |
| Bori_Aron_solution-1 |     0.63369  |       145.09   |   18.098   |