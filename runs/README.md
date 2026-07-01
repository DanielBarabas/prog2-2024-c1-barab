# 2026-07-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.468313 |       0.410376 |   0.429279 |
| solution-1           |     8.07007  |       1e-06    |   0.430612 |
| barab-szabi-1        |     0.471397 |       0.409392 |   0.43299  |
| barab-szabi-2        |     8.89137  |       0.640163 |   0.46859  |
| Bori_Aron_solution-1 |     0.451546 |       0.538933 |   0.545952 |
| k-d_tree_pandas      |     0.474023 |       0.383503 |   0.547369 |
| k-d_tree_sklearn     |     3.42328  |       1.26698  |   1.12069  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485213 |       0.430851 |   0.445221 |
| k-d_tree_polars      |     0.471094 |       0.421992 |   0.450562 |
| barab-szabi-1        |     0.475609 |       0.415814 |   0.468344 |
| k-d_tree_pandas      |     0.472542 |       0.398692 |   0.56244  |
| Bori_Aron_solution-1 |     0.479064 |       0.584571 |   0.563008 |
| k-d_tree_sklearn     |     0.475869 |       1.02794  |   1.0901   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479548 |       0.447527 |   0.449261 |
| k-d_tree_polars      |     0.468011 |       0.435386 |   0.462409 |
| barab-szabi-1        |     0.479179 |       0.450971 |   0.463843 |
| Bori_Aron_solution-1 |     0.469055 |       0.596313 |   0.552044 |
| k-d_tree_pandas      |     0.473007 |       0.413297 |   0.592863 |
| k-d_tree_sklearn     |     0.472931 |       1.0535   |   1.12139  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477304 |       0.512974 |   0.476439 |
| Bori_Aron_solution-1 |     0.485193 |       0.778047 |   0.557759 |
| k-d_tree_polars      |     0.475437 |       0.552716 |   0.56321  |
| barab-szabi-1        |     0.477634 |       0.574663 |   0.589596 |
| k-d_tree_pandas      |     0.474871 |       0.50173  |   0.733505 |
| k-d_tree_sklearn     |     0.477639 |       1.35097  |   1.13784  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472929 |       0.768297 |   0.542425 |
| Bori_Aron_solution-1 |     0.4744   |       1.45573  |   0.579939 |
| k-d_tree_polars      |     0.468629 |       0.907487 |   0.956984 |
| barab-szabi-1        |     0.483279 |       0.898778 |   1.01334  |
| k-d_tree_pandas      |     0.4739   |       0.796469 |   1.20784  |
| k-d_tree_sklearn     |     0.472732 |       2.26822  |   1.26409  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472696 |        5.74075 |   0.750308 |
| Bori_Aron_solution-1 |     0.45522  |       11.6837  |   0.845611 |
| k-d_tree_sklearn     |     0.488183 |       17.8838  |   1.28416  |
| barab-szabi-1        |     0.470012 |        5.04429 |   7.58692  |
| k-d_tree_polars      |     0.485219 |        5.15024 |   7.64916  |
| k-d_tree_pandas      |     0.477714 |        4.02824 |   7.95264  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472616 |        82.5054 |    2.83504 |
| k-d_tree_sklearn     |     0.798748 |       268.857  |    3.52809 |
| Bori_Aron_solution-1 |     0.467641 |       155.677  |   18.6677  |