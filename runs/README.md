# 2026-09-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485509 |       0.457064 |   0.455169 |
| k-d_tree_polars      |     0.478197 |       0.443169 |   0.471927 |
| k-d_tree_pandas      |     0.470365 |       0.395258 |   0.560274 |
| Bori_Aron_solution-1 |     0.461768 |       0.553478 |   0.564039 |
| solution-1           |     7.79729  |       1e-06    |   0.637362 |
| barab-szabi-1        |     8.83184  |       0.553999 |   0.924302 |
| k-d_tree_sklearn     |     3.02898  |       1.40887  |   1.09804  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481336 |       0.45666  |   0.461926 |
| barab-szabi-1        |     0.476975 |       0.4311   |   0.465619 |
| k-d_tree_polars      |     0.488974 |       0.446394 |   0.470166 |
| Bori_Aron_solution-1 |     0.485474 |       0.570275 |   0.561421 |
| k-d_tree_pandas      |     0.479109 |       0.415212 |   0.577461 |
| k-d_tree_sklearn     |     0.482624 |       1.03329  |   1.10831  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484354 |       0.464601 |   0.466986 |
| barab-szabi-1        |     0.483581 |       0.474203 |   0.48155  |
| k-d_tree_polars      |     0.478466 |       0.455852 |   0.49725  |
| Bori_Aron_solution-1 |     0.477675 |       0.601806 |   0.564519 |
| k-d_tree_pandas      |     0.471748 |       0.41828  |   0.617788 |
| k-d_tree_sklearn     |     0.490072 |       1.08228  |   1.19366  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474474 |       0.522438 |   0.49718  |
| Bori_Aron_solution-1 |     0.478964 |       0.788874 |   0.57636  |
| k-d_tree_polars      |     0.483906 |       0.591178 |   0.604931 |
| barab-szabi-1        |     0.484265 |       0.590335 |   0.607226 |
| k-d_tree_pandas      |     0.481319 |       0.51377  |   0.754656 |
| k-d_tree_sklearn     |     0.501755 |       1.31856  |   1.20339  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.493448 |       0.750223 |   0.524697 |
| Bori_Aron_solution-1 |     0.485903 |       1.46092  |   0.599525 |
| k-d_tree_polars      |     0.482134 |       0.936263 |   0.950305 |
| barab-szabi-1        |     0.48434  |       0.9341   |   0.980889 |
| k-d_tree_pandas      |     0.482919 |       0.806851 |   1.22677  |
| k-d_tree_sklearn     |     0.492251 |       2.17885  |   1.29283  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476617 |        5.2646  |   0.77798  |
| Bori_Aron_solution-1 |     0.469602 |       11.1053  |   0.838778 |
| k-d_tree_sklearn     |     0.48747  |       17.1597  |   1.3347   |
| barab-szabi-1        |     0.480776 |        5.42926 |   6.78623  |
| k-d_tree_polars      |     0.485094 |        5.39462 |   6.85291  |
| k-d_tree_pandas      |     0.484056 |        4.39413 |   7.13285  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590911 |        76.8232 |    3.02683 |
| k-d_tree_sklearn     |     0.826036 |       248.035  |    4.1113  |
| Bori_Aron_solution-1 |     0.475203 |       159.515  |   23.9992  |