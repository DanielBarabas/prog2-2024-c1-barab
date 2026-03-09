# 2026-03-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.513886 |       0.47102  |   0.466295 |
| k-d_tree_polars      |     0.521183 |       0.442518 |   0.471975 |
| Bori_Aron_solution-1 |     0.51245  |       0.600035 |   0.585944 |
| solution-1           |     8.09707  |       2e-06    |   0.60015  |
| k-d_tree_pandas      |     0.514249 |       0.419105 |   0.609321 |
| barab-szabi-1        |     8.35559  |       0.49674  |   0.658238 |
| k-d_tree_sklearn     |     3.1409   |       1.37276  |   1.16947  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.521609 |       0.443553 |   0.462647 |
| barab-szabi-1        |     0.52576  |       0.439025 |   0.469143 |
| barab-szabi-2        |     0.520067 |       0.466874 |   0.472268 |
| Bori_Aron_solution-1 |     0.520632 |       0.621015 |   0.617175 |
| k-d_tree_pandas      |     0.526487 |       0.424006 |   0.620595 |
| k-d_tree_sklearn     |     0.530736 |       1.072    |   1.20006  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.513289 |       0.478995 |   0.468825 |
| k-d_tree_polars      |     0.51632  |       0.474287 |   0.49301  |
| barab-szabi-1        |     0.53782  |       0.467444 |   0.504849 |
| Bori_Aron_solution-1 |     0.526296 |       0.62543  |   0.608341 |
| k-d_tree_pandas      |     0.519912 |       0.445635 |   0.644982 |
| k-d_tree_sklearn     |     0.520885 |       1.10692  |   1.13562  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.521587 |       0.536432 |   0.501901 |
| k-d_tree_polars      |     0.52483  |       0.591279 |   0.597451 |
| Bori_Aron_solution-1 |     0.499405 |       0.829244 |   0.601781 |
| barab-szabi-1        |     0.513591 |       0.591316 |   0.608076 |
| k-d_tree_pandas      |     0.520219 |       0.528888 |   0.775956 |
| k-d_tree_sklearn     |     0.524905 |       1.34643  |   1.22247  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.516028 |       0.778404 |   0.60762  |
| Bori_Aron_solution-1 |     0.519    |       1.57543  |   0.666119 |
| k-d_tree_polars      |     0.518333 |       0.962325 |   0.966751 |
| barab-szabi-1        |     0.514725 |       0.983091 |   0.990794 |
| k-d_tree_pandas      |     0.52853  |       0.852575 |   1.28923  |
| k-d_tree_sklearn     |     0.54252  |       2.33222  |   1.33038  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.517524 |        6.10342 |   0.873693 |
| Bori_Aron_solution-1 |     0.517655 |       12.1718  |   0.905575 |
| k-d_tree_sklearn     |     0.520545 |       19.122   |   1.39777  |
| barab-szabi-1        |     0.524226 |        5.60278 |   7.37248  |
| k-d_tree_polars      |     0.528674 |        5.63018 |   7.47665  |
| k-d_tree_pandas      |     0.513175 |        4.41025 |   7.8505   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.514701 |        73.3012 |    2.8035  |
| k-d_tree_sklearn     |     0.759185 |       243.175  |    3.88406 |
| Bori_Aron_solution-1 |     0.499583 |       149.506  |   18.188   |