# 2026-08-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.19232  |       1e-06    |   0.331558 |
| barab-szabi-2        |     4.81129  |       0.434152 |   0.40737  |
| barab-szabi-1        |     0.402905 |       0.379908 |   0.419733 |
| k-d_tree_polars      |     0.408208 |       0.381468 |   0.422805 |
| Bori_Aron_solution-1 |     3.8741   |       0.538245 |   0.451012 |
| k-d_tree_pandas      |     0.403256 |       0.357589 |   0.499858 |
| k-d_tree_sklearn     |     2.4715   |       1.01134  |   0.96687  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.411361 |       0.42005  |   0.408297 |
| barab-szabi-1        |     0.415136 |       0.388947 |   0.4227   |
| k-d_tree_polars      |     0.413482 |       0.388645 |   0.425973 |
| Bori_Aron_solution-1 |     0.407794 |       0.504893 |   0.500197 |
| k-d_tree_pandas      |     0.414411 |       0.407061 |   0.577855 |
| k-d_tree_sklearn     |     0.423584 |       0.909007 |   0.972985 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.411911 |       0.459713 |   0.413519 |
| k-d_tree_polars      |     0.416229 |       0.457061 |   0.448138 |
| barab-szabi-1        |     0.415405 |       0.413949 |   0.457824 |
| Bori_Aron_solution-1 |     0.412845 |       0.553024 |   0.503614 |
| k-d_tree_pandas      |     0.417175 |       0.377155 |   0.537903 |
| k-d_tree_sklearn     |     0.42162  |       0.952973 |   0.991828 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.419053 |       0.49164  |   0.446106 |
| k-d_tree_polars      |     0.426958 |       0.53663  |   0.510503 |
| Bori_Aron_solution-1 |     0.412556 |       0.693349 |   0.520816 |
| barab-szabi-1        |     0.411799 |       0.574686 |   0.563249 |
| k-d_tree_pandas      |     0.417757 |       0.452713 |   0.643865 |
| k-d_tree_sklearn     |     0.418932 |       1.20364  |   1.00858  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.413494 |       0.693475 |   0.488985 |
| Bori_Aron_solution-1 |     0.40777  |       1.2546   |   0.543798 |
| k-d_tree_polars      |     0.418218 |       0.934896 |   0.815844 |
| barab-szabi-1        |     0.414377 |       0.935736 |   0.856718 |
| k-d_tree_pandas      |     0.414937 |       0.693559 |   1.00996  |
| k-d_tree_sklearn     |     0.419396 |       2.00822  |   1.06587  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.410503 |        4.2962  |   0.665133 |
| Bori_Aron_solution-1 |     0.409285 |        9.22211 |   0.849327 |
| k-d_tree_sklearn     |     0.417681 |       14.4516  |   1.19226  |
| k-d_tree_polars      |     0.41298  |        5.04753 |   5.69596  |
| barab-szabi-1        |     0.41604  |        5.14769 |   5.743    |
| k-d_tree_pandas      |     0.415582 |        3.58413 |   6.06886  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.665457 |        63.6992 |    2.56173 |
| k-d_tree_sklearn     |     0.520623 |       176.814  |    3.78163 |
| Bori_Aron_solution-1 |     0.411594 |       148.571  |   27.2879  |