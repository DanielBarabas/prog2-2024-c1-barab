# 2024-12-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.53915  |       1e-06    |   0.381641 |
| barab-szabi-1        |     0.616837 |       0.399689 |   0.390882 |
| k-d_tree_polars      |     0.611657 |       0.39624  |   0.4022   |
| barab-szabi-2        |     0.61518  |       0.385225 |   0.404803 |
| k-d_tree_pandas      |     0.615867 |       0.380121 |   0.523647 |
| Bori_Aron_solution-1 |     0.604971 |       0.532856 |   0.528162 |
| k-d_tree_sklearn     |    10.3626   |       1.13549  |   0.973847 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.61654  |       0.407597 |   0.397577 |
| barab-szabi-2        |     0.624879 |       0.397373 |   0.400118 |
| barab-szabi-1        |     0.624271 |       0.464216 |   0.402821 |
| Bori_Aron_solution-1 |     0.616081 |       0.533695 |   0.523911 |
| k-d_tree_pandas      |     0.611649 |       0.386201 |   0.536396 |
| k-d_tree_sklearn     |     0.617218 |       0.914966 |   0.97106  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623698 |       0.404286 |   0.39877  |
| k-d_tree_polars      |     0.615787 |       0.427721 |   0.418403 |
| barab-szabi-1        |     0.647875 |       0.433285 |   0.433175 |
| Bori_Aron_solution-1 |     0.610061 |       0.563952 |   0.530513 |
| k-d_tree_pandas      |     0.62672  |       0.40843  |   0.576994 |
| k-d_tree_sklearn     |     0.622822 |       0.943682 |   1.00243  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620064 |       0.464705 |   0.434893 |
| k-d_tree_polars      |     0.614217 |       0.538987 |   0.524552 |
| barab-szabi-1        |     0.620672 |       0.532268 |   0.52587  |
| Bori_Aron_solution-1 |     0.610266 |       0.746871 |   0.538075 |
| k-d_tree_pandas      |     0.619319 |       0.4791   |   0.711244 |
| k-d_tree_sklearn     |     0.630936 |       1.15765  |   1.06169  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623707 |       0.743758 |   0.508231 |
| Bori_Aron_solution-1 |     0.617548 |       1.41112  |   0.588061 |
| k-d_tree_polars      |     0.615993 |       0.858244 |   0.88354  |
| barab-szabi-1        |     0.624004 |       0.877711 |   0.910748 |
| k-d_tree_sklearn     |     0.624213 |       2.00238  |   1.1445   |
| k-d_tree_pandas      |     0.622657 |       0.771739 |   1.17391  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614516 |        5.42201 |   0.732878 |
| Bori_Aron_solution-1 |     0.630487 |       10.8599  |   0.835923 |
| k-d_tree_sklearn     |     0.626521 |       16.191   |   1.26269  |
| k-d_tree_polars      |     0.627351 |        4.88783 |   6.48452  |
| barab-szabi-1        |     0.631591 |        4.89682 |   6.75838  |
| k-d_tree_pandas      |     0.644565 |        3.90982 |   7.13752  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62462  |        68.9254 |    3.14055 |
| k-d_tree_sklearn     |     0.637022 |       219.683  |    4.1399  |
| Bori_Aron_solution-1 |     0.624292 |       149.484  |   16.6575  |