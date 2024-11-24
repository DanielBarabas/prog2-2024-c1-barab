# 2024-11-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.43412  |       1e-06    |   0.348225 |
| barab-szabi-1        |     0.613853 |       0.39914  |   0.386434 |
| barab-szabi-2        |     0.61379  |       0.396697 |   0.387783 |
| k-d_tree_polars      |     0.611573 |       0.396136 |   0.389688 |
| Bori_Aron_solution-1 |     0.60844  |       0.519098 |   0.522933 |
| k-d_tree_pandas      |     0.612453 |       0.380351 |   0.525892 |
| k-d_tree_sklearn     |    10.0852   |       1.01757  |   0.958763 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622703 |       0.391581 |   0.386304 |
| k-d_tree_polars      |     0.610014 |       0.404542 |   0.392943 |
| barab-szabi-1        |     0.635875 |       0.401026 |   0.408235 |
| Bori_Aron_solution-1 |     0.630175 |       0.532767 |   0.518358 |
| k-d_tree_pandas      |     0.615042 |       0.385512 |   0.548348 |
| k-d_tree_sklearn     |     0.678697 |       0.885691 |   0.953138 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615272 |       0.400793 |   0.41767  |
| k-d_tree_polars      |     0.614975 |       0.429373 |   0.418953 |
| barab-szabi-1        |     0.610137 |       0.426567 |   0.420926 |
| Bori_Aron_solution-1 |     0.632322 |       0.566606 |   0.520469 |
| k-d_tree_pandas      |     0.617425 |       0.416904 |   0.621336 |
| k-d_tree_sklearn     |     0.623781 |       0.93056  |   0.982925 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.640424 |       0.479583 |   0.435416 |
| k-d_tree_polars      |     0.613398 |       0.535658 |   0.51057  |
| barab-szabi-1        |     0.623875 |       0.54102  |   0.524097 |
| Bori_Aron_solution-1 |     0.611407 |       0.745813 |   0.534884 |
| k-d_tree_pandas      |     0.614548 |       0.480003 |   0.70946  |
| k-d_tree_sklearn     |     0.629006 |       1.14447  |   1.03992  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615833 |       0.728596 |   0.466633 |
| Bori_Aron_solution-1 |     0.601353 |       1.38589  |   0.563402 |
| k-d_tree_polars      |     0.608263 |       0.866434 |   0.863114 |
| barab-szabi-1        |     0.616369 |       0.865084 |   0.901901 |
| k-d_tree_sklearn     |     0.616488 |       1.97517  |   1.13447  |
| k-d_tree_pandas      |     0.61339  |       0.743264 |   1.14379  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623357 |        5.19929 |   0.740411 |
| Bori_Aron_solution-1 |     0.606609 |       10.5381  |   0.814127 |
| k-d_tree_sklearn     |     0.6143   |       15.6269  |   1.26306  |
| k-d_tree_polars      |     0.619403 |        4.88505 |   6.31073  |
| barab-szabi-1        |     0.616743 |        4.88667 |   6.34768  |
| k-d_tree_pandas      |     0.622641 |        3.88705 |   6.74919  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.66082  |        74.0403 |    3.02126 |
| k-d_tree_sklearn     |     0.615098 |       237.431  |    4.43982 |
| Bori_Aron_solution-1 |     0.659688 |       152.509  |   18.0131  |