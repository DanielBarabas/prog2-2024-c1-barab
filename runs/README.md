# 2026-10-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     5.05743  |       0        |   0.303013 |
| k-d_tree_polars      |     0.302192 |       0.307234 |   0.329815 |
| barab-szabi-2        |     0.32158  |       0.312932 |   0.361552 |
| Bori_Aron_solution-1 |     0.311664 |       0.389627 |   0.391449 |
| k-d_tree_pandas      |     0.288646 |       0.266771 |   0.433272 |
| barab-szabi-1        |     7.40467  |       0.413159 |   0.775993 |
| k-d_tree_sklearn     |     2.83352  |       0.913527 |   0.799585 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.316734 |       0.317453 |   0.288966 |
| barab-szabi-2        |     0.294677 |       0.293971 |   0.293465 |
| barab-szabi-1        |     0.321071 |       0.334552 |   0.308666 |
| k-d_tree_pandas      |     0.313768 |       0.283644 |   0.396663 |
| Bori_Aron_solution-1 |     0.306952 |       0.39522  |   0.494262 |
| k-d_tree_sklearn     |     0.298798 |       0.691742 |   0.748014 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.298824 |       0.299992 |   0.30595  |
| k-d_tree_polars      |     0.292705 |       0.310934 |   0.323909 |
| barab-szabi-1        |     0.279794 |       0.312145 |   0.326954 |
| Bori_Aron_solution-1 |     0.294278 |       0.399878 |   0.37454  |
| k-d_tree_pandas      |     0.284807 |       0.270235 |   0.404145 |
| k-d_tree_sklearn     |     0.305975 |       0.741334 |   0.774278 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.299145 |       0.355434 |   0.332464 |
| k-d_tree_polars      |     0.291363 |       0.372086 |   0.368495 |
| Bori_Aron_solution-1 |     0.284732 |       0.517476 |   0.413152 |
| barab-szabi-1        |     0.30406  |       0.387581 |   0.440612 |
| k-d_tree_pandas      |     0.299597 |       0.323062 |   0.465274 |
| k-d_tree_sklearn     |     0.294378 |       0.85535  |   0.776034 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.293643 |       0.536125 |   0.36344  |
| Bori_Aron_solution-1 |     0.30115  |       1.02127  |   0.415924 |
| k-d_tree_polars      |     0.308908 |       0.565792 |   0.593747 |
| barab-szabi-1        |     0.296916 |       0.555471 |   0.610333 |
| k-d_tree_pandas      |     0.290113 |       0.483421 |   0.758396 |
| k-d_tree_sklearn     |     0.304896 |       1.36468  |   0.79519  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.302446 |        3.4778  |   0.544968 |
| Bori_Aron_solution-1 |     0.284554 |        6.67683 |   0.555829 |
| k-d_tree_sklearn     |     0.297876 |       11.2434  |   0.837404 |
| barab-szabi-1        |     0.301235 |        4.66536 |   4.60184  |
| k-d_tree_polars      |     0.288421 |        3.41954 |   4.65705  |
| k-d_tree_pandas      |     0.294138 |        2.26551 |   4.76126  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.448385 |       161.604  |    2.24573 |
| barab-szabi-2        |     0.646013 |        63.3215 |    2.27024 |
| Bori_Aron_solution-1 |     0.300337 |       125.947  |   22.7396  |