# 2026-04-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.90904  |       0.581698 |   0.446621 |
| barab-szabi-1        |     0.468008 |       0.414735 |   0.449011 |
| k-d_tree_polars      |     0.47267  |       0.428    |   0.451607 |
| Bori_Aron_solution-1 |     0.499458 |       0.562355 |   0.566728 |
| k-d_tree_pandas      |     0.47467  |       0.394038 |   0.577235 |
| solution-1           |     7.37187  |       1e-06    |   0.581105 |
| k-d_tree_sklearn     |     2.93305  |       1.1079   |   1.11276  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.477515 |       0.438115 |   0.442612 |
| k-d_tree_polars      |     0.46598  |       0.438895 |   0.443113 |
| barab-szabi-2        |     0.467419 |       0.447931 |   0.513522 |
| Bori_Aron_solution-1 |     0.46316  |       0.567147 |   0.556266 |
| k-d_tree_pandas      |     0.467529 |       0.395535 |   0.567139 |
| k-d_tree_sklearn     |     0.470249 |       1.00125  |   1.10015  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475782 |       0.457917 |   0.460746 |
| k-d_tree_polars      |     0.482006 |       0.460469 |   0.483406 |
| barab-szabi-1        |     0.483666 |       0.491743 |   0.497139 |
| Bori_Aron_solution-1 |     0.469225 |       0.601249 |   0.567108 |
| k-d_tree_pandas      |     0.472803 |       0.430843 |   0.615016 |
| k-d_tree_sklearn     |     0.481376 |       1.04568  |   1.12736  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466298 |       0.525904 |   0.488551 |
| k-d_tree_polars      |     0.472847 |       0.573377 |   0.57653  |
| barab-szabi-1        |     0.464879 |       0.580213 |   0.592394 |
| Bori_Aron_solution-1 |     0.487924 |       0.812681 |   0.593027 |
| k-d_tree_pandas      |     0.470253 |       0.525021 |   0.772496 |
| k-d_tree_sklearn     |     0.481156 |       1.33943  |   1.23527  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473361 |       0.751146 |   0.532627 |
| Bori_Aron_solution-1 |     0.458802 |       1.48247  |   0.599463 |
| k-d_tree_polars      |     0.49069  |       0.945699 |   0.941633 |
| barab-szabi-1        |     0.485999 |       0.952612 |   0.977392 |
| k-d_tree_pandas      |     0.476554 |       0.822279 |   1.23894  |
| k-d_tree_sklearn     |     0.481834 |       2.18426  |   1.25602  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47339  |        5.42155 |   0.773728 |
| Bori_Aron_solution-1 |     0.468022 |       11.2505  |   0.816198 |
| k-d_tree_sklearn     |     0.47663  |       17.9102  |   1.33375  |
| k-d_tree_polars      |     0.478086 |        5.52848 |   6.77771  |
| barab-szabi-1        |     0.465095 |        5.44199 |   6.86803  |
| k-d_tree_pandas      |     0.468048 |        4.51907 |   7.43072  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464699 |        75.6551 |    2.64336 |
| k-d_tree_sklearn     |     0.51162  |       243.743  |    3.64358 |
| Bori_Aron_solution-1 |     0.463045 |       149.403  |   28.6353  |