# 2026-08-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.0968   |       1e-06    |   0.363202 |
| barab-szabi-1        |     0.473865 |       0.422683 |   0.45261  |
| barab-szabi-2        |     4.94159  |       0.456357 |   0.45298  |
| k-d_tree_polars      |     0.463574 |       0.428867 |   0.462372 |
| Bori_Aron_solution-1 |     4.68338  |       0.547545 |   0.493903 |
| k-d_tree_pandas      |     0.476133 |       0.392015 |   0.565736 |
| k-d_tree_sklearn     |     3.26627  |       1.05212  |   1.08528  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476443 |       0.456284 |   0.451737 |
| k-d_tree_polars      |     0.475605 |       0.423203 |   0.457566 |
| barab-szabi-1        |     0.474448 |       0.428268 |   0.457769 |
| Bori_Aron_solution-1 |     0.47068  |       0.563647 |   0.550844 |
| k-d_tree_pandas      |     0.473997 |       0.39414  |   0.563526 |
| k-d_tree_sklearn     |     0.476786 |       1.00068  |   1.10193  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474242 |       0.459978 |   0.462398 |
| k-d_tree_polars      |     0.481961 |       0.455197 |   0.475754 |
| barab-szabi-1        |     0.473809 |       0.459451 |   0.479647 |
| Bori_Aron_solution-1 |     0.477324 |       0.601377 |   0.557329 |
| k-d_tree_pandas      |     0.480663 |       0.413125 |   0.606936 |
| k-d_tree_sklearn     |     0.476411 |       1.04639  |   1.11947  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472969 |       0.519139 |   0.482766 |
| Bori_Aron_solution-1 |     0.468669 |       0.794077 |   0.570912 |
| k-d_tree_polars      |     0.481986 |       0.575475 |   0.580394 |
| barab-szabi-1        |     0.472448 |       0.586207 |   0.604169 |
| k-d_tree_pandas      |     0.476156 |       0.508727 |   0.748589 |
| k-d_tree_sklearn     |     0.484097 |       1.29249  |   1.17745  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471762 |       0.74077  |   0.518109 |
| Bori_Aron_solution-1 |     0.469349 |       1.45884  |   0.591087 |
| k-d_tree_polars      |     0.485463 |       0.931131 |   0.926871 |
| barab-szabi-1        |     0.474714 |       0.955126 |   0.968854 |
| k-d_tree_pandas      |     0.482466 |       0.80255  |   1.19048  |
| k-d_tree_sklearn     |     0.47767  |       2.13384  |   1.24608  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473788 |        5.1452  |   0.781819 |
| Bori_Aron_solution-1 |     0.470518 |       11.0946  |   0.826035 |
| k-d_tree_sklearn     |     0.479938 |       17.0576  |   1.35546  |
| k-d_tree_polars      |     0.476161 |        5.331   |   6.79595  |
| barab-szabi-1        |     0.489496 |        5.32006 |   6.81473  |
| k-d_tree_pandas      |     0.478545 |        4.42739 |   7.28637  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.766036 |        72.4499 |    3.05451 |
| k-d_tree_sklearn     |     0.603419 |       238.813  |    4.00526 |
| Bori_Aron_solution-1 |     0.473727 |       152.808  |   14.7628  |