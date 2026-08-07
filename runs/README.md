# 2026-08-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482641 |       0.450424 |   0.45675  |
| solution-1           |     7.84743  |       1e-06    |   0.460137 |
| barab-szabi-1        |     0.495362 |       0.463886 |   0.482477 |
| Bori_Aron_solution-1 |     4.73082  |       0.659191 |   0.521511 |
| k-d_tree_polars      |     4.84077  |       0.483553 |   0.541313 |
| k-d_tree_pandas      |     0.479086 |       0.395745 |   0.560225 |
| k-d_tree_sklearn     |     3.11557  |       1.18388  |   1.12986  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479556 |       0.453403 |   0.450156 |
| barab-szabi-1        |     0.484476 |       0.453351 |   0.450531 |
| k-d_tree_polars      |     0.49579  |       0.438136 |   0.464839 |
| k-d_tree_pandas      |     0.511032 |       0.420075 |   0.567084 |
| Bori_Aron_solution-1 |     0.473097 |       0.564088 |   0.57426  |
| k-d_tree_sklearn     |     0.487796 |       1.03048  |   1.10398  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485885 |       0.456446 |   0.463614 |
| barab-szabi-1        |     0.481954 |       0.469387 |   0.480145 |
| k-d_tree_polars      |     0.485552 |       0.482571 |   0.506951 |
| Bori_Aron_solution-1 |     0.472756 |       0.602836 |   0.567963 |
| k-d_tree_pandas      |     0.47753  |       0.444357 |   0.624984 |
| k-d_tree_sklearn     |     0.485204 |       1.0955   |   1.14081  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486027 |       0.521407 |   0.479409 |
| k-d_tree_polars      |     0.491346 |       0.579932 |   0.576644 |
| Bori_Aron_solution-1 |     0.47922  |       0.80342  |   0.583629 |
| barab-szabi-1        |     0.479756 |       0.592843 |   0.58491  |
| k-d_tree_pandas      |     0.476549 |       0.504374 |   0.794119 |
| k-d_tree_sklearn     |     0.481907 |       1.32759  |   1.22197  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.477496 |       1.47683  |   0.599414 |
| barab-szabi-2        |     0.479379 |       0.78169  |   0.599824 |
| k-d_tree_polars      |     0.487912 |       0.978413 |   0.973902 |
| barab-szabi-1        |     0.480561 |       0.91921  |   1.01491  |
| k-d_tree_pandas      |     0.478901 |       0.785158 |   1.21357  |
| k-d_tree_sklearn     |     0.500087 |       2.27606  |   1.22295  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480955 |        5.56081 |   0.739831 |
| Bori_Aron_solution-1 |     0.475538 |       11.2601  |   0.82111  |
| k-d_tree_sklearn     |     0.480052 |       17.3804  |   1.28689  |
| barab-szabi-1        |     0.476307 |        5.09636 |   7.40237  |
| k-d_tree_polars      |     0.480268 |        5.1357  |   7.53444  |
| k-d_tree_pandas      |     0.477422 |        4.02337 |   7.80183  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556367 |        77.8341 |    2.65811 |
| k-d_tree_sklearn     |     0.730004 |       263.144  |    3.41271 |
| Bori_Aron_solution-1 |     0.490772 |       154.095  |   24.0465  |