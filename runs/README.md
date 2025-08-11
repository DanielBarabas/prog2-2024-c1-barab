# 2025-08-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.521367 |       0.422702 |   0.423851 |
| k-d_tree_polars      |     0.593157 |       0.412313 |   0.426453 |
| solution-1           |     7.97783  |       1e-06    |   0.430319 |
| barab-szabi-1        |     0.528611 |       0.419144 |   0.465489 |
| Bori_Aron_solution-1 |     0.537088 |       0.544777 |   0.552751 |
| k-d_tree_pandas      |     8.44739  |       0.430719 |   0.682525 |
| k-d_tree_sklearn     |     2.96856  |       1.12752  |   1.11229  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554642 |       0.427495 |   0.427341 |
| k-d_tree_polars      |     0.53699  |       0.414552 |   0.437024 |
| barab-szabi-1        |     0.537154 |       0.409331 |   0.440437 |
| Bori_Aron_solution-1 |     0.532004 |       0.553971 |   0.549574 |
| k-d_tree_pandas      |     0.540532 |       0.392212 |   0.557263 |
| k-d_tree_sklearn     |     0.544661 |       0.982983 |   1.06381  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545497 |       0.446614 |   0.444194 |
| k-d_tree_polars      |     0.561537 |       0.43288  |   0.458766 |
| barab-szabi-1        |     0.53801  |       0.437178 |   0.460909 |
| Bori_Aron_solution-1 |     0.55143  |       0.608381 |   0.566206 |
| k-d_tree_pandas      |     0.538172 |       0.405133 |   0.599551 |
| k-d_tree_sklearn     |     0.549109 |       1.02227  |   1.07886  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.540033 |       0.508138 |   0.496203 |
| k-d_tree_polars      |     0.537962 |       0.54466  |   0.546069 |
| Bori_Aron_solution-1 |     0.53187  |       0.761197 |   0.557086 |
| barab-szabi-1        |     0.539455 |       0.557426 |   0.561137 |
| k-d_tree_pandas      |     0.549964 |       0.489601 |   0.752431 |
| k-d_tree_sklearn     |     0.542208 |       1.22857  |   1.1138   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535043 |       0.737561 |   0.504968 |
| Bori_Aron_solution-1 |     0.528347 |       1.39496  |   0.5781   |
| barab-szabi-1        |     0.533857 |       0.880698 |   0.936789 |
| k-d_tree_polars      |     0.550682 |       0.885466 |   0.937271 |
| k-d_tree_pandas      |     0.53209  |       0.76348  |   1.17275  |
| k-d_tree_sklearn     |     0.544569 |       2.0686   |   1.20945  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535293 |        5.19    |   0.726571 |
| Bori_Aron_solution-1 |     0.534307 |       10.5262  |   0.839354 |
| k-d_tree_sklearn     |     0.539985 |       15.9413  |   1.30038  |
| k-d_tree_polars      |     0.538939 |        5.04445 |   6.50335  |
| barab-szabi-1        |     0.539248 |        5.09511 |   6.50711  |
| k-d_tree_pandas      |     0.535122 |        3.97449 |   6.8873   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.535923 |        70.8414 |    2.64141 |
| k-d_tree_sklearn     |     0.544404 |       225.842  |    4.45592 |
| Bori_Aron_solution-1 |     0.635397 |       146.844  |   18.9635  |