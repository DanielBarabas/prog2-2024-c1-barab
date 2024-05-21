# 2024-05-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.850377 |       0.436436 |   0.364024 |
| k-d_tree_polars      |     0.83684  |       0.458798 |   0.386166 |
| barab-szabi-2        |     4.87494  |       0.432545 |   0.387463 |
| Bori_Aron_solution-1 |     4.72812  |       0.474686 |   0.430547 |
| k-d_tree_pandas      |     0.817757 |       0.407108 |   0.541638 |
| solution-1           |     8.53727  |       1e-06    |   0.650494 |
| k-d_tree_sklearn     |     3.55285  |       1.21576  |   0.748349 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.871361 |       0.413955 |   0.16437  |
| barab-szabi-1        |     0.843126 |       0.448781 |   0.382101 |
| k-d_tree_polars      |     0.806924 |       0.448503 |   0.39185  |
| k-d_tree_pandas      |     0.831155 |       0.422064 |   0.5049   |
| Bori_Aron_solution-1 |     0.843362 |       0.581826 |   0.561913 |
| k-d_tree_sklearn     |     0.848358 |       0.964244 |   0.729588 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.845738 |       0.383039 |   0.162046 |
| k-d_tree_polars      |     0.84969  |       0.477986 |   0.401802 |
| barab-szabi-1        |     0.844685 |       0.470845 |   0.408502 |
| Bori_Aron_solution-1 |     0.815086 |       0.56017  |   0.528654 |
| k-d_tree_pandas      |     0.816067 |       0.423756 |   0.578405 |
| k-d_tree_sklearn     |     0.843105 |       1.08721  |   0.785721 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.83884  |       0.40161  |   0.17259  |
| barab-szabi-1        |     0.847129 |       0.554871 |   0.508917 |
| k-d_tree_polars      |     0.844901 |       0.57645  |   0.525438 |
| Bori_Aron_solution-1 |     0.833542 |       0.734708 |   0.546309 |
| k-d_tree_pandas      |     0.83241  |       0.518234 |   0.7012   |
| k-d_tree_sklearn     |     0.837318 |       1.22782  |   0.828876 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.820091 |       0.424666 |   0.159106 |
| Bori_Aron_solution-1 |     0.847108 |       1.44932  |   0.564221 |
| k-d_tree_polars      |     0.833064 |       0.89445  |   0.904414 |
| k-d_tree_sklearn     |     0.845109 |       2.15905  |   0.923491 |
| barab-szabi-1        |     0.821891 |       0.894169 |   0.936194 |
| k-d_tree_pandas      |     0.842882 |       0.806626 |   1.19037  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.875772 |       0.847684 |   0.165337 |
| Bori_Aron_solution-1 |     0.863609 |      11.1696   |   0.797651 |
| k-d_tree_sklearn     |     0.865334 |      17.4163   |   1.15368  |
| k-d_tree_polars      |     0.823102 |       5.03918  |   6.94387  |
| barab-szabi-1        |     0.850296 |       5.04335  |   7.07275  |
| k-d_tree_pandas      |     0.807739 |       4.03875  |   7.25245  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.04039  |        5.24374 |   0.160403 |
| k-d_tree_sklearn     |     0.843786 |      241.737   |   4.96747  |
| Bori_Aron_solution-1 |     0.801239 |      161.811   |  15.1168   |