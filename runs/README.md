# 2025-06-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535171 |       0.423658 |   0.421599 |
| k-d_tree_polars      |     0.547731 |       0.405394 |   0.425175 |
| solution-1           |     7.37233  |       1e-06    |   0.428549 |
| barab-szabi-1        |     0.539048 |       0.420514 |   0.446219 |
| Bori_Aron_solution-1 |     0.538393 |       0.548905 |   0.547132 |
| k-d_tree_pandas      |     7.6458   |       0.407328 |   0.639768 |
| k-d_tree_sklearn     |     3.01507  |       1.06075  |   1.04126  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.551569 |       0.407539 |   0.426849 |
| barab-szabi-2        |     0.645048 |       0.418688 |   0.440912 |
| k-d_tree_polars      |     0.555046 |       0.429889 |   0.446013 |
| Bori_Aron_solution-1 |     0.543769 |       0.557375 |   0.543554 |
| k-d_tree_pandas      |     0.551154 |       0.390979 |   0.620868 |
| k-d_tree_sklearn     |     0.595833 |       0.968337 |   1.05559  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552267 |       0.438389 |   0.435964 |
| barab-szabi-1        |     0.547263 |       0.435365 |   0.457713 |
| k-d_tree_polars      |     0.554929 |       0.444569 |   0.460407 |
| Bori_Aron_solution-1 |     0.54063  |       0.587094 |   0.558968 |
| k-d_tree_pandas      |     0.548084 |       0.41151  |   0.598718 |
| k-d_tree_sklearn     |     0.554406 |       1.03038  |   1.07519  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548122 |       0.49462  |   0.456053 |
| k-d_tree_polars      |     0.560468 |       0.54549  |   0.549699 |
| barab-szabi-1        |     0.586104 |       0.565027 |   0.565783 |
| Bori_Aron_solution-1 |     0.550308 |       0.812206 |   0.605808 |
| k-d_tree_pandas      |     0.556953 |       0.495712 |   0.744837 |
| k-d_tree_sklearn     |     0.55248  |       1.27144  |   1.12605  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567955 |       0.79531  |   0.524906 |
| Bori_Aron_solution-1 |     0.556864 |       1.45028  |   0.610574 |
| barab-szabi-1        |     0.543241 |       0.870147 |   0.948124 |
| k-d_tree_polars      |     0.549284 |       0.914168 |   0.956475 |
| k-d_tree_pandas      |     0.548439 |       0.768912 |   1.22736  |
| k-d_tree_sklearn     |     0.568429 |       2.14444  |   1.25138  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598766 |        5.27942 |   0.727536 |
| Bori_Aron_solution-1 |     0.579579 |       10.5598  |   0.852544 |
| k-d_tree_sklearn     |     0.549944 |       16.4682  |   1.31428  |
| barab-szabi-1        |     0.585985 |        4.99296 |   6.60818  |
| k-d_tree_polars      |     0.552552 |        4.91061 |   7.02584  |
| k-d_tree_pandas      |     0.557473 |        3.93174 |   7.44775  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.693189 |        75.5271 |    2.77172 |
| k-d_tree_sklearn     |     0.692355 |       232.468  |    3.8281  |
| Bori_Aron_solution-1 |     0.543915 |       142.952  |   18.063   |