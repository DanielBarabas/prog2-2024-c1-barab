# 2025-05-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.00283  |       0.403161 |   0.406041 |
| barab-szabi-1        |     1.00068  |       0.395437 |   0.406329 |
| Bori_Aron_solution-1 |     5.54637  |       0.763802 |   0.481932 |
| k-d_tree_polars      |     4.80387  |       0.428716 |   0.535944 |
| k-d_tree_pandas      |     0.985827 |       0.390635 |   0.550365 |
| solution-1           |     8.22497  |       1e-06    |   0.61807  |
| k-d_tree_sklearn     |     3.69862  |       1.11072  |   1.02438  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.512493 |       0.410381 |   0.410569 |
| barab-szabi-1        |     0.584074 |       0.406527 |   0.41569  |
| k-d_tree_polars      |     1.03122  |       0.406276 |   0.417951 |
| Bori_Aron_solution-1 |     0.996642 |       0.548476 |   0.543892 |
| k-d_tree_pandas      |     0.513406 |       0.387443 |   0.550762 |
| k-d_tree_sklearn     |     0.52492  |       0.973564 |   1.03207  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.51201  |       0.421201 |   0.419569 |
| k-d_tree_polars      |     0.529092 |       0.429268 |   0.439726 |
| barab-szabi-1        |     0.517443 |       0.431459 |   0.447502 |
| Bori_Aron_solution-1 |     0.509121 |       0.578444 |   0.53999  |
| k-d_tree_pandas      |     0.516125 |       0.400947 |   0.589805 |
| k-d_tree_sklearn     |     0.520819 |       1.0191   |   1.05985  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.514913 |       0.48427  |   0.451581 |
| k-d_tree_polars      |     0.520889 |       0.542059 |   0.53592  |
| Bori_Aron_solution-1 |     0.511525 |       0.759964 |   0.554486 |
| barab-szabi-1        |     0.512694 |       0.567649 |   0.5569   |
| k-d_tree_pandas      |     0.513907 |       0.492859 |   0.731019 |
| k-d_tree_sklearn     |     0.516897 |       1.22087  |   1.10799  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.513034 |       0.725785 |   0.483901 |
| Bori_Aron_solution-1 |     0.509431 |       1.39403  |   0.579205 |
| k-d_tree_polars      |     0.521588 |       0.883499 |   0.88366  |
| barab-szabi-1        |     0.515631 |       0.889666 |   0.926923 |
| k-d_tree_pandas      |     0.513078 |       0.764492 |   1.16698  |
| k-d_tree_sklearn     |     0.517472 |       2.06621  |   1.20863  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.514772 |        5.39786 |   0.761736 |
| Bori_Aron_solution-1 |     0.510847 |       11.1456  |   0.924004 |
| k-d_tree_sklearn     |     0.521182 |       16.6254  |   1.31551  |
| barab-szabi-1        |     0.53073  |        5.02968 |   6.84549  |
| k-d_tree_pandas      |     0.518698 |        3.9846  |   7.20002  |
| k-d_tree_polars      |     0.540242 |        5.09899 |   7.20619  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.568735 |        74.9132 |    3.13451 |
| k-d_tree_sklearn     |     0.677842 |       237.797  |    4.35642 |
| Bori_Aron_solution-1 |     0.511189 |       155.946  |   14.5663  |