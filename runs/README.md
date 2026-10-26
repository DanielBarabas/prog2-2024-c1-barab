# 2026-10-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.453446 |       0.426774 |   0.416292 |
| k-d_tree_polars      |     0.463539 |       0.410102 |   0.435982 |
| solution-1           |     7.47612  |       1e-06    |   0.480731 |
| Bori_Aron_solution-1 |     0.444443 |       0.540821 |   0.542031 |
| k-d_tree_pandas      |     0.45275  |       0.385106 |   0.542297 |
| barab-szabi-1        |     8.10525  |       0.674567 |   0.627905 |
| k-d_tree_sklearn     |     2.90902  |       1.49552  |   1.05532  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460751 |       0.420648 |   0.419354 |
| k-d_tree_polars      |     0.469424 |       0.418644 |   0.429828 |
| barab-szabi-1        |     0.465538 |       0.418697 |   0.433682 |
| Bori_Aron_solution-1 |     0.453659 |       0.542517 |   0.53216  |
| k-d_tree_pandas      |     0.460705 |       0.391922 |   0.538584 |
| k-d_tree_sklearn     |     0.469265 |       0.995585 |   1.09882  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463799 |       0.440352 |   0.418427 |
| barab-szabi-1        |     0.462017 |       0.447045 |   0.453863 |
| k-d_tree_polars      |     0.46322  |       0.456507 |   0.458023 |
| Bori_Aron_solution-1 |     0.460153 |       0.585793 |   0.558462 |
| k-d_tree_pandas      |     0.465523 |       0.40944  |   0.578557 |
| k-d_tree_sklearn     |     0.467061 |       1.12537  |   1.11088  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464821 |       0.521454 |   0.464546 |
| Bori_Aron_solution-1 |     0.457532 |       0.783984 |   0.555979 |
| k-d_tree_polars      |     0.464558 |       0.574505 |   0.564885 |
| barab-szabi-1        |     0.461391 |       0.563747 |   0.570413 |
| k-d_tree_pandas      |     0.459813 |       0.496835 |   0.715995 |
| k-d_tree_sklearn     |     0.467021 |       1.26773  |   1.10377  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.457572 |       0.788687 |   0.522244 |
| Bori_Aron_solution-1 |     0.453921 |       1.49261  |   0.610013 |
| k-d_tree_polars      |     0.462992 |       0.899221 |   0.966674 |
| barab-szabi-1        |     0.460907 |       0.884869 |   1.01736  |
| k-d_tree_sklearn     |     0.467149 |       2.13882  |   1.17475  |
| k-d_tree_pandas      |     0.459065 |       0.780746 |   1.19687  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.46095  |        5.88524 |   0.890355 |
| Bori_Aron_solution-1 |     0.462844 |       11.701   |   1.12809  |
| k-d_tree_sklearn     |     0.472286 |       16.967   |   1.33192  |
| k-d_tree_polars      |     0.467188 |        4.94778 |   7.58803  |
| barab-szabi-1        |     0.463141 |        4.94312 |   7.74685  |
| k-d_tree_pandas      |     0.459869 |        4.035   |   8.00109  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.562721 |       261.049  |    3.60521 |
| barab-szabi-2        |     0.690266 |        82.9826 |    4.27315 |
| Bori_Aron_solution-1 |     0.448845 |       161.47   |   16.1415  |