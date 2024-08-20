# 2024-08-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.47736  |       1e-06    |   0.384867 |
| k-d_tree_polars      |     0.589304 |       0.399958 |   0.38604  |
| barab-szabi-1        |     0.588045 |       0.385316 |   0.389768 |
| barab-szabi-2        |     7.92337  |       0.480813 |   0.436231 |
| k-d_tree_pandas      |     0.590104 |       0.41248  |   0.5145   |
| Bori_Aron_solution-1 |     0.595931 |       0.50757  |   0.516907 |
| k-d_tree_sklearn     |     2.90469  |       0.923482 |   0.687321 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605515 |       0.386888 |   0.380172 |
| barab-szabi-1        |     0.602756 |       0.399069 |   0.387444 |
| k-d_tree_polars      |     0.603278 |       0.393964 |   0.388608 |
| Bori_Aron_solution-1 |     0.592901 |       0.51847  |   0.512444 |
| k-d_tree_pandas      |     0.624039 |       0.37585  |   0.528268 |
| k-d_tree_sklearn     |     0.607422 |       0.884248 |   0.693514 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.602112 |       0.400012 |   0.390971 |
| k-d_tree_polars      |     0.604855 |       0.420479 |   0.412386 |
| barab-szabi-1        |     0.604875 |       0.418359 |   0.421181 |
| Bori_Aron_solution-1 |     0.595078 |       0.558883 |   0.519558 |
| k-d_tree_pandas      |     0.601817 |       0.389945 |   0.566757 |
| k-d_tree_sklearn     |     0.603121 |       0.970795 |   0.721713 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.599541 |       0.463647 |   0.42315  |
| k-d_tree_polars      |     0.604621 |       0.529368 |   0.513333 |
| barab-szabi-1        |     0.606276 |       0.528868 |   0.526566 |
| Bori_Aron_solution-1 |     0.595954 |       0.736827 |   0.533515 |
| k-d_tree_pandas      |     0.600869 |       0.475863 |   0.698562 |
| k-d_tree_sklearn     |     0.605061 |       1.13384  |   0.776151 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60122  |       0.709998 |   0.453245 |
| Bori_Aron_solution-1 |     0.593395 |       1.36827  |   0.560683 |
| k-d_tree_polars      |     0.606567 |       0.842191 |   0.854943 |
| k-d_tree_sklearn     |     0.611921 |       1.95317  |   0.863986 |
| barab-szabi-1        |     0.605834 |       0.833115 |   0.889883 |
| k-d_tree_pandas      |     0.605038 |       0.749631 |   1.12785  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.601732 |        5.38435 |   0.725205 |
| Bori_Aron_solution-1 |     0.599296 |       10.7345  |   0.819121 |
| k-d_tree_sklearn     |     0.605977 |       15.9953  |   0.972077 |
| k-d_tree_polars      |     0.606518 |        4.84561 |   6.52822  |
| barab-szabi-1        |     0.597514 |        4.88381 |   6.58855  |
| k-d_tree_pandas      |     0.604558 |        3.86943 |   6.98322  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.597276 |         71.629 |    3.20648 |
| k-d_tree_sklearn     |     0.627378 |        228.882 |    3.87499 |
| Bori_Aron_solution-1 |     0.686923 |        145.957 |   18.3176  |