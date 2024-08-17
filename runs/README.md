# 2024-08-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.48433  |       1e-06    |   0.371047 |
| barab-szabi-2        |     7.68777  |       0.480587 |   0.381092 |
| k-d_tree_polars      |     0.589924 |       0.391136 |   0.390382 |
| barab-szabi-1        |     0.597695 |       0.390495 |   0.391766 |
| Bori_Aron_solution-1 |     0.599959 |       0.518864 |   0.517851 |
| k-d_tree_pandas      |     0.603801 |       0.41094  |   0.519124 |
| k-d_tree_sklearn     |     2.88572  |       0.922152 |   0.694493 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605405 |       0.389633 |   0.385009 |
| k-d_tree_polars      |     0.65816  |       0.404048 |   0.394592 |
| barab-szabi-1        |     0.606304 |       0.42231  |   0.399327 |
| Bori_Aron_solution-1 |     0.614426 |       0.530356 |   0.51714  |
| k-d_tree_pandas      |     0.612612 |       0.378846 |   0.52849  |
| k-d_tree_sklearn     |     0.615212 |       0.89337  |   0.703942 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606016 |       0.40136  |   0.40132  |
| k-d_tree_polars      |     0.604723 |       0.42502  |   0.416198 |
| barab-szabi-1        |     0.609341 |       0.424858 |   0.421494 |
| Bori_Aron_solution-1 |     0.609423 |       0.562276 |   0.524681 |
| k-d_tree_pandas      |     0.610077 |       0.405495 |   0.564092 |
| k-d_tree_sklearn     |     0.637252 |       0.929197 |   0.737901 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60609  |       0.467006 |   0.430686 |
| k-d_tree_polars      |     0.613748 |       0.539976 |   0.516613 |
| barab-szabi-1        |     0.608032 |       0.534284 |   0.524095 |
| Bori_Aron_solution-1 |     0.61331  |       0.740103 |   0.532695 |
| k-d_tree_pandas      |     0.607141 |       0.477019 |   0.707902 |
| k-d_tree_sklearn     |     0.619677 |       1.15158  |   0.795273 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606345 |       0.720022 |   0.460606 |
| Bori_Aron_solution-1 |     0.608841 |       1.36887  |   0.557526 |
| k-d_tree_polars      |     0.614347 |       0.851149 |   0.855568 |
| k-d_tree_sklearn     |     0.610279 |       1.9701   |   0.875081 |
| barab-szabi-1        |     0.610684 |       0.843594 |   0.898493 |
| k-d_tree_pandas      |     0.614574 |       0.745339 |   1.12965  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606925 |        5.40503 |   0.731645 |
| Bori_Aron_solution-1 |     0.611259 |       10.8457  |   0.846956 |
| k-d_tree_sklearn     |     0.614865 |       16.2892  |   0.97357  |
| k-d_tree_polars      |     0.606419 |        4.80728 |   6.58721  |
| barab-szabi-1        |     0.607593 |        4.82687 |   6.61151  |
| k-d_tree_pandas      |     0.620712 |        3.87822 |   7.01609  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612872 |        71.8008 |    2.94206 |
| k-d_tree_sklearn     |     0.623149 |       228.707  |    4.0116  |
| Bori_Aron_solution-1 |     0.658645 |       153.518  |   18.4086  |