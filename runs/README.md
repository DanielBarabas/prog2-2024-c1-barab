# 2026-09-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.88506  |       1e-06    |   0.415488 |
| barab-szabi-2        |     0.479523 |       0.45609  |   0.469656 |
| k-d_tree_polars      |     0.486917 |       0.441926 |   0.475744 |
| barab-szabi-1        |     8.78226  |       0.478566 |   0.568959 |
| k-d_tree_pandas      |     0.479803 |       0.415668 |   0.581539 |
| Bori_Aron_solution-1 |     0.493429 |       0.59025  |   0.605577 |
| k-d_tree_sklearn     |     3.16824  |       1.16078  |   1.13106  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.494961 |       0.468967 |   0.453224 |
| k-d_tree_polars      |     0.495646 |       0.449457 |   0.471981 |
| barab-szabi-1        |     0.497942 |       0.438084 |   0.478729 |
| k-d_tree_pandas      |     0.499284 |       0.411366 |   0.572723 |
| Bori_Aron_solution-1 |     0.478565 |       0.575471 |   0.581229 |
| k-d_tree_sklearn     |     0.509213 |       1.06526  |   1.16172  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.499461 |       0.484754 |   0.468806 |
| barab-szabi-1        |     0.487009 |       0.455281 |   0.491168 |
| k-d_tree_polars      |     0.498799 |       0.483691 |   0.49778  |
| Bori_Aron_solution-1 |     0.479316 |       0.604121 |   0.570372 |
| k-d_tree_pandas      |     0.482813 |       0.420378 |   0.598618 |
| k-d_tree_sklearn     |     0.490525 |       1.09382  |   1.16619  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488145 |       0.532856 |   0.502195 |
| k-d_tree_polars      |     0.49338  |       0.587406 |   0.580005 |
| Bori_Aron_solution-1 |     0.472843 |       0.800814 |   0.586622 |
| barab-szabi-1        |     0.495181 |       0.598111 |   0.609973 |
| k-d_tree_pandas      |     0.492883 |       0.514845 |   0.744388 |
| k-d_tree_sklearn     |     0.4977   |       1.31483  |   1.21387  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480478 |       0.762911 |   0.536284 |
| Bori_Aron_solution-1 |     0.473074 |       1.46293  |   0.600904 |
| k-d_tree_polars      |     0.484658 |       0.970988 |   0.95972  |
| barab-szabi-1        |     0.496964 |       0.930114 |   0.974521 |
| k-d_tree_pandas      |     0.477756 |       0.810253 |   1.19339  |
| k-d_tree_sklearn     |     0.488717 |       2.23087  |   1.29648  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467936 |        4.87912 |   0.742235 |
| Bori_Aron_solution-1 |     0.474631 |       10.7107  |   0.803323 |
| k-d_tree_sklearn     |     0.485049 |       16.8262  |   1.37127  |
| k-d_tree_polars      |     0.473746 |        5.21776 |   6.39408  |
| barab-szabi-1        |     0.484852 |        5.40146 |   6.46092  |
| k-d_tree_pandas      |     0.485721 |        4.38227 |   6.87748  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.867007 |         71.935 |    2.80865 |
| k-d_tree_sklearn     |     0.613815 |        235.346 |    3.82249 |
| Bori_Aron_solution-1 |     0.483255 |        149.299 |   29.5162  |