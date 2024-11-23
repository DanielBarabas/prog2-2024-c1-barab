# 2024-11-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.643176 |       0.408132 |   0.406078 |
| barab-szabi-1        |     0.641239 |       0.427867 |   0.416053 |
| k-d_tree_polars      |     0.645931 |       0.430914 |   0.425611 |
| solution-1           |     7.80239  |       1e-06    |   0.514081 |
| Bori_Aron_solution-1 |     0.633308 |       0.561835 |   0.556643 |
| k-d_tree_pandas      |     0.662825 |       0.410995 |   0.56228  |
| k-d_tree_sklearn     |    10.7104   |       1.23978  |   1.06519  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.643802 |       0.415646 |   0.407096 |
| barab-szabi-1        |     0.649043 |       0.429845 |   0.417273 |
| k-d_tree_polars      |     0.644147 |       0.437183 |   0.466032 |
| Bori_Aron_solution-1 |     0.633796 |       0.556101 |   0.542135 |
| k-d_tree_pandas      |     0.648806 |       0.40066  |   0.568233 |
| k-d_tree_sklearn     |     0.659445 |       0.944368 |   1.0443   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.633306 |       0.418229 |   0.412473 |
| barab-szabi-1        |     0.628561 |       0.448134 |   0.437117 |
| k-d_tree_polars      |     0.633323 |       0.443442 |   0.443133 |
| Bori_Aron_solution-1 |     0.638376 |       0.591436 |   0.549162 |
| k-d_tree_pandas      |     0.649428 |       0.431762 |   0.619846 |
| k-d_tree_sklearn     |     0.643732 |       0.97627  |   1.03164  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632658 |       0.476881 |   0.440619 |
| k-d_tree_polars      |     0.64333  |       0.552381 |   0.528597 |
| barab-szabi-1        |     0.647096 |       0.553743 |   0.55425  |
| Bori_Aron_solution-1 |     0.630791 |       0.767936 |   0.571163 |
| k-d_tree_pandas      |     0.641781 |       0.499213 |   0.728738 |
| k-d_tree_sklearn     |     0.659928 |       1.24523  |   1.11629  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.643266 |       0.743837 |   0.497305 |
| Bori_Aron_solution-1 |     0.629436 |       1.48588  |   0.583473 |
| k-d_tree_polars      |     0.629586 |       0.87447  |   0.918308 |
| barab-szabi-1        |     0.63309  |       0.894519 |   0.947206 |
| k-d_tree_sklearn     |     0.638453 |       2.07661  |   1.18432  |
| k-d_tree_pandas      |     0.643338 |       0.763719 |   1.20463  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.636209 |        5.72754 |   0.757503 |
| Bori_Aron_solution-1 |     0.620402 |       11.1044  |   0.833065 |
| k-d_tree_sklearn     |     0.656245 |       17.2732  |   1.29962  |
| k-d_tree_polars      |     0.646286 |        4.88268 |   6.86157  |
| barab-szabi-1        |     0.629616 |        4.95129 |   7.05155  |
| k-d_tree_pandas      |     0.634161 |        3.90522 |   7.54585  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.664491 |        75.0938 |    3.00163 |
| k-d_tree_sklearn     |     0.632023 |       235.686  |    4.29899 |
| Bori_Aron_solution-1 |     0.670844 |       152.48   |   18.1183  |