# 2024-04-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.698961 |       0.417818 |   0.339284 |
| barab-szabi-2        |     0.706064 |       0.336236 |   0.340418 |
| barab-szabi-1        |     9.44611  |       0.419052 |   0.352255 |
| solution-1           |     8.28121  |       1e-06    |   0.356749 |
| Bori_Aron_solution-1 |     0.691588 |       0.471323 |   0.470806 |
| k-d_tree_pandas      |     0.702935 |       0.377572 |   0.473832 |
| k-d_tree_sklearn     |     3.46304  |       0.959885 |   0.647003 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.718295 |       0.345782 |   0.335309 |
| barab-szabi-1        |     0.733665 |       0.408955 |   0.343663 |
| k-d_tree_polars      |     0.721364 |       0.404325 |   0.345514 |
| Bori_Aron_solution-1 |     0.721327 |       0.484975 |   0.467053 |
| k-d_tree_pandas      |     0.725734 |       0.388451 |   0.500701 |
| k-d_tree_sklearn     |     0.743764 |       0.842072 |   0.659337 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.72858  |       0.356124 |   0.351227 |
| barab-szabi-1        |     0.736188 |       0.427561 |   0.370268 |
| k-d_tree_polars      |     0.736191 |       0.424783 |   0.370967 |
| k-d_tree_pandas      |     0.729789 |       0.397751 |   0.524893 |
| Bori_Aron_solution-1 |     0.71572  |       0.520142 |   0.54843  |
| k-d_tree_sklearn     |     0.757218 |       0.878637 |   0.684326 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.731869 |       0.428287 |   0.386421 |
| k-d_tree_polars      |     0.732559 |       0.533032 |   0.475702 |
| barab-szabi-1        |     0.736699 |       0.545997 |   0.481489 |
| Bori_Aron_solution-1 |     0.721645 |       0.696417 |   0.486818 |
| k-d_tree_pandas      |     0.734138 |       0.479645 |   0.657705 |
| k-d_tree_sklearn     |     0.735798 |       1.10132  |   0.75017  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.733829 |       0.677174 |   0.422631 |
| Bori_Aron_solution-1 |     0.723655 |       1.32627  |   0.512914 |
| k-d_tree_polars      |     0.728854 |       0.882291 |   0.819336 |
| k-d_tree_sklearn     |     0.736726 |       1.90111  |   0.842375 |
| barab-szabi-1        |     0.730742 |       0.857097 |   0.849912 |
| k-d_tree_pandas      |     0.736689 |       0.753188 |   1.0745   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.733473 |        5.34502 |   0.754093 |
| Bori_Aron_solution-1 |     0.716367 |       10.6629  |   0.770843 |
| k-d_tree_sklearn     |     0.74006  |       15.89    |   1.0477   |
| barab-szabi-1        |     0.729501 |        4.83672 |   6.51565  |
| k-d_tree_polars      |     0.732043 |        4.79609 |   6.5589   |
| k-d_tree_pandas      |     0.729256 |        3.86703 |   6.87313  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.05762  |        72.8069 |    3.48779 |
| k-d_tree_sklearn     |     0.84209  |       228.399  |    4.84823 |
| Bori_Aron_solution-1 |     0.721714 |       146.675  |   17.3605  |