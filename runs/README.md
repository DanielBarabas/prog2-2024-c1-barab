# 2025-09-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.559505 |       0.443613 |   0.464322 |
| k-d_tree_polars      |     0.567822 |       0.439618 |   0.464755 |
| barab-szabi-2        |     7.96549  |       0.879416 |   0.479649 |
| Bori_Aron_solution-1 |     0.55046  |       0.591185 |   0.576771 |
| solution-1           |     7.81533  |       1e-06    |   0.578243 |
| k-d_tree_pandas      |     0.56296  |       0.416594 |   0.594566 |
| k-d_tree_sklearn     |     3.09821  |       1.20071  |   1.16458  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.572274 |       0.441896 |   0.454609 |
| barab-szabi-1        |     0.572918 |       0.453703 |   0.475492 |
| barab-szabi-2        |     0.590394 |       0.463183 |   0.476507 |
| k-d_tree_pandas      |     0.563862 |       0.408807 |   0.604011 |
| Bori_Aron_solution-1 |     0.568452 |       0.603916 |   0.628666 |
| k-d_tree_sklearn     |     0.574009 |       1.0486   |   1.19853  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577654 |       0.478954 |   0.463388 |
| barab-szabi-1        |     0.585973 |       0.468238 |   0.499854 |
| k-d_tree_polars      |     0.57343  |       0.473667 |   0.508895 |
| Bori_Aron_solution-1 |     0.579133 |       0.61956  |   0.592005 |
| k-d_tree_pandas      |     0.569531 |       0.450227 |   0.651709 |
| k-d_tree_sklearn     |     0.575422 |       1.1003   |   1.17642  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566458 |       0.52661  |   0.489318 |
| barab-szabi-1        |     0.581487 |       0.584125 |   0.596251 |
| k-d_tree_polars      |     0.578802 |       0.590599 |   0.59787  |
| Bori_Aron_solution-1 |     0.561222 |       0.810532 |   0.633181 |
| k-d_tree_pandas      |     0.575178 |       0.52871  |   0.78761  |
| k-d_tree_sklearn     |     0.567336 |       1.31894  |   1.22038  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55994  |       0.800043 |   0.601731 |
| Bori_Aron_solution-1 |     0.569422 |       1.46192  |   0.614332 |
| k-d_tree_polars      |     0.583834 |       0.927609 |   0.961613 |
| barab-szabi-1        |     0.57486  |       0.924367 |   0.998925 |
| k-d_tree_pandas      |     0.574718 |       0.788819 |   1.26248  |
| k-d_tree_sklearn     |     0.568448 |       2.24104  |   1.29762  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569853 |        5.77193 |   0.800949 |
| Bori_Aron_solution-1 |     0.578704 |       11.1622  |   0.898363 |
| k-d_tree_sklearn     |     0.625017 |       17.6642  |   1.39686  |
| k-d_tree_polars      |     0.585417 |        5.05788 |   7.04761  |
| barab-szabi-1        |     0.568067 |        5.17129 |   7.35138  |
| k-d_tree_pandas      |     0.57274  |        4.02146 |   7.45854  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57378  |         78.243 |    2.88334 |
| k-d_tree_sklearn     |     1.17332  |        248.047 |    4.19679 |
| Bori_Aron_solution-1 |     0.571673 |        150.659 |   17.5565  |