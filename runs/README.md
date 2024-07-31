# 2024-07-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.02502  |       0.379661 |   0.379567 |
| k-d_tree_polars      |     0.549093 |       0.386682 |   0.383538 |
| Bori_Aron_solution-1 |     0.567467 |       0.504208 |   0.510071 |
| k-d_tree_pandas      |     0.554894 |       0.369545 |   0.512954 |
| solution-1           |     8.18967  |       1e-06    |   0.535086 |
| barab-szabi-1        |     8.65573  |       0.479718 |   0.604593 |
| k-d_tree_sklearn     |     3.20362  |       1.04733  |   0.691805 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54811  |       0.389578 |   0.376906 |
| barab-szabi-1        |     0.543931 |       0.398823 |   0.382468 |
| k-d_tree_polars      |     0.543963 |       0.394079 |   0.389969 |
| Bori_Aron_solution-1 |     0.543701 |       0.544287 |   0.522487 |
| k-d_tree_pandas      |     0.552665 |       0.374391 |   0.523954 |
| k-d_tree_sklearn     |     0.553938 |       0.873717 |   0.693939 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549216 |       0.393713 |   0.391887 |
| k-d_tree_polars      |     0.548461 |       0.418428 |   0.40986  |
| barab-szabi-1        |     0.551498 |       0.419911 |   0.481767 |
| Bori_Aron_solution-1 |     0.54354  |       0.560484 |   0.522011 |
| k-d_tree_pandas      |     0.552125 |       0.392411 |   0.562443 |
| k-d_tree_sklearn     |     0.572441 |       0.926418 |   0.711255 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560495 |       0.464998 |   0.422327 |
| k-d_tree_polars      |     0.54713  |       0.523392 |   0.511481 |
| barab-szabi-1        |     0.550211 |       0.528366 |   0.522449 |
| Bori_Aron_solution-1 |     0.548588 |       0.738275 |   0.528005 |
| k-d_tree_pandas      |     0.555412 |       0.476578 |   0.703046 |
| k-d_tree_sklearn     |     0.55507  |       1.14316  |   0.780561 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550375 |       0.716342 |   0.453996 |
| Bori_Aron_solution-1 |     0.543918 |       1.37619  |   0.55205  |
| k-d_tree_polars      |     0.552085 |       0.845902 |   0.856411 |
| k-d_tree_sklearn     |     0.555367 |       1.95253  |   0.865453 |
| barab-szabi-1        |     0.553501 |       0.849377 |   0.895817 |
| k-d_tree_pandas      |     0.557533 |       0.742495 |   1.22179  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548779 |        5.43713 |   0.733302 |
| Bori_Aron_solution-1 |     0.543432 |       10.8531  |   0.843816 |
| k-d_tree_sklearn     |     0.551971 |       16.1093  |   0.975217 |
| barab-szabi-1        |     0.552135 |        4.82482 |   6.57173  |
| k-d_tree_polars      |     0.550624 |        4.8455  |   6.65846  |
| k-d_tree_pandas      |     0.54941  |        3.91176 |   7.03468  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553223 |        71.9644 |    3.06857 |
| k-d_tree_sklearn     |     0.572361 |       229.997  |    3.88594 |
| Bori_Aron_solution-1 |     0.608689 |       152.168  |   16.7103  |