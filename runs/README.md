# 2024-10-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.51619  |       1e-06    |   0.353217 |
| barab-szabi-1        |     0.614954 |       0.399537 |   0.390818 |
| barab-szabi-2        |     0.617391 |       0.388481 |   0.391517 |
| k-d_tree_polars      |     0.619581 |       0.403233 |   0.408463 |
| Bori_Aron_solution-1 |     0.607805 |       0.52901  |   0.527356 |
| k-d_tree_pandas      |     0.613271 |       0.381795 |   0.552431 |
| k-d_tree_sklearn     |    10.1928   |       1.11201  |   0.969597 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.612019 |       0.410716 |   0.391695 |
| k-d_tree_polars      |     0.612939 |       0.413418 |   0.39888  |
| barab-szabi-2        |     0.6124   |       0.459401 |   0.401381 |
| Bori_Aron_solution-1 |     0.611214 |       0.529585 |   0.523061 |
| k-d_tree_pandas      |     0.616394 |       0.383775 |   0.562535 |
| k-d_tree_sklearn     |     0.619945 |       0.886809 |   0.963602 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627496 |       0.40173  |   0.40134  |
| k-d_tree_polars      |     0.622356 |       0.431713 |   0.417949 |
| barab-szabi-1        |     0.617958 |       0.433718 |   0.421956 |
| Bori_Aron_solution-1 |     0.607213 |       0.563516 |   0.524155 |
| k-d_tree_pandas      |     0.650702 |       0.40571  |   0.577057 |
| k-d_tree_sklearn     |     0.622513 |       0.943606 |   0.991546 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615134 |       0.467052 |   0.426879 |
| k-d_tree_polars      |     0.616014 |       0.541647 |   0.522137 |
| barab-szabi-1        |     0.613095 |       0.539294 |   0.527827 |
| Bori_Aron_solution-1 |     0.60645  |       0.749533 |   0.540663 |
| k-d_tree_pandas      |     0.6146   |       0.489264 |   0.709097 |
| k-d_tree_sklearn     |     0.620709 |       1.16516  |   1.03762  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61573  |       0.72074  |   0.462248 |
| Bori_Aron_solution-1 |     0.60575  |       1.41068  |   0.561722 |
| k-d_tree_polars      |     0.614272 |       0.864361 |   0.863128 |
| barab-szabi-1        |     0.617078 |       0.854598 |   0.908982 |
| k-d_tree_sklearn     |     0.637246 |       1.99469  |   1.14484  |
| k-d_tree_pandas      |     0.616883 |       0.742394 |   1.14589  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620846 |        5.26046 |   0.719067 |
| Bori_Aron_solution-1 |     0.609248 |       10.611   |   0.809874 |
| k-d_tree_sklearn     |     0.617855 |       15.7787  |   1.27746  |
| k-d_tree_polars      |     0.628147 |        4.83825 |   6.39021  |
| barab-szabi-1        |     0.611698 |        4.88258 |   6.48865  |
| k-d_tree_pandas      |     0.628556 |        3.9069  |   6.8263   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.647679 |        72.6145 |    2.97243 |
| k-d_tree_sklearn     |     0.617777 |       230.531  |    4.17256 |
| Bori_Aron_solution-1 |     0.637556 |       152.824  |   18.5527  |