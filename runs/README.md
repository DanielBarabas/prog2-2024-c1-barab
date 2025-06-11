# 2025-06-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567224 |       0.440452 |   0.438033 |
| k-d_tree_polars      |     0.57155  |       0.438091 |   0.449832 |
| solution-1           |     8.30585  |       1e-06    |   0.460421 |
| barab-szabi-1        |     0.649675 |       0.453455 |   0.479006 |
| Bori_Aron_solution-1 |     1.00902  |       0.583761 |   0.587227 |
| k-d_tree_pandas      |     8.74895  |       0.457342 |   0.689624 |
| k-d_tree_sklearn     |     3.62493  |       1.25456  |   1.17394  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.578779 |       0.429385 |   0.439275 |
| barab-szabi-2        |     0.566986 |       0.441008 |   0.442443 |
| barab-szabi-1        |     0.575829 |       0.445142 |   0.453717 |
| Bori_Aron_solution-1 |     0.572073 |       0.589551 |   0.578791 |
| k-d_tree_pandas      |     0.585865 |       0.404384 |   0.590489 |
| k-d_tree_sklearn     |     0.577684 |       1.02301  |   1.14819  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612593 |       0.469975 |   0.478716 |
| k-d_tree_polars      |     0.601808 |       0.47647  |   0.480295 |
| barab-szabi-1        |     0.613988 |       0.487731 |   0.507625 |
| k-d_tree_pandas      |     0.563392 |       0.433352 |   0.651239 |
| Bori_Aron_solution-1 |     0.575558 |       0.687886 |   0.655475 |
| k-d_tree_sklearn     |     0.601045 |       1.17423  |   1.21455  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.568798 |       0.512951 |   0.475074 |
| k-d_tree_polars      |     0.579605 |       0.567457 |   0.57458  |
| barab-szabi-1        |     0.587826 |       0.562494 |   0.575703 |
| Bori_Aron_solution-1 |     0.582002 |       0.844082 |   0.617558 |
| k-d_tree_pandas      |     0.599855 |       0.517087 |   0.803596 |
| k-d_tree_sklearn     |     0.577842 |       1.28266  |   1.16504  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.573798 |       0.753623 |   0.501623 |
| Bori_Aron_solution-1 |     0.574029 |       1.46222  |   0.604269 |
| k-d_tree_polars      |     0.560193 |       0.914796 |   0.968472 |
| barab-szabi-1        |     0.572016 |       0.913559 |   0.987154 |
| k-d_tree_sklearn     |     0.582063 |       2.18058  |   1.23528  |
| k-d_tree_pandas      |     0.553474 |       0.78635  |   1.24953  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562354 |        5.94809 |   0.832797 |
| Bori_Aron_solution-1 |     0.550625 |       10.9656  |   0.85534  |
| k-d_tree_sklearn     |     0.575896 |       18.1564  |   1.38045  |
| k-d_tree_polars      |     0.565545 |        5.02816 |   7.04069  |
| barab-szabi-1        |     0.569221 |        5.11563 |   7.35926  |
| k-d_tree_pandas      |     0.554687 |        3.94216 |   7.38297  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.740559 |        81.9036 |    3.4984  |
| k-d_tree_sklearn     |     0.733765 |       252.676  |    3.97414 |
| Bori_Aron_solution-1 |     0.574055 |       164.286  |   15.7631  |