# 2025-12-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.54162  |       0.41349  |   0.439271 |
| barab-szabi-1        |     0.540899 |       0.444652 |   0.439841 |
| barab-szabi-2        |     0.567005 |       0.527948 |   0.442326 |
| solution-1           |     8.35641  |       1e-06    |   0.499555 |
| Bori_Aron_solution-1 |     0.537285 |       0.572399 |   0.553812 |
| k-d_tree_pandas      |     9.0036   |       0.442855 |   0.701897 |
| k-d_tree_sklearn     |     3.2504   |       1.13365  |   1.06797  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548278 |       0.438226 |   0.43754  |
| barab-szabi-1        |     0.545648 |       0.424503 |   0.443835 |
| k-d_tree_polars      |     0.543604 |       0.415437 |   0.446615 |
| Bori_Aron_solution-1 |     0.529425 |       0.569195 |   0.557946 |
| k-d_tree_pandas      |     0.530846 |       0.395714 |   0.575715 |
| k-d_tree_sklearn     |     0.544212 |       1.01093  |   1.10019  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538128 |       0.452509 |   0.457208 |
| k-d_tree_polars      |     0.541915 |       0.456563 |   0.46515  |
| barab-szabi-1        |     0.554216 |       0.45116  |   0.468174 |
| Bori_Aron_solution-1 |     0.536804 |       0.609337 |   0.574407 |
| k-d_tree_pandas      |     0.534712 |       0.420542 |   0.624951 |
| k-d_tree_sklearn     |     0.54838  |       1.0498   |   1.13146  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547761 |       0.519198 |   0.476555 |
| Bori_Aron_solution-1 |     0.540713 |       0.798007 |   0.572878 |
| k-d_tree_polars      |     0.541151 |       0.571068 |   0.57998  |
| barab-szabi-1        |     0.537281 |       0.570129 |   0.582272 |
| k-d_tree_pandas      |     0.543317 |       0.510843 |   0.747776 |
| k-d_tree_sklearn     |     0.540504 |       1.29325  |   1.16605  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539018 |       0.765552 |   0.521555 |
| Bori_Aron_solution-1 |     0.527451 |       1.48373  |   0.609144 |
| k-d_tree_polars      |     0.537252 |       0.931358 |   0.927871 |
| barab-szabi-1        |     0.569976 |       0.931495 |   0.97732  |
| k-d_tree_pandas      |     0.536545 |       0.83494  |   1.21708  |
| k-d_tree_sklearn     |     0.543562 |       2.17615  |   1.26495  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548254 |        5.64014 |   0.794116 |
| Bori_Aron_solution-1 |     0.544193 |       11.738   |   0.868623 |
| k-d_tree_sklearn     |     0.556836 |       18.7181  |   1.38494  |
| k-d_tree_polars      |     0.578463 |        5.37155 |   7.13292  |
| k-d_tree_pandas      |     0.554939 |        4.51339 |   7.34197  |
| barab-szabi-1        |     0.548781 |        5.42288 |   7.38982  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550365 |        81.6691 |    2.83408 |
| k-d_tree_sklearn     |     0.540207 |       249.508  |    4.12046 |
| Bori_Aron_solution-1 |     0.650834 |       152.99   |   16.6162  |