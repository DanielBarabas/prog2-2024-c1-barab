# 2025-10-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.541488 |       0.40517  |   0.423994 |
| barab-szabi-2        |     0.534494 |       0.444073 |   0.424768 |
| barab-szabi-1        |     0.542203 |       0.43741  |   0.431187 |
| solution-1           |     7.21924  |       1e-06    |   0.461354 |
| Bori_Aron_solution-1 |     0.531486 |       0.542404 |   0.541282 |
| k-d_tree_pandas      |     7.68813  |       0.395993 |   0.578709 |
| k-d_tree_sklearn     |     2.92725  |       1.06944  |   1.0523   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543682 |       0.426231 |   0.427962 |
| k-d_tree_polars      |     0.538688 |       0.407781 |   0.430691 |
| barab-szabi-1        |     0.540841 |       0.40766  |   0.430889 |
| Bori_Aron_solution-1 |     0.534944 |       0.546052 |   0.534816 |
| k-d_tree_pandas      |     0.541779 |       0.387859 |   0.549827 |
| k-d_tree_sklearn     |     0.542774 |       0.969949 |   1.06112  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5416   |       0.436944 |   0.439358 |
| barab-szabi-1        |     0.544997 |       0.437176 |   0.459406 |
| k-d_tree_polars      |     0.549109 |       0.440513 |   0.460621 |
| Bori_Aron_solution-1 |     0.536433 |       0.588414 |   0.543909 |
| k-d_tree_pandas      |     0.541488 |       0.40691  |   0.597282 |
| k-d_tree_sklearn     |     0.54267  |       1.00005  |   1.07983  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.543428 |       0.514457 |   0.470747 |
| k-d_tree_polars      |     0.538856 |       0.561747 |   0.550856 |
| Bori_Aron_solution-1 |     0.532761 |       0.77785  |   0.556298 |
| barab-szabi-1        |     0.539447 |       0.565038 |   0.567431 |
| k-d_tree_pandas      |     0.54112  |       0.505089 |   0.73593  |
| k-d_tree_sklearn     |     0.564226 |       1.26636  |   1.13146  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539836 |       0.736699 |   0.502222 |
| Bori_Aron_solution-1 |     0.543697 |       1.47707  |   0.586789 |
| k-d_tree_polars      |     0.547625 |       0.956044 |   0.92212  |
| barab-szabi-1        |     0.541274 |       0.951364 |   0.935146 |
| k-d_tree_pandas      |     0.540375 |       0.82298  |   1.166    |
| k-d_tree_sklearn     |     0.543047 |       2.12669  |   1.20822  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535885 |        5.19671 |   0.736337 |
| Bori_Aron_solution-1 |     0.561904 |       11.7119  |   0.897115 |
| k-d_tree_sklearn     |     0.545526 |       16.4971  |   1.30788  |
| barab-szabi-1        |     0.539531 |        5.72756 |   6.69652  |
| k-d_tree_pandas      |     0.543052 |        4.60745 |   7.01198  |
| k-d_tree_polars      |     0.5697   |        5.76691 |   7.11873  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574811 |        71.7951 |    2.74859 |
| k-d_tree_sklearn     |     0.547727 |       241.357  |    4.16043 |
| Bori_Aron_solution-1 |     0.780529 |       150.249  |   18.1521  |