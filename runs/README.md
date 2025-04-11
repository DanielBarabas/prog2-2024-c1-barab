# 2025-04-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.62443  |       1e-06    |   0.363549 |
| barab-szabi-2        |     0.574564 |       0.423778 |   0.412889 |
| k-d_tree_polars      |     0.554977 |       0.410581 |   0.413415 |
| barab-szabi-1        |     0.556961 |       0.408538 |   0.419984 |
| Bori_Aron_solution-1 |     0.562491 |       0.56082  |   0.544327 |
| k-d_tree_pandas      |     8.25217  |       0.447477 |   0.642713 |
| k-d_tree_sklearn     |     3.13505  |       0.995772 |   1.04544  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.572649 |       0.416797 |   0.408947 |
| barab-szabi-1        |     0.58274  |       0.417063 |   0.417747 |
| k-d_tree_polars      |     0.593329 |       0.417014 |   0.419672 |
| k-d_tree_pandas      |     0.581679 |       0.39404  |   0.56246  |
| Bori_Aron_solution-1 |     0.563998 |       0.566364 |   0.592779 |
| k-d_tree_sklearn     |     0.57082  |       0.988034 |   1.0509   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.572361 |       0.427926 |   0.423922 |
| k-d_tree_polars      |     0.565379 |       0.443127 |   0.442888 |
| barab-szabi-1        |     0.575542 |       0.436167 |   0.444793 |
| Bori_Aron_solution-1 |     0.554939 |       0.592607 |   0.569208 |
| k-d_tree_pandas      |     0.582292 |       0.416485 |   0.606735 |
| k-d_tree_sklearn     |     0.59903  |       1.03177  |   1.1029   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575094 |       0.501913 |   0.456515 |
| barab-szabi-1        |     0.578329 |       0.572689 |   0.554206 |
| k-d_tree_polars      |     0.5682   |       0.547668 |   0.560192 |
| Bori_Aron_solution-1 |     0.564769 |       0.761443 |   0.570672 |
| k-d_tree_pandas      |     0.582596 |       0.488325 |   0.73447  |
| k-d_tree_sklearn     |     0.573327 |       1.23199  |   1.13484  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.565139 |       0.733079 |   0.488522 |
| Bori_Aron_solution-1 |     0.563775 |       1.40345  |   0.598773 |
| k-d_tree_polars      |     0.579138 |       0.875054 |   0.911253 |
| barab-szabi-1        |     0.576377 |       0.884003 |   0.94824  |
| k-d_tree_pandas      |     0.568989 |       0.753106 |   1.18027  |
| k-d_tree_sklearn     |     0.586377 |       2.06842  |   1.2227   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570001 |        5.74881 |   0.760159 |
| Bori_Aron_solution-1 |     0.562871 |       11.1292  |   0.893497 |
| k-d_tree_sklearn     |     0.581565 |       16.771   |   1.3368   |
| barab-szabi-1        |     0.578743 |        4.97121 |   7.03185  |
| k-d_tree_polars      |     0.569573 |        5.061   |   7.04573  |
| k-d_tree_pandas      |     0.57519  |        3.8673  |   7.56959  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.767179 |         77.775 |    3.38266 |
| k-d_tree_sklearn     |     0.67101  |        246.282 |    4.27299 |
| Bori_Aron_solution-1 |     0.563756 |        166.072 |   15.4966  |