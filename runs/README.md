# 2024-11-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611387 |       0.389701 |   0.383335 |
| barab-szabi-1        |     0.620021 |       0.404817 |   0.394317 |
| k-d_tree_polars      |     0.629297 |       0.432263 |   0.394579 |
| solution-1           |     7.71224  |       1e-06    |   0.417414 |
| Bori_Aron_solution-1 |     0.633049 |       0.539809 |   0.547168 |
| k-d_tree_pandas      |     0.634918 |       0.401271 |   0.589104 |
| k-d_tree_sklearn     |    11.3836   |       0.979054 |   0.964918 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611655 |       0.400115 |   0.391133 |
| barab-szabi-1        |     0.617521 |       0.410824 |   0.394099 |
| k-d_tree_polars      |     0.632092 |       0.408709 |   0.396219 |
| Bori_Aron_solution-1 |     0.603791 |       0.523727 |   0.533422 |
| k-d_tree_pandas      |     0.607725 |       0.384357 |   0.546036 |
| k-d_tree_sklearn     |     0.644578 |       0.929747 |   1.01249  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.641624 |       0.411452 |   0.422808 |
| k-d_tree_polars      |     0.627903 |       0.429499 |   0.425257 |
| barab-szabi-1        |     0.624708 |       0.43632  |   0.439328 |
| Bori_Aron_solution-1 |     0.639732 |       0.584202 |   0.536817 |
| k-d_tree_pandas      |     0.642426 |       0.429571 |   0.587583 |
| k-d_tree_sklearn     |     0.618072 |       0.938846 |   1.01688  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62148  |       0.472075 |   0.434247 |
| k-d_tree_polars      |     0.626253 |       0.542964 |   0.530257 |
| barab-szabi-1        |     0.624562 |       0.549058 |   0.538271 |
| Bori_Aron_solution-1 |     0.628571 |       0.759094 |   0.541437 |
| k-d_tree_pandas      |     0.629183 |       0.492182 |   0.714273 |
| k-d_tree_sklearn     |     0.628685 |       1.16753  |   1.07664  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613497 |       0.723115 |   0.468425 |
| Bori_Aron_solution-1 |     0.601439 |       1.40847  |   0.582426 |
| k-d_tree_polars      |     0.624214 |       0.89307  |   0.864755 |
| barab-szabi-1        |     0.611241 |       0.858133 |   0.908315 |
| k-d_tree_sklearn     |     0.633237 |       2.02992  |   1.15755  |
| k-d_tree_pandas      |     0.630116 |       0.748702 |   1.1827   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614255 |        5.62741 |   0.764708 |
| Bori_Aron_solution-1 |     0.628676 |       10.9091  |   0.821139 |
| k-d_tree_sklearn     |     0.625784 |       16.4597  |   1.2604   |
| k-d_tree_polars      |     0.618045 |        4.92621 |   6.77116  |
| barab-szabi-1        |     0.608096 |        4.88372 |   7.03049  |
| k-d_tree_pandas      |     0.621861 |        3.91165 |   7.19318  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631904 |        73.9623 |    3.11762 |
| k-d_tree_sklearn     |     0.616288 |       234.137  |    4.26187 |
| Bori_Aron_solution-1 |     0.635306 |       150.304  |   17.0625  |