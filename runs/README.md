# 2026-06-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.459363 |       0.402971 |   0.432596 |
| barab-szabi-1        |     0.463189 |       0.405946 |   0.452183 |
| barab-szabi-2        |     7.77785  |       1.23403  |   0.461999 |
| k-d_tree_pandas      |     0.475348 |       0.383552 |   0.546951 |
| Bori_Aron_solution-1 |     0.460029 |       0.544882 |   0.553678 |
| solution-1           |     7.49664  |       1e-06    |   1.00835  |
| k-d_tree_sklearn     |     3.00856  |       1.17348  |   1.06291  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.473127 |       0.399707 |   0.440516 |
| barab-szabi-1        |     0.474499 |       0.415905 |   0.443548 |
| barab-szabi-2        |     0.4614   |       0.437669 |   0.447986 |
| Bori_Aron_solution-1 |     0.45265  |       0.547739 |   0.540043 |
| k-d_tree_pandas      |     0.467186 |       0.383837 |   0.54858  |
| k-d_tree_sklearn     |     0.468112 |       0.973186 |   1.05643  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462414 |       0.45146  |   0.449262 |
| k-d_tree_polars      |     0.4611   |       0.43388  |   0.462066 |
| barab-szabi-1        |     0.468903 |       0.452835 |   0.471836 |
| Bori_Aron_solution-1 |     0.454421 |       0.584167 |   0.547283 |
| k-d_tree_pandas      |     0.464682 |       0.401469 |   0.59059  |
| k-d_tree_sklearn     |     0.469535 |       1.01971  |   1.09102  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.457074 |       0.507254 |   0.474679 |
| Bori_Aron_solution-1 |     0.465496 |       0.77866  |   0.558854 |
| k-d_tree_polars      |     0.467935 |       0.556918 |   0.56269  |
| barab-szabi-1        |     0.461447 |       0.547074 |   0.579008 |
| k-d_tree_pandas      |     0.471374 |       0.497881 |   0.73761  |
| k-d_tree_sklearn     |     0.465949 |       1.25929  |   1.12437  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466298 |       0.736705 |   0.524775 |
| Bori_Aron_solution-1 |     0.468758 |       1.45536  |   0.59238  |
| k-d_tree_polars      |     0.475144 |       0.91867  |   0.931669 |
| barab-szabi-1        |     0.467529 |       0.914387 |   0.979274 |
| k-d_tree_pandas      |     0.461291 |       0.789952 |   1.16368  |
| k-d_tree_sklearn     |     0.477315 |       2.07366  |   1.21176  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.461941 |        5.17363 |   0.748217 |
| Bori_Aron_solution-1 |     0.453535 |       10.9132  |   0.829891 |
| k-d_tree_sklearn     |     0.478046 |       16.8238  |   1.28062  |
| k-d_tree_polars      |     0.458771 |        5.25521 |   6.70542  |
| barab-szabi-1        |     0.480334 |        5.29542 |   6.78193  |
| k-d_tree_pandas      |     0.462156 |        4.30091 |   7.08498  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.459612 |        72.3425 |    2.75789 |
| k-d_tree_sklearn     |     0.669263 |       239.577  |    3.90208 |
| Bori_Aron_solution-1 |     0.464991 |       148.042  |   17.9948  |