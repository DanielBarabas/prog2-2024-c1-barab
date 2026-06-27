# 2026-06-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.24977  |       1e-06    |   0.406662 |
| barab-szabi-2        |     8.49479  |       0.614381 |   0.428011 |
| barab-szabi-1        |     0.484143 |       0.401878 |   0.432293 |
| k-d_tree_polars      |     0.460888 |       0.411845 |   0.456221 |
| Bori_Aron_solution-1 |     0.45242  |       0.539747 |   0.537229 |
| k-d_tree_pandas      |     0.468889 |       0.376933 |   0.543469 |
| k-d_tree_sklearn     |     2.88053  |       1.1062   |   1.04845  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464491 |       0.431821 |   0.437965 |
| barab-szabi-1        |     0.462199 |       0.404813 |   0.44007  |
| k-d_tree_polars      |     0.463306 |       0.407926 |   0.446358 |
| Bori_Aron_solution-1 |     0.460451 |       0.543031 |   0.533424 |
| k-d_tree_pandas      |     0.459768 |       0.387045 |   0.554821 |
| k-d_tree_sklearn     |     0.466424 |       0.984616 |   1.06739  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471054 |       0.445441 |   0.459706 |
| k-d_tree_polars      |     0.464359 |       0.430917 |   0.46541  |
| barab-szabi-1        |     0.472803 |       0.430971 |   0.47078  |
| Bori_Aron_solution-1 |     0.466046 |       0.582652 |   0.547318 |
| k-d_tree_pandas      |     0.473023 |       0.402973 |   0.596114 |
| k-d_tree_sklearn     |     0.469336 |       1.01914  |   1.07871  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.460699 |       0.508578 |   0.483237 |
| Bori_Aron_solution-1 |     0.505583 |       0.780399 |   0.551033 |
| k-d_tree_polars      |     0.466106 |       0.547571 |   0.566585 |
| barab-szabi-1        |     0.463979 |       0.556769 |   0.569218 |
| k-d_tree_pandas      |     0.467994 |       0.497685 |   0.725279 |
| k-d_tree_sklearn     |     0.47383  |       1.25916  |   1.13021  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.46128  |       0.734224 |   0.51351  |
| Bori_Aron_solution-1 |     0.457743 |       1.40276  |   0.582628 |
| k-d_tree_polars      |     0.468004 |       0.908561 |   0.910487 |
| barab-szabi-1        |     0.460869 |       0.909689 |   0.948647 |
| k-d_tree_pandas      |     0.463607 |       0.789661 |   1.15446  |
| k-d_tree_sklearn     |     0.466805 |       2.17394  |   1.20265  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.461783 |        5.48132 |   0.764207 |
| Bori_Aron_solution-1 |     0.457982 |       10.949   |   0.814498 |
| k-d_tree_sklearn     |     0.462242 |       17.2199  |   1.37376  |
| k-d_tree_polars      |     0.462698 |        5.34085 |   6.75689  |
| barab-szabi-1        |     0.478561 |        5.37938 |   6.84443  |
| k-d_tree_pandas      |     0.476212 |        4.32321 |   7.2002   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474076 |        70.1183 |    2.78733 |
| k-d_tree_sklearn     |     0.737981 |       234.431  |    3.98915 |
| Bori_Aron_solution-1 |     0.484359 |       151.293  |   25.0439  |