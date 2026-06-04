# 2026-06-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.04021  |       1e-06    |   0.371904 |
| barab-szabi-2        |     0.456393 |       0.433945 |   0.431998 |
| k-d_tree_polars      |     0.465411 |       0.407759 |   0.432317 |
| barab-szabi-1        |     8.99986  |       0.430563 |   0.473855 |
| Bori_Aron_solution-1 |     0.455427 |       0.555635 |   0.545713 |
| k-d_tree_pandas      |     0.462183 |       0.407883 |   0.556596 |
| k-d_tree_sklearn     |     3.39614  |       1.01181  |   1.07586  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471696 |       0.442506 |   0.430313 |
| barab-szabi-1        |     0.469291 |       0.416831 |   0.441976 |
| k-d_tree_polars      |     0.463123 |       0.407444 |   0.444319 |
| k-d_tree_pandas      |     0.467386 |       0.391217 |   0.543705 |
| Bori_Aron_solution-1 |     0.460067 |       0.54565  |   0.544116 |
| k-d_tree_sklearn     |     0.473706 |       0.988773 |   1.0848   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472803 |       0.446922 |   0.448242 |
| k-d_tree_polars      |     0.472508 |       0.441584 |   0.462003 |
| barab-szabi-1        |     0.477957 |       0.440347 |   0.466139 |
| Bori_Aron_solution-1 |     0.45923  |       0.621665 |   0.548205 |
| k-d_tree_pandas      |     0.476471 |       0.411589 |   0.584396 |
| k-d_tree_sklearn     |     0.477437 |       1.07821  |   1.1068   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476225 |       0.519896 |   0.477746 |
| Bori_Aron_solution-1 |     0.464929 |       0.806182 |   0.568911 |
| k-d_tree_polars      |     0.474754 |       0.572474 |   0.571852 |
| barab-szabi-1        |     0.473055 |       0.563186 |   0.59794  |
| k-d_tree_pandas      |     0.471483 |       0.502327 |   0.719081 |
| k-d_tree_sklearn     |     0.478933 |       1.29323  |   1.15136  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476517 |       0.79178  |   0.570435 |
| Bori_Aron_solution-1 |     0.481602 |       1.50042  |   0.606451 |
| k-d_tree_polars      |     0.483319 |       0.919086 |   0.970857 |
| barab-szabi-1        |     0.479847 |       0.939966 |   0.996806 |
| k-d_tree_pandas      |     0.496243 |       0.794707 |   1.19711  |
| k-d_tree_sklearn     |     0.493036 |       2.23895  |   1.22308  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464528 |        5.95157 |   0.773622 |
| Bori_Aron_solution-1 |     0.458117 |       11.5969  |   0.805828 |
| k-d_tree_sklearn     |     0.474477 |       17.7346  |   1.26917  |
| barab-szabi-1        |     0.484534 |        5.20471 |   7.60789  |
| k-d_tree_polars      |     0.471298 |        5.26611 |   7.63154  |
| k-d_tree_pandas      |     0.488841 |        4.16822 |   8.0282   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465446 |        82.0633 |    2.75368 |
| k-d_tree_sklearn     |     0.679356 |       273.965  |    3.54913 |
| Bori_Aron_solution-1 |     0.481526 |       163.881  |   15.6079  |