# 2025-03-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.2913   |       1e-06    |   0.374414 |
| barab-szabi-2        |     0.591863 |       0.423436 |   0.423402 |
| barab-szabi-1        |     0.575937 |       0.429733 |   0.438446 |
| k-d_tree_polars      |     0.5695   |       0.433862 |   0.444445 |
| Bori_Aron_solution-1 |     0.576419 |       0.58372  |   0.579113 |
| k-d_tree_pandas      |     7.67356  |       0.418904 |   0.74828  |
| k-d_tree_sklearn     |     2.99707  |       1.22753  |   1.07824  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.578379 |       0.432124 |   0.415581 |
| barab-szabi-1        |     0.591812 |       0.417433 |   0.422392 |
| k-d_tree_polars      |     0.568343 |       0.4197   |   0.423279 |
| Bori_Aron_solution-1 |     0.576431 |       0.611297 |   0.56951  |
| k-d_tree_pandas      |     0.586513 |       0.399518 |   0.573017 |
| k-d_tree_sklearn     |     0.58042  |       0.967182 |   1.05854  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.580012 |       0.432833 |   0.429223 |
| k-d_tree_polars      |     0.582971 |       0.452835 |   0.452658 |
| barab-szabi-1        |     0.582505 |       0.447364 |   0.454529 |
| Bori_Aron_solution-1 |     0.571963 |       0.604901 |   0.568966 |
| k-d_tree_pandas      |     0.612015 |       0.415673 |   0.613529 |
| k-d_tree_sklearn     |     0.606671 |       1.04918  |   1.09309  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575114 |       0.489686 |   0.456816 |
| k-d_tree_polars      |     0.576017 |       0.552275 |   0.543397 |
| barab-szabi-1        |     0.573663 |       0.567671 |   0.569027 |
| Bori_Aron_solution-1 |     0.579728 |       0.785796 |   0.57296  |
| k-d_tree_pandas      |     0.576447 |       0.48935  |   0.754109 |
| k-d_tree_sklearn     |     0.575892 |       1.23535  |   1.15157  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.579507 |       0.748568 |   0.507661 |
| Bori_Aron_solution-1 |     0.571293 |       1.4229   |   0.609825 |
| k-d_tree_polars      |     0.588673 |       0.891017 |   0.912576 |
| barab-szabi-1        |     0.58024  |       0.886904 |   0.954939 |
| k-d_tree_pandas      |     0.582251 |       0.753376 |   1.20588  |
| k-d_tree_sklearn     |     0.579667 |       2.12606  |   1.24454  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.587451 |        5.67528 |   0.775995 |
| Bori_Aron_solution-1 |     0.585293 |       11.0419  |   0.901912 |
| k-d_tree_sklearn     |     0.581911 |       17.4067  |   1.35444  |
| k-d_tree_polars      |     0.589874 |        4.98486 |   7.0443   |
| barab-szabi-1        |     0.586209 |        4.95606 |   7.08521  |
| k-d_tree_pandas      |     0.582827 |        3.83685 |   7.43854  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.71955  |         74.822 |    3.62284 |
| k-d_tree_sklearn     |     0.683014 |        239.418 |    4.23039 |
| Bori_Aron_solution-1 |     0.574799 |        158.127 |   15.2256  |