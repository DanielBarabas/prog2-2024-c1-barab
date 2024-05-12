# 2024-05-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     8.79067  |       0.433981 |   0.359038 |
| barab-szabi-2        |     0.768636 |       0.361122 |   0.362352 |
| k-d_tree_polars      |     0.727147 |       0.425719 |   0.365849 |
| solution-1           |     8.26768  |       1e-06    |   0.374279 |
| Bori_Aron_solution-1 |     0.713985 |       0.497809 |   0.503683 |
| k-d_tree_pandas      |     0.73721  |       0.41194  |   0.511548 |
| k-d_tree_sklearn     |     3.24187  |       0.920795 |   0.694075 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.750904 |       0.437559 |   0.36642  |
| k-d_tree_polars      |     0.754735 |       0.436365 |   0.369985 |
| barab-szabi-2        |     0.760664 |       0.369857 |   0.41134  |
| Bori_Aron_solution-1 |     0.757311 |       0.520958 |   0.517422 |
| k-d_tree_pandas      |     0.770523 |       0.415098 |   0.518961 |
| k-d_tree_sklearn     |     0.767612 |       0.910765 |   0.70547  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.751236 |       0.404889 |   0.376963 |
| k-d_tree_polars      |     0.759397 |       0.446745 |   0.387472 |
| barab-szabi-1        |     0.763252 |       0.451215 |   0.393779 |
| Bori_Aron_solution-1 |     0.74085  |       0.550097 |   0.512759 |
| k-d_tree_pandas      |     0.758351 |       0.428344 |   0.556765 |
| k-d_tree_sklearn     |     0.764943 |       0.941252 |   0.726949 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.753963 |       0.443537 |   0.405828 |
| k-d_tree_polars      |     0.761621 |       0.557829 |   0.488951 |
| barab-szabi-1        |     0.755548 |       0.556519 |   0.49597  |
| Bori_Aron_solution-1 |     0.738542 |       0.716852 |   0.501911 |
| k-d_tree_pandas      |     0.754002 |       0.498534 |   0.683944 |
| k-d_tree_sklearn     |     0.762531 |       1.21379  |   0.780555 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.754492 |       0.720826 |   0.491941 |
| Bori_Aron_solution-1 |     0.761625 |       1.40356  |   0.539428 |
| k-d_tree_polars      |     0.758224 |       0.884746 |   0.871471 |
| k-d_tree_sklearn     |     0.754614 |       2.0336   |   0.900807 |
| barab-szabi-1        |     0.763392 |       0.882693 |   0.920835 |
| k-d_tree_pandas      |     0.767557 |       0.787767 |   1.14709  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.753225 |        5.48521 |   0.75421  |
| Bori_Aron_solution-1 |     0.74023  |       11.1412  |   0.795595 |
| k-d_tree_sklearn     |     0.743999 |       16.8778  |   1.09937  |
| barab-szabi-1        |     0.748511 |        4.85723 |   6.93407  |
| k-d_tree_pandas      |     0.743396 |        3.94291 |   6.97584  |
| k-d_tree_polars      |     0.750004 |        4.92358 |   7.13591  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.00649  |        79.4307 |    3.78743 |
| k-d_tree_sklearn     |     0.864338 |       232.137  |    4.82749 |
| Bori_Aron_solution-1 |     0.726233 |       157.655  |   18.5556  |