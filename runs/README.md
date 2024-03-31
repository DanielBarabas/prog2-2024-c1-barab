# 2024-03-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.712569 |       0.41521  |   0.366095 |
| k-d_tree_polars      |     0.752008 |       0.398561 |   0.372086 |
| barab-szabi-1        |     0.744809 |       0.414229 |   0.377093 |
| solution-1           |     8.26394  |       1e-06    |   0.467926 |
| Bori_Aron_solution-1 |     0.703307 |       0.523461 |   0.50535  |
| k-d_tree_pandas      |     8.32284  |       0.414196 |   0.655535 |
| k-d_tree_sklearn     |     3.23602  |       0.967263 |   0.682909 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.735977 |       0.37459  |   0.369127 |
| k-d_tree_polars      |     0.750711 |       0.40669  |   0.37762  |
| barab-szabi-1        |     0.743666 |       0.413249 |   0.380448 |
| Bori_Aron_solution-1 |     0.729821 |       0.509469 |   0.498914 |
| k-d_tree_pandas      |     0.750108 |       0.407455 |   0.514901 |
| k-d_tree_sklearn     |     0.749602 |       0.858794 |   0.682254 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.747781 |       0.382585 |   0.379677 |
| barab-szabi-1        |     0.743718 |       0.434122 |   0.398454 |
| k-d_tree_polars      |     0.741493 |       0.434598 |   0.39942  |
| Bori_Aron_solution-1 |     0.728976 |       0.546385 |   0.538074 |
| k-d_tree_pandas      |     0.748721 |       0.405813 |   0.55369  |
| k-d_tree_sklearn     |     0.735929 |       0.983558 |   0.702955 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.731812 |       0.449786 |   0.406161 |
| k-d_tree_polars      |     0.738853 |       0.538703 |   0.511627 |
| barab-szabi-1        |     0.754109 |       0.544026 |   0.513061 |
| Bori_Aron_solution-1 |     0.733478 |       0.742803 |   0.531903 |
| k-d_tree_pandas      |     0.735301 |       0.483857 |   0.689328 |
| k-d_tree_sklearn     |     0.772059 |       1.13721  |   0.767063 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.726524 |       0.699423 |   0.440834 |
| Bori_Aron_solution-1 |     0.722406 |       1.35697  |   0.535634 |
| k-d_tree_polars      |     0.744015 |       0.846216 |   0.849364 |
| k-d_tree_sklearn     |     0.749897 |       1.92309  |   0.865113 |
| barab-szabi-1        |     0.749881 |       0.84572  |   0.883977 |
| k-d_tree_pandas      |     0.736602 |       0.745076 |   1.1249   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.730188 |        5.08037 |   0.728894 |
| Bori_Aron_solution-1 |     0.730581 |       10.5256  |   0.803806 |
| k-d_tree_sklearn     |     0.744394 |       15.443   |   1.06686  |
| barab-szabi-1        |     0.742774 |        4.8745  |   6.40682  |
| k-d_tree_polars      |     0.729348 |        4.82965 |   6.47766  |
| k-d_tree_pandas      |     0.730438 |        3.86038 |   6.66324  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.738775 |         70.422 |    3.62699 |
| k-d_tree_sklearn     |     0.915071 |        221.484 |    4.8667  |
| Bori_Aron_solution-1 |     0.838812 |        144.384 |   13.9659  |