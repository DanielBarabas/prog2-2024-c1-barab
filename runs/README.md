# 2024-10-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.637997 |       0.398941 |   0.397179 |
| barab-szabi-1        |     0.641914 |       0.412188 |   0.398916 |
| k-d_tree_polars      |     0.643729 |       0.409927 |   0.399571 |
| solution-1           |     8.04169  |       1e-06    |   0.448314 |
| k-d_tree_pandas      |     0.642746 |       0.393542 |   0.541732 |
| Bori_Aron_solution-1 |     0.623309 |       0.547508 |   0.545595 |
| k-d_tree_sklearn     |    11.3503   |       1.388    |   1.0163   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.661855 |       0.406765 |   0.398731 |
| k-d_tree_polars      |     0.644191 |       0.424552 |   0.400926 |
| barab-szabi-1        |     0.644159 |       0.422124 |   0.403024 |
| Bori_Aron_solution-1 |     0.638105 |       0.554208 |   0.53576  |
| k-d_tree_pandas      |     0.633013 |       0.399591 |   0.54681  |
| k-d_tree_sklearn     |     0.63658  |       0.93215  |   0.987576 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632277 |       0.416961 |   0.409071 |
| k-d_tree_polars      |     0.630503 |       0.459189 |   0.424197 |
| barab-szabi-1        |     0.635631 |       0.441576 |   0.430312 |
| Bori_Aron_solution-1 |     0.630179 |       0.604214 |   0.54467  |
| k-d_tree_pandas      |     0.637139 |       0.413553 |   0.601273 |
| k-d_tree_sklearn     |     0.656327 |       0.958147 |   1.03809  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.630997 |       0.479187 |   0.434968 |
| k-d_tree_polars      |     0.630593 |       0.549245 |   0.530407 |
| barab-szabi-1        |     0.63375  |       0.558229 |   0.54153  |
| Bori_Aron_solution-1 |     0.626964 |       0.767266 |   0.557835 |
| k-d_tree_pandas      |     0.631298 |       0.497198 |   0.732242 |
| k-d_tree_sklearn     |     0.630242 |       1.19104  |   1.07249  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.633573 |       0.742115 |   0.523606 |
| Bori_Aron_solution-1 |     0.631425 |       1.42348  |   0.581564 |
| k-d_tree_polars      |     0.628872 |       0.868045 |   0.899649 |
| barab-szabi-1        |     0.629913 |       0.875967 |   0.948291 |
| k-d_tree_sklearn     |     0.639559 |       2.05041  |   1.17839  |
| k-d_tree_pandas      |     0.636221 |       0.773774 |   1.21489  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.63583  |        5.43846 |   0.724874 |
| Bori_Aron_solution-1 |     0.619359 |       10.9237  |   0.819611 |
| k-d_tree_sklearn     |     0.650494 |       16.8702  |   1.30462  |
| k-d_tree_polars      |     0.637044 |        4.91089 |   6.76733  |
| barab-szabi-1        |     0.620102 |        4.91522 |   6.77686  |
| k-d_tree_pandas      |     0.616913 |        3.89093 |   7.04829  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.654724 |        71.8192 |    2.95549 |
| k-d_tree_sklearn     |     0.626844 |       229.004  |    4.30615 |
| Bori_Aron_solution-1 |     0.653991 |       160.941  |   17.8875  |