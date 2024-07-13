# 2024-07-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.50184  |       1e-06    |   0.343607 |
| barab-szabi-2        |     0.544163 |       0.375727 |   0.369314 |
| k-d_tree_polars      |     0.550861 |       0.381721 |   0.377409 |
| barab-szabi-1        |     0.557213 |       0.383487 |   0.393223 |
| Bori_Aron_solution-1 |     0.535687 |       0.500463 |   0.500836 |
| k-d_tree_pandas      |     0.544451 |       0.370211 |   0.50616  |
| k-d_tree_sklearn     |    10.2537   |       1.01694  |   0.684052 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54338  |       0.380662 |   0.374516 |
| k-d_tree_polars      |     0.545851 |       0.401197 |   0.383892 |
| barab-szabi-1        |     0.544675 |       0.40052  |   0.384142 |
| Bori_Aron_solution-1 |     0.535135 |       0.511295 |   0.501427 |
| k-d_tree_pandas      |     0.543762 |       0.371026 |   0.511961 |
| k-d_tree_sklearn     |     0.545356 |       0.871232 |   0.685587 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545818 |       0.392456 |   0.389808 |
| k-d_tree_polars      |     0.566635 |       0.415714 |   0.40811  |
| barab-szabi-1        |     0.54505  |       0.413907 |   0.410731 |
| Bori_Aron_solution-1 |     0.534879 |       0.549033 |   0.505333 |
| k-d_tree_pandas      |     0.545186 |       0.392143 |   0.5599   |
| k-d_tree_sklearn     |     0.547082 |       0.908305 |   0.724772 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54431  |       0.46585  |   0.432966 |
| k-d_tree_polars      |     0.539649 |       0.520379 |   0.502794 |
| barab-szabi-1        |     0.54652  |       0.521965 |   0.519871 |
| Bori_Aron_solution-1 |     0.539771 |       0.72397  |   0.51997  |
| k-d_tree_pandas      |     0.546349 |       0.468598 |   0.692404 |
| k-d_tree_sklearn     |     0.547906 |       1.17516  |   0.764582 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543276 |       0.708354 |   0.456333 |
| Bori_Aron_solution-1 |     0.533981 |       1.35895  |   0.547463 |
| k-d_tree_polars      |     0.545885 |       0.839541 |   0.857999 |
| k-d_tree_sklearn     |     0.548919 |       1.93754  |   0.874031 |
| barab-szabi-1        |     0.546499 |       0.838189 |   0.893582 |
| k-d_tree_pandas      |     0.542913 |       0.723681 |   1.12627  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547858 |        5.10745 |   0.734647 |
| Bori_Aron_solution-1 |     0.536247 |       10.3722  |   0.831079 |
| k-d_tree_sklearn     |     0.549285 |       15.1186  |   1.01551  |
| barab-szabi-1        |     0.543763 |        4.82872 |   6.28578  |
| k-d_tree_polars      |     0.549094 |        4.79733 |   6.30627  |
| k-d_tree_pandas      |     0.544819 |        3.87538 |   6.63791  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.775489 |        72.2155 |    3.69175 |
| k-d_tree_sklearn     |     0.547634 |       219.194  |    4.25805 |
| Bori_Aron_solution-1 |     0.545762 |       142.411  |   19.0402  |