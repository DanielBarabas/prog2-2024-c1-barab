# 2025-11-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.492872 |       0.382346 |   0.406379 |
| barab-szabi-1        |     0.495145 |       0.381333 |   0.407182 |
| barab-szabi-2        |     0.480601 |       0.47074  |   0.407695 |
| solution-1           |     7.51486  |       1e-06    |   0.468985 |
| Bori_Aron_solution-1 |     0.4886   |       0.540197 |   0.523489 |
| k-d_tree_pandas      |     8.19126  |       0.405993 |   0.611769 |
| k-d_tree_sklearn     |     3.1362   |       1.09858  |   0.998301 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492121 |       0.403313 |   0.407872 |
| barab-szabi-1        |     0.495316 |       0.404192 |   0.410531 |
| k-d_tree_polars      |     0.503601 |       0.382826 |   0.412299 |
| Bori_Aron_solution-1 |     0.486978 |       0.522963 |   0.517296 |
| k-d_tree_pandas      |     0.489819 |       0.375916 |   0.531909 |
| k-d_tree_sklearn     |     0.495695 |       0.914507 |   1.00637  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.489843 |       0.413356 |   0.421825 |
| k-d_tree_polars      |     0.491603 |       0.411798 |   0.433253 |
| barab-szabi-1        |     0.490108 |       0.417123 |   0.43815  |
| Bori_Aron_solution-1 |     0.485683 |       0.559686 |   0.558184 |
| k-d_tree_pandas      |     0.51089  |       0.389847 |   0.568207 |
| k-d_tree_sklearn     |     0.502714 |       0.956454 |   1.04995  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496357 |       0.478755 |   0.448962 |
| k-d_tree_polars      |     0.494249 |       0.525558 |   0.523854 |
| Bori_Aron_solution-1 |     0.484187 |       0.736586 |   0.530914 |
| barab-szabi-1        |     0.49189  |       0.528427 |   0.538671 |
| k-d_tree_pandas      |     0.497766 |       0.468985 |   0.687235 |
| k-d_tree_sklearn     |     0.505248 |       1.16743  |   1.07502  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495757 |       0.715289 |   0.477032 |
| Bori_Aron_solution-1 |     0.486566 |       1.37286  |   0.553112 |
| k-d_tree_polars      |     0.49637  |       0.862102 |   0.854467 |
| barab-szabi-1        |     0.491705 |       0.863133 |   0.895809 |
| k-d_tree_pandas      |     0.495896 |       0.774735 |   1.10044  |
| k-d_tree_sklearn     |     0.498348 |       1.98062  |   1.15086  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.490978 |        4.83727 |   0.716274 |
| Bori_Aron_solution-1 |     0.487753 |       10.3011  |   0.797468 |
| k-d_tree_sklearn     |     0.496103 |       15.0262  |   1.24252  |
| k-d_tree_polars      |     0.505171 |        5.00521 |   6.04218  |
| barab-szabi-1        |     0.492256 |        5.06988 |   6.06815  |
| k-d_tree_pandas      |     0.49056  |        4.20791 |   6.41628  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492701 |        67.8236 |    2.58677 |
| k-d_tree_sklearn     |     0.506291 |       220.311  |    3.8017  |
| Bori_Aron_solution-1 |     0.581796 |       136.097  |   17.4813  |