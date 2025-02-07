# 2025-02-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.41941  |       0.529934 |   0.402011 |
| barab-szabi-1        |     0.61503  |       0.407878 |   0.406399 |
| k-d_tree_polars      |     0.578848 |       0.402435 |   0.411821 |
| solution-1           |     7.13536  |       1e-06    |   0.511615 |
| Bori_Aron_solution-1 |     0.587979 |       0.540324 |   0.533182 |
| k-d_tree_pandas      |     0.594864 |       0.388578 |   0.543092 |
| k-d_tree_sklearn     |     3.1587   |       1.12204  |   1.04777  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.597219 |       0.41528  |   0.408814 |
| k-d_tree_polars      |     0.599077 |       0.423109 |   0.419557 |
| barab-szabi-1        |     0.604277 |       0.414931 |   0.427037 |
| Bori_Aron_solution-1 |     0.597046 |       0.545554 |   0.542981 |
| k-d_tree_pandas      |     0.595515 |       0.393395 |   0.551661 |
| k-d_tree_sklearn     |     0.598211 |       0.969044 |   1.02543  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.589295 |       0.420241 |   0.421784 |
| k-d_tree_polars      |     0.589688 |       0.445256 |   0.439393 |
| barab-szabi-1        |     0.60655  |       0.465946 |   0.465412 |
| Bori_Aron_solution-1 |     0.628814 |       0.587451 |   0.540617 |
| k-d_tree_pandas      |     0.619044 |       0.434899 |   0.605348 |
| k-d_tree_sklearn     |     0.598099 |       0.998734 |   1.05982  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617149 |       0.493106 |   0.448516 |
| k-d_tree_polars      |     0.596139 |       0.553947 |   0.534162 |
| Bori_Aron_solution-1 |     0.594196 |       0.755915 |   0.556203 |
| barab-szabi-1        |     0.602906 |       0.547138 |   0.557497 |
| k-d_tree_pandas      |     0.593405 |       0.50076  |   0.72854  |
| k-d_tree_sklearn     |     0.598625 |       1.26602  |   1.12791  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.590922 |       0.772123 |   0.520745 |
| Bori_Aron_solution-1 |     0.584383 |       1.37536  |   0.578868 |
| k-d_tree_polars      |     0.601958 |       0.876609 |   0.897341 |
| barab-szabi-1        |     0.591282 |       0.885025 |   0.94815  |
| k-d_tree_sklearn     |     0.601752 |       2.1006   |   1.20443  |
| k-d_tree_pandas      |     0.595618 |       0.765023 |   1.20924  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611115 |        5.44849 |   0.731913 |
| Bori_Aron_solution-1 |     0.608583 |       10.8748  |   0.873929 |
| k-d_tree_sklearn     |     0.605101 |       16.9368  |   1.39736  |
| barab-szabi-1        |     0.585194 |        4.89175 |   6.73422  |
| k-d_tree_polars      |     0.589766 |        4.86787 |   6.81616  |
| k-d_tree_pandas      |     0.588458 |        3.76525 |   7.18329  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591719 |        73.2635 |    3.02783 |
| k-d_tree_sklearn     |     0.595568 |       229.09   |    4.43527 |
| Bori_Aron_solution-1 |     0.703379 |       144.242  |   18.4866  |