# 2024-09-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.650376 |       0.429909 |   0.412307 |
| solution-1           |     8.00226  |       1e-06    |   0.431451 |
| barab-szabi-2        |     0.6594   |       0.411225 |   0.438011 |
| Bori_Aron_solution-1 |     4.60475  |       0.574308 |   0.484068 |
| k-d_tree_polars      |     0.646393 |       0.429992 |   0.497753 |
| k-d_tree_pandas      |     4.35551  |       0.425665 |   0.556388 |
| k-d_tree_sklearn     |     3.21445  |       1.06899  |   1.02706  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.654907 |       0.4388   |   0.420067 |
| barab-szabi-1        |     0.669177 |       0.445947 |   0.423254 |
| barab-szabi-2        |     0.652018 |       0.411565 |   0.423579 |
| Bori_Aron_solution-1 |     0.652411 |       0.574188 |   0.575156 |
| k-d_tree_pandas      |     0.666734 |       0.415289 |   0.589666 |
| k-d_tree_sklearn     |     0.650287 |       0.975636 |   1.05026  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.672624 |       0.431174 |   0.429985 |
| barab-szabi-1        |     0.662544 |       0.46823  |   0.442615 |
| k-d_tree_polars      |     0.672385 |       0.474626 |   0.493829 |
| Bori_Aron_solution-1 |     0.675523 |       0.619183 |   0.568872 |
| k-d_tree_pandas      |     0.646211 |       0.429547 |   0.608619 |
| k-d_tree_sklearn     |     0.653767 |       1.02102  |   1.09565  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.661345 |       0.489392 |   0.451563 |
| k-d_tree_polars      |     0.668206 |       0.576252 |   0.546232 |
| barab-szabi-1        |     0.654574 |       0.573183 |   0.56639  |
| Bori_Aron_solution-1 |     0.658416 |       0.795821 |   0.582724 |
| k-d_tree_pandas      |     0.648906 |       0.512202 |   0.790469 |
| k-d_tree_sklearn     |     0.643289 |       1.26764  |   1.11237  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.66238  |       0.734038 |   0.553519 |
| Bori_Aron_solution-1 |     0.642757 |       1.42773  |   0.621683 |
| k-d_tree_polars      |     0.648888 |       0.881829 |   0.920305 |
| barab-szabi-1        |     0.650757 |       0.886334 |   0.949077 |
| k-d_tree_pandas      |     0.642795 |       0.766564 |   1.20658  |
| k-d_tree_sklearn     |     0.659754 |       2.21793  |   1.24273  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.651994 |        5.66785 |   0.775715 |
| Bori_Aron_solution-1 |     0.651144 |       11.2099  |   0.861912 |
| k-d_tree_sklearn     |     0.644923 |       18.0901  |   1.3885   |
| barab-szabi-1        |     0.664866 |        4.99155 |   7.27725  |
| k-d_tree_polars      |     0.653838 |        4.93617 |   7.30501  |
| k-d_tree_pandas      |     0.652384 |        3.87947 |   7.58332  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.765627 |         77.185 |    3.70743 |
| k-d_tree_sklearn     |     0.966559 |        240.153 |    4.32372 |
| Bori_Aron_solution-1 |     0.636126 |        154.275 |   18.3098  |