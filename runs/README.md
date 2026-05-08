# 2026-05-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.46858  |       0.415138 |   0.439538 |
| barab-szabi-2        |     0.468437 |       0.443527 |   0.441617 |
| k-d_tree_polars      |     0.465672 |       0.413655 |   0.445765 |
| solution-1           |     8.23737  |       1e-06    |   0.478244 |
| Bori_Aron_solution-1 |     0.463106 |       0.555955 |   0.551634 |
| k-d_tree_pandas      |     0.471113 |       0.395273 |   0.567843 |
| k-d_tree_sklearn     |    11.1639   |       1.51479  |   1.10534  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.466439 |       0.415452 |   0.433034 |
| k-d_tree_polars      |     0.462993 |       0.420253 |   0.433784 |
| barab-szabi-2        |     0.46243  |       0.431467 |   0.438843 |
| Bori_Aron_solution-1 |     0.466957 |       0.564112 |   0.549803 |
| k-d_tree_pandas      |     0.465156 |       0.394637 |   0.563182 |
| k-d_tree_sklearn     |     0.471748 |       1.03167  |   1.1124   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.455401 |       0.462482 |   0.441183 |
| barab-szabi-1        |     0.466691 |       0.444505 |   0.457036 |
| k-d_tree_polars      |     0.458855 |       0.439597 |   0.459453 |
| Bori_Aron_solution-1 |     0.455848 |       0.596512 |   0.544478 |
| k-d_tree_pandas      |     0.467352 |       0.408308 |   0.584678 |
| k-d_tree_sklearn     |     0.46618  |       1.03439  |   1.09073  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.458921 |       0.505492 |   0.464755 |
| k-d_tree_polars      |     0.463762 |       0.565061 |   0.555486 |
| Bori_Aron_solution-1 |     0.454003 |       0.790708 |   0.563166 |
| barab-szabi-1        |     0.459131 |       0.562469 |   0.569725 |
| k-d_tree_pandas      |     0.458193 |       0.498286 |   0.721442 |
| k-d_tree_sklearn     |     0.465126 |       1.26669  |   1.14088  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467349 |       0.757646 |   0.568595 |
| Bori_Aron_solution-1 |     0.44759  |       1.48231  |   0.588892 |
| k-d_tree_polars      |     0.462733 |       0.914394 |   0.982071 |
| barab-szabi-1        |     0.467759 |       0.932808 |   1.00303  |
| k-d_tree_sklearn     |     0.462521 |       2.14545  |   1.15185  |
| k-d_tree_pandas      |     0.466161 |       0.792042 |   1.21122  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462592 |        5.84443 |   0.764581 |
| Bori_Aron_solution-1 |     0.450342 |       11.6859  |   0.830044 |
| k-d_tree_sklearn     |     0.46531  |       18.1303  |   1.26154  |
| barab-szabi-1        |     0.460017 |        5.16    |   7.64149  |
| k-d_tree_polars      |     0.461253 |        5.40331 |   7.71957  |
| k-d_tree_pandas      |     0.461149 |        4.1907  |   7.99805  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.727881 |        81.5135 |    2.70829 |
| k-d_tree_sklearn     |     0.46573  |       269.58   |    3.38979 |
| Bori_Aron_solution-1 |     0.459117 |       160.595  |   17.597   |