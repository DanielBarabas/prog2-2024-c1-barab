# 2026-09-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.407942 |       0.420753 |   0.409198 |
| solution-1           |     7.15232  |       1e-06    |   0.427397 |
| k-d_tree_polars      |     0.400807 |       0.392966 |   0.431306 |
| k-d_tree_pandas      |     0.419867 |       0.360152 |   0.497338 |
| Bori_Aron_solution-1 |     0.405704 |       0.495882 |   0.505096 |
| barab-szabi-1        |    11.5615   |       0.749055 |   0.843525 |
| k-d_tree_sklearn     |     2.84034  |       1.13845  |   0.969265 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.417174 |       0.399932 |   0.429897 |
| barab-szabi-2        |     0.417563 |       0.420305 |   0.430619 |
| k-d_tree_polars      |     0.404877 |       0.38688  |   0.431632 |
| Bori_Aron_solution-1 |     0.413964 |       0.509472 |   0.503219 |
| k-d_tree_pandas      |     0.427681 |       0.377671 |   0.514895 |
| k-d_tree_sklearn     |     0.406642 |       0.868175 |   0.953491 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.410416 |       0.468766 |   0.409548 |
| k-d_tree_polars      |     0.400132 |       0.41007  |   0.433198 |
| barab-szabi-1        |     0.425507 |       0.456584 |   0.45809  |
| Bori_Aron_solution-1 |     0.407421 |       0.548671 |   0.515201 |
| k-d_tree_pandas      |     0.407547 |       0.384382 |   0.540153 |
| k-d_tree_sklearn     |     0.401468 |       0.95701  |   0.986606 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.422947 |       0.486743 |   0.482087 |
| Bori_Aron_solution-1 |     0.404871 |       0.692641 |   0.519696 |
| k-d_tree_polars      |     0.419774 |       0.523265 |   0.524126 |
| barab-szabi-1        |     0.412941 |       0.557956 |   0.529873 |
| k-d_tree_pandas      |     0.401669 |       0.454778 |   0.661676 |
| k-d_tree_sklearn     |     0.416886 |       1.1852   |   1.04315  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.412642 |       0.694987 |   0.492511 |
| Bori_Aron_solution-1 |     0.413425 |       1.26347  |   0.566023 |
| k-d_tree_polars      |     0.42676  |       0.816991 |   0.8165   |
| barab-szabi-1        |     0.424254 |       0.842443 |   0.852538 |
| k-d_tree_sklearn     |     0.415857 |       1.9561   |   1.07844  |
| k-d_tree_pandas      |     0.418172 |       0.707538 |   1.13583  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.390788 |        3.84838 |   0.653551 |
| Bori_Aron_solution-1 |     0.398361 |        8.8123  |   0.852908 |
| k-d_tree_sklearn     |     0.396969 |       12.9225  |   1.12746  |
| k-d_tree_polars      |     0.411001 |        4.80785 |   5.23075  |
| barab-szabi-1        |     0.401747 |        5.25974 |   5.37408  |
| k-d_tree_pandas      |     0.408476 |        3.45903 |   5.52451  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.720563 |        60.7412 |    2.88479 |
| k-d_tree_sklearn     |     1.33275  |       174.978  |    4.36753 |
| Bori_Aron_solution-1 |     0.394199 |       148.126  |   42.5139  |