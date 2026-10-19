# 2026-10-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.94213  |       1e-06    |   0.4216   |
| barab-szabi-2        |     0.462686 |       0.441154 |   0.440794 |
| k-d_tree_polars      |     0.471238 |       0.4417   |   0.450521 |
| barab-szabi-1        |     8.50219  |       0.460113 |   0.487078 |
| k-d_tree_pandas      |     0.460806 |       0.382433 |   0.551632 |
| Bori_Aron_solution-1 |     0.454732 |       0.555839 |   0.560673 |
| k-d_tree_sklearn     |     3.37678  |       1.08014  |   1.08635  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474229 |       0.436772 |   0.430487 |
| k-d_tree_polars      |     0.476318 |       0.431226 |   0.442792 |
| barab-szabi-1        |     0.47675  |       0.434278 |   0.456389 |
| Bori_Aron_solution-1 |     0.474894 |       0.563745 |   0.554468 |
| k-d_tree_pandas      |     0.471184 |       0.403872 |   0.56158  |
| k-d_tree_sklearn     |     0.484343 |       1.01303  |   1.11132  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491631 |       0.459635 |   0.458178 |
| k-d_tree_polars      |     0.500606 |       0.463279 |   0.474387 |
| barab-szabi-1        |     0.489217 |       0.478578 |   0.482545 |
| Bori_Aron_solution-1 |     0.477018 |       0.609494 |   0.561699 |
| k-d_tree_pandas      |     0.498437 |       0.418353 |   0.603181 |
| k-d_tree_sklearn     |     0.495056 |       1.08824  |   1.16383  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.4906   |       0.540849 |   0.490255 |
| k-d_tree_polars      |     0.486807 |       0.604103 |   0.573559 |
| Bori_Aron_solution-1 |     0.492404 |       0.798999 |   0.580009 |
| barab-szabi-1        |     0.493581 |       0.601583 |   0.591972 |
| k-d_tree_pandas      |     0.50515  |       0.51671  |   0.762357 |
| k-d_tree_sklearn     |     0.500599 |       1.3652   |   1.20322  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481816 |       0.778493 |   0.530922 |
| Bori_Aron_solution-1 |     0.476007 |       1.49793  |   0.61649  |
| k-d_tree_polars      |     0.492352 |       0.954505 |   0.943669 |
| barab-szabi-1        |     0.49265  |       0.951403 |   0.995908 |
| k-d_tree_pandas      |     0.494722 |       0.822161 |   1.21416  |
| k-d_tree_sklearn     |     0.490918 |       2.22687  |   1.30216  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479132 |        5.3091  |   0.752963 |
| Bori_Aron_solution-1 |     0.492544 |       11.4786  |   0.849372 |
| k-d_tree_sklearn     |     0.469655 |       17.495   |   1.35797  |
| k-d_tree_polars      |     0.500462 |        5.31716 |   6.72098  |
| barab-szabi-1        |     0.504617 |        5.33489 |   7.05399  |
| k-d_tree_pandas      |     0.49507  |        4.39327 |   7.38773  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.676795 |        80.1792 |    3.14818 |
| k-d_tree_sklearn     |     0.627306 |       260.408  |    4.16534 |
| Bori_Aron_solution-1 |     0.501386 |       160.716  |   27.146   |