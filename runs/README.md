# 2026-01-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.03566  |       1e-06    |   0.407119 |
| k-d_tree_polars      |     0.474327 |       0.368183 |   0.409141 |
| barab-szabi-1        |     0.480846 |       0.411233 |   0.425101 |
| barab-szabi-2        |     0.464247 |       0.434274 |   0.458195 |
| Bori_Aron_solution-1 |     0.468218 |       0.502232 |   0.499818 |
| k-d_tree_pandas      |     8.06381  |       0.375103 |   0.615242 |
| k-d_tree_sklearn     |     2.69128  |       0.961379 |   0.974357 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.475611 |       0.385272 |   0.417945 |
| barab-szabi-2        |     0.477646 |       0.411724 |   0.418458 |
| barab-szabi-1        |     0.476196 |       0.382285 |   0.41965  |
| Bori_Aron_solution-1 |     0.478063 |       0.527544 |   0.515293 |
| k-d_tree_pandas      |     0.474795 |       0.36504  |   0.5163   |
| k-d_tree_sklearn     |     0.483047 |       0.890114 |   0.967643 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483188 |       0.426262 |   0.418016 |
| k-d_tree_polars      |     0.496473 |       0.434491 |   0.443005 |
| barab-szabi-1        |     0.482067 |       0.415018 |   0.449832 |
| Bori_Aron_solution-1 |     0.481957 |       0.570444 |   0.523756 |
| k-d_tree_pandas      |     0.483941 |       0.385695 |   0.562795 |
| k-d_tree_sklearn     |     0.487627 |       0.959032 |   1.01259  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484662 |       0.480321 |   0.447828 |
| k-d_tree_polars      |     0.480539 |       0.52593  |   0.520758 |
| Bori_Aron_solution-1 |     0.468468 |       0.718235 |   0.526071 |
| barab-szabi-1        |     0.476737 |       0.529263 |   0.530982 |
| k-d_tree_pandas      |     0.493318 |       0.46562  |   0.686987 |
| k-d_tree_sklearn     |     0.48489  |       1.20132  |   1.04823  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480985 |       0.687908 |   0.477317 |
| Bori_Aron_solution-1 |     0.468863 |       1.33485  |   0.564767 |
| k-d_tree_polars      |     0.484667 |       0.842299 |   0.829997 |
| barab-szabi-1        |     0.472881 |       0.841938 |   0.865444 |
| k-d_tree_pandas      |     0.480732 |       0.72004  |   1.05922  |
| k-d_tree_sklearn     |     0.480133 |       1.92016  |   1.10496  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487276 |        4.85653 |   0.693851 |
| Bori_Aron_solution-1 |     0.471127 |        9.92757 |   0.896613 |
| k-d_tree_sklearn     |     0.482348 |       14.7598  |   1.24074  |
| barab-szabi-1        |     0.479104 |        4.8466  |   6.00178  |
| k-d_tree_polars      |     0.480348 |        4.79474 |   6.00287  |
| k-d_tree_pandas      |     0.489769 |        3.79272 |   6.36665  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479613 |        78.7004 |    2.71034 |
| k-d_tree_sklearn     |     0.489794 |       174.354  |    4.20962 |
| Bori_Aron_solution-1 |     0.598338 |       138.505  |   17.1235  |