# 2024-03-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.781262 |       0.434057 |   0.39088  |
| barab-szabi-1        |     0.757823 |       0.433517 |   0.393853 |
| barab-szabi-2        |     0.756387 |       0.399062 |   0.426223 |
| solution-1           |     8.21246  |       1e-06    |   0.477505 |
| Bori_Aron_solution-1 |     0.727174 |       0.539328 |   0.538757 |
| k-d_tree_pandas      |     8.21507  |       0.515276 |   0.609793 |
| k-d_tree_sklearn     |     3.35195  |       1.14708  |   0.725429 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.728863 |       0.414241 |   0.373799 |
| k-d_tree_polars      |     0.729466 |       0.414598 |   0.375773 |
| barab-szabi-2        |     0.774034 |       0.418476 |   0.390349 |
| Bori_Aron_solution-1 |     0.725179 |       0.519903 |   0.504165 |
| k-d_tree_pandas      |     0.771524 |       0.41061  |   0.533178 |
| k-d_tree_sklearn     |     0.736511 |       0.887811 |   0.713614 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.723556 |       0.385796 |   0.383157 |
| k-d_tree_polars      |     0.735956 |       0.443548 |   0.400043 |
| barab-szabi-1        |     0.734092 |       0.444881 |   0.408647 |
| Bori_Aron_solution-1 |     0.71893  |       0.554289 |   0.50999  |
| k-d_tree_pandas      |     0.728554 |       0.430602 |   0.584732 |
| k-d_tree_sklearn     |     0.739382 |       0.936413 |   0.70587  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.727539 |       0.447851 |   0.408904 |
| k-d_tree_polars      |     0.74878  |       0.564056 |   0.521781 |
| barab-szabi-1        |     0.768662 |       0.579015 |   0.539926 |
| Bori_Aron_solution-1 |     0.719612 |       0.753961 |   0.557661 |
| k-d_tree_pandas      |     0.7461   |       0.496541 |   0.697199 |
| k-d_tree_sklearn     |     0.755441 |       1.19081  |   0.778851 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.770331 |       0.724149 |   0.471069 |
| Bori_Aron_solution-1 |     0.738112 |       1.4177   |   0.559847 |
| k-d_tree_polars      |     0.727592 |       0.870544 |   0.848699 |
| k-d_tree_sklearn     |     0.762445 |       1.97607  |   0.87223  |
| barab-szabi-1        |     0.736346 |       0.873035 |   0.905261 |
| k-d_tree_pandas      |     0.757195 |       0.808599 |   1.2011   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.722006 |        5.5777  |   0.750479 |
| Bori_Aron_solution-1 |     0.718342 |       11.1293  |   0.805335 |
| k-d_tree_sklearn     |     0.759075 |       17.2959  |   1.13247  |
| k-d_tree_polars      |     0.746256 |        5.02381 |   6.90513  |
| k-d_tree_pandas      |     0.727061 |        4.00096 |   6.93691  |
| barab-szabi-1        |     0.765548 |        5.05786 |   6.98077  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.74786  |        74.6313 |    3.66972 |
| k-d_tree_sklearn     |     1.11616  |       236.249  |    5.04391 |
| Bori_Aron_solution-1 |     0.942214 |       144.99   |   19.1313  |