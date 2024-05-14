# 2024-05-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.718129 |       0.411433 |   0.353067 |
| barab-szabi-1        |     8.57447  |       0.481215 |   0.363158 |
| barab-szabi-2        |     0.716127 |       0.355535 |   0.378479 |
| solution-1           |     8.13953  |       1e-06    |   0.381775 |
| k-d_tree_pandas      |     0.722519 |       0.389418 |   0.476633 |
| Bori_Aron_solution-1 |     0.710889 |       0.504396 |   0.492111 |
| k-d_tree_sklearn     |     3.27989  |       0.936447 |   0.688468 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.745031 |       0.411198 |   0.355934 |
| barab-szabi-1        |     0.753784 |       0.41138  |   0.356972 |
| barab-szabi-2        |     0.740791 |       0.360439 |   0.362229 |
| k-d_tree_pandas      |     0.742818 |       0.391369 |   0.492427 |
| Bori_Aron_solution-1 |     0.74226  |       0.505218 |   0.495729 |
| k-d_tree_sklearn     |     0.761605 |       0.915863 |   0.681231 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.747817 |       0.373999 |   0.380944 |
| barab-szabi-1        |     0.741719 |       0.443437 |   0.389516 |
| k-d_tree_polars      |     0.731868 |       0.440647 |   0.392974 |
| Bori_Aron_solution-1 |     0.738934 |       0.538915 |   0.486251 |
| k-d_tree_pandas      |     0.754873 |       0.424244 |   0.542246 |
| k-d_tree_sklearn     |     0.763169 |       0.919785 |   0.699826 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.744159 |       0.440104 |   0.392728 |
| k-d_tree_polars      |     0.749878 |       0.553761 |   0.487959 |
| barab-szabi-1        |     0.745576 |       0.561814 |   0.503551 |
| Bori_Aron_solution-1 |     0.74373  |       0.702448 |   0.514247 |
| k-d_tree_pandas      |     0.747453 |       0.492004 |   0.674649 |
| k-d_tree_sklearn     |     0.751505 |       1.13637  |   0.781474 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.743702 |       0.698764 |   0.446387 |
| Bori_Aron_solution-1 |     0.743472 |       1.36605  |   0.534149 |
| k-d_tree_polars      |     0.741101 |       0.86981  |   0.850703 |
| k-d_tree_sklearn     |     0.751124 |       1.97338  |   0.877462 |
| barab-szabi-1        |     0.771449 |       0.863536 |   0.930692 |
| k-d_tree_pandas      |     0.748101 |       0.763666 |   1.12692  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.744401 |        5.59789 |   0.773002 |
| Bori_Aron_solution-1 |     0.734601 |       11.0967  |   0.81136  |
| k-d_tree_sklearn     |     0.743412 |       16.7758  |   1.0515   |
| k-d_tree_polars      |     0.755022 |        4.92965 |   6.97749  |
| barab-szabi-1        |     0.750976 |        4.94172 |   7.03084  |
| k-d_tree_pandas      |     0.736829 |        3.88329 |   7.36558  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.06014  |        75.0941 |    3.8729  |
| k-d_tree_sklearn     |     0.854506 |       232.971  |    4.94619 |
| Bori_Aron_solution-1 |     0.725914 |       160.21   |   18.4974  |