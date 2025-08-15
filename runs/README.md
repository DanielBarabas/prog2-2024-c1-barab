# 2025-08-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527205 |       0.421438 |   0.424033 |
| solution-1           |     8.01495  |       1e-06    |   0.429479 |
| k-d_tree_polars      |     0.543584 |       0.401355 |   0.450511 |
| barab-szabi-1        |     0.527305 |       0.409257 |   0.467638 |
| Bori_Aron_solution-1 |     0.53666  |       0.552378 |   0.547397 |
| k-d_tree_pandas      |     8.09839  |       0.408592 |   0.691223 |
| k-d_tree_sklearn     |     2.98994  |       1.08066  |   1.05003  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540317 |       0.423808 |   0.42611  |
| barab-szabi-1        |     0.541985 |       0.415639 |   0.432112 |
| k-d_tree_polars      |     0.544358 |       0.41351  |   0.439704 |
| Bori_Aron_solution-1 |     0.53599  |       0.549998 |   0.547368 |
| k-d_tree_pandas      |     0.537385 |       0.391354 |   0.555295 |
| k-d_tree_sklearn     |     0.554381 |       0.960469 |   1.05945  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555006 |       0.432577 |   0.439322 |
| k-d_tree_polars      |     0.542554 |       0.437843 |   0.455557 |
| barab-szabi-1        |     0.541128 |       0.433028 |   0.460345 |
| Bori_Aron_solution-1 |     0.534758 |       0.584278 |   0.543289 |
| k-d_tree_pandas      |     0.5394   |       0.406531 |   0.593514 |
| k-d_tree_sklearn     |     0.546077 |       1.0115   |   1.0767   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541546 |       0.498948 |   0.46819  |
| k-d_tree_polars      |     0.542007 |       0.546041 |   0.55919  |
| barab-szabi-1        |     0.557203 |       0.546268 |   0.563514 |
| Bori_Aron_solution-1 |     0.533909 |       0.769564 |   0.569988 |
| k-d_tree_pandas      |     0.540944 |       0.489527 |   0.733049 |
| k-d_tree_sklearn     |     0.54487  |       1.22962  |   1.12613  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539062 |       0.751763 |   0.498312 |
| Bori_Aron_solution-1 |     0.536225 |       1.40257  |   0.585167 |
| k-d_tree_polars      |     0.547508 |       0.889723 |   0.905635 |
| barab-szabi-1        |     0.544933 |       0.890467 |   0.949072 |
| k-d_tree_pandas      |     0.540887 |       0.779981 |   1.18783  |
| k-d_tree_sklearn     |     0.545662 |       2.07159  |   1.21758  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54062  |        5.23481 |   0.746213 |
| Bori_Aron_solution-1 |     0.531954 |       10.583   |   0.842049 |
| k-d_tree_sklearn     |     0.544804 |       15.9899  |   1.32004  |
| barab-szabi-1        |     0.537709 |        5.00239 |   6.48882  |
| k-d_tree_polars      |     0.538645 |        4.98384 |   6.60787  |
| k-d_tree_pandas      |     0.539255 |        3.9561  |   6.87858  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541274 |         74.56  |    2.72507 |
| k-d_tree_sklearn     |     0.547527 |        233.584 |    4.0975  |
| Bori_Aron_solution-1 |     0.5897   |        142.305 |   17.8503  |