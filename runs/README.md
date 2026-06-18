# 2026-06-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.489148 |       0.43304  |   0.473223 |
| barab-szabi-2        |     8.36766  |       0.732588 |   0.473477 |
| solution-1           |     7.97872  |       1e-06    |   0.481381 |
| barab-szabi-1        |     0.491673 |       0.449117 |   0.481531 |
| Bori_Aron_solution-1 |     0.48484  |       0.598342 |   0.59478  |
| k-d_tree_pandas      |     0.50706  |       0.413421 |   0.605603 |
| k-d_tree_sklearn     |     3.06202  |       1.24184  |   1.1915   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.513121 |       0.439741 |   0.470392 |
| barab-szabi-2        |     0.508623 |       0.4739   |   0.476191 |
| barab-szabi-1        |     0.508443 |       0.433064 |   0.485285 |
| Bori_Aron_solution-1 |     0.518384 |       0.605024 |   0.586234 |
| k-d_tree_pandas      |     0.524306 |       0.444282 |   0.635958 |
| k-d_tree_sklearn     |     0.509776 |       1.12878  |   1.20819  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.522178 |       0.500861 |   0.49469  |
| k-d_tree_polars      |     0.507309 |       0.470055 |   0.501968 |
| barab-szabi-1        |     0.507056 |       0.467813 |   0.512283 |
| Bori_Aron_solution-1 |     0.501685 |       0.648066 |   0.591133 |
| k-d_tree_pandas      |     0.515313 |       0.449581 |   0.656021 |
| k-d_tree_sklearn     |     0.516252 |       1.13419  |   1.20256  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.506799 |       0.548497 |   0.512459 |
| k-d_tree_polars      |     0.491862 |       0.607436 |   0.607533 |
| Bori_Aron_solution-1 |     0.496723 |       0.8266   |   0.615171 |
| barab-szabi-1        |     0.503803 |       0.579658 |   0.622963 |
| k-d_tree_pandas      |     0.505816 |       0.545749 |   0.78996  |
| k-d_tree_sklearn     |     0.51738  |       1.37944  |   1.23699  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.507748 |       1.5498   |   0.641984 |
| barab-szabi-2        |     0.498877 |       0.806023 |   0.706648 |
| k-d_tree_polars      |     0.541342 |       0.968949 |   1.00884  |
| barab-szabi-1        |     0.525874 |       0.996414 |   1.06122  |
| k-d_tree_pandas      |     0.514727 |       0.856453 |   1.30814  |
| k-d_tree_sklearn     |     0.514668 |       2.43524  |   1.38468  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.503543 |        5.29925 |   0.794499 |
| Bori_Aron_solution-1 |     0.512264 |       11.4108  |   0.870589 |
| k-d_tree_sklearn     |     0.494478 |       17.9103  |   1.3843   |
| barab-szabi-1        |     0.5034   |        5.52572 |   6.92595  |
| k-d_tree_polars      |     0.499777 |        5.46234 |   6.93404  |
| k-d_tree_pandas      |     0.490318 |        4.50702 |   7.31265  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.495076 |        75.2479 |    2.85665 |
| k-d_tree_sklearn     |     0.885315 |       250.042  |    4.27281 |
| Bori_Aron_solution-1 |     0.506383 |       153.535  |   20.855   |