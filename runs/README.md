# 2024-03-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.673141 |       0.377551 |   0.3545   |
| solution-1           |     8.06591  |       1e-06    |   0.358926 |
| barab-szabi-1        |     0.711719 |       0.392037 |   0.362028 |
| k-d_tree_polars      |     0.707561 |       0.398059 |   0.364454 |
| Bori_Aron_solution-1 |     0.662351 |       0.495057 |   0.505898 |
| k-d_tree_pandas      |     8.79612  |       0.392768 |   0.535405 |
| k-d_tree_sklearn     |     3.31683  |       0.880417 |   0.668923 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.701314 |       0.367553 |   0.359497 |
| k-d_tree_polars      |     0.710358 |       0.404873 |   0.367736 |
| barab-szabi-1        |     0.702227 |       0.402028 |   0.372924 |
| Bori_Aron_solution-1 |     0.694987 |       0.503707 |   0.498482 |
| k-d_tree_pandas      |     0.713771 |       0.383241 |   0.507444 |
| k-d_tree_sklearn     |     0.727926 |       0.853688 |   0.674137 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.701618 |       0.382395 |   0.370473 |
| barab-szabi-1        |     0.709313 |       0.427333 |   0.39865  |
| k-d_tree_polars      |     0.701958 |       0.424012 |   0.398963 |
| Bori_Aron_solution-1 |     0.686318 |       0.538041 |   0.495911 |
| k-d_tree_pandas      |     0.707232 |       0.396698 |   0.547781 |
| k-d_tree_sklearn     |     0.71769  |       0.912968 |   0.698647 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.703029 |       0.442882 |   0.401849 |
| k-d_tree_polars      |     0.708869 |       0.521911 |   0.480369 |
| barab-szabi-1        |     0.684165 |       0.533008 |   0.506824 |
| Bori_Aron_solution-1 |     0.702991 |       0.720392 |   0.509511 |
| k-d_tree_pandas      |     0.701468 |       0.477884 |   0.683986 |
| k-d_tree_sklearn     |     0.706327 |       1.10498  |   0.763307 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.700549 |       0.700791 |   0.438319 |
| Bori_Aron_solution-1 |     0.687064 |       1.32951  |   0.528724 |
| k-d_tree_polars      |     0.701734 |       0.843174 |   0.843948 |
| k-d_tree_sklearn     |     0.679713 |       1.90149  |   0.862168 |
| barab-szabi-1        |     0.708053 |       0.839938 |   0.881419 |
| k-d_tree_pandas      |     0.708789 |       0.754826 |   1.11389  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.696403 |       10.3995  |   0.784317 |
| barab-szabi-2        |     0.705222 |        5.16443 |   0.79165  |
| k-d_tree_sklearn     |     0.709951 |       15.2618  |   1.06126  |
| barab-szabi-1        |     0.736693 |        4.78076 |   6.43801  |
| k-d_tree_polars      |     0.708581 |        4.8425  |   6.46388  |
| k-d_tree_pandas      |     0.700242 |        3.85874 |   6.72079  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.702072 |        72.1122 |    3.86641 |
| k-d_tree_sklearn     |     0.866078 |       223.248  |    4.77982 |
| Bori_Aron_solution-1 |     0.771501 |       142.626  |   14.0923  |