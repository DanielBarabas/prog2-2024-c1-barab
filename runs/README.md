# 2026-05-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.46108  |       0.403976 |   0.445292 |
| barab-szabi-2        |     0.460128 |       0.444866 |   0.446833 |
| solution-1           |     8.2078   |       1e-06    |   0.5323   |
| k-d_tree_pandas      |     0.462872 |       0.396683 |   0.545688 |
| Bori_Aron_solution-1 |     0.455273 |       0.545137 |   0.549394 |
| barab-szabi-1        |     8.4839   |       0.484358 |   0.884605 |
| k-d_tree_sklearn     |     3.15637  |       1.28737  |   1.08445  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471098 |       0.446737 |   0.434901 |
| barab-szabi-1        |     0.475884 |       0.413345 |   0.450867 |
| k-d_tree_polars      |     0.472696 |       0.44107  |   0.453946 |
| Bori_Aron_solution-1 |     0.463257 |       0.558545 |   0.547739 |
| k-d_tree_pandas      |     0.474897 |       0.392064 |   0.555741 |
| k-d_tree_sklearn     |     0.482099 |       0.970997 |   1.07792  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484522 |       0.464856 |   0.454955 |
| barab-szabi-1        |     0.477734 |       0.441677 |   0.473737 |
| k-d_tree_polars      |     0.506038 |       0.441998 |   0.476263 |
| Bori_Aron_solution-1 |     0.465675 |       0.59346  |   0.558029 |
| k-d_tree_pandas      |     0.476043 |       0.412816 |   0.601666 |
| k-d_tree_sklearn     |     0.478043 |       1.03476  |   1.11116  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474674 |       0.513733 |   0.481309 |
| Bori_Aron_solution-1 |     0.461562 |       0.785779 |   0.560387 |
| k-d_tree_polars      |     0.471184 |       0.558791 |   0.566448 |
| barab-szabi-1        |     0.469007 |       0.562391 |   0.583229 |
| k-d_tree_pandas      |     0.4752   |       0.502682 |   0.742216 |
| k-d_tree_sklearn     |     0.477856 |       1.26798  |   1.16776  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47384  |       0.731641 |   0.513651 |
| Bori_Aron_solution-1 |     0.466581 |       1.43087  |   0.584569 |
| k-d_tree_polars      |     0.471516 |       0.931005 |   0.91545  |
| barab-szabi-1        |     0.474765 |       0.939824 |   0.959371 |
| k-d_tree_pandas      |     0.470253 |       0.820296 |   1.18427  |
| k-d_tree_sklearn     |     0.479492 |       2.12656  |   1.22833  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470798 |        5.01356 |   0.739513 |
| Bori_Aron_solution-1 |     0.466443 |       10.9812  |   0.811828 |
| k-d_tree_sklearn     |     0.472304 |       16.5002  |   1.29466  |
| barab-szabi-1        |     0.482456 |        5.56631 |   6.64394  |
| k-d_tree_polars      |     0.47546  |        5.5135  |   6.68961  |
| k-d_tree_pandas      |     0.46652  |        4.42922 |   7.00584  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472445 |        69.2263 |     2.5636 |
| k-d_tree_sklearn     |     0.779274 |       232.881  |     3.8056 |
| Bori_Aron_solution-1 |     0.476604 |       146.67   |    25.4767 |