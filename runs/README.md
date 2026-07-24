# 2026-07-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.51349  |       0.472768 |   0.445353 |
| barab-szabi-1        |     0.481832 |       0.427448 |   0.458572 |
| Bori_Aron_solution-1 |     0.45552  |       0.547698 |   0.549923 |
| solution-1           |     7.15229  |       1e-06    |   0.564049 |
| k-d_tree_pandas      |     0.471637 |       0.388825 |   0.573884 |
| k-d_tree_polars      |     8.52339  |       0.504099 |   0.621393 |
| k-d_tree_sklearn     |     2.85329  |       1.35115  |   1.11622  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.500363 |       0.458921 |   0.449453 |
| k-d_tree_polars      |     0.480232 |       0.433688 |   0.465297 |
| barab-szabi-1        |     0.496706 |       0.440953 |   0.467716 |
| Bori_Aron_solution-1 |     0.467837 |       0.562983 |   0.56709  |
| k-d_tree_pandas      |     0.483066 |       0.393689 |   0.572068 |
| k-d_tree_sklearn     |     0.484625 |       1.06688  |   1.14163  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.499847 |       0.483296 |   0.477257 |
| barab-szabi-1        |     0.493185 |       0.458855 |   0.485571 |
| k-d_tree_polars      |     0.480366 |       0.469434 |   0.491529 |
| Bori_Aron_solution-1 |     0.474899 |       0.647518 |   0.596855 |
| k-d_tree_pandas      |     0.475941 |       0.442015 |   0.640637 |
| k-d_tree_sklearn     |     0.532487 |       1.22656  |   1.19359  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488075 |       0.531303 |   0.49306  |
| barab-szabi-1        |     0.487243 |       0.599005 |   0.595012 |
| Bori_Aron_solution-1 |     0.485776 |       0.814415 |   0.595383 |
| k-d_tree_polars      |     0.480572 |       0.564901 |   0.595508 |
| k-d_tree_pandas      |     0.486098 |       0.512934 |   0.772891 |
| k-d_tree_sklearn     |     0.487391 |       1.31359  |   1.24397  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484406 |       0.754315 |   0.594753 |
| Bori_Aron_solution-1 |     0.459036 |       1.45097  |   0.637671 |
| k-d_tree_polars      |     0.50975  |       0.922121 |   0.946803 |
| barab-szabi-1        |     0.489853 |       0.972352 |   1.02738  |
| k-d_tree_pandas      |     0.497343 |       0.812543 |   1.23284  |
| k-d_tree_sklearn     |     0.477836 |       2.22692  |   1.28709  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.507129 |        5.79137 |   0.800796 |
| Bori_Aron_solution-1 |     0.485646 |       11.5912  |   0.857725 |
| k-d_tree_sklearn     |     0.49578  |       18.5046  |   1.42387  |
| k-d_tree_polars      |     0.497283 |        5.39204 |   7.31468  |
| barab-szabi-1        |     0.521869 |        5.45717 |   7.37856  |
| k-d_tree_pandas      |     0.502151 |        4.45805 |   7.83043  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614429 |        76.7198 |    2.99041 |
| k-d_tree_sklearn     |     0.862677 |       248.304  |    4.19634 |
| Bori_Aron_solution-1 |     0.474112 |       161.214  |   14.8362  |