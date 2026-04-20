# 2026-04-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.473479 |       0.413334 |   0.430622 |
| barab-szabi-2        |     0.46935  |       0.438725 |   0.436692 |
| k-d_tree_polars      |     0.469308 |       0.409891 |   0.443387 |
| solution-1           |     7.94108  |       1e-06    |   0.485992 |
| k-d_tree_pandas      |     0.478928 |       0.432145 |   0.56359  |
| Bori_Aron_solution-1 |     0.472354 |       0.558407 |   0.563674 |
| k-d_tree_sklearn     |    10.8197   |       1.32048  |   1.15217  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.461957 |       0.420054 |   0.434437 |
| barab-szabi-2        |     0.473498 |       0.440161 |   0.442004 |
| barab-szabi-1        |     0.47406  |       0.445147 |   0.442119 |
| k-d_tree_pandas      |     0.481838 |       0.397682 |   0.574011 |
| Bori_Aron_solution-1 |     0.457439 |       0.555194 |   0.575408 |
| k-d_tree_sklearn     |     0.485603 |       1.07198  |   1.11565  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469137 |       0.448246 |   0.443568 |
| k-d_tree_polars      |     0.470109 |       0.441476 |   0.463916 |
| barab-szabi-1        |     0.471712 |       0.444746 |   0.474309 |
| Bori_Aron_solution-1 |     0.468495 |       0.602748 |   0.556606 |
| k-d_tree_pandas      |     0.483457 |       0.42713  |   0.598723 |
| k-d_tree_sklearn     |     0.465205 |       1.06168  |   1.11115  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483879 |       0.5026   |   0.490323 |
| barab-szabi-1        |     0.464756 |       0.564242 |   0.573971 |
| Bori_Aron_solution-1 |     0.454399 |       0.803108 |   0.580693 |
| k-d_tree_polars      |     0.480359 |       0.570419 |   0.583135 |
| k-d_tree_pandas      |     0.472106 |       0.508463 |   0.736419 |
| k-d_tree_sklearn     |     0.477513 |       1.31763  |   1.16088  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.490667 |       0.766347 |   0.512072 |
| Bori_Aron_solution-1 |     0.474866 |       1.5332   |   0.603348 |
| k-d_tree_polars      |     0.47651  |       0.917477 |   0.972557 |
| barab-szabi-1        |     0.469507 |       0.914907 |   1.00126  |
| k-d_tree_sklearn     |     0.485348 |       2.27776  |   1.18879  |
| k-d_tree_pandas      |     0.47219  |       0.792408 |   1.21355  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484769 |        5.78073 |   0.750064 |
| Bori_Aron_solution-1 |     0.46822  |       11.5212  |   0.816729 |
| k-d_tree_sklearn     |     0.474161 |       18.0229  |   1.33811  |
| k-d_tree_polars      |     0.468199 |        5.40972 |   7.59921  |
| barab-szabi-1        |     0.468316 |        5.40883 |   7.66586  |
| k-d_tree_pandas      |     0.480447 |        4.27623 |   7.97204  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.736157 |        77.4663 |    2.47598 |
| k-d_tree_sklearn     |     0.481314 |       261.628  |    3.14479 |
| Bori_Aron_solution-1 |     0.453847 |       154.893  |   17.3701  |