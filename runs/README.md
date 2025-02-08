# 2025-02-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.35913  |       1e-06    |   0.358902 |
| barab-szabi-1        |     0.582824 |       0.393421 |   0.399874 |
| barab-szabi-2        |     7.80278  |       0.533758 |   0.401209 |
| k-d_tree_polars      |     0.571151 |       0.394678 |   0.401631 |
| Bori_Aron_solution-1 |     0.570791 |       0.528027 |   0.532255 |
| k-d_tree_pandas      |     0.585362 |       0.383108 |   0.534652 |
| k-d_tree_sklearn     |     3.10971  |       0.962702 |   0.998512 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.582679 |       0.401422 |   0.403227 |
| k-d_tree_polars      |     0.580868 |       0.404907 |   0.408091 |
| barab-szabi-1        |     0.585478 |       0.405038 |   0.472293 |
| Bori_Aron_solution-1 |     0.580599 |       0.533293 |   0.52735  |
| k-d_tree_pandas      |     0.581399 |       0.382275 |   0.538634 |
| k-d_tree_sklearn     |     0.623818 |       0.934864 |   1.0144   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581901 |       0.420381 |   0.417654 |
| k-d_tree_polars      |     0.584064 |       0.428577 |   0.429045 |
| barab-szabi-1        |     0.587529 |       0.433095 |   0.458912 |
| Bori_Aron_solution-1 |     0.574866 |       0.570418 |   0.532474 |
| k-d_tree_pandas      |     0.585881 |       0.399706 |   0.583373 |
| k-d_tree_sklearn     |     0.616343 |       0.986193 |   1.04069  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585208 |       0.479406 |   0.440547 |
| k-d_tree_polars      |     0.583404 |       0.533174 |   0.531347 |
| barab-szabi-1        |     0.584777 |       0.53363  |   0.533438 |
| Bori_Aron_solution-1 |     0.574011 |       0.734987 |   0.539685 |
| k-d_tree_pandas      |     0.583062 |       0.480775 |   0.713629 |
| k-d_tree_sklearn     |     0.586573 |       1.21012  |   1.10059  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586892 |       0.722251 |   0.475033 |
| Bori_Aron_solution-1 |     0.577432 |       1.36399  |   0.569437 |
| k-d_tree_polars      |     0.582941 |       0.860247 |   0.881736 |
| barab-szabi-1        |     0.588784 |       0.864542 |   0.913475 |
| k-d_tree_pandas      |     0.579574 |       0.739061 |   1.15453  |
| k-d_tree_sklearn     |     0.586358 |       2.00774  |   1.18303  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580697 |        5.28922 |   0.731161 |
| Bori_Aron_solution-1 |     0.57655  |       10.5275  |   0.881249 |
| k-d_tree_sklearn     |     0.591093 |       16.0248  |   1.29391  |
| k-d_tree_polars      |     0.587474 |        4.89886 |   6.55933  |
| barab-szabi-1        |     0.586841 |        4.89946 |   6.71163  |
| k-d_tree_pandas      |     0.600243 |        3.84963 |   7.05018  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583169 |        74.0844 |    2.90463 |
| k-d_tree_sklearn     |     0.601521 |       223.599  |    4.4663  |
| Bori_Aron_solution-1 |     0.687246 |       148.508  |   16.1272  |