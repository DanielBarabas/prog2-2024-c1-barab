# 2025-03-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556756 |       0.410564 |   0.397601 |
| k-d_tree_polars      |     0.553489 |       0.397984 |   0.415415 |
| barab-szabi-1        |     0.547391 |       0.41086  |   0.479533 |
| solution-1           |     7.53336  |       1e-06    |   0.522008 |
| Bori_Aron_solution-1 |     0.548959 |       0.539362 |   0.539443 |
| k-d_tree_pandas      |     7.59066  |       0.441527 |   0.680852 |
| k-d_tree_sklearn     |     3.11846  |       1.11393  |   1.00393  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.568496 |       0.405087 |   0.407646 |
| k-d_tree_polars      |     0.564364 |       0.414023 |   0.41632  |
| barab-szabi-1        |     0.564061 |       0.416238 |   0.420809 |
| Bori_Aron_solution-1 |     0.568781 |       0.564243 |   0.560341 |
| k-d_tree_pandas      |     0.578933 |       0.414513 |   0.593964 |
| k-d_tree_sklearn     |     0.581281 |       0.949667 |   1.02335  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56343  |       0.421071 |   0.424296 |
| barab-szabi-1        |     0.560722 |       0.434356 |   0.439169 |
| k-d_tree_polars      |     0.562349 |       0.433084 |   0.448546 |
| k-d_tree_pandas      |     0.562418 |       0.403725 |   0.590737 |
| Bori_Aron_solution-1 |     0.553733 |       0.604628 |   0.591357 |
| k-d_tree_sklearn     |     0.5997   |       1.01739  |   1.06862  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555825 |       0.478513 |   0.446269 |
| k-d_tree_polars      |     0.559233 |       0.531697 |   0.533479 |
| barab-szabi-1        |     0.564948 |       0.533021 |   0.558504 |
| Bori_Aron_solution-1 |     0.573227 |       0.762516 |   0.566726 |
| k-d_tree_pandas      |     0.575296 |       0.484527 |   0.740505 |
| k-d_tree_sklearn     |     0.558946 |       1.19648  |   1.09874  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.572527 |       0.746296 |   0.499319 |
| Bori_Aron_solution-1 |     0.54943  |       1.37959  |   0.584563 |
| k-d_tree_polars      |     0.558244 |       0.878642 |   0.89874  |
| barab-szabi-1        |     0.555473 |       0.852558 |   0.91759  |
| k-d_tree_pandas      |     0.558399 |       0.734877 |   1.16411  |
| k-d_tree_sklearn     |     0.571043 |       2.09688  |   1.20732  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.600182 |        5.80696 |   0.807883 |
| Bori_Aron_solution-1 |     0.598473 |       10.9534  |   0.909783 |
| k-d_tree_sklearn     |     0.63699  |       18.2294  |   1.46625  |
| k-d_tree_polars      |     0.594422 |        4.96988 |   6.8884   |
| barab-szabi-1        |     0.595029 |        5.03962 |   6.94392  |
| k-d_tree_pandas      |     0.566712 |        3.89123 |   7.47008  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.839812 |        73.3288 |    4.02094 |
| k-d_tree_sklearn     |     0.63974  |       224.179  |    4.21684 |
| Bori_Aron_solution-1 |     0.610295 |       152.635  |   12.7964  |