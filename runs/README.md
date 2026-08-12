# 2026-08-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.04405  |       1e-06    |   0.422841 |
| barab-szabi-1        |     0.441573 |       0.402005 |   0.436967 |
| barab-szabi-2        |     0.443998 |       0.440891 |   0.463326 |
| Bori_Aron_solution-1 |     0.424128 |       0.528809 |   0.52535  |
| k-d_tree_pandas      |     0.436589 |       0.375921 |   0.530867 |
| k-d_tree_polars      |     7.96463  |       0.435456 |   0.543904 |
| k-d_tree_sklearn     |     2.65361  |       1.07949  |   1.04566  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.430126 |       0.42585  |   0.421075 |
| barab-szabi-1        |     0.431686 |       0.394004 |   0.427893 |
| k-d_tree_polars      |     0.439845 |       0.39947  |   0.439396 |
| Bori_Aron_solution-1 |     0.470699 |       0.530852 |   0.517764 |
| k-d_tree_pandas      |     0.432415 |       0.373457 |   0.525324 |
| k-d_tree_sklearn     |     0.438148 |       0.946026 |   1.03547  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.429824 |       0.440532 |   0.433667 |
| barab-szabi-1        |     0.429723 |       0.42236  |   0.448389 |
| k-d_tree_polars      |     0.426192 |       0.426703 |   0.455889 |
| Bori_Aron_solution-1 |     0.42368  |       0.560167 |   0.521004 |
| k-d_tree_pandas      |     0.435714 |       0.388362 |   0.563515 |
| k-d_tree_sklearn     |     0.432838 |       0.990025 |   1.01134  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.433672 |       0.499448 |   0.46419  |
| Bori_Aron_solution-1 |     0.422421 |       0.721894 |   0.525185 |
| k-d_tree_polars      |     0.43154  |       0.550363 |   0.530174 |
| barab-szabi-1        |     0.427041 |       0.528504 |   0.533242 |
| k-d_tree_pandas      |     0.432972 |       0.4599   |   0.680387 |
| k-d_tree_sklearn     |     0.432552 |       1.19258  |   1.05039  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.432551 |       0.710541 |   0.503835 |
| Bori_Aron_solution-1 |     0.427496 |       1.30966  |   0.566773 |
| k-d_tree_polars      |     0.435843 |       0.847397 |   0.83795  |
| barab-szabi-1        |     0.43286  |       0.854403 |   0.867563 |
| k-d_tree_pandas      |     0.432587 |       0.726346 |   1.06887  |
| k-d_tree_sklearn     |     0.430955 |       1.92487  |   1.11018  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.428812 |        5.05237 |   0.71103  |
| Bori_Aron_solution-1 |     0.428166 |        9.92967 |   0.872763 |
| k-d_tree_sklearn     |     0.438188 |       14.5361  |   1.25456  |
| barab-szabi-1        |     0.434512 |        4.74847 |   6.20744  |
| k-d_tree_polars      |     0.429392 |        4.77871 |   6.29902  |
| k-d_tree_pandas      |     0.4398   |        3.78473 |   6.56428  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527178 |        69.1787 |    2.6867  |
| k-d_tree_sklearn     |     0.709443 |       177.565  |    4.09334 |
| Bori_Aron_solution-1 |     0.421972 |       138.369  |   15.0707  |