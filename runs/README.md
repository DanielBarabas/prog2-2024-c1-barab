# 2026-06-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.375164 |       0.366832 |   0.352342 |
| k-d_tree_polars      |     0.360955 |       0.318791 |   0.361612 |
| solution-1           |     6.86641  |       1e-06    |   0.371839 |
| Bori_Aron_solution-1 |     0.356906 |       0.43419  |   0.43494  |
| k-d_tree_pandas      |     0.359946 |       0.310143 |   0.438    |
| barab-szabi-1        |     8.54102  |       0.380217 |   0.735145 |
| k-d_tree_sklearn     |     2.58974  |       0.978096 |   0.921721 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.370863 |       0.349314 |   0.356427 |
| barab-szabi-1        |     0.371079 |       0.336924 |   0.357995 |
| k-d_tree_polars      |     0.369642 |       0.330853 |   0.359841 |
| Bori_Aron_solution-1 |     0.363922 |       0.437383 |   0.43682  |
| k-d_tree_pandas      |     0.372799 |       0.315824 |   0.452913 |
| k-d_tree_sklearn     |     0.380163 |       0.799732 |   0.885124 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.367831 |       0.347617 |   0.380571 |
| k-d_tree_polars      |     0.373508 |       0.352947 |   0.390967 |
| barab-szabi-2        |     0.373695 |       0.368486 |   0.400306 |
| Bori_Aron_solution-1 |     0.366538 |       0.480671 |   0.446672 |
| k-d_tree_pandas      |     0.382475 |       0.332464 |   0.484077 |
| k-d_tree_sklearn     |     0.369314 |       0.833151 |   0.917975 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.366662 |       0.407867 |   0.384845 |
| k-d_tree_polars      |     0.369513 |       0.445236 |   0.455523 |
| Bori_Aron_solution-1 |     0.365086 |       0.633558 |   0.458714 |
| barab-szabi-1        |     0.370908 |       0.451302 |   0.470408 |
| k-d_tree_pandas      |     0.378302 |       0.406394 |   0.64089  |
| k-d_tree_sklearn     |     0.367107 |       1.0362   |   0.91483  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.370492 |       0.614764 |   0.41961  |
| Bori_Aron_solution-1 |     0.370878 |       1.18472  |   0.475626 |
| k-d_tree_polars      |     0.377328 |       0.801609 |   0.751204 |
| barab-szabi-1        |     0.366646 |       0.783183 |   0.785053 |
| k-d_tree_pandas      |     0.371717 |       0.623439 |   0.936121 |
| k-d_tree_sklearn     |     0.375645 |       1.74267  |   0.941054 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.37235  |        4.63894 |   0.632596 |
| Bori_Aron_solution-1 |     0.375408 |        9.24041 |   0.653794 |
| k-d_tree_sklearn     |     0.379102 |       14.9221  |   0.994544 |
| barab-szabi-1        |     0.366703 |        4.82896 |   6.07359  |
| k-d_tree_polars      |     0.377148 |        4.76261 |   6.08242  |
| k-d_tree_pandas      |     0.371299 |        3.29065 |   6.39306  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.364403 |        72.1551 |    2.34367 |
| k-d_tree_sklearn     |     2.33053  |       224.034  |    4.20647 |
| Bori_Aron_solution-1 |     0.628214 |       149.928  |   28.2908  |