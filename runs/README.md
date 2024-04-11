# 2024-04-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.743439 |       0.412395 |   0.347577 |
| barab-szabi-2        |     0.755905 |       0.372995 |   0.349096 |
| k-d_tree_polars      |     8.50781  |       0.462887 |   0.366307 |
| solution-1           |     8.04029  |       1e-06    |   0.395249 |
| k-d_tree_pandas      |     0.722734 |       0.396683 |   0.4874   |
| Bori_Aron_solution-1 |     0.743259 |       0.484553 |   0.488294 |
| k-d_tree_sklearn     |     3.30406  |       0.949414 |   0.680192 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.747615 |       0.356534 |   0.355649 |
| barab-szabi-1        |     0.747314 |       0.41201  |   0.356345 |
| k-d_tree_polars      |     0.750994 |       0.415731 |   0.35691  |
| Bori_Aron_solution-1 |     0.754074 |       0.509566 |   0.487411 |
| k-d_tree_pandas      |     0.745432 |       0.401537 |   0.504412 |
| k-d_tree_sklearn     |     0.769614 |       0.872441 |   0.68272  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.742601 |       0.368549 |   0.367433 |
| barab-szabi-1        |     0.747006 |       0.44413  |   0.385823 |
| k-d_tree_polars      |     0.746222 |       0.443581 |   0.387198 |
| Bori_Aron_solution-1 |     0.743984 |       0.535661 |   0.500722 |
| k-d_tree_pandas      |     0.741006 |       0.42462  |   0.547406 |
| k-d_tree_sklearn     |     0.761534 |       0.914907 |   0.720191 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.741214 |       0.43854  |   0.393768 |
| k-d_tree_polars      |     0.75359  |       0.552007 |   0.47693  |
| barab-szabi-1        |     0.747384 |       0.548362 |   0.493868 |
| Bori_Aron_solution-1 |     0.729206 |       0.70788  |   0.503094 |
| k-d_tree_pandas      |     0.780188 |       0.501322 |   0.679536 |
| k-d_tree_sklearn     |     0.767956 |       1.14388  |   0.772517 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.750548 |       0.695231 |   0.44441  |
| Bori_Aron_solution-1 |     0.731819 |       1.38026  |   0.522375 |
| k-d_tree_polars      |     0.746638 |       0.865353 |   0.841542 |
| k-d_tree_sklearn     |     0.753026 |       1.97674  |   0.880172 |
| barab-szabi-1        |     0.744249 |       0.853332 |   0.886937 |
| k-d_tree_pandas      |     0.743592 |       0.749082 |   1.13728  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.735145 |        5.31839 |   0.721357 |
| Bori_Aron_solution-1 |     0.737216 |       10.6344  |   0.779857 |
| k-d_tree_sklearn     |     0.748866 |       15.944   |   1.05718  |
| k-d_tree_polars      |     0.735404 |        4.83192 |   6.56298  |
| barab-szabi-1        |     0.742066 |        4.84846 |   6.58813  |
| k-d_tree_pandas      |     0.740082 |        3.89573 |   6.86407  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.8628   |        72.1891 |    3.34043 |
| k-d_tree_sklearn     |     0.752119 |       230.395  |    5.23546 |
| Bori_Aron_solution-1 |     0.826159 |       144.024  |   16.063   |