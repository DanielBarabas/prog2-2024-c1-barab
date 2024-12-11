# 2024-12-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.14149  |       1e-06    |   0.383984 |
| barab-szabi-2        |     0.667831 |       0.4162   |   0.411043 |
| barab-szabi-1        |     0.642575 |       0.437623 |   0.412097 |
| k-d_tree_polars      |     0.64288  |       0.429169 |   0.422906 |
| k-d_tree_pandas      |     0.64659  |       0.465405 |   0.562309 |
| Bori_Aron_solution-1 |     0.643023 |       0.566098 |   0.566544 |
| k-d_tree_sklearn     |    10.8629   |       1.06818  |   1.08407  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.674842 |       0.413527 |   0.412435 |
| barab-szabi-1        |     0.6454   |       0.453363 |   0.419695 |
| k-d_tree_polars      |     0.639172 |       0.429306 |   0.420751 |
| Bori_Aron_solution-1 |     0.629801 |       0.563467 |   0.553305 |
| k-d_tree_pandas      |     0.648408 |       0.405066 |   0.566277 |
| k-d_tree_sklearn     |     0.643248 |       0.972239 |   1.03571  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.640867 |       0.42759  |   0.43481  |
| k-d_tree_polars      |     0.641418 |       0.458668 |   0.443181 |
| barab-szabi-1        |     0.666431 |       0.459939 |   0.455974 |
| Bori_Aron_solution-1 |     0.653427 |       0.633816 |   0.568135 |
| k-d_tree_pandas      |     0.648153 |       0.427614 |   0.603319 |
| k-d_tree_sklearn     |     0.651167 |       0.995175 |   1.06664  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.64163  |       0.501028 |   0.462606 |
| k-d_tree_polars      |     0.652575 |       0.572099 |   0.548098 |
| barab-szabi-1        |     0.663573 |       0.567337 |   0.562333 |
| Bori_Aron_solution-1 |     0.652392 |       0.775771 |   0.591899 |
| k-d_tree_pandas      |     0.661584 |       0.514829 |   0.762813 |
| k-d_tree_sklearn     |     0.645817 |       1.25015  |   1.13564  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.645713 |       0.760244 |   0.518048 |
| Bori_Aron_solution-1 |     0.645698 |       1.44911  |   0.592202 |
| k-d_tree_polars      |     0.652597 |       0.880868 |   0.936498 |
| barab-szabi-1        |     0.651126 |       0.878691 |   0.950412 |
| k-d_tree_sklearn     |     0.653692 |       2.1302   |   1.18638  |
| k-d_tree_pandas      |     0.649324 |       0.777225 |   1.20558  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.646778 |        5.52891 |   0.756803 |
| Bori_Aron_solution-1 |     0.627704 |       11.0519  |   0.839505 |
| k-d_tree_sklearn     |     0.66123  |       17.0268  |   1.33447  |
| k-d_tree_polars      |     0.635924 |        4.89794 |   6.77412  |
| barab-szabi-1        |     0.653073 |        4.94719 |   6.86829  |
| k-d_tree_pandas      |     0.647936 |        3.86824 |   7.23564  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.652101 |         75.688 |    3.10631 |
| k-d_tree_sklearn     |     0.653451 |        239.104 |    4.3026  |
| Bori_Aron_solution-1 |     0.639675 |        158.842 |   17.3307  |