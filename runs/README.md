# 2025-10-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52684  |       0.644627 |   0.422594 |
| k-d_tree_polars      |     0.544688 |       0.400001 |   0.423577 |
| barab-szabi-1        |     0.546943 |       0.412167 |   0.426095 |
| solution-1           |     7.35098  |       1e-06    |   0.521989 |
| Bori_Aron_solution-1 |     0.535872 |       0.549023 |   0.543581 |
| k-d_tree_pandas      |    15.9354   |       0.423985 |   0.816554 |
| k-d_tree_sklearn     |     3.03289  |       1.19301  |   1.0438   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544748 |       0.427281 |   0.430016 |
| k-d_tree_polars      |     0.542291 |       0.412605 |   0.43057  |
| barab-szabi-1        |     0.544192 |       0.41169  |   0.436655 |
| Bori_Aron_solution-1 |     0.561434 |       0.555097 |   0.54768  |
| k-d_tree_pandas      |     0.540768 |       0.391731 |   0.556734 |
| k-d_tree_sklearn     |     0.546553 |       0.974359 |   1.06052  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541059 |       0.44298  |   0.445885 |
| k-d_tree_polars      |     0.541251 |       0.435266 |   0.45889  |
| barab-szabi-1        |     0.544952 |       0.435406 |   0.461122 |
| Bori_Aron_solution-1 |     0.538002 |       0.589971 |   0.55021  |
| k-d_tree_pandas      |     0.541954 |       0.410184 |   0.593207 |
| k-d_tree_sklearn     |     0.569132 |       1.01088  |   1.08366  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542195 |       0.505738 |   0.467633 |
| k-d_tree_polars      |     0.543864 |       0.562211 |   0.55924  |
| Bori_Aron_solution-1 |     0.534028 |       0.779356 |   0.563989 |
| barab-szabi-1        |     0.542182 |       0.565342 |   0.568599 |
| k-d_tree_pandas      |     0.544642 |       0.50206  |   0.726769 |
| k-d_tree_sklearn     |     0.549716 |       1.27397  |   1.13202  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541717 |       0.744939 |   0.502869 |
| Bori_Aron_solution-1 |     0.542394 |       1.46585  |   0.589066 |
| k-d_tree_polars      |     0.548597 |       0.953569 |   0.906763 |
| barab-szabi-1        |     0.54886  |       0.9497   |   0.940433 |
| k-d_tree_pandas      |     0.541258 |       0.839608 |   1.1724   |
| k-d_tree_sklearn     |     0.551054 |       2.12136  |   1.21559  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545278 |        5.21448 |   0.727611 |
| Bori_Aron_solution-1 |     0.534926 |       11.207   |   0.848797 |
| k-d_tree_sklearn     |     0.548357 |       16.6418  |   1.3087   |
| barab-szabi-1        |     0.552073 |        5.57941 |   6.50687  |
| k-d_tree_polars      |     0.545801 |        5.66332 |   6.5159   |
| k-d_tree_pandas      |     0.545776 |        4.52936 |   6.93744  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541787 |        72.1802 |    2.62267 |
| k-d_tree_sklearn     |     0.554945 |       235.148  |    4.04283 |
| Bori_Aron_solution-1 |     0.777787 |       150.05   |   17.861   |