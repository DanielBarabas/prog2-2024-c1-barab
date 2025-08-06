# 2025-08-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.547848 |       0.413476 |   0.423439 |
| barab-szabi-2        |     8.01431  |       0.687727 |   0.427272 |
| k-d_tree_polars      |     0.556849 |       0.402433 |   0.430982 |
| solution-1           |     7.7858   |       1e-06    |   0.513564 |
| Bori_Aron_solution-1 |     0.545265 |       0.550172 |   0.549852 |
| k-d_tree_pandas      |     0.558388 |       0.385543 |   0.561801 |
| k-d_tree_sklearn     |     3.43371  |       1.13892  |   1.05753  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562732 |       0.425572 |   0.428685 |
| k-d_tree_polars      |     0.56562  |       0.42748  |   0.440029 |
| barab-szabi-1        |     0.570337 |       0.421334 |   0.442033 |
| Bori_Aron_solution-1 |     0.55896  |       0.561919 |   0.55989  |
| k-d_tree_pandas      |     0.5619   |       0.405459 |   0.576547 |
| k-d_tree_sklearn     |     0.569878 |       0.990914 |   1.09778  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571142 |       0.44503  |   0.4475   |
| k-d_tree_polars      |     0.560261 |       0.435507 |   0.465272 |
| barab-szabi-1        |     0.566555 |       0.442382 |   0.472823 |
| Bori_Aron_solution-1 |     0.563468 |       0.605733 |   0.562925 |
| k-d_tree_pandas      |     0.557929 |       0.414318 |   0.599545 |
| k-d_tree_sklearn     |     0.569189 |       1.02855  |   1.09037  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55369  |       0.521664 |   0.470245 |
| k-d_tree_polars      |     0.561172 |       0.551862 |   0.55193  |
| Bori_Aron_solution-1 |     0.555896 |       0.770535 |   0.562557 |
| barab-szabi-1        |     0.558748 |       0.547041 |   0.569006 |
| k-d_tree_pandas      |     0.55842  |       0.49172  |   0.739825 |
| k-d_tree_sklearn     |     0.562476 |       1.23718  |   1.13017  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556562 |       0.746238 |   0.498066 |
| Bori_Aron_solution-1 |     0.555037 |       1.41924  |   0.587473 |
| k-d_tree_polars      |     0.561858 |       0.902411 |   0.916666 |
| barab-szabi-1        |     0.553403 |       0.892352 |   0.955859 |
| k-d_tree_pandas      |     0.56002  |       0.764557 |   1.1858   |
| k-d_tree_sklearn     |     0.563953 |       2.1061   |   1.22967  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564512 |        5.2401  |   0.726987 |
| Bori_Aron_solution-1 |     0.548621 |       10.591   |   0.840062 |
| k-d_tree_sklearn     |     0.559564 |       16.3426  |   1.29336  |
| k-d_tree_polars      |     0.553615 |        4.97782 |   6.6047   |
| barab-szabi-1        |     0.554169 |        5.08605 |   6.6075   |
| k-d_tree_pandas      |     0.576707 |        3.95672 |   7.00509  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559902 |        72.8173 |    2.65593 |
| k-d_tree_sklearn     |     0.833781 |       232.859  |    4.04899 |
| Bori_Aron_solution-1 |     0.568598 |       146.535  |   17.7623  |