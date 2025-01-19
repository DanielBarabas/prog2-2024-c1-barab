# 2025-01-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.18082  |       1e-06    |   0.358262 |
| k-d_tree_polars      |     0.58672  |       0.400689 |   0.399487 |
| barab-szabi-2        |     0.571494 |       0.40897  |   0.400185 |
| barab-szabi-1        |     0.569748 |       0.408109 |   0.402677 |
| Bori_Aron_solution-1 |     0.585896 |       0.535959 |   0.564408 |
| k-d_tree_pandas      |     7.79091  |       0.437654 |   0.643869 |
| k-d_tree_sklearn     |     3.02938  |       1.02829  |   1.00991  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.578886 |       0.402662 |   0.397447 |
| k-d_tree_polars      |     0.584368 |       0.405175 |   0.404762 |
| barab-szabi-1        |     0.578309 |       0.405895 |   0.408688 |
| Bori_Aron_solution-1 |     0.576356 |       0.533482 |   0.525565 |
| k-d_tree_pandas      |     0.593245 |       0.387927 |   0.539017 |
| k-d_tree_sklearn     |     0.581772 |       0.942911 |   1.01726  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581702 |       0.412086 |   0.408402 |
| k-d_tree_polars      |     0.579723 |       0.42778  |   0.428079 |
| barab-szabi-1        |     0.58252  |       0.440232 |   0.439476 |
| Bori_Aron_solution-1 |     0.572344 |       0.574552 |   0.539222 |
| k-d_tree_pandas      |     0.602841 |       0.402694 |   0.582968 |
| k-d_tree_sklearn     |     0.598286 |       0.980174 |   1.04389  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587282 |       0.472504 |   0.454832 |
| k-d_tree_polars      |     0.58092  |       0.534285 |   0.522068 |
| barab-szabi-1        |     0.585468 |       0.545825 |   0.535755 |
| Bori_Aron_solution-1 |     0.5733   |       0.742004 |   0.545827 |
| k-d_tree_pandas      |     0.583105 |       0.474133 |   0.716126 |
| k-d_tree_sklearn     |     0.583967 |       1.19862  |   1.10334  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.582682 |       0.709742 |   0.476984 |
| Bori_Aron_solution-1 |     0.580623 |       1.37484  |   0.570619 |
| k-d_tree_polars      |     0.588011 |       0.862602 |   0.871967 |
| barab-szabi-1        |     0.584638 |       0.855811 |   0.90132  |
| k-d_tree_pandas      |     0.582126 |       0.741685 |   1.15427  |
| k-d_tree_sklearn     |     0.583112 |       2.0814   |   1.20473  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.581228 |        5.28837 |   0.737842 |
| Bori_Aron_solution-1 |     0.575977 |       10.4068  |   0.864055 |
| k-d_tree_sklearn     |     0.588627 |       15.9801  |   1.31391  |
| k-d_tree_polars      |     0.584331 |        4.92069 |   6.5429   |
| barab-szabi-1        |     0.580275 |        4.86809 |   6.59641  |
| k-d_tree_pandas      |     0.576826 |        3.81    |   6.95303  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.582481 |         75.873 |    3.02728 |
| k-d_tree_sklearn     |     0.585901 |        229.684 |    4.49358 |
| Bori_Aron_solution-1 |     0.649858 |        150.251 |   17.3311  |