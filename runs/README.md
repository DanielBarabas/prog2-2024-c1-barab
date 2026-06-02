# 2026-06-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.50793  |       1e-06    |   0.438678 |
| barab-szabi-2        |     0.46445  |       0.450679 |   0.445477 |
| k-d_tree_polars      |     0.464074 |       0.410866 |   0.448282 |
| Bori_Aron_solution-1 |     0.459625 |       0.555223 |   0.546592 |
| k-d_tree_pandas      |     0.46639  |       0.386755 |   0.558777 |
| barab-szabi-1        |     7.98482  |       0.5014   |   0.629472 |
| k-d_tree_sklearn     |     2.88857  |       1.20656  |   1.10267  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.474559 |       0.408762 |   0.442217 |
| barab-szabi-1        |     0.476167 |       0.416775 |   0.445604 |
| barab-szabi-2        |     0.475146 |       0.437938 |   0.447336 |
| Bori_Aron_solution-1 |     0.472926 |       0.560465 |   0.546316 |
| k-d_tree_pandas      |     0.475424 |       0.399908 |   0.559389 |
| k-d_tree_sklearn     |     0.487378 |       1.00687  |   1.0946   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475912 |       0.453542 |   0.460647 |
| barab-szabi-1        |     0.479734 |       0.443516 |   0.473957 |
| k-d_tree_polars      |     0.476464 |       0.443545 |   0.497566 |
| Bori_Aron_solution-1 |     0.48736  |       0.593689 |   0.557388 |
| k-d_tree_pandas      |     0.468646 |       0.412828 |   0.601884 |
| k-d_tree_sklearn     |     0.49425  |       1.03754  |   1.11155  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477555 |       0.517396 |   0.495553 |
| Bori_Aron_solution-1 |     0.485834 |       0.800771 |   0.572977 |
| k-d_tree_polars      |     0.476558 |       0.567305 |   0.576    |
| barab-szabi-1        |     0.477211 |       0.561406 |   0.585948 |
| k-d_tree_pandas      |     0.490174 |       0.508146 |   0.742512 |
| k-d_tree_sklearn     |     0.482521 |       1.27656  |   1.165    |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481488 |       0.745704 |   0.52222  |
| Bori_Aron_solution-1 |     0.466957 |       1.46155  |   0.581026 |
| k-d_tree_polars      |     0.477767 |       0.943331 |   0.930998 |
| barab-szabi-1        |     0.477746 |       0.94047  |   0.976476 |
| k-d_tree_pandas      |     0.472509 |       0.822421 |   1.16918  |
| k-d_tree_sklearn     |     0.479055 |       2.10732  |   1.25462  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484465 |        5.44131 |   0.784141 |
| Bori_Aron_solution-1 |     0.475101 |       11.515   |   0.829654 |
| k-d_tree_sklearn     |     0.480868 |       17.6062  |   1.31183  |
| k-d_tree_polars      |     0.498133 |        5.40376 |   6.93167  |
| barab-szabi-1        |     0.479293 |        5.56787 |   6.98756  |
| k-d_tree_pandas      |     0.489904 |        4.55841 |   7.47936  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47875  |        71.9376 |    2.91638 |
| k-d_tree_sklearn     |     0.941805 |       235.013  |    3.98583 |
| Bori_Aron_solution-1 |     0.482048 |       147.732  |   28.7508  |