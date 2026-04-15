# 2026-04-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.4965   |       0.426389 |   0.464759 |
| barab-szabi-2        |     0.498695 |       0.460865 |   0.464955 |
| solution-1           |     7.97775  |       1e-06    |   0.474203 |
| k-d_tree_polars      |     0.699021 |       0.446426 |   0.480085 |
| Bori_Aron_solution-1 |     0.98283  |       0.592803 |   0.592208 |
| k-d_tree_pandas      |     0.506924 |       0.416282 |   0.612859 |
| k-d_tree_sklearn     |    10.6087   |       1.45978  |   1.17471  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535914 |       0.483173 |   0.473427 |
| k-d_tree_polars      |     0.503414 |       0.444162 |   0.474426 |
| barab-szabi-1        |     0.519798 |       0.446776 |   0.487574 |
| Bori_Aron_solution-1 |     0.486868 |       0.61469  |   0.598981 |
| k-d_tree_pandas      |     0.497175 |       0.432586 |   0.634216 |
| k-d_tree_sklearn     |     0.489416 |       1.13156  |   1.18035  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.49313  |       0.487938 |   0.502883 |
| k-d_tree_polars      |     0.503575 |       0.483703 |   0.506323 |
| barab-szabi-1        |     0.51882  |       0.485812 |   0.530688 |
| Bori_Aron_solution-1 |     0.499202 |       0.61551  |   0.616528 |
| k-d_tree_pandas      |     0.511834 |       0.464864 |   0.657329 |
| k-d_tree_sklearn     |     0.504115 |       1.15993  |   1.27659  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498953 |       0.542254 |   0.515393 |
| k-d_tree_polars      |     0.495296 |       0.625847 |   0.602305 |
| Bori_Aron_solution-1 |     0.488234 |       0.839896 |   0.605697 |
| barab-szabi-1        |     0.518978 |       0.627175 |   0.629518 |
| k-d_tree_pandas      |     0.50906  |       0.535341 |   0.783124 |
| k-d_tree_sklearn     |     0.506907 |       1.42889  |   1.26176  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.496258 |       1.53184  |   0.652871 |
| barab-szabi-2        |     0.50933  |       0.780407 |   0.680861 |
| k-d_tree_polars      |     0.51984  |       0.980198 |   0.986534 |
| barab-szabi-1        |     0.510437 |       0.9894   |   1.03096  |
| k-d_tree_pandas      |     0.502946 |       0.845783 |   1.28521  |
| k-d_tree_sklearn     |     0.500664 |       2.33984  |   1.31696  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498972 |        5.7595  |   0.798758 |
| Bori_Aron_solution-1 |     0.483826 |       11.9522  |   0.874436 |
| k-d_tree_sklearn     |     0.503482 |       18.9567  |   1.38507  |
| barab-szabi-1        |     0.503876 |        5.63044 |   7.28906  |
| k-d_tree_polars      |     0.499822 |        5.7438  |   7.38701  |
| k-d_tree_pandas      |     0.503795 |        4.58573 |   7.74443  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.774541 |         72.384 |    2.75646 |
| k-d_tree_sklearn     |     0.49788  |        250.914 |    4.07928 |
| Bori_Aron_solution-1 |     0.487526 |        155.747 |   26.5855  |