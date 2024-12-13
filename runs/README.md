# 2024-12-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.10952  |       1e-06    |   0.3862   |
| k-d_tree_polars      |     0.640312 |       0.443145 |   0.414969 |
| barab-szabi-2        |     0.677308 |       0.411485 |   0.416926 |
| barab-szabi-1        |     0.647277 |       0.427338 |   0.416967 |
| k-d_tree_pandas      |     0.651696 |       0.408055 |   0.558159 |
| Bori_Aron_solution-1 |     0.642302 |       0.572668 |   0.565071 |
| k-d_tree_sklearn     |    10.9129   |       1.07647  |   1.05549  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.649988 |       0.426044 |   0.415803 |
| k-d_tree_polars      |     0.658359 |       0.436976 |   0.42245  |
| barab-szabi-1        |     0.642492 |       0.446242 |   0.447056 |
| Bori_Aron_solution-1 |     0.703388 |       0.610417 |   0.567236 |
| k-d_tree_pandas      |     0.646288 |       0.416608 |   0.589859 |
| k-d_tree_sklearn     |     0.64618  |       0.958393 |   1.04479  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.679264 |       0.470604 |   0.47759  |
| barab-szabi-1        |     0.745357 |       0.495551 |   0.478255 |
| k-d_tree_polars      |     0.660563 |       0.495316 |   0.505774 |
| Bori_Aron_solution-1 |     0.702939 |       0.637183 |   0.634106 |
| k-d_tree_pandas      |     0.706163 |       0.484001 |   0.663505 |
| k-d_tree_sklearn     |     0.654183 |       1.05278  |   1.12697  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.674598 |       0.529391 |   0.513959 |
| k-d_tree_polars      |     0.70988  |       0.595761 |   0.59516  |
| barab-szabi-1        |     0.694356 |       0.621001 |   0.595228 |
| Bori_Aron_solution-1 |     0.682066 |       0.840194 |   0.630501 |
| k-d_tree_pandas      |     0.666592 |       0.519721 |   0.79588  |
| k-d_tree_sklearn     |     0.68055  |       1.31056  |   1.20335  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.63508  |       1.44278  |   0.607743 |
| barab-szabi-2        |     0.644484 |       0.805772 |   0.647051 |
| k-d_tree_polars      |     0.693278 |       0.89192  |   0.901163 |
| barab-szabi-1        |     0.669327 |       0.896204 |   0.959947 |
| k-d_tree_pandas      |     0.654801 |       0.779357 |   1.18147  |
| k-d_tree_sklearn     |     0.67928  |       2.28909  |   1.33658  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.641844 |        5.74408 |   0.781296 |
| Bori_Aron_solution-1 |     0.634352 |       11.2567  |   0.865864 |
| k-d_tree_sklearn     |     0.649153 |       17.3418  |   1.38638  |
| k-d_tree_polars      |     0.660371 |        4.93299 |   6.9855   |
| barab-szabi-1        |     0.649129 |        5.01351 |   7.03669  |
| k-d_tree_pandas      |     0.718652 |        3.91125 |   7.53743  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.681024 |        76.8218 |    3.13125 |
| k-d_tree_sklearn     |     0.731668 |       246.557  |    4.4166  |
| Bori_Aron_solution-1 |     0.674003 |       155.069  |   18.3273  |