# 2026-11-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     5.18874  |       1e-06    |   0.240931 |
| barab-szabi-1        |     0.314173 |       0.317638 |   0.324776 |
| barab-szabi-2        |     0.314254 |       0.330727 |   0.328018 |
| k-d_tree_polars      |     8.20288  |       0.320054 |   0.359395 |
| k-d_tree_pandas      |     0.295515 |       0.26225  |   0.374924 |
| Bori_Aron_solution-1 |     0.290429 |       0.383914 |   0.39397  |
| k-d_tree_sklearn     |     2.26302  |       0.764629 |   0.783356 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.332254 |       0.360199 |   0.330804 |
| barab-szabi-1        |     0.312299 |       0.37009  |   0.331817 |
| k-d_tree_polars      |     0.298983 |       0.308821 |   0.340673 |
| k-d_tree_pandas      |     0.311799 |       0.28561  |   0.401745 |
| Bori_Aron_solution-1 |     0.357353 |       0.417898 |   0.421409 |
| k-d_tree_sklearn     |     0.321017 |       0.83458  |   0.90239  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.32392  |       0.347116 |   0.350855 |
| barab-szabi-1        |     0.356113 |       0.380828 |   0.361826 |
| k-d_tree_polars      |     0.331208 |       0.43381  |   0.370441 |
| Bori_Aron_solution-1 |     0.337852 |       0.445649 |   0.42598  |
| k-d_tree_pandas      |     0.331053 |       0.322363 |   0.446419 |
| k-d_tree_sklearn     |     0.334398 |       0.898084 |   0.919391 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.306983 |       0.403343 |   0.330136 |
| k-d_tree_polars      |     0.344056 |       0.434027 |   0.411676 |
| Bori_Aron_solution-1 |     0.315938 |       0.582075 |   0.419363 |
| barab-szabi-1        |     0.313389 |       0.413648 |   0.427923 |
| k-d_tree_pandas      |     0.3427   |       0.398005 |   0.51505  |
| k-d_tree_sklearn     |     0.319753 |       0.947021 |   0.904677 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.348834 |       1.04348  |   0.496914 |
| barab-szabi-2        |     0.35323  |       0.606116 |   0.497646 |
| k-d_tree_polars      |     0.352966 |       0.723724 |   0.720032 |
| barab-szabi-1        |     0.342844 |       0.714068 |   0.735422 |
| k-d_tree_pandas      |     0.362228 |       0.570837 |   0.865155 |
| k-d_tree_sklearn     |     0.337305 |       1.60889  |   0.998071 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.342666 |        4.46417 |   0.748031 |
| Bori_Aron_solution-1 |     0.370803 |        8.25303 |   0.906909 |
| k-d_tree_sklearn     |     0.362035 |       13.2064  |   1.13555  |
| k-d_tree_polars      |     0.3369   |        3.87724 |   5.65405  |
| barab-szabi-1        |     0.360564 |        3.9018  |   5.66388  |
| k-d_tree_pandas      |     0.339352 |        2.53461 |   5.9605   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.458413 |       170.75   |    2.50588 |
| barab-szabi-2        |     0.605926 |        64.6082 |    3.5625  |
| Bori_Aron_solution-1 |     0.336042 |       132.392  |   21.974   |