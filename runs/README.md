# 2026-04-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.58903  |       1e-06    |   0.381733 |
| k-d_tree_polars      |     0.459709 |       0.407088 |   0.435156 |
| barab-szabi-2        |     0.472391 |       0.428784 |   0.442208 |
| barab-szabi-1        |     7.7882   |       0.445841 |   0.494167 |
| Bori_Aron_solution-1 |     0.451788 |       0.54652  |   0.564241 |
| k-d_tree_pandas      |     0.461638 |       0.405124 |   0.565648 |
| k-d_tree_sklearn     |     2.8657   |       1.14027  |   1.10797  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465903 |       0.443334 |   0.442208 |
| k-d_tree_polars      |     0.466019 |       0.418918 |   0.443427 |
| barab-szabi-1        |     0.468202 |       0.412071 |   0.445131 |
| Bori_Aron_solution-1 |     0.467818 |       0.560792 |   0.545528 |
| k-d_tree_pandas      |     0.461821 |       0.394197 |   0.564631 |
| k-d_tree_sklearn     |     0.470668 |       1.01063  |   1.09388  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456789 |       0.46151  |   0.45999  |
| barab-szabi-1        |     0.466785 |       0.44394  |   0.466268 |
| k-d_tree_polars      |     0.479689 |       0.45362  |   0.476539 |
| Bori_Aron_solution-1 |     0.453568 |       0.625961 |   0.55517  |
| k-d_tree_pandas      |     0.46852  |       0.415535 |   0.616508 |
| k-d_tree_sklearn     |     0.475629 |       1.03613  |   1.15116  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482415 |       0.503209 |   0.482889 |
| barab-szabi-1        |     0.484264 |       0.564996 |   0.577906 |
| k-d_tree_polars      |     0.479845 |       0.582181 |   0.581643 |
| Bori_Aron_solution-1 |     0.482053 |       0.802178 |   0.592084 |
| k-d_tree_pandas      |     0.482527 |       0.516404 |   0.77312  |
| k-d_tree_sklearn     |     0.501357 |       1.28494  |   1.18076  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471188 |       0.735765 |   0.51539  |
| Bori_Aron_solution-1 |     0.46972  |       1.47308  |   0.596088 |
| k-d_tree_polars      |     0.465582 |       0.946024 |   0.925709 |
| barab-szabi-1        |     0.479171 |       0.940746 |   0.979918 |
| k-d_tree_pandas      |     0.463933 |       0.818288 |   1.20329  |
| k-d_tree_sklearn     |     0.468179 |       2.1884   |   1.24183  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492046 |        5.38295 |   0.783746 |
| Bori_Aron_solution-1 |     0.473147 |       11.3988  |   0.847684 |
| k-d_tree_sklearn     |     0.469121 |       17.5569  |   1.32651  |
| barab-szabi-1        |     0.46282  |        5.67235 |   6.73723  |
| k-d_tree_polars      |     0.469414 |        5.57762 |   7.05526  |
| k-d_tree_pandas      |     0.480143 |        4.569   |   7.33455  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.707433 |        72.1587 |    2.75223 |
| k-d_tree_sklearn     |     0.474651 |       239.524  |    3.96976 |
| Bori_Aron_solution-1 |     0.490479 |       149.872  |   15.6814  |