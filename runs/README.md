# 2024-05-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.81835  |       0.352592 |   0.334643 |
| barab-szabi-1        |     0.784552 |       0.4031   |   0.346602 |
| solution-1           |     7.87689  |       1e-06    |   0.362373 |
| k-d_tree_polars      |     0.927706 |       0.439134 |   0.394027 |
| Bori_Aron_solution-1 |     4.63635  |       0.407913 |   0.404066 |
| k-d_tree_pandas      |     0.790483 |       0.378477 |   0.473359 |
| k-d_tree_sklearn     |     3.35022  |       0.921031 |   0.674128 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.784041 |       0.350746 |   0.344343 |
| k-d_tree_polars      |     0.802973 |       0.40742  |   0.348665 |
| barab-szabi-1        |     0.78762  |       0.414315 |   0.350421 |
| Bori_Aron_solution-1 |     0.797226 |       0.486115 |   0.472484 |
| k-d_tree_pandas      |     0.790634 |       0.432069 |   0.519811 |
| k-d_tree_sklearn     |     0.889982 |       0.856034 |   0.681495 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.78896  |       0.429219 |   0.37839  |
| barab-szabi-2        |     0.792431 |       0.416918 |   0.391203 |
| barab-szabi-1        |     0.790165 |       0.442244 |   0.439826 |
| Bori_Aron_solution-1 |     0.790006 |       0.51891  |   0.470535 |
| k-d_tree_pandas      |     0.873182 |       0.406589 |   0.527041 |
| k-d_tree_sklearn     |     0.795191 |       0.894317 |   0.702976 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.778487 |       0.424787 |   0.394746 |
| barab-szabi-1        |     0.803202 |       0.538192 |   0.482013 |
| Bori_Aron_solution-1 |     0.781849 |       0.711058 |   0.501368 |
| k-d_tree_polars      |     0.841978 |       0.624985 |   0.557857 |
| k-d_tree_pandas      |     0.785738 |       0.489747 |   0.676702 |
| k-d_tree_sklearn     |     0.809952 |       1.12672  |   0.763659 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.879866 |       1.35981  |   0.518105 |
| barab-szabi-2        |     0.795896 |       0.672657 |   0.581351 |
| k-d_tree_polars      |     0.815377 |       0.877697 |   0.848911 |
| k-d_tree_sklearn     |     0.836548 |       2.03637  |   0.874652 |
| barab-szabi-1        |     0.794265 |       0.882039 |   0.87718  |
| k-d_tree_pandas      |     0.817214 |       0.855657 |   1.29077  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.887951 |        5.43888 |   0.725176 |
| Bori_Aron_solution-1 |     0.78081  |       11.2481  |   0.864655 |
| k-d_tree_sklearn     |     0.798907 |       19.0611  |   1.07758  |
| barab-szabi-1        |     0.810049 |        5.14539 |   7.09373  |
| k-d_tree_polars      |     0.868284 |        5.06864 |   7.64947  |
| k-d_tree_pandas      |     0.791883 |        4.16519 |   8.03006  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.06033  |        77.5197 |    3.83677 |
| k-d_tree_sklearn     |     0.957798 |       250.827  |    5.24381 |
| Bori_Aron_solution-1 |     0.887112 |       151.769  |   17.241   |