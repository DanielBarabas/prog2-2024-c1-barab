# 2024-03-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.753381 |       0.411995 |   0.36956  |
| barab-szabi-2        |     0.714406 |       0.595494 |   0.370269 |
| k-d_tree_polars      |     0.74046  |       0.421931 |   0.374328 |
| Bori_Aron_solution-1 |     0.696028 |       0.521238 |   0.513268 |
| k-d_tree_sklearn     |     3.36574  |       1.13406  |   0.695137 |
| solution-1           |     9.10505  |       1e-06    |   0.720096 |
| k-d_tree_pandas      |     8.22722  |       0.452913 |   0.728519 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.740174 |       0.3763   |   0.371254 |
| barab-szabi-1        |     0.742244 |       0.426212 |   0.378969 |
| k-d_tree_polars      |     0.740664 |       0.4245   |   0.382087 |
| k-d_tree_pandas      |     0.735367 |       0.395656 |   0.520819 |
| Bori_Aron_solution-1 |     0.728755 |       0.543255 |   0.523131 |
| k-d_tree_sklearn     |     0.770094 |       0.901821 |   0.693466 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.73539  |       0.390543 |   0.381273 |
| k-d_tree_polars      |     0.743247 |       0.441565 |   0.409491 |
| barab-szabi-1        |     0.739205 |       0.448279 |   0.409593 |
| Bori_Aron_solution-1 |     0.747094 |       0.574788 |   0.515713 |
| k-d_tree_pandas      |     0.744804 |       0.418609 |   0.576243 |
| k-d_tree_sklearn     |     0.746809 |       0.921528 |   0.717612 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.751878 |       0.460439 |   0.406323 |
| k-d_tree_polars      |     0.739888 |       0.554146 |   0.497898 |
| barab-szabi-1        |     0.7444   |       0.556319 |   0.510231 |
| Bori_Aron_solution-1 |     0.726737 |       0.745624 |   0.523628 |
| k-d_tree_pandas      |     0.740149 |       0.49349  |   0.719767 |
| k-d_tree_sklearn     |     0.743132 |       1.16136  |   0.791506 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.734738 |       0.706805 |   0.454758 |
| Bori_Aron_solution-1 |     0.753053 |       1.41997  |   0.55434  |
| k-d_tree_polars      |     0.749725 |       0.878557 |   0.877198 |
| k-d_tree_sklearn     |     0.748815 |       2.04654  |   0.892816 |
| barab-szabi-1        |     0.743083 |       0.883119 |   0.910378 |
| k-d_tree_pandas      |     0.7449   |       0.770267 |   1.1682   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.73761  |        5.39552 |   0.76511  |
| Bori_Aron_solution-1 |     0.723167 |       10.9025  |   0.813449 |
| k-d_tree_sklearn     |     0.751743 |       16.8388  |   1.10328  |
| barab-szabi-1        |     0.755149 |        4.94585 |   6.66023  |
| k-d_tree_polars      |     0.747465 |        5.01588 |   6.84488  |
| k-d_tree_pandas      |     0.73809  |        3.97608 |   6.96518  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.738471 |        74.2204 |    4.07044 |
| k-d_tree_sklearn     |     0.968175 |       233.371  |    5.13621 |
| Bori_Aron_solution-1 |     0.885942 |       149.041  |   16.5346  |