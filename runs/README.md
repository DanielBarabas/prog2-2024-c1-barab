# 2024-11-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |      1.10819 |       0.419546 |   0.412543 |
| barab-szabi-1        |      1.09449 |       0.405409 |   0.413072 |
| k-d_tree_polars      |      1.09593 |       0.430315 |   0.413874 |
| Bori_Aron_solution-1 |      1.10326 |       0.577318 |   0.533765 |
| k-d_tree_pandas      |      1.08435 |       0.379719 |   0.546155 |
| solution-1           |      8.36572 |       1e-06    |   1.06121  |
| k-d_tree_sklearn     |     10.9512  |       2.62685  |   1.07945  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     1.11485  |       0.416506 |   0.393597 |
| barab-szabi-1        |     1.09565  |       0.405202 |   0.396709 |
| barab-szabi-2        |     1.08964  |       0.406389 |   0.403622 |
| Bori_Aron_solution-1 |     1.09273  |       0.543997 |   0.537022 |
| k-d_tree_pandas      |     0.774704 |       0.394289 |   0.5512   |
| k-d_tree_sklearn     |     1.09255  |       0.937307 |   0.97843  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.637938 |       0.412825 |   0.400418 |
| k-d_tree_polars      |     0.643595 |       0.433685 |   0.423624 |
| barab-szabi-1        |     0.617927 |       0.444311 |   0.444753 |
| Bori_Aron_solution-1 |     0.644246 |       0.570818 |   0.53429  |
| k-d_tree_pandas      |     0.648302 |       0.437193 |   0.585272 |
| k-d_tree_sklearn     |     0.638906 |       1.02303  |   1.05701  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627542 |       0.47525  |   0.434718 |
| k-d_tree_polars      |     0.684991 |       0.563955 |   0.527699 |
| barab-szabi-1        |     0.633892 |       0.549937 |   0.534309 |
| Bori_Aron_solution-1 |     0.632918 |       0.775253 |   0.569484 |
| k-d_tree_pandas      |     0.649208 |       0.495474 |   0.739316 |
| k-d_tree_sklearn     |     0.65025  |       1.22449  |   1.11164  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622754 |       0.72621  |   0.508916 |
| Bori_Aron_solution-1 |     0.644698 |       1.43609  |   0.577454 |
| k-d_tree_polars      |     0.63496  |       0.871434 |   0.87659  |
| barab-szabi-1        |     0.624321 |       0.870926 |   0.927823 |
| k-d_tree_pandas      |     0.634132 |       0.754698 |   1.17036  |
| k-d_tree_sklearn     |     0.651774 |       2.05125  |   1.21825  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.639271 |        5.90526 |   0.777378 |
| Bori_Aron_solution-1 |     0.633798 |       11.0687  |   0.834417 |
| k-d_tree_sklearn     |     0.639524 |       16.7975  |   1.3035   |
| k-d_tree_polars      |     0.648504 |        4.89284 |   6.80993  |
| barab-szabi-1        |     0.651861 |        4.94625 |   6.86934  |
| k-d_tree_pandas      |     0.6341   |        3.93471 |   7.14871  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.661362 |        77.0541 |    3.07717 |
| k-d_tree_sklearn     |     0.625807 |       237.635  |    4.27374 |
| Bori_Aron_solution-1 |     0.675131 |       151.313  |   18.0538  |