# 2026-08-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.414426 |       0.401742 |   0.434116 |
| k-d_tree_polars      |     0.40859  |       0.38207  |   0.442378 |
| Bori_Aron_solution-1 |     5.53766  |       0.653345 |   0.461849 |
| barab-szabi-2        |     6.46439  |       0.524334 |   0.47526  |
| solution-1           |     7.83264  |       1e-06    |   0.518344 |
| k-d_tree_pandas      |     0.41863  |       0.375681 |   0.521036 |
| k-d_tree_sklearn     |     2.94814  |       1.04068  |   1.01345  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.430174 |       0.427453 |   0.429343 |
| k-d_tree_polars      |     0.433925 |       0.404204 |   0.437817 |
| barab-szabi-1        |     0.430793 |       0.409498 |   0.442337 |
| Bori_Aron_solution-1 |     0.43059  |       0.536343 |   0.534109 |
| k-d_tree_pandas      |     0.426283 |       0.382055 |   0.536232 |
| k-d_tree_sklearn     |     0.431118 |       0.973651 |   1.02082  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.43346  |       0.462461 |   0.430064 |
| k-d_tree_polars      |     0.43646  |       0.447269 |   0.450187 |
| barab-szabi-1        |     0.430116 |       0.44062  |   0.465151 |
| Bori_Aron_solution-1 |     0.424358 |       0.565306 |   0.532097 |
| k-d_tree_pandas      |     0.426142 |       0.385672 |   0.569444 |
| k-d_tree_sklearn     |     0.443977 |       1.03241  |   1.03404  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.433303 |       0.498823 |   0.470915 |
| Bori_Aron_solution-1 |     0.421085 |       0.717165 |   0.537657 |
| k-d_tree_polars      |     0.43445  |       0.553495 |   0.538106 |
| barab-szabi-1        |     0.438362 |       0.578087 |   0.550548 |
| k-d_tree_pandas      |     0.433771 |       0.479282 |   0.678012 |
| k-d_tree_sklearn     |     0.43556  |       1.20763  |   1.07306  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.428885 |       0.729504 |   0.505102 |
| Bori_Aron_solution-1 |     0.426128 |       1.32875  |   0.580052 |
| k-d_tree_polars      |     0.430012 |       0.837716 |   0.848731 |
| barab-szabi-1        |     0.431772 |       0.846016 |   0.89327  |
| k-d_tree_pandas      |     0.427064 |       0.732969 |   1.10017  |
| k-d_tree_sklearn     |     0.426733 |       1.99733  |   1.14905  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.436935 |        4.7801  |   0.727506 |
| Bori_Aron_solution-1 |     0.41968  |        9.84917 |   0.905753 |
| k-d_tree_sklearn     |     0.443305 |       15.7802  |   1.31015  |
| k-d_tree_polars      |     0.438508 |        5.6062  |   6.33763  |
| barab-szabi-1        |     0.461134 |        5.6543  |   6.34273  |
| k-d_tree_pandas      |     0.436284 |        3.80021 |   6.69224  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.813287 |        67.1567 |    2.85006 |
| k-d_tree_sklearn     |     0.675371 |       183.897  |    3.99877 |
| Bori_Aron_solution-1 |     0.440843 |       159.56   |   55.9019  |