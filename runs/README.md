# 2026-01-19

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.459914 |       0.444203 |   0.418741 |
| k-d_tree_polars      |     0.546067 |       0.372074 |   0.426331 |
| barab-szabi-1        |     0.541306 |       0.377824 |   0.457408 |
| Bori_Aron_solution-1 |     0.538002 |       0.627883 |   0.548103 |
| solution-1           |     6.53638  |       2e-06    |   0.728733 |
| k-d_tree_pandas      |     7.35109  |       0.524415 |   0.794168 |
| k-d_tree_sklearn     |     2.71421  |       1.08906  |   1.09539  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.47777  |       0.452709 |   0.407401 |
| barab-szabi-1        |     0.530535 |       0.469518 |   0.493507 |
| k-d_tree_polars      |     0.539097 |       0.479104 |   0.501839 |
| Bori_Aron_solution-1 |     0.529786 |       0.508338 |   0.539474 |
| k-d_tree_pandas      |     0.465554 |       0.361496 |   0.578293 |
| k-d_tree_sklearn     |     0.482035 |       0.870772 |   0.949395 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.521554 |       0.397432 |   0.437953 |
| barab-szabi-2        |     0.467542 |       0.492502 |   0.448753 |
| k-d_tree_polars      |     0.463198 |       0.428798 |   0.464786 |
| Bori_Aron_solution-1 |     0.471245 |       0.579865 |   0.583227 |
| k-d_tree_pandas      |     0.56257  |       0.484438 |   0.641317 |
| k-d_tree_sklearn     |     0.476218 |       0.940768 |   1.01705  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467201 |       0.528084 |   0.492358 |
| k-d_tree_polars      |     0.508198 |       0.57792  |   0.507253 |
| Bori_Aron_solution-1 |     0.460771 |       0.757285 |   0.528557 |
| barab-szabi-1        |     0.562236 |       0.602797 |   0.577852 |
| k-d_tree_pandas      |     0.468363 |       0.485636 |   0.674581 |
| k-d_tree_sklearn     |     0.483401 |       1.19967  |   1.21998  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.461842 |       0.81318  |   0.492166 |
| Bori_Aron_solution-1 |     0.469052 |       1.2971   |   0.554899 |
| barab-szabi-1        |     0.484589 |       0.820081 |   0.839489 |
| k-d_tree_polars      |     0.484829 |       0.858505 |   0.921251 |
| k-d_tree_pandas      |     0.468084 |       0.707882 |   1.02489  |
| k-d_tree_sklearn     |     0.469092 |       1.87254  |   1.07001  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.509591 |        5.00828 |   0.708949 |
| Bori_Aron_solution-1 |     0.460994 |        9.70165 |   0.888908 |
| k-d_tree_sklearn     |     0.471006 |       13.6789  |   1.21736  |
| barab-szabi-1        |     0.471122 |        5.00655 |   5.96743  |
| k-d_tree_polars      |     0.465744 |        4.97183 |   6.02886  |
| k-d_tree_pandas      |     0.481696 |        3.88403 |   6.24394  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.503225 |        85.3158 |    2.61277 |
| k-d_tree_sklearn     |     0.531932 |       174.191  |    4.06912 |
| Bori_Aron_solution-1 |     0.597065 |       136.302  |   14.2755  |