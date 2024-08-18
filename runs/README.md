# 2024-08-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     8.34645  |       0.567086 |   0.390976 |
| barab-szabi-1        |     0.615237 |       0.404123 |   0.391141 |
| k-d_tree_polars      |     0.599391 |       0.401473 |   0.411454 |
| solution-1           |     8.13961  |       1e-06    |   0.432377 |
| k-d_tree_pandas      |     0.626236 |       0.405283 |   0.530654 |
| Bori_Aron_solution-1 |     0.617539 |       0.522735 |   0.570583 |
| k-d_tree_sklearn     |     2.99383  |       0.991016 |   0.754704 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.612871 |       0.406446 |   0.391777 |
| k-d_tree_polars      |     0.620057 |       0.407945 |   0.397338 |
| barab-szabi-2        |     0.611128 |       0.391551 |   0.398323 |
| Bori_Aron_solution-1 |     0.627556 |       0.533408 |   0.52864  |
| k-d_tree_pandas      |     0.614029 |       0.384917 |   0.52958  |
| k-d_tree_sklearn     |     0.618641 |       0.901507 |   0.711515 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611323 |       0.4084   |   0.407527 |
| k-d_tree_polars      |     0.631881 |       0.425378 |   0.417175 |
| barab-szabi-1        |     0.615817 |       0.427625 |   0.427831 |
| Bori_Aron_solution-1 |     0.603089 |       0.565158 |   0.519081 |
| k-d_tree_pandas      |     0.609956 |       0.402831 |   0.59145  |
| k-d_tree_sklearn     |     0.619606 |       0.935572 |   0.774374 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613702 |       0.464147 |   0.426905 |
| k-d_tree_polars      |     0.622985 |       0.534683 |   0.528657 |
| barab-szabi-1        |     0.609678 |       0.544253 |   0.531426 |
| Bori_Aron_solution-1 |     0.603341 |       0.747823 |   0.548006 |
| k-d_tree_pandas      |     0.626582 |       0.486634 |   0.717925 |
| k-d_tree_sklearn     |     0.618498 |       1.16685  |   0.798705 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610101 |       0.719554 |   0.466316 |
| Bori_Aron_solution-1 |     0.617085 |       1.39026  |   0.562906 |
| k-d_tree_polars      |     0.615607 |       0.853139 |   0.861668 |
| k-d_tree_sklearn     |     0.621845 |       2.0235   |   0.882032 |
| barab-szabi-1        |     0.611656 |       0.856047 |   0.915214 |
| k-d_tree_pandas      |     0.623154 |       0.74962  |   1.1546   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609384 |        5.37663 |   0.745896 |
| Bori_Aron_solution-1 |     0.618198 |       10.7921  |   0.85285  |
| k-d_tree_sklearn     |     0.612717 |       16.2461  |   0.996341 |
| k-d_tree_polars      |     0.625037 |        4.85373 |   6.51903  |
| barab-szabi-1        |     0.622589 |        4.86056 |   6.62692  |
| k-d_tree_pandas      |     0.618894 |        3.91279 |   6.9743   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610409 |        76.4988 |    3.06052 |
| k-d_tree_sklearn     |     0.651766 |       238.299  |    3.93176 |
| Bori_Aron_solution-1 |     0.709466 |       151.746  |   17.3799  |