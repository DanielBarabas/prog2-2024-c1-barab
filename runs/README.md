# 2025-09-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.81265  |       1e-06    |   0.387073 |
| barab-szabi-2        |     8.39299  |       0.569542 |   0.443161 |
| barab-szabi-1        |     0.605678 |       0.429121 |   0.454467 |
| k-d_tree_polars      |     0.553785 |       0.426233 |   0.481942 |
| k-d_tree_pandas      |     0.555923 |       0.407718 |   0.575624 |
| Bori_Aron_solution-1 |     0.537127 |       0.570151 |   0.588522 |
| k-d_tree_sklearn     |     3.00986  |       1.19758  |   1.12288  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.562287 |       0.43278  |   0.441963 |
| barab-szabi-1        |     0.564297 |       0.432304 |   0.443713 |
| barab-szabi-2        |     0.563688 |       0.450329 |   0.446477 |
| Bori_Aron_solution-1 |     0.556887 |       0.592661 |   0.572629 |
| k-d_tree_pandas      |     0.574791 |       0.41145  |   0.607033 |
| k-d_tree_sklearn     |     0.559871 |       0.995231 |   1.11552  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564471 |       0.456658 |   0.451643 |
| barab-szabi-1        |     0.573949 |       0.460121 |   0.47569  |
| k-d_tree_polars      |     0.547754 |       0.455094 |   0.487401 |
| Bori_Aron_solution-1 |     0.552381 |       0.622269 |   0.59436  |
| k-d_tree_pandas      |     0.58231  |       0.425769 |   0.625933 |
| k-d_tree_sklearn     |     0.574424 |       1.09325  |   1.17904  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570318 |       0.559939 |   0.501369 |
| k-d_tree_polars      |     0.56444  |       0.577961 |   0.574137 |
| barab-szabi-1        |     0.562336 |       0.570077 |   0.593612 |
| Bori_Aron_solution-1 |     0.568206 |       0.796365 |   0.604109 |
| k-d_tree_pandas      |     0.572016 |       0.510488 |   0.778468 |
| k-d_tree_sklearn     |     0.561626 |       1.2936   |   1.25231  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5839   |       0.762929 |   0.522593 |
| Bori_Aron_solution-1 |     0.551363 |       1.45694  |   0.615541 |
| k-d_tree_polars      |     0.563407 |       0.911676 |   0.952888 |
| barab-szabi-1        |     0.562433 |       0.914808 |   0.991586 |
| k-d_tree_pandas      |     0.552532 |       0.774627 |   1.21404  |
| k-d_tree_sklearn     |     0.574823 |       2.21824  |   1.31726  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565253 |        5.69523 |   0.764869 |
| Bori_Aron_solution-1 |     0.553972 |       11.1418  |   0.875798 |
| k-d_tree_sklearn     |     0.562641 |       16.4509  |   1.30479  |
| barab-szabi-1        |     0.574777 |        5.03132 |   6.8051   |
| k-d_tree_polars      |     0.539989 |        5.07816 |   6.98681  |
| k-d_tree_pandas      |     0.561296 |        3.9368  |   7.21578  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542737 |        71.7496 |    2.68684 |
| k-d_tree_sklearn     |     1.16878  |       230.738  |    4.25876 |
| Bori_Aron_solution-1 |     0.564916 |       142.126  |   17.2112  |