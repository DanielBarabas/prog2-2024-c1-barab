# 2026-07-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.9484   |       1e-06    |   0.356589 |
| barab-szabi-2        |     8.62229  |       0.503282 |   0.446865 |
| k-d_tree_polars      |     0.469923 |       0.426006 |   0.452598 |
| barab-szabi-1        |     0.477701 |       0.457022 |   0.459839 |
| k-d_tree_pandas      |     0.479092 |       0.394037 |   0.559462 |
| Bori_Aron_solution-1 |     0.468606 |       0.570186 |   0.56758  |
| k-d_tree_sklearn     |     3.23883  |       1.05897  |   1.20598  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477378 |       0.446771 |   0.444541 |
| barab-szabi-1        |     0.474705 |       0.419938 |   0.455573 |
| k-d_tree_polars      |     0.487782 |       0.44057  |   0.458948 |
| Bori_Aron_solution-1 |     0.472624 |       0.569469 |   0.55572  |
| k-d_tree_pandas      |     0.475948 |       0.397421 |   0.574344 |
| k-d_tree_sklearn     |     0.49319  |       1.00757  |   1.11049  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475293 |       0.456781 |   0.458863 |
| barab-szabi-1        |     0.475895 |       0.464041 |   0.487788 |
| k-d_tree_polars      |     0.481609 |       0.458053 |   0.488945 |
| Bori_Aron_solution-1 |     0.482353 |       0.605388 |   0.558939 |
| k-d_tree_pandas      |     0.480358 |       0.417203 |   0.606811 |
| k-d_tree_sklearn     |     0.480626 |       1.08182  |   1.11926  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480352 |       0.518508 |   0.491984 |
| Bori_Aron_solution-1 |     0.467575 |       0.792114 |   0.566662 |
| k-d_tree_polars      |     0.474503 |       0.564209 |   0.571824 |
| barab-szabi-1        |     0.48373  |       0.572304 |   0.58494  |
| k-d_tree_pandas      |     0.474982 |       0.498386 |   0.739904 |
| k-d_tree_sklearn     |     0.478523 |       1.28763  |   1.15017  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474084 |       0.76186  |   0.529129 |
| Bori_Aron_solution-1 |     0.495786 |       1.48285  |   0.597437 |
| k-d_tree_polars      |     0.47573  |       0.946171 |   0.953779 |
| barab-szabi-1        |     0.481646 |       0.949361 |   1.00185  |
| k-d_tree_pandas      |     0.490401 |       0.803118 |   1.21184  |
| k-d_tree_sklearn     |     0.485528 |       2.22315  |   1.26554  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481329 |        5.12945 |   0.767971 |
| Bori_Aron_solution-1 |     0.488044 |       10.9811  |   0.836735 |
| k-d_tree_sklearn     |     0.476616 |       17.0666  |   1.30261  |
| k-d_tree_polars      |     0.46993  |        5.30811 |   6.83789  |
| barab-szabi-1        |     0.495714 |        5.32792 |   6.9781   |
| k-d_tree_pandas      |     0.47411  |        4.28656 |   7.35783  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496454 |        72.7194 |    2.78882 |
| k-d_tree_sklearn     |     0.762819 |       255.174  |    4.07232 |
| Bori_Aron_solution-1 |     0.470922 |       152.692  |   18.0469  |