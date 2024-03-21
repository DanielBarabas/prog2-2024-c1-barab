# 2024-03-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.707987 |       0.500849 |   0.36942  |
| barab-szabi-1        |     0.729977 |       0.416848 |   0.371264 |
| k-d_tree_polars      |     0.73123  |       0.411723 |   0.373178 |
| Bori_Aron_solution-1 |     0.687457 |       0.522022 |   0.532716 |
| solution-1           |    28.4444   |       1e-06    |   0.688773 |
| k-d_tree_sklearn     |     3.37033  |       1.0543   |   0.690068 |
| k-d_tree_pandas      |    48.034    |       0.468284 |   0.73108  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.717423 |       0.367729 |   0.366771 |
| barab-szabi-1        |     0.729138 |       0.41415  |   0.371161 |
| k-d_tree_polars      |     0.727155 |       0.413185 |   0.374662 |
| Bori_Aron_solution-1 |     0.728794 |       0.522517 |   0.512332 |
| k-d_tree_pandas      |     0.734844 |       0.400062 |   0.527219 |
| k-d_tree_sklearn     |     0.734449 |       0.868338 |   0.680758 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732964 |       0.384387 |   0.384061 |
| k-d_tree_polars      |     0.737766 |       0.447059 |   0.403411 |
| barab-szabi-1        |     0.731416 |       0.434486 |   0.414765 |
| Bori_Aron_solution-1 |     0.7272   |       0.558196 |   0.503236 |
| k-d_tree_pandas      |     0.727454 |       0.40808  |   0.562202 |
| k-d_tree_sklearn     |     0.757903 |       0.914333 |   0.72981  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734475 |       0.444689 |   0.402449 |
| k-d_tree_polars      |     0.724223 |       0.540812 |   0.492265 |
| barab-szabi-1        |     0.723826 |       0.538154 |   0.503881 |
| Bori_Aron_solution-1 |     0.71575  |       0.728424 |   0.509351 |
| k-d_tree_pandas      |     0.741629 |       0.489031 |   0.686999 |
| k-d_tree_sklearn     |     0.725927 |       1.14628  |   0.759951 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.728921 |       0.691443 |   0.445185 |
| Bori_Aron_solution-1 |     0.712204 |       1.37691  |   0.538086 |
| k-d_tree_polars      |     0.715333 |       0.851293 |   0.838268 |
| k-d_tree_sklearn     |     0.72358  |       1.95367  |   0.865405 |
| barab-szabi-1        |     0.722759 |       0.899165 |   0.901124 |
| k-d_tree_pandas      |     0.727201 |       0.761582 |   1.11591  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.722422 |        5.68159 |   0.794876 |
| Bori_Aron_solution-1 |     0.730763 |       11.1203  |   0.806963 |
| k-d_tree_sklearn     |     0.734204 |       17.0717  |   1.09308  |
| barab-szabi-1        |     0.720632 |        4.9559  |   6.80646  |
| k-d_tree_polars      |     0.730698 |        5.02989 |   7.01701  |
| k-d_tree_pandas      |     0.729235 |        4.02261 |   7.03008  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.724692 |        74.8963 |    3.8192  |
| k-d_tree_sklearn     |     0.943157 |       231.18   |    4.84166 |
| Bori_Aron_solution-1 |     0.835926 |       150.009  |   18.4905  |