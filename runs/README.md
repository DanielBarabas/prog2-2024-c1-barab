# 2025-07-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.3408   |       1e-06    |   0.420786 |
| barab-szabi-1        |     0.542142 |       0.411951 |   0.422643 |
| barab-szabi-2        |     7.65336  |       0.630332 |   0.423065 |
| k-d_tree_polars      |     0.562386 |       0.413787 |   0.432429 |
| Bori_Aron_solution-1 |     0.540426 |       0.548519 |   0.555061 |
| k-d_tree_pandas      |     0.566098 |       0.40758  |   0.56525  |
| k-d_tree_sklearn     |     2.92536  |       1.09169  |   1.08523  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561457 |       0.44751  |   0.425615 |
| barab-szabi-1        |     0.557718 |       0.420444 |   0.43317  |
| k-d_tree_polars      |     0.559723 |       0.417304 |   0.435159 |
| Bori_Aron_solution-1 |     0.557204 |       0.564959 |   0.55211  |
| k-d_tree_pandas      |     0.571543 |       0.397827 |   0.55918  |
| k-d_tree_sklearn     |     0.568728 |       0.979897 |   1.10195  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559186 |       0.441587 |   0.44376  |
| k-d_tree_polars      |     0.563092 |       0.443702 |   0.455207 |
| barab-szabi-1        |     0.565866 |       0.441804 |   0.461746 |
| Bori_Aron_solution-1 |     0.553193 |       0.594258 |   0.551553 |
| k-d_tree_pandas      |     0.557145 |       0.412254 |   0.604434 |
| k-d_tree_sklearn     |     0.562126 |       1.0275   |   1.10024  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556186 |       0.507662 |   0.470654 |
| k-d_tree_polars      |     0.564933 |       0.547162 |   0.55542  |
| Bori_Aron_solution-1 |     0.55796  |       0.769408 |   0.562088 |
| barab-szabi-1        |     0.559427 |       0.555321 |   0.566649 |
| k-d_tree_pandas      |     0.564879 |       0.491199 |   0.739889 |
| k-d_tree_sklearn     |     0.559296 |       1.25429  |   1.13512  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570977 |       0.746394 |   0.496067 |
| Bori_Aron_solution-1 |     0.566171 |       1.41959  |   0.610213 |
| k-d_tree_polars      |     0.554225 |       0.897461 |   0.913735 |
| barab-szabi-1        |     0.558558 |       0.894766 |   0.958535 |
| k-d_tree_pandas      |     0.558949 |       0.765473 |   1.18469  |
| k-d_tree_sklearn     |     0.562865 |       2.10416  |   1.21796  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551882 |        5.55369 |   0.749149 |
| Bori_Aron_solution-1 |     0.554488 |       11.1555  |   0.865398 |
| k-d_tree_sklearn     |     0.566129 |       16.8973  |   1.32186  |
| barab-szabi-1        |     0.559587 |        5.09467 |   6.8351   |
| k-d_tree_polars      |     0.557799 |        5.07051 |   6.93635  |
| k-d_tree_pandas      |     0.562526 |        3.96236 |   7.22628  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562696 |        74.2786 |    2.77577 |
| k-d_tree_sklearn     |     0.771461 |       233.832  |    4.0239  |
| Bori_Aron_solution-1 |     0.563613 |       140.788  |   17.7808  |