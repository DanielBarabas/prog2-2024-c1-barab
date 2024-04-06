# 2024-04-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.735892 |       0.338753 |   0.338103 |
| barab-szabi-1        |     0.743745 |       0.40163  |   0.341538 |
| k-d_tree_polars      |     8.22297  |       0.472782 |   0.387646 |
| Bori_Aron_solution-1 |     0.724037 |       0.470436 |   0.471846 |
| k-d_tree_pandas      |     0.722174 |       0.381486 |   0.484241 |
| solution-1           |     8.64289  |       1e-06    |   0.547858 |
| k-d_tree_sklearn     |     3.2721   |       0.999697 |   0.660198 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.736222 |       0.343344 |   0.333601 |
| barab-szabi-1        |     0.735955 |       0.424462 |   0.346466 |
| k-d_tree_polars      |     0.744056 |       0.411935 |   0.347962 |
| Bori_Aron_solution-1 |     0.728057 |       0.485532 |   0.470186 |
| k-d_tree_pandas      |     0.747705 |       0.396698 |   0.486099 |
| k-d_tree_sklearn     |     0.749146 |       0.840876 |   0.667472 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.735665 |       0.358531 |   0.350416 |
| k-d_tree_polars      |     0.738326 |       0.431122 |   0.373526 |
| barab-szabi-1        |     0.764152 |       0.427997 |   0.382329 |
| Bori_Aron_solution-1 |     0.721719 |       0.52054  |   0.478655 |
| k-d_tree_pandas      |     0.732573 |       0.425726 |   0.526281 |
| k-d_tree_sklearn     |     0.746588 |       0.89043  |   0.686574 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732982 |       0.429087 |   0.386462 |
| k-d_tree_polars      |     0.742554 |       0.534528 |   0.470892 |
| barab-szabi-1        |     0.73504  |       0.535182 |   0.480807 |
| Bori_Aron_solution-1 |     0.721144 |       0.69619  |   0.482313 |
| k-d_tree_pandas      |     0.739627 |       0.481845 |   0.658657 |
| k-d_tree_sklearn     |     0.735785 |       1.09622  |   0.748354 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.73618  |       0.674934 |   0.423316 |
| Bori_Aron_solution-1 |     0.729909 |       1.32531  |   0.5361   |
| k-d_tree_polars      |     0.738198 |       0.847051 |   0.820824 |
| barab-szabi-1        |     0.740249 |       0.850093 |   0.860533 |
| k-d_tree_sklearn     |     0.742374 |       1.9019   |   0.861533 |
| k-d_tree_pandas      |     0.738763 |       0.766088 |   1.09843  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.737938 |        5.36989 |   0.724616 |
| Bori_Aron_solution-1 |     0.722034 |       10.6608  |   0.768073 |
| k-d_tree_sklearn     |     0.741721 |       16.0996  |   1.04009  |
| barab-szabi-1        |     0.735645 |        4.8265  |   6.63583  |
| k-d_tree_polars      |     0.741764 |        4.81956 |   6.64438  |
| k-d_tree_pandas      |     0.740058 |        3.86639 |   6.93701  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.906629 |        71.0928 |    3.8268  |
| k-d_tree_sklearn     |     0.739274 |       227.499  |    5.19077 |
| Bori_Aron_solution-1 |     0.828953 |       143.52   |   14.1592  |