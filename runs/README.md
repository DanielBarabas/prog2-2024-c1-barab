# 2025-10-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543238 |       0.596362 |   0.434235 |
| k-d_tree_polars      |     0.554805 |       0.423751 |   0.445777 |
| barab-szabi-1        |     0.61588  |       0.434617 |   0.452116 |
| solution-1           |     7.81682  |       1e-06    |   0.488876 |
| Bori_Aron_solution-1 |     0.550466 |       0.561108 |   0.558043 |
| k-d_tree_pandas      |     9.44344  |       0.425736 |   0.718816 |
| k-d_tree_sklearn     |     3.32194  |       1.15672  |   1.10904  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558219 |       0.434986 |   0.437902 |
| barab-szabi-1        |     0.550718 |       0.422823 |   0.441938 |
| k-d_tree_polars      |     0.555239 |       0.425867 |   0.445031 |
| Bori_Aron_solution-1 |     0.558516 |       0.576319 |   0.553969 |
| k-d_tree_pandas      |     0.558315 |       0.400743 |   0.568799 |
| k-d_tree_sklearn     |     0.554915 |       1.01241  |   1.09138  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571437 |       0.459257 |   0.459024 |
| k-d_tree_polars      |     0.563443 |       0.453537 |   0.470487 |
| barab-szabi-1        |     0.560312 |       0.459764 |   0.478623 |
| Bori_Aron_solution-1 |     0.546219 |       0.606017 |   0.570525 |
| k-d_tree_pandas      |     0.557727 |       0.424522 |   0.621861 |
| k-d_tree_sklearn     |     0.575528 |       1.07258  |   1.12759  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556728 |       0.51882  |   0.485849 |
| k-d_tree_polars      |     0.566126 |       0.596254 |   0.572825 |
| Bori_Aron_solution-1 |     0.562124 |       0.814483 |   0.58463  |
| barab-szabi-1        |     0.559546 |       0.581763 |   0.588451 |
| k-d_tree_pandas      |     0.555216 |       0.518974 |   0.758061 |
| k-d_tree_sklearn     |     0.572954 |       1.28762  |   1.17471  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556758 |       0.754685 |   0.513543 |
| Bori_Aron_solution-1 |     0.550447 |       1.50759  |   0.616612 |
| k-d_tree_polars      |     0.546694 |       0.967408 |   0.935941 |
| barab-szabi-1        |     0.551598 |       0.953995 |   0.968488 |
| k-d_tree_pandas      |     0.562498 |       0.836431 |   1.19598  |
| k-d_tree_sklearn     |     0.559865 |       2.20049  |   1.23808  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565647 |        5.47467 |   0.758874 |
| Bori_Aron_solution-1 |     0.547914 |       11.6231  |   0.843236 |
| k-d_tree_sklearn     |     0.559279 |       17.3119  |   1.36393  |
| k-d_tree_polars      |     0.554492 |        5.59075 |   6.76338  |
| barab-szabi-1        |     0.565515 |        5.56308 |   6.76967  |
| k-d_tree_pandas      |     0.559539 |        4.59264 |   7.22296  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554633 |        76.8893 |    2.80507 |
| k-d_tree_sklearn     |     0.571197 |       245.994  |    4.22287 |
| Bori_Aron_solution-1 |     0.78367  |       151.651  |   18.0237  |