# 2025-01-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.85532  |       0.536918 |   0.402397 |
| k-d_tree_polars      |     0.576686 |       0.42132  |   0.413961 |
| solution-1           |     7.49556  |       1e-06    |   0.418339 |
| barab-szabi-1        |     0.63073  |       0.440366 |   0.439638 |
| Bori_Aron_solution-1 |     0.605424 |       0.560582 |   0.574431 |
| k-d_tree_pandas      |     0.615012 |       0.424706 |   0.589337 |
| k-d_tree_sklearn     |     2.965    |       1.09698  |   1.13554  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.6148   |       0.433529 |   0.426628 |
| barab-szabi-1        |     0.613505 |       0.427433 |   0.43076  |
| barab-szabi-2        |     0.606642 |       0.442761 |   0.450999 |
| k-d_tree_pandas      |     0.605719 |       0.403323 |   0.567896 |
| Bori_Aron_solution-1 |     0.615191 |       0.577908 |   0.575868 |
| k-d_tree_sklearn     |     0.66444  |       1.02127  |   1.0985   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.597905 |       0.430771 |   0.432904 |
| barab-szabi-1        |     0.622721 |       0.434335 |   0.448571 |
| k-d_tree_polars      |     0.610991 |       0.450165 |   0.471967 |
| Bori_Aron_solution-1 |     0.58921  |       0.595045 |   0.554002 |
| k-d_tree_pandas      |     0.5852   |       0.408064 |   0.594676 |
| k-d_tree_sklearn     |     0.603853 |       1.03363  |   1.1014   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.593845 |       0.486782 |   0.48162  |
| k-d_tree_polars      |     0.602598 |       0.550827 |   0.537432 |
| barab-szabi-1        |     0.59574  |       0.543087 |   0.546836 |
| Bori_Aron_solution-1 |     0.590441 |       0.749485 |   0.556091 |
| k-d_tree_pandas      |     0.590698 |       0.485897 |   0.746004 |
| k-d_tree_sklearn     |     0.596935 |       1.24833  |   1.13687  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.585475 |       1.41275  |   0.593795 |
| barab-szabi-2        |     0.602816 |       0.772648 |   0.600097 |
| barab-szabi-1        |     0.598536 |       0.877919 |   0.944509 |
| k-d_tree_polars      |     0.626522 |       0.936649 |   0.978314 |
| k-d_tree_pandas      |     0.611211 |       0.754767 |   1.1979   |
| k-d_tree_sklearn     |     0.654786 |       2.13355  |   1.23811  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.616468 |       10.7555  |   0.871639 |
| barab-szabi-2        |     0.592808 |        6.18081 |   0.879033 |
| k-d_tree_sklearn     |     0.595105 |       18.6005  |   1.42752  |
| k-d_tree_polars      |     0.635041 |        4.84947 |   6.9759   |
| k-d_tree_pandas      |     0.592167 |        3.87555 |   7.44384  |
| barab-szabi-1        |     0.580894 |        4.97545 |   7.46114  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618303 |        82.1507 |    3.50939 |
| k-d_tree_sklearn     |     0.616055 |       240.995  |    4.81683 |
| Bori_Aron_solution-1 |     0.730331 |       153.994  |   17.1296  |