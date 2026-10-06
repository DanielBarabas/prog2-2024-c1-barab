# 2026-10-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463069 |       0.43534  |   0.435725 |
| k-d_tree_polars      |     0.465202 |       0.443949 |   0.451342 |
| barab-szabi-1        |     9.60692  |       0.484038 |   0.521343 |
| solution-1           |     8.17945  |       1e-06    |   0.534559 |
| k-d_tree_pandas      |     0.452587 |       0.392631 |   0.53578  |
| Bori_Aron_solution-1 |     0.439169 |       0.546328 |   0.577587 |
| k-d_tree_sklearn     |     3.10041  |       1.31872  |   1.13041  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469168 |       0.448179 |   0.430677 |
| barab-szabi-1        |     0.445383 |       0.432797 |   0.439016 |
| k-d_tree_polars      |     0.456036 |       0.42785  |   0.449197 |
| Bori_Aron_solution-1 |     0.431366 |       0.551932 |   0.556953 |
| k-d_tree_pandas      |     0.443855 |       0.391699 |   0.592516 |
| k-d_tree_sklearn     |     0.465133 |       1.04651  |   1.08699  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.456517 |       0.454016 |   0.436174 |
| k-d_tree_polars      |     0.467566 |       0.455376 |   0.457421 |
| barab-szabi-1        |     0.453981 |       0.45553  |   0.479556 |
| Bori_Aron_solution-1 |     0.464458 |       0.643146 |   0.615661 |
| k-d_tree_pandas      |     0.486609 |       0.471178 |   0.634609 |
| k-d_tree_sklearn     |     0.457206 |       1.11126  |   1.15584  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.457385 |       0.539617 |   0.479679 |
| k-d_tree_polars      |     0.457686 |       0.593237 |   0.54449  |
| Bori_Aron_solution-1 |     0.457609 |       0.738652 |   0.554083 |
| barab-szabi-1        |     0.4503   |       0.595143 |   0.570253 |
| k-d_tree_pandas      |     0.448762 |       0.490539 |   0.735485 |
| k-d_tree_sklearn     |     0.455743 |       1.33397  |   1.19838  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.444281 |       0.771829 |   0.532993 |
| Bori_Aron_solution-1 |     0.463123 |       1.36552  |   0.588034 |
| k-d_tree_polars      |     0.460889 |       0.993106 |   0.874211 |
| barab-szabi-1        |     0.467771 |       0.937156 |   0.905409 |
| k-d_tree_pandas      |     0.451237 |       0.761925 |   1.09006  |
| k-d_tree_sklearn     |     0.47062  |       2.12526  |   1.23995  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.452497 |        4.98613 |   0.714661 |
| Bori_Aron_solution-1 |     0.459154 |       10.4104  |   0.910387 |
| k-d_tree_sklearn     |     0.447244 |       15.8852  |   1.34735  |
| k-d_tree_polars      |     0.446252 |        5.57161 |   6.53481  |
| barab-szabi-1        |     0.47588  |        5.49578 |   6.5783   |
| k-d_tree_pandas      |     0.480677 |        3.84007 |   6.84091  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.844396 |        67.6987 |    2.6069  |
| k-d_tree_sklearn     |     0.627289 |       184.834  |    3.89547 |
| Bori_Aron_solution-1 |     0.475863 |       161.148  |   50.3711  |