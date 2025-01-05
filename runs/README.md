# 2025-01-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.69606  |       1e-06    |   0.391896 |
| barab-szabi-2        |     0.571314 |       0.408376 |   0.392375 |
| k-d_tree_polars      |     0.592829 |       0.399957 |   0.396827 |
| barab-szabi-1        |     0.574284 |       0.398305 |   0.400956 |
| Bori_Aron_solution-1 |     0.577715 |       0.523123 |   0.532676 |
| k-d_tree_pandas      |     8.29012  |       0.432943 |   0.605526 |
| k-d_tree_sklearn     |     3.07318  |       0.961687 |   1.0107   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585032 |       0.412886 |   0.403997 |
| barab-szabi-1        |     0.588177 |       0.403493 |   0.404263 |
| k-d_tree_polars      |     0.589232 |       0.403096 |   0.404882 |
| Bori_Aron_solution-1 |     0.578329 |       0.540235 |   0.532184 |
| k-d_tree_pandas      |     0.595616 |       0.389684 |   0.538532 |
| k-d_tree_sklearn     |     0.590722 |       0.947261 |   1.01376  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579987 |       0.413296 |   0.412887 |
| k-d_tree_polars      |     0.58296  |       0.425155 |   0.427684 |
| barab-szabi-1        |     0.582963 |       0.424004 |   0.430718 |
| Bori_Aron_solution-1 |     0.577371 |       0.565497 |   0.530059 |
| k-d_tree_pandas      |     0.588141 |       0.398143 |   0.577798 |
| k-d_tree_sklearn     |     0.584909 |       0.995492 |   1.04497  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591827 |       0.475206 |   0.440584 |
| k-d_tree_polars      |     0.584741 |       0.526136 |   0.524803 |
| barab-szabi-1        |     0.59069  |       0.528965 |   0.537229 |
| Bori_Aron_solution-1 |     0.577141 |       0.739093 |   0.544382 |
| k-d_tree_pandas      |     0.585053 |       0.470783 |   0.711187 |
| k-d_tree_sklearn     |     0.587428 |       1.19458  |   1.08951  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585323 |       0.708066 |   0.471473 |
| Bori_Aron_solution-1 |     0.581933 |       1.36042  |   0.561421 |
| k-d_tree_polars      |     0.585635 |       0.851315 |   0.866947 |
| barab-szabi-1        |     0.588097 |       0.8408   |   0.907842 |
| k-d_tree_pandas      |     0.586164 |       0.736336 |   1.14629  |
| k-d_tree_sklearn     |     0.585279 |       1.99538  |   1.18472  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583458 |        5.34116 |   0.729006 |
| Bori_Aron_solution-1 |     0.579795 |       10.563   |   0.812398 |
| k-d_tree_sklearn     |     0.588663 |       15.9465  |   1.2847   |
| k-d_tree_polars      |     0.590506 |        4.78486 |   6.58206  |
| barab-szabi-1        |     0.58592  |        4.79067 |   6.61608  |
| k-d_tree_pandas      |     0.584144 |        3.82552 |   6.97923  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.585796 |        72.8037 |    2.91104 |
| k-d_tree_sklearn     |     0.601587 |       223.447  |    4.53454 |
| Bori_Aron_solution-1 |     0.700649 |       148.973  |   17.0775  |