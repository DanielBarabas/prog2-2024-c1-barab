# 2026-11-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.68432  |       1e-06    |   0.347865 |
| barab-szabi-2        |     0.443095 |       0.432383 |   0.428344 |
| k-d_tree_polars      |     9.06355  |       0.424936 |   0.463576 |
| barab-szabi-1        |     0.447669 |       0.427086 |   0.46837  |
| k-d_tree_pandas      |     0.441627 |       0.386847 |   0.537069 |
| Bori_Aron_solution-1 |     0.443656 |       0.534056 |   0.540909 |
| k-d_tree_sklearn     |     4.28423  |       1.04597  |   1.09731  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471468 |       0.434285 |   0.434229 |
| k-d_tree_polars      |     0.451398 |       0.432568 |   0.451035 |
| barab-szabi-1        |     0.463224 |       0.422346 |   0.457165 |
| Bori_Aron_solution-1 |     0.443894 |       0.54337  |   0.540358 |
| k-d_tree_pandas      |     0.4506   |       0.387488 |   0.547321 |
| k-d_tree_sklearn     |     0.468208 |       1.01135  |   1.06661  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.458658 |       0.469904 |   0.44367  |
| k-d_tree_polars      |     0.449689 |       0.436454 |   0.465853 |
| barab-szabi-1        |     0.463319 |       0.46207  |   0.478079 |
| Bori_Aron_solution-1 |     0.447365 |       0.585889 |   0.564064 |
| k-d_tree_pandas      |     0.450255 |       0.408761 |   0.593567 |
| k-d_tree_sklearn     |     0.471701 |       1.02749  |   1.22254  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462698 |       0.550558 |   0.475699 |
| Bori_Aron_solution-1 |     0.450017 |       0.792363 |   0.566447 |
| k-d_tree_polars      |     0.509582 |       0.580936 |   0.572054 |
| barab-szabi-1        |     0.459831 |       0.585811 |   0.583939 |
| k-d_tree_pandas      |     0.464879 |       0.509634 |   0.748269 |
| k-d_tree_sklearn     |     0.460605 |       1.29699  |   1.1723   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467324 |       0.801267 |   0.622014 |
| Bori_Aron_solution-1 |     0.461991 |       1.5207   |   0.634535 |
| k-d_tree_polars      |     0.465162 |       0.933374 |   0.977264 |
| barab-szabi-1        |     0.469807 |       0.939683 |   1.02232  |
| k-d_tree_pandas      |     0.472221 |       0.816373 |   1.23874  |
| k-d_tree_sklearn     |     0.481128 |       2.16757  |   1.24004  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478397 |        5.5998  |   0.924909 |
| Bori_Aron_solution-1 |     0.441487 |       11.4177  |   1.17342  |
| k-d_tree_sklearn     |     0.454585 |       17.5289  |   1.45436  |
| k-d_tree_polars      |     0.457014 |        5.28039 |   6.82392  |
| barab-szabi-1        |     0.460174 |        5.14625 |   6.95975  |
| k-d_tree_pandas      |     0.443952 |        4.36122 |   7.17008  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.781224 |        79.8933 |    4.47892 |
| k-d_tree_sklearn     |     0.58328  |       261.033  |    4.58192 |
| Bori_Aron_solution-1 |     0.457696 |       150.714  |   24.0446  |